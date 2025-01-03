# My Migration to Hugo

This repository starts from a clone of https://github.com/wowchemy/starter-hugo-academic, where the original README.md can be found.

## Install Hugo

I did it on Windows 10 following https://wowchemy.com/docs/getting-started/install-hugo-extended/#windows

1. Open the Windows Powershell 5 app, installing it if necessary.
2. Install Scoop, the package manager for Windows, by pasting the following commands into Powershell and pressing the Enter ↵ key:

    ```sh
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
    iwr -useb get.scoop.sh | iex
    ```

    Press Y and enter if asked Do you want to change the execution policy?.
3. Install Hugo and its dependencies:

    ```sh
    scoop install git go hugo-extended
    ```

## Clone starter-hugo-academic

Follow https://lakemper.eu/blog/getting-started-with-hugo-academic-and-github-pages/

Create a new (private/public) repository on GitHub, e.g., hugo-academic, without initializing README, .gitignore, and licence.

Clone https://github.com/wowchemy/starter-hugo-academic
```sh
git clone https://github.com/wowchemy/starter-hugo-academic hugo-academic
cd hugo-academic
git remote set-url origin https://github.com/haipinglu/hugo-academic
git push
```

Then rename `master` to `main` and follow the instructions on github.

Then,

```sh
git submodule update --init --recursive
```

[*This problem is gone when last checked 17 April 2022*] If `hugo` now, several security errors will be reported. I had a hard time with this. Eventually, by Googling *"WC_POST_CSS" is not whitelisted in policy "security.funcs.getenv"*, I found the solution at https://stackoverflow.com/questions/70429317/blogdownserve-site-fails-to-produce-template-site:

The config file is config/_default/config.yaml in your website project. Add
```sh
security:
  funcs:
    getenv:
      - ^HUGO_
      - ^WC_
```
to it to whitelist the environment variable `WC_POST_CSS`.

Therefore, I followed the above to add the security config to the end of the config file. Now it works perfectly. [*No need when checked 17 April 2022*] 

## Deploy on GitHub Pages (can be skipped)

Follow https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7

```sh
hugo
cd public
git init -b main
git add .
git remote add origin https://github.com/haipinglu/haipinglu.github.io.git
git pull origin main
git commit -m “add Hugo content”
git push origin main
```

## Hugo Action for auto deployment

Follow https://github.com/peaceiris/actions-hugo, https://github.com/peaceiris/actions-gh-pages#%EF%B8%8F-create-ssh-deploy-key, https://github.com/peaceiris/actions-gh-pages#%EF%B8%8F-create-ssh-deploy-key,  and https://medium.com/@asishrs/automate-your-github-pages-deployment-using-hugo-and-actions-518b959a51f9

<!-- Add `.gitmodules` and `https://github.com/peaceiris/actions-hugo`. -->

```sh
ssh-keygen -t ed25519 -C "h.lu@sheffield.ac.uk" -f gh-pages -N ""
```

Or the following with `empty for no passphrase`.

```sh
ssh-keygen -t ed25519 -C "h.lu@sheffield.ac.uk" -f gh-pages
```

Add the private key as a secret with name ACTIONS_DEPLOY_KEY in the Hugo Source Repository.
Add the public key as deployment key in the GitHub pages repository

## Convert old HTML to Markdown

Follow https://pandoc.org/MANUAL.html

```sh
pandoc -s -o home.md home.html
```

## Manual edit

With the above done, manually update and customise the files.

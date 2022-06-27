# NSecurityTS
NOLD Security TypeScript: Security implementation OAuth2
 
### ENVIRONMENT SETUP

1. Install and initialize a git to control changes
        
    Install git [https://git-scm.com]

    ```bash
    git init
    ```

2. Install and initialize a NodeJS project

    Install NodeJS [https://nodejs.org]
    
    ```bash
    npm init
    ```
    
    2.1. [Optional] Install a NodeJS control version

    Install NVM [https://github.com/nvm-sh/nvm]
    
    ```bash
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
    ```

    If you are using windows install this option bellow
    Install NVM-Windows [https://github.com/coreybutler/nvm-windows]

    2.2. [Optional] Install NodeJS using the NVM
      
    ```bash
    nvm install node
    ```

3. Setting a Conventional Commits
    * The file .gitconfig has the alias to git commands.
    * [https://www.conventionalcommits.org/en/v1.0.0]
    * [https://www.npmjs.com/package/git-commit-msg-linter]

    ~~~bash
    npm i -D git-commit-msg-linter
    ~~~

4. Adding TypeScript
* with es2021 use node 15.14.0 or above
[https://node.green/#ES2021]
* include the TypeScript plugin to VSCode 

~~~bash
npm i -D typescript @types/node
~~~

### VISUAL STUDIO CODE Plugins
* TypeScript 


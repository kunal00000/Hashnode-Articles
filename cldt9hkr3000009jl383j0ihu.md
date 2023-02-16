# Using Multiple Node Versions

## **Introduction to Node Version Manager (NVM)**

NVM (Node Version Manager) is a tool that allows you to install and switch between multiple Node.js versions on your local machine. It makes it easy to manage different Node.js environments, ensuring that you can work with the version that best suits your needs. NVM is available for Windows, Linux, and macOS, and it supports all current Node.js versions.

## **Installing Node.js Versions**

Here are the steps to install a specific version:

1. Open a terminal window.
    
2. Run the following command to install a specific version:
    

```bash
nvm install <node_version>
```

1. For example, to install the version `14.15.4`, run the following command:
    
    ```bash
    nvm install 14.15.4
    ```
    
    You can also install the latest version of Node.js by running the following command:
    
    ```bash
    nvm install latest
    ```
    
    Switch Between Node.js Versions
    
    To switch between different Node.js versions, use the following command:
    
    ```bash
    nvm use <version>
    ```
    
    For example, to switch to version 14.15.4, run the following command:
    
    ```bash
    nvm use 14.15.4
    ```
    
    You can also switch to the latest version by running the following command:
    
    ```bash
    nvm use latest
    ```
    
    Listing Installed Node.js Versions
    
    You can list all the installed Node.js versions on your machine by running the following command:
    
    ```bash
    nvm ls
    ```
    
    This command will show you a list of all installed Node.js versions and the currently active version will be marked with an asterisk (\*).
    

## Some more nvm commands:

### Install Node

```bash
nvm install <node_version>      // Install a specific Node version nvm install node                // Install latest Node release (Current) 
nvm install --lts               // Install latest LTS release of NodeJS 
nvm install-latest-npm          // Install latest NPM release only nvm install 14                  // Installing Node.js 14.X version 
```

### List Available Node Releases

```bash
nvm ls-remote
nvm ls-remote | grep -i "latest"        
nvm ls-remote | grep -i "<node_version>"
```

### List Installed Nodes

```bash
nvm list node                   // Lists installed Node versions
nvm list  (or)  nvm ls          // Lists installed Node versions with additional release info
```

### Switch To Another Node Version

```bash
nvm use node                      // Switch to the latest available Node version
nvm use <node_version_or_alias>  // Switch to a specific version
nvm use --lts                    // Switch to the latest LTS Node version
```

### Verifying Node Version

```bash
node -v  (or)  node --version
npm -v   (or)  npm --version
nvm -v   (or)  nvm --version
```

### Set Alias

```bash
nvm alias default node                  // Always defaults to the latest available node version on a shell
nvm alias default <node_version>        // Set default node version on a shell
nvm alias <alias_name> <node_version>   // Set user-defined alias to Node versions 

nvm unalias <alias_name>                // Deletes the alias named <alias_name>
```

### Path to Node Executable

```bash
nvm which <installed_node_version>      // path to the executable where a specific Node version is installed
```

### Uninstall Specific Node Version

```bash
nvm uninstall <node_version>    // Uninstall a specific Node version
nvm uninstall --lts             // Uninstall the latest LTS release of Node
nvm uninstall node              // Uninstall latest (Current) release of Node
```
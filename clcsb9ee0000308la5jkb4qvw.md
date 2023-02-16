# Setup and Collaboration using Github Codespaces

If you haven't read my blog on the Power of GitHub Codespaces, do check it out ([unleash the power of codespaces](https://kunalverma2468.hashnode.dev/unleash-the-power-of-codespaces-as-a-developer)).  
We have talked about its features, requirements and how can you use it in your favour 😎.

Now let's start with creating a codespace...

## Creating your first CodeSpace.

1. Navigate to the repository you want to work on, and click the &lt;&gt;**Code** button, then click the **Codespaces** tab.
    

![](https://docs.github.com/assets/cb-15803/images/help/codespaces/new-codespace-button.png align="center")

1. Click the ellipsis (**...**) at the top right of the **Codespaces** tab and select **New with options**. On the options page for your codespace, choose your preferred options from the dropdown menus.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673476471318/f1e2a750-3f27-4101-813d-ba93f50ea827.png align="center")

1. Click **Create codespace**.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673476339978/7f7d10f8-b64e-4067-b8fc-d0e71901fa4e.png align="center")

## Opening an existing codespace

1. Navigate to the "Your codespaces" page at [github.com/codespaces](http://github.com/codespaces).
    
2. To open a codespace in your default editor, click the name of the codespace.
    
3. To open the codespace in an editor other than your default:
    
    1. Click the ellipsis (**...**) to the right of the codespace you want to open.
        
    2. Click **Open in**.
        
    3. Click **Open in APPLICATION**.
        
    
    ![Screenshot of the "Open in" dialog box, with "Open in Visual Studio Code" highlighted](https://docs.github.com/assets/cb-49328/images/help/codespaces/open-codespace-in-another-editor.png align="left")
    
    You can open the codespace in:
    
    * Your browser
        
    * Visual Studio Code
        
    * JetBrains Gateway
        
    * JupyterLab
        
    
    If you choose **Visual Studio Code** or **JetBrains Gateway**, you must make sure you have installed the selected application on your local machine.
    

## Customising your CodeSpace

The **codespace** we created using GitHub is the **default docker image**. So what we will do next is create a few configuration files so that we can customise the **default image.** Open the codespace in VS-Code.

1. Access the Visual Studio Code Command Palette ( `Command+Shift+P` / `Ctrl+Shift+P` ), then start typing "dev container". Click **Codespaces: Add Development Container Configuration Files**.
    
    ![Screenshot of the "Codespaces: Add Development Container Configuration Files" option](https://res.cloudinary.com/practicaldev/image/fetch/s--wk9-iFJ8--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/Pwd9000-ML/blog-devto/main/posts/2022/GitHub-Codespaces/assets/config001.png align="center")
    
2. Click **Show All Definitions**.
    
    ![Screenshot of the "Show All Definitions" option](https://res.cloudinary.com/practicaldev/image/fetch/s--1NOMbrbu--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/Pwd9000-ML/blog-devto/main/posts/2022/GitHub-Codespaces/assets/config02.png align="center")
    
3. Select the Ubuntu version to use.
    
    ![Screenshot of the 'Python 3' option](https://res.cloudinary.com/practicaldev/image/fetch/s--I2i2CLnw--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/Pwd9000-ML/blog-devto/main/posts/2022/GitHub-Codespaces/assets/config03.png align="center")
    
4. Click the latest version of Ubuntu.
    
    ![Screenshot of the Python 3 version selection](https://res.cloudinary.com/practicaldev/image/fetch/s--0-Qr9JzU--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/Pwd9000-ML/blog-devto/main/posts/2022/GitHub-Codespaces/assets/config06.png align="center")
    
5. Select the additional features to install inside of the **dev container**, then click **OK**.
    
    ![Screenshot of additional features for 'dotnet'](https://res.cloudinary.com/practicaldev/image/fetch/s--X202YDz_--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/Pwd9000-ML/blog-devto/main/posts/2022/GitHub-Codespaces/assets/config04.png align="center")
    
6. A `devcontainer.json` file is created and is opened in the editor.
# Unleash the Power of Codespaces as a Developer

# **🤔Let's start with knowing what a codespace is**

If you are a developer, you would be probably well aware of the **PAIN** points when it comes to maintaining **developer workstations** such as:

* Setup and maintenance of a dev workstation or setting up of workstations for a project.
    
* The time that is wasted before a 'first commit'.
    
* Inconsistency between dev workstations for configurations/tooling/settings.
    
* Versioning Tools/Extensions, Debuggers and Dependencies.
    
* Personal or Team based settings and customisations.
    
* Security and vulnerabilities.
    
* Hardware spec requirements.
    

The list goes on, and these are all factors that can cause a lot of pain😭, frustration😤 and time wasted😰 before actual development can start.

So, here comes GitHub Codespaces, a **GitHub codespace** is a development environment running inside of a **container** that's remotely hosted on a cloud-based **Virtual Machine** linked to your code repository that allows developers to easily **create**, **collaborate** on, and **manage their code**. With the ability to spin up new development environments in just seconds.

![](https://docs.github.com/assets/cb-89172/images/help/codespaces/codespaces-diagram.png align="center")

You can choose the type of machine you want to use, depending on the resources you need. Various types of machine are available, starting with a 2-core processor, 4 GB of RAM, and 32 GB of storage.

![](https://docs.github.com/assets/cb-34785/images/help/codespaces/change-machine-type-choice.png align="center")

Codespaces offers the flexibility and resources needed to tackle even the most complex projects. Additionally, it allows developers to **customize** and **standardize** the development environment on both a user and repository basis, making it possible to eliminate **OS-specific problems** and ensure that all team members are working with the same tools, which can greatly reduce potential issues and inconsistencies in the development process.

# 👨‍💻Explore some features of Codespaces

The main features and aspects of GitHub Codespaces, organized into headings for easy reference:

### ➾Streamlined Development Environment:

GitHub Codespaces provides you with a one-stop shop for working with code repositories by providing a built-in code editor, terminal, and debugging tools all within the browser.

<mark>For example</mark>, let us say, one developer might be using Ubuntu while another is using Mac, but both can use the same exact version of Node.js, and the same set of extensions, thus eliminating any compatibility issues.

### Built on Visual Studio Code:

GitHub Codespaces is built on top of Microsoft's popular code editor, Visual Studio Code, making it familiar and easy for developers who are already using it.

### Language Support:

GitHub Codespaces support a wide range of programming languages, including C#, Java, JavaScript, Python, and many more.

### 🤝Collaboration and Version Control:

The ability to share and collaborate on code with other team members by easily **sharing codespaces via a link** and submitting pull requests.

**For Example**: Assume you are working on a project in your **macOS** and you get stuck somewhere, have no idea about the error and have tried several ways to solve it but no help. Now you feel that your **friend(developer)** can help you but he has **windows** (assume that compatibility is not matching with the project configuration) 😩.  
In this case, the simple thing you can do is send the link for the codespace of your project to him, he **wouldn't have to locally set up the project** he can directly **view** and **edit** your code in codespace.

Built-in version control functionality makes it easy to keep track of changes and revert to previous versions.

### ☁Cloud-Based:

GitHub Codespaces is completely cloud-based, which means that developers can access their code and development environment from anywhere with an internet connection.

**I use my repositories from anywhere, like on college computers with no compatibility issues, and without worrying about setup. Just a link to codespace works it all for me and I can code in my free time from college 😎.**

### 🤗Easy Environment Setup:

GitHub Codespaces allows developers to easily set up and configure their development environments by spinning up a new codespace with all necessary tools and dependencies pre-installed.  
Once I was setting up an open-source project locally in VS-Code, to download the dependencies I ran a simple command

```plaintext
npm install
```

The result I got:-

According to this error, the version of dependency libvips used in the project is 8.9 and this version is not compatible to arm64 architecture but in macOS, it's arm64.

the architecture needed was x86, then I got to know about codespace and explored it more, got it resolved using codespace 🙂.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673449722606/bb74ffb4-a31c-4af0-8b91-aa3a5c4ca67d.png align="center")

## 🫵🏻Who can use Codespaces?

In the past **Codespaces** could only be enabled in settings by **organisation owners** for **Team** and **Enterprise** Cloud plans. However, GitHub since Nov 2022 GitHub announced that **Codespaces** are available for all GitHub users 😊, and everyone will have up to 60 hours of Codespaces for free every month.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673447227534/1af447a8-ffe6-4f02-a13d-968013d34873.png align="center")

* To calculate core hours :
    
    \--&gt; (number of cores) x (number of active hours) = total core hours
    
* For example:
    
    \--&gt; (4-core machine) x (active for 2 hour) = 8 core hours
    
    \--&gt; (2-core machine) x (active for 60 hour) = 120 core hours
    

## Why use Codespaces?

So, why should you use Codespaces over other development tools? Of course you have read it's features - comprising its flexibility, customization options, and powerful features, Codespaces offers everything you need to create and collaborate on code in an efficient and streamlined way. Plus, with its tight integration with GitHub, it makes it easy to track changes, merge pull requests, and stay up-to-date with the latest developments on your team's projects.

## ❌<s>Cons</s> Limitations to note

GitHub Codespaces is a relatively new product, and like any development tool, it has its pros and cons. We have discussed a lot of pros now its turn for <s>cons</s> limitations:

**Limited availability**: GitHub Codespaces provides up to 60 hours per month(free version users).

**Resource limitations**: While Codespaces allows for a large amount of RAM and CPU cores, some users or organisations may still find that it doesn't meet all of their resource needs.

**Internet connectivity**: Since it's a cloud-based solution, it is dependent on an internet connection, if your connection is not reliable the experience may be affected

**Integration with other tools**: While Codespaces is tightly integrated with GitHub, it may not be as well-integrated with other tools that you use in your development workflow.

**Limited Platform Support**: Currently, it only supports Linux and Windows environments, and it doesn't have support for macOS or other platforms.

It is worth noting that these limitations are subject to change as Github is continuously updating and improving the product to bring more features and capabilities, it is always a good idea to check the official documentation and release notes to know the latest state of the product.

## Conclusion

In conclusion, GitHub Codespaces is an incredibly powerful tool that can greatly improve your development workflow and collaboration. By eliminating OS-specific problems and offering a host of powerful features, it makes it easy to focus on what really matters - writing great code. With the ability to use different OS specifications like Ubuntu, Windows and many more, it ensures that everyone can work with the same tools and configurations. So, I encourage you to give Codespaces a try and see the difference for yourself!

**🙌🏼 Don't wait, start creating your own Codespaces now and experience the power of customization and standardization in just a few simple steps. No more compatibility issues, no more waiting around for environment setup. With Github Codespaces, everything you need to collaborate and code efficiently is at your fingertips.  
Get** [**A Step-by-Step Guide to Effortless Setup and Collaboration**](https://kunalverma2468.hashnode.dev/a-step-by-step-guide-to-effortless-setup-and-collaboration-using-github-codespaces).
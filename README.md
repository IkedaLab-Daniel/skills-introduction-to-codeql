<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Enable CodeQL to secure your source code

_Ensuring the security of application source code is a critical step in modern software development. In this GitHub Skills course, you will learn to use GitHub code scanning to identify, resolve, and prevent insecure coding patterns._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
  TBD-step-1-notes.
-->

## Step 1: Enable CodeQL

👋 Hello! Welcome to the GitHub Skills course: Enable code scanning! 

Let's get started!  

In this first step, we'll be learning more about CodeQL and how to use it to secure your source code. 

**What is GitHub code scanning**: _[Code scanning](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning)_ is a capability that allows development teams to integrate security testing tools into the software development process. This is done using GitHub Actions. With code scanning, you can integrate many different types of tools including SAST, container, and infrastructure as code security tools.

**What is CodeQL**: _[CodeQL](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql)_ is a static analysis testing tool that helps you identify security weaknesses such as SQL injection, cross-site scripting, and code injection issues.

### :keyboard: Activity: Enable code scanning with CodeQL
  
First, we will enable code scanning with CodeQL in our repository.

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
2. Navigate to the **Settings** tab at the top of your newly created repository.
3. Under the **Security** section on the left side, select **Code security and analysis**.
4. Scroll down to the section titled **Code scanning**. For the purpose of this course, we will focus on CodeQL analysis.
5. Click on the **Set up** dropdown menu and choose **Default**.
![enable-code-scanning-default.png](/images/enable-code-scanning-default.png)

Let's take a look at the configuration options in the modal:
  
  - **Languages to analyze:** These are the languages that will be scanned by CodeQL. In this case, we will be scanning in `Python`.  
  - **Query suites:** CodeQL [queries](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql#about-codeql-queries) are packaged in bundles called "suites". This section allows you to choose which query suite to use.  We'll leave this set as **Default** for this exercise. For more information, see "[About CodeQL queries](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql#about-codeql-queries)." 
  - **Events:** This section tells CodeQL when to scan. In this case, it's set to scan on any pull request to the `main` branch.
    
![codeql-default-configuration-box.png](/images/codeql-default-configuration-box.png)

6. Click **Enable CodeQL**
7. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-codeql) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>

<a name="readme-top"></a>
<div align="center">
</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Run tests](#run-tests)
 - [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)

# 📖 [Hello-Microverse] <a name="about-project"></a>

**[Hello-Microverse]** is a project that enables you to set up the environment for coding.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>
<details>
  <summary>Javascript</summary>
  <ul>
    <li><a href="https://nodejs.org/en/">Node.js</a></li>
  </ul>
</details>

<details>
  <summary>HTML</summary>
  <ul>
    <li><a href="https://www.w3schools.com/html/">HTML</a></li>
  </ul>
</details>

<details>
<summary>CSS</summary>
  <ul>
    <li><a href="https://www.w3schools.com/css/">CSS</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>


- **[key_feature_1]**
- **[key_feature_2]**
- **[key_feature_3]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

1. Set-up linters in your local environment

The `npm` package manager is going to create a `node_modules` directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a [`.gitignore`](https://git-scm.com/docs/gitignore) file and add `node_modules` to it:

```
# .gitignore
node_modules/
```

### [Lighthouse](https://developers.google.com/web/tools/lighthouse)

An open-source, automated tool for improving the quality of web pages. It has audits for performance, accessibility, progressive web apps, SEO and more.

You can get the Lighthouse report by any of the following ways:

- [In Chrome DevTools](https://developers.google.com/web/tools/lighthouse#devtools)
- [From the command line](https://developers.google.com/web/tools/lighthouse#cli)
- [As a Node module](https://developers.google.com/web/tools/lighthouse#programmatic)
- [From a web UI](https://developers.google.com/web/tools/lighthouse#psi)

To access the report generated by Lighthouse on your pull request, click the `Details` link for the `Linters/Lighthouse` check and you will see the full output of the action:

![lighthouse report](../assets/images/lighthouse-report.png)

### [Webhint](https://webhint.io/)

A customizable linting tool that helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.

**NOTE:** If you are running on Windows, you need to initialize npm to create `package.json` file. 
   ```
   npm init -y
   ```

1. Run
   ```
   npm install --save-dev hint@7.x
   ```
   *not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*
2. Copy [.hintrc](.hintrc) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx hint .
   ```
5. Fix validation errors.

### [Stylelint](https://stylelint.io/)

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

1. Run

   ```
   npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
   ```

   *not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*

2. Copy [.stylelintrc.json](./.stylelintrc.json) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run `npx stylelint "**/*.{css,scss}"` on the root of your directory of your project.
5. Fix linter errors.
6. **IMPORTANT NOTE**: feel free to research [auto-correct options for Stylelint](https://stylelint.io/user-guide/usage/options) if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!



### Setup

Clone this repository to your desired folder:

```
  cd my-folder
  git clone https://github.com/fatmahussein/Hello-Microverse.git
```
--->

### Run tests

To run tests, click on Go Live on the bottom left side of your visual studio code.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>


👤 **Author1**

- GitHub: [@githubhandle](https://github.com/fatmahussein)
- Twitter: [@twitterhandle](https://twitter.com/FatmaHussein200)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/fatuma-hussein-48149917b/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>


- [ ] **[Portfolio]**
- [ ] **[about-me]**
- [ ] **[contact-us]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project, give it a star!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank Microverse for guiding me through this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ (optional) -->

## ❓ FAQ (OPTIONAL) <a name="faq"></a>

- **[What are linters? ]**

  - [ a linter is a tool to help you improve your code by analyzing your source code looking for problems]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
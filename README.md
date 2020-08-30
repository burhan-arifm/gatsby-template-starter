<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby starter
</h1>

This starter is included with node-sass as CSS preprocessor. You can remove ith if you didn't need it.

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the minimal starter.

    ```shell
    # create a new Gatsby site using the minimal starter
    gatsby new my-site https://github.com/burhan-arifm/gatsby-starter-minimum
    ```

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-site/
    gatsby develop
    ```

3.  **Open the code and start customizing!**

    Your site is now running at `http://localhost:8000`!

## 📂 Directories Explanation

In this starter, you would find the directory structure like this:

```shell
[your-project-directory]
 ┣ 📂src
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂atoms
 ┃ ┃ ┣ 📂molecules
 ┃ ┃ ┣ 📂organisms
 ┃ ┃ ┗ 📂templates
 ┃ ┣ 📂images
 ┃ ┣ 📂pages
 ┃ ┃ ┣ 📜404.jsx
 ┃ ┃ ┗ 📜index.jsx
 ┃ ┗ 📂utils
 ┣ 📜.editorconfig
 ┣ 📜.eslintrc
 ┣ 📜.gitignore
 ┣ 📜.prettierignore
 ┣ 📜.prettierrc
 ┣ 📜gatsby-browser.js
 ┣ 📜gatsby-config.js
 ┣ 📜gatsby-node.js
 ┣ 📜jsconfig.json
 ┣ 📜LICENSE
 ┣ 📜package.json
 ┣ 📜README.md
 ┗ 📜yarn.lock
```

1.  📂 **Components**

    This directory follows as atomic design principles. All the components that structured the web pages would be put here. Learn more about [atomic design principles here](https://bradfrost.com/blog/post/atomic-web-design/).

2.  📂 **Pages**

    When you make a new page in Gatsby, you have to put that file in this directory. I've already put two files, `index.jsx` and `404.jsx` as a start. Feel free to customize both of them as you need.

3.  📂 **Utils**

    This directory is home for all the javascript file that doesn't have any html tag besides the Gatsby configuration file itself. You can put any helper or module configuration files here.

4.  📜 **.editorconfig**, **.eslintrc**, **.prettierignore**, and **.prettierrc**

    These files serve as code linter and formatter. You can read more about them in the links below.

    - [ESLint](https://eslint.org/docs/user-guide/getting-started)
    - [Prettier](https://prettier.io/docs/en/index.html)
    - [EditorConfig](https://editorconfig.org/)

5.  📜 **gatsby-\*.js**

    These files serve as Gatsby configuration file. `gatsby-config.js` is required to use the framework, whereas the other two is optional.

6.  📜 **jsconfig.json**

    This file is optional, but really helpful if you use vscode as your editor. In a nutshell, it makes the import path shorter.

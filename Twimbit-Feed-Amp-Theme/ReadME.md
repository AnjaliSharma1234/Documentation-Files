# Feed - Amp - Theme : A wordpress theme

[![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-tomato.svg?style=flat&logo=git)](https://github.com/twimbit/Feed-Amp-Theme/issues) [![GitHub stars](https://img.shields.io/github/stars/twimbit/Feed-Amp-Theme.svg?logo=github)](https://github.com/twimbit/Feed-Amp-Theme/stargazers) [![GitHub forks](https://img.shields.io/github/forks/twimbit/Feed-Amp-Theme.svg?logo=github&color=teal)](https://github.com/twimbit/Feed-Amp-Theme/network) [![GitHub top language](https://img.shields.io/github/languages/top/twimbit/Feed-Amp-Theme?color=yellow&logo=javascript)](https://github.com/twimbit/Feed-Amp-Theme) 

Feed - Amp - Theme is a 100% valid feed amp theme for wordpress. 

## Tech Stack 

- **Frontend:** HTML5, CSS3, JavaScript, Amp

## Getting Started

### System Requirements

****To be changed below this****

As this is a wordpress theme application, you need the following to support your development environment.

* [Git](https://git-scm.com/downloads)
* mySQL
* [Linux Based Terminal](https://gitforwindows.org/), if you're using Windows and installed with Git.
* [Google Chrome](https://www.google.com/chrome/) or a decent latest web browser.
* **[Visual Studio Code](https://code.visualstudio.com/)** is the go-to editor for some complex languages like React using JSX or TypeScript and I finally agreed with [Wes Bos](https://wesbos.com/) that VS Code is better for development of React JS. Obviously, with VS Code, you should be having the right extensions to support your React JS development, but comparing with Sublime Text 2, VS Code is still in its infancy. Get these extensions and here's my [dotfile](https://gist.github.com/praveenscience/ebb5439f31774ad2fdc14cb9e7de1fc0):
  1. [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) helps you to format your JavaScript / TypeScript / CSS using [Prettier](https://github.com/prettier/prettier).
  2. [Cobalt2 Theme Official](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2) is the theme used by Wes Bos, which comes with a nice user experience and a lot of awesome features. I am using a modified version of Cobalt2 that's a crossover between [Monokai](https://www.monokai.pro/) and Cobalt2.
  3. [GitLens - Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) supercharges the Git capabilities built into Visual Studio Code. It helps you to visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.
  4. [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) helps you to view git log, file history, compare branches or commits inside VS Code.
  5. [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) integrates ESLint into VS Code. If you are new to ESLint check the [documentation](http://eslint.org/).
  6. [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) provides you JavaScript and React/Redux snippets in ES7 with Babel plugin features for VS Code.
  7. [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) `(optional)` quickly searches (using ripgrep) your workspace for comment tags like TODO and FIXME, and displays them in a tree view in the explorer pane. Clicking a TODO within the tree will open the file and put the cursor on the line containing the TODO.
  8. [`vscode-icons`](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) `(optional)` is more of a cosmetic thing, which brings icons to the Visual Studio Code editor.

### Installation Instructions

[Create React App](https://github.com/facebookincubator/create-react-app) is a comfortable environment for **learning React**, and is the best way to start building **a new [single-page](https://reactjs.org/docs/glossary.html#single-page-application) application** in React. This project makes use of Create React App. It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimises your app for production. You’ll need to have [Node >= 8.10 and npm >= 5.6](https://nodejs.org/en/) on your machine.

### Running the Application Locally

**First Time Only**

1. [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) the project.
2. Clone the project.
   ```bash
   git clone https://<your-github-username>@github.com/<your-github-username>/Rezume.git
   ```
3. Enter the project directory.
   ```bash
   cd Rezume
   ```
4. Install the required modules.
   ```bash
   npm install
   ```

**Every time when you start to develop, please do this.**

1. Enter the project directory.
   ```bash
   cd Rezume
   ```
   
2. Start the application.
   ```bash
   npm start
   ```
   
3. Open http://localhost:3000/ on your favourite browser. Let anyone from the mentoring team know, if you are facing any troubles.

   ****To be changed above this****

## Contribution Guidelines

[![GitHub issues](https://img.shields.io/github/issues/twimbit/Feed-Amp-Theme?logo=github)](https://github.com/codeuino/Feed-Amp-Theme/issues) ![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/twimbit/Feed-Amp-Theme?logo=git&logoColor=white) ![GitHub contributors](https://img.shields.io/github/contributors/twimbit/Feed-Amp-Theme?logo=github) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat&logo=git&logoColor=white)](https://github.com/twimbit)  [![GitHub last commit](https://img.shields.io/github/last-commit/twimbit/Feed-Amp-Theme?logo=github)](https://github.com/twimbit)[![twimbit](https://img.shields.io/badge/Author-@siddhantdante-gray.svg?colorA=gray&colorB=dodgerblue&logo=github)](https://github.com/siddhantdante) [![twimbit](https://img.shields.io/badge/Author-@amanintech-gray.svg?colorA=gray&colorB=dodgerblue&logo=github)](https://github.com/amanintech) 


- Please read our [Code of Conduct](https://github.com/twimbit/Feed-Amp-Theme/blob/master/CONTRIBUTING.md) and [Gitflow](https://github.com/twimbit/Feed-Amp-Theme/blob/master/CONTRIBUTING.md) for contributing towards the project.
- Write clear meaningful git commit messages (Do read [this](http://chris.beams.io/posts/git-commit/)).
- Make sure your PR's description contains GitHub's special keyword references that automatically close the related issue when the PR is merged. (Check [this](https://github.com/blog/1506-closing-issues-via-pull-requests) for more info)
- When you make very very minor changes to a PR of yours (like for example fixing a text in button, minor changes requested by reviewers) make sure you squash your commits afterwards so that you don't have an absurd number of commits for a very small fix. (Learn how to squash at [here](https://davidwalsh.name/squash-commits-git))
- When you're submitting a PR for a UI-related issue, it would be really awesome if you add a screenshot of your change or a link to a deployment where it can be tested out along with your PR. It makes it very easy for the reviewers and you'll also get reviews quicker.
- Always create PR to `develop` branch.


## Mentors

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/twimbit/Feed-Amp-Theme) ![GitHub pull requests](https://img.shields.io/github/issues-pr-closed-raw/twimbit/Feed-Amp-Theme?logo=git&logoColor=white) 

| GitHub Usernames                                  | Domain |
| ---------------------------------------------------- | -------------------------- |
| Aman Sharma [(@amanintech)](https://github.com/amanintech) | Full Stack  |
| Siddhant Kumar [(@siddhantdante)](https://github.com/siddhantdante) | Full Stack  |         |


[![built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/AnjaliSharma1234/)

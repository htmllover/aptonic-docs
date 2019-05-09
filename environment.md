### Environment Setup 

Now we will explain how to setup your gulp environment, if you've never worked, with `npm`, `gulp`. We need to setup a **nodejs** environment. 



!>If you already have `node` and `npm` installed on your machine, you can skip the following sections.

#### Npm

To start working with Aptonic, we are going to need the `Node Package Manager`, commonly known as `npm`. `npm` makes it easy for JavaScript developers to share and reuse code, and makes it easy to update the code that you’re sharing, so you can build amazing things.


#### Install nodejs

`npm` is distributed with `Node.js`, which means that when you download Node.js, you automatically get npm installed on your computer. First, check if you already have node and npm installed. To check if you have Node.js installed, run this command in your terminal:



```bash
node -v
```

To confirm that you have npm installed you can run this command in your terminal:

```bash
npm -v
```

If node is not installed on your machine, follow the steps described in one of the following guides, depending on your operating system:

- [Install node.js and npm on Windows](https://treehouse.github.io/installation-guides/windows/node-windows.html)
- [Install node.js and npm on Linux](https://www.ostechnix.com/install-node-js-linux/)
- [Install node.js and npm on Mac OSX](https://www.codementor.io/mercurial/how-to-install-node-js-on-macos-sierra-mphz41ekk)


#### Installing gulp.js

Gulp is a "Task runner" served as a Frontend tool. It is capable of executing chunks of code and save you huge amounts of time. What gulp can do is very vast :

* Simple operations like CSS and Javascript minification / concatenation
* Directory creation or deletion
* Image optimization and compression
* Deploying a local server to run tests etc ...

To stay simple, Gulp will help you save tremendous amounts of time by handling recurring and automated tasks. You can then focus on your real work : produce clear and concise code, and get a coffee from time to time ! If you want to install Gulp globally on your machine, meaning that you will have access to its commands everywhere, follow the following steps. Otherwise jump to the next section.

As soon as `node` and `npm` are installed, you can start instaling Gulp. In your terminal window, enter the following command :

```bash
npm install gulp -g
```

!>If you are working in a Linux or a Mac OSX environment, you will probably need to add the `sudo` command to have the required rights


```bash
sudo npm install gulp -g
```

Gulp should now be installed and ready to serve.

To work properly, it relies on 2 files that you can find at the root of the project :


* `package.json`
* `gulpfile.js`


The `package.json` file lists all your project's developement and production dependencies installed via `npm`, an effective way to manage your project's assets consistently. The `gulpfile.js` file contains all the task that Gulp will perform once launched.




























# LifeLink landing page

This repo builds the static pages used for the LifeLink landing page.  (This page lets people sign up for a MailChimp mailing list.)  It is based on Foundation for Apps and is built with NPM.

## Requirements

You'll need the following software installed to get started.

  - [Node.js](http://nodejs.org): Use the installer for your OS.
  - [Git](http://git-scm.com/downloads): Use the installer for your OS.
    - Windows users can also try [Git for Windows](http://git-for-windows.github.io/).
  - [Gulp](http://gulpjs.com/) and [Bower](http://bower.io): Run `npm install -g gulp bower`
    - Depending on how Node is configured on your machine, you may need to run `sudo npm install -g gulp bower` instead, if you get an error with the first command.

## Get Started

Clone this repository.

```bash
git clone https://github.com/claytonmeador/node-sphere
```

Change into the directory.

```bash
cd app
```

Install the dependencies. If you're running Mac OS or Linux, you may need to run `sudo npm install` instead, depending on how your machine is configured.

```bash
npm install
bower install
```

While you're working on your project, run:

```bash
npm start
```

This will compile the Sass and assemble your Angular app. **Now go to `localhost:8080` in your browser to see it in action.** When you change any file in the `client` folder, the appropriate Gulp task will run to build new files.

To run the compiling process once, without watching any files, use the `build` command.

```bash
npm start build
```

# Publish

When you're happy with the site, copy the contents of the build/ directory into https://github.com/lifelink-core/lifelink-core.github.io.  Pushing that repo will update the pages shown by MailChimp (which are served by GitHub Pages.)

Or, make this process more automated.

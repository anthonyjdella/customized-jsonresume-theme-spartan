# Customized JSON Resume Theme: Spartan

🖼️ This is a slightly tweaked version of the [Spartan theme](https://github.com/phoinixi/jsonresume-theme-spartan). Tweaked to fit my design preferences. Published on NPM and GitHub Registry.

## Notable Changes

* 2 Page version in PDF/printable mode 
* Added sections for speaking and articles
* Style changes

## Prerequisites

To build and start the local server, it needs to use the cli command, which is custom cli I tweaked.

`npm i @anthonyjdella/customized-resume-cli`

## How to Start

`npm run start`

## How to Change

* `resume.hbs` is the order of the resume.
* `style.css` is the styling
* To make changes to the PDF/printable version, make changes in the `@print` section of `style.css`
* Change version number in `package.json`
* Deploy the changes via `npm publish --access public`
* To see changes from `resume.anthonydellavecchia.com` you need to go to the [registry project](https://github.com/anthonyjdella/customized-registry-functions), then cd into `functions`, run `npm i` and `npm update`, then `firebase deploy`.

<details>
  <summary>Click to expand README.md of the source repository!</summary>

# Spartan theme for jsonresume [![npm version](https://badge.fury.io/js/jsonresume-theme-spartan.svg)](http://badge.fury.io/js/jsonresume-theme-spartan)

This is a theme for JSON Resume. It is available via npm:
```
npm install jsonresume-theme-spartan
```
[DEMO](https://phoinixi.github.io/website/resume/spartan)

## Getting started

### Install the command line

The official [resume-cli](https://github.com/jsonresume/resume-cli) to run the development server.

Go ahead and install it:

```
sudo npm install -g resume-cli
```
### Serve theme

While inside the theme folder, simply run:

```
resume serve
```

You should now see this message:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

### Social Profiles Icons

**Profiles supported with brand colors:**

github, stack overflow, linkedin, dribbble, twitter, facebook, pinterest, instagram, soundcloud, wordpress, youtube, flickr, google plus, tumblr, foursquare.

To have a social icon close the social link profile (or username) it is enough to set a `network` the name of the Social Network (es: 'Stack Overflow').

## Contribute

To test the theme, this is what you'll need:

- [node.js](http://howtonode.org/how-to-install-nodejs)
- [npm](http://howtonode.org/introduction-to-npm)

If you're on Linux, you can simply run:

```
sudo apt-get install nodejs-legacy npm
```

Or if you're on OSX and got [Homebrew](http://brew.sh/) installed:
```
brew install node
```

## License

Available under the [MIT license](http://opensource.org/licenses/mit-license.php).

<p align="center">
  <a href="https://jekyllup.com">
    <img src="https://cdn.itwcreativeworks.com/assets/jekyllup/images/logo/jekyllup-brandmark-color-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/jekyllup/jekyllup.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/jekyllup.svg">
  <img src="https://img.shields.io/bundlephobia/min/jekyllup.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/jekyllup/jekyllup.svg">
  <img src="https://img.shields.io/npm/dm/jekyllup.svg">
  <img src="https://img.shields.io/node/v/jekyllup.svg">
  <img src="https://img.shields.io/website/https/jekyllup.com.svg">
  <img src="https://img.shields.io/github/license/jekyllup/jekyllup.svg">
  <img src="https://img.shields.io/github/contributors/jekyllup/jekyllup.svg">
  <img src="https://img.shields.io/github/last-commit/jekyllup/jekyllup.svg">
  <br>
  <br>
  <a href="https://jekyllup.com">Site</a> | <a href="https://www.npmjs.com/package/jekyllup">NPM Module</a> | <a href="https://github.com/jekyllup/jekyllup">GitHub Repo</a>
  <br>
  <br>
  <strong>jekyllup</strong> is the official npm module of <a href="https://jekyllup.com">JekyllUp</a>, a free theme database for Jekyll websites.
</p>

## 🌐 JekyllUp Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## 🦄 Features
* Theme database for Jekyll websites.

## 🔑 Getting an API key
You can use so much of `jekyllup` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a JekyllUp account](https://jekyllup.com/signup).

## 📦 Install JekyllUp
### Option 1: Install via npm
Install with npm if you plan to use `jekyllup` in a Node project or in the browser.
```shell
npm install jekyllup
```
If you plan to use `jekyllup` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const jekyllup = new (require('jekyllup'))({
  // Not required, but having one removes limits (get your key at https://jekyllup.com).
  apiKey: 'api_test_key'
});
```

### Option 2: Install via CDN
Install with CDN if you plan to use JekyllUp only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/jekyllup@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var jekyllup = new JekyllUp({
    // Not required, but having one removes limits (get your key at https://jekyllup.com).
    apiKey: 'api_test_Key'
  });
</script>
```

### Option 3: Use without installation
You can use `jekyllup` in a variety of ways that require no installation, such as `curl` in terminal/shell.

```shell
# Standard
curl -X POST https://api.jekyllup.com
```

## ⚡️ Usage
### jekyllup.run(options)
```js
jekyllup.run(options);
```

## 📘 Using JekyllUp
After you have followed the install step, you can start using `jekyllup` to enhance your project.

For a more in-depth documentation of this library and the JekyllUp service, please visit the official JekyllUp website.

## 📝 What Can JekyllUp do?
JekyllUp is a free theme database for Jekyll websites

## 🗨️ Final Words
If you are still having difficulty, we would love for you to post
a question to [the JekyllUp issues page](https://github.com/jekyllup/jekyllup/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## 📚 Projects Using this Library
* [ITW Creative Works](https://itwcreativeworks.com)
* [Somiibo](https://somiibo.com)
* [Slapform](https://slapform.com)
* [StudyMonkey](https://studymonkey.ai)
* [DashQR](https://dashqr.com)
* [Replyify](https://replyify.app)
* [SoundGrail](https://soundgrail.com)
* [Trusteroo](https://trusteroo.com)

Ask us to have your project listed! :)

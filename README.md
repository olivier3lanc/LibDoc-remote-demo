---
title: Jekyll LibDoc as remote theme
description: Steps to follow to use quickly Jekyll LibDoc without tricky installation
permalink: index.html
---
[DEMO - View Github Pages of the current repository](https://olivier3lanc.github.io/LibDoc-remote-demo/)

This repository contains only the configuration and the content of [Jekyll LibDoc theme](https://github.com/olivier3lanc/Jekyll-LibDoc).

*Available only on GitHub*, [remote theme feature](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll#adding-a-theme) is the most simple way to use LibDoc, it does not require any installation, just follow these few steps:

1. **Create a repository** <br>Just add a new repository on your GitHub account, this directory is an example.<br><br>
2. **Create a LibDoc config file** <br>Create and configure your LibDoc config file called [_config.yml](libdoc-config.html), required for GitHub Pages, do not forget to add/uncomment the following line:<br>`remote_theme: olivier3lanc/Jekyll-LibDoc`<br>[View a _config.yml example](https://github.com/olivier3lanc/LibDoc-remote-demo/blob/main/_config.yml)<br><br>
3. **Enable Github Pages** <br>To automatically compile your LibDoc project, just enable GitHub Pages at `https://github.com/[GH_USER_NAME]/[REPO_NAME]/settings/pages`. Each time you commit and push on the specified branch, [Github Pages](https://pages.github.com) builds and hosts your project on the URL `https://[GH_USER_NAME].github.io/[REPO_NAME]`.

Your repository is now ready to be deployed as GitHub Pages website, all you have to do is adding your content! Learn more about [remote themes](https://github.blog/2017-11-29-use-any-theme-with-github-pages/)

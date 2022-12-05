<div align="center">
<h1 align="center">Minimalistic portfolio website</h1>
<img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg"/><br><br>
This portfolio site is built using Hugo static site generator.<br><br>
</div>

## Requirements:
- Hugo theme [hello-friend-ng](https://github.com/rhazdon/hugo-theme-hello-friend-ng/tree/929b9efaab6cecaab23030f6bb1463ac306d505d)
- Fevicon [Generator](https://realfavicongenerator.net/)

## Setup guide
1. Initiate a new Hugo project
```bash
$ hugo new site <project-name>
```
2. Install the hello-friend-ng theme
```bash
$ git submodule add https://github.com/rhazdon/hugo-theme-hello-friend-ng.git themes/hello-friend-ng
```
3. Edit [config.toml](/config.toml) for social media links, sub-pages routes, homepage and other configuration changes.
4. Generate fevicon files with the help of generator & place it in static folder
5. Deploy on hosting platforms like Vercel or GitHub pages
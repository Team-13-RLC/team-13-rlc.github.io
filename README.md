# RLC (Team 13)
## Project website
### Requirements
* [hugo](https://gohugo.io/)
* [git](https://git-scm.com/)
* linux or [wsl](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (optional, recommended)
### Instructions
* clone the repository
```shell
git clone --recursive https://github.com/dk949/dk949.github.io
```
**Note:** All commands from here are run from the **_site-source** directory
* generate the static pages
```shell
hugo -d ../
```
* create a new post
```shell
hugo new post/name-of-the-post.md
```
* create new documentation
```shell
hugo new docs/name-of-the-document.md
```
* create a new link to the executable
```shell
hugo new docs/name-of-the-download.md
```
* generate the site
```shell
hugo -d ../
```
* safely delete the generated pages (linux/wsl only, possibly macOS)
```shell
./cleanup
```
* test the website locally (site will be available at 127.0.0.1:1313)
```shell
hugo -D server
```
* make the changes public
```shell
cd ../
git add .
git commit -m "Commit message"
git push
```
**Note:** Every markdown page created with "hugo new" will have some metadata at the top. This includes "draft: true". This needs to be changed to "draft: false" in order for the page to be visible publicly.

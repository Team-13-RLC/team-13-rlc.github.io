# RLC (Team 13)
## Project website
### Requirements
* [hugo](https://gohugo.io/)
* [git](https://git-scm.com/)
* linux or [wsl](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (optional, recommended)
### Instructions
* clone the repository with the --recursive flag
```shell
git clone https://github.com/Team-13-RLC/team-13-rlc.github.io/
```
* add/modify the necessary pages
```shell
cd _site-source
hugo new post/new-post.md
```
* generate newly modified pages
    * Make sure they are generated in the main directory
```shell
cd _site-source
hugo -d ../
```
* See more detailed instructions in [the wiki](https://github.com/Team-13-RLC/team-13-rlc.github.io/wiki)

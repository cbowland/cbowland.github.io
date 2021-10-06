# cbowland.github.io

This is the base repository for a Hugo templated blog platform. 
The base url is "cbow.io".

The website https://cbow.io is a static site generated using the hugo tooling.
The hugo config file has a non-standard output for the generated site.

```
publishdir = "../cbowland.github.io"
```
In order to publish new version fo the site use the following steps:

```
clone this repo
cd into the cloned repo
make changes
execute `hugo server` to test changes
execute `hugo` to deploy new static version of the site in the ../cbowland.github.io directory
cd to ../cbowland.github.io
review changes
git add, commit, and push to https://github.com/cbowland/cbowland.github.io.

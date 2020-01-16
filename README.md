# Profile

This is the profile page for Asher Pembroke


# note on mkdocs

Getting mkdocs your profile onto github pages with markdown-include is a bit of a chore and the instructions on the mkdocs site won't work. 

1. create a git repo (e.g. github.com/<username>/profile)
2. create a second git repo (<username>.github.io)
3. from the profile repo run `mkdocs build`. This will build and place the static contents in `site`
4. copy the contents of the `site` folder to your second repo
5. from <username>.github.io, run `git add .`
6. commit and push the contents of the second repo

After you make changes to your site and are ready to deploy:

1. from the profile repo run `mkdocs build` again.
2. from the <username>.github.io site, run `git rm -rf .` 
3. continue with steps 4-6 above


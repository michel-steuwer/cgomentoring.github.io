# 18
27th International Conference on Compiler Construction 2018

# setting up website locally

Clone the git repository (change GIT_REPO_NAME): `git clone GIT_REPO_NAME`

Make sure to have the ruby header files installed on your system, then:

`gem install bundler`

`bundle install`

To build the website: `bundle exec jekyll build`

Then test it locally using a local webserver (this will make sure the website gets rebuilt automatically when any file changes):

`bundle exec jekyll serve --incremental`

To continuously update the local copy of the website while changing it use the command:

`bundle exec jekyll serve --watch`

To see the local version go to the following URL:

http://localhost:4000/

Once done with changes:

`git commit -a`

`git push`

Check to see everything works: [https://cc-conference.github.io/18/]

J. Nelson Amaral, July 2018:

- To remove the "Program" and "Attending" menus (for which there is no content when the site is first created for a new edition of the conference), comment out the corresponding <li> entries in the file _layouts/default.html



- I also added CC18 to the "Previous CCs" at the bottom of the file _layouts/default.html

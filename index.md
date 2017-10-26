## Welcome to my Heroku Pages

Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.

Create a new app in Heroku call `exampleapp`.

To install the Heroku CLI with homebrew:

`$ brew install heroku/brew/heroku
`

To verify your CLI installation use the `heroku --version` command.

You should see `heroku-cli/x.y.z` in the output. If you don’t, but have installed the Heroku CLI, it’s possible you have an old heroku gem on your system 

You will be asked to enter your Heroku credentials the first time you run a command; after the first time, your email address and an API token will be saved to `~/.netrc` for future use.

Open a terminal on your computer and type:`$Heroku login`

Initialize a git repository in a new or existing directory
```
$ cd my-project/
$ git init
$ heroku git:remote -a exampleapp

```
Commit the code to the repository and deploy it to Heroku using git.
```
$ git add.
$ git commit -am "make it better"
$ git push heroku master

```


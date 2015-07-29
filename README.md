# gifdump
If you want to add some gifs, send me a PR.

## Steps to setup

* Purchase [Alfred](http://www.alfredapp.com/) to get access to custom workflows
* Pull down this repo onto your machine
* Import `gif-workflow` into Alfred
* Edit the workflow to add the directory where <repo>/gifs is located on your machine
* Open up Alfred and type `gif the-gif-you-want`
* A publically accessible URL will be copied to your clipboard so you can post the GIF in Slack/Twitter/etc.

## Adding new GIFs

There are two options if you want to add new GIFs

1. Open up a pull request on this repo with the new gifs which you would like added. Once they are merged pull down the changes and have fun.
2. Fork this repository and change the `bin/bash` part of the workflow to reference your fork. `github_url="https://raw.githubusercontent.com/<your_username>/gifdump/master/gifs"`

the-listserve-archive
=====================

An automatic archive of posts from [The Listserve](http://thelistserve.com/). Check it out at www.TheListserveArchive.com.

If you're interested in a machine-friendly data format, see https://github.com/simon-weber/the-listserve-archive/tree/gh-pages/data. This is also available through http, eg www.TheListserveArchive.com/data/all_posts.json.

##Branches:

* **master**: backend code. Hosted on Heroku, it uses [Context.io](http://context.io/) to listen for new posts, then commits them to the gh-pages branch. It's stateless; Github is our database, basically.
* **gh-pages**: Jekyll code that builds to www.TheListserveArchive.com.
* **testing**: orphan branch that I use to test my interactions with the Github api.

All code is MIT licensed. If you find it useful, a mention would be cool.

# mu-feed
A MangaUpdates RSS feed generator

One can self-host this on [now.sh](https://now.sh) with very little knowledge and use this to generate RSS feeds for [MangaUpdates](https://www.mangaupdates.com/)

## Instructions

To use it, one should make their list public.

The settings I use on my reading list are below:

![](https://i.imgur.com/mpURglK.png)

You will then be able to see your public list URL, for example, mine is: 

`https://www.mangaupdates.com/mylist.html?id=542166&list=read`

After publishing this to [now.sh](https://now.sh), you will get a URL in the syntax of:

`https://<project>.<username>.now.sh`

To get the RSS feed, you will want to use the data from your public list url:

`https://<project>.<username>.now.sh/feed.js??id=542166&list=read`

## Thoughts

[now.sh](https://now.sh) lets you create a project from a GitHub project, so you should be able to simply fork this project and create it from that without any other work to be done.

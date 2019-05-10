# mu-feed
A MangaUpdates RSS feed generator

One can self-host this on [now.sh](https://now.sh) with very little knowledge and use this to generate RSS feeds for [MangaUpdates](https://www.mangaupdates.com/)

## Setup

To use it, one should make their list public.

The settings I use on my reading list are below:

![](https://i.imgur.com/mpURglK.png)

You will then be able to see your public list URL, for example, mine is: 

`https://www.mangaupdates.com/mylist.html?id=542166&list=read`

Take note of the `?id=xxxx&list=xxxx` part for later

## Instructions

Go to import a repository, as seen below:

![](https://i.imgur.com/6WhK53g.png)

Use the following url during import: `https://github.com/TSedlar/mu-feed.git`

Fill in the form and press `Begin import`

![](https://i.imgur.com/Buv6CXP.png)

## Registering

Head on over to [now.sh](https://now.sh) and get started with GitHub

![](https://i.imgur.com/RPFqKyh.png)

![](https://i.imgur.com/pUOz1LJ.png)

Now you will want to go to your [now.sh account](https://zeit.co/account), and install Now for GitHub.

Select the repository you imported and click next/install:

![](https://i.imgur.com/oDndsh6.png)

Now go to your [GitHub repositories](https://github.com/settings/repositories) and locate the repository you imported.

Click the `Create File` button

![](https://i.imgur.com/EFoKcL3.png)

Type `BUILD` or anything you want in the field it highlights and click `Commit new file`

![](https://i.imgur.com/mNTowvP.png)
![](https://i.imgur.com/RSGI7aB.png)

## Finishing up

Now you will have the project imported to your [now.sh project](https://zeit.co/dashboard/projects)

Click the project and locate the URLs

![](https://i.imgur.com/mXuSN29.png)

Refer to the above section for your `id` and `list`

You can now obtain your MangaUpdates RSS feed file at `https://mu-feed.<username>.now.sh/feed.js?id=xxxxxx&list=xxxx`

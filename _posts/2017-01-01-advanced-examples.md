---
title:  "Ranking U2 | Part 1"
layout: post
categories: media
---

![U2 on Unforgettable Fire Tour in Sydney, 1984](https://upload.wikimedia.org/wikipedia/commons/a/ad/U2_on_Unforgettable_Fire_Tour_09-09-1984.jpg)


## Unforgettable Fire

Not sure why I started here but I did. I'm going to listen to all of U2's album's 10 times and do a ranking. This one was a blind spot, relatively speaking. I owned it on cassette in the early 90s so I *must* have listened to it a decent number of times back then but some of the lesser known tracks here were *very* unfamiliar to my 40-something ears. Anyway, I'll do a track-by-track for each album so here goes...

#### A sort of homecoming

Jesus. What an opener. I mean I of course new this song but it had been a while since I listened to it. Bono's vocals are off the scale. As they are on the whole album, perfectly caught between his early english-punk style affectations and the later american stadium yawp. And has he written a better lyric? I'm not sure. Gorgeous song. Jesus. What an opener.

#### Pride (in the name of love)

It's all about the drumming. The way it pushes into every chorus like a train. Not my favourite type of U2, and even on this album I prefer the songs that are less sure of what they are, less quick to declare themselves. But you can't deny its power, from that three note opening. It is a bit hard to hear the song properly, it feels like trying to see a table for the first time. God I'm talking shite.



## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

<script src="https://gist.github.com/5555251.js?file=gist.md"></script>

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}

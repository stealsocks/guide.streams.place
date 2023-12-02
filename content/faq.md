---
title: 'The [streams.place](https://streams.place) FAQ'
description: "FAQ • Streams"
---

### Can I quote/thread/link my Drops?

There's no threading, because you can just edit your Drop to add more words to it whenever you want.

You can however, link to Drops in two ways. Use the `/link` command to reply to the message you want to link to, and the bot will give you the link for it. You can then use this however you like.

Or, you can try quotedrops, which are a fancier way to embed a drop within a page. Reply to a message with the `/quote` command and use the code provided by the bot to add a quoted drop.


### Why isn't there support for videos?

I don't want to pay to host really large media files. The site allows media embeds (including YouTube and Vimeo), you can always use those to add videos. Or you can convert videos to GIFs, the bot accepts those.  

### What’s the encryption and security of how data goes from my Telegram chat to my Stream?

Data is stored on Telegram's servers, and then sent to the bot, which lives on a Digital Ocean droplet. Encryption and security are taken care of by Telegram and the bot's token.  

### Can Streams be made private?

Yes, if you set your <b>keyphrase</b>, your Stream will only be visible at `streams.place/stream-name/your-keyphrase`.


### Why isn't my embed working?

Currently, the bot only renders iframe embeds from a few specific websites, if you want to embed something that isn't on this list, let me know and I'll add it. 

| Website | Allowed URLs |
|-|-|
| Youtube | www.youtube.com |
| Spotify | open.spotify.com |
| Vimeo | www.vimeo.com, player.vimeo.com |
| Google | docs.google.com, drive.google.com, www.google.com |
| Soundcloud | w.soundcloud.com |
| DailyMotion | www.dailymotion.com, dailymotion.com|
| Facebook | www.facebook.com, facebook.com |
| Pinterest | www.pinterest.com |
| Twitch | player.twitch.tv |
| Tumblr | www.tumblr.com |
| Instagram | www.instagram.com |
    
**Note:** Twitter is unsupported because their embeds do not use an `<iframe>`.

### Can I add my Stream to my own site?

Yes! There are two ways to do this. 

The simpler way is to add an `<iframe>` element to your page, with it's `src` attribute set to your Stream's URL. Below is a snippet that you can just copy-paste into a webpage after changing the "[username]" in the src to your own username.

```html
<iframe src="https://streams.place/[username]"></iframe>
```

If you're more technical, you can use the [API](/api) to fetch your Drops as JSON and render them on your own site.


### Is this free? How? Why?

Yes, it is. Firstly, becasue it was fairly easy to build, just under month of work. Second, at the moment, it costs me close to nothing to keep it running. 

However, "close to nothing" doesn't mean $0. Labour, servers and domains aren't exactly free. And so you can, of course, choose to <a href="https://www.buymeacoffee.com/joodaloop">send me money</a> if you feel like it.

### Will it always be free?

*Always* is a strong word. I'm not even sure how long Telegram will be around for. But all your data is stored in it's original format and will be avilable to export whenever you wish to do so. 

It's possible that there will one day be a paid tier that will provide things like higher quality images, video hosting, etc. But the most important bits will be free. 



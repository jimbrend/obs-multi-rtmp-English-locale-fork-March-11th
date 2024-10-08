# Pushing original contributor's down to compiled notes here before the Japanese starts on later lines
# Working on live streaming to multiple platform specifically on multi-tool usage: 
## Guide, Comments, and English translation by me... feel free to ping me here @jimbrend with any questions

Think I found what is the reliable multi-tool OBS plugin: https://www.youtube.com/watch?v=8m-IQfA_LV8&pp=ygUYbXVsdGkgc3RyZWFtIHR3aXRjaCB0b29s

The YouTube explains the installation... 

To actually install for an overview and easy step-by-step go here: https://obsproject.com/forum/resources/multiple-rtmp-outputs-plugin.964/

Then click Go to download: 

![image](https://github.com/user-attachments/assets/3e51c44e-6379-4150-a54a-61017c2e0a05)


Scroll down to latest version for your platform: 

![image](https://github.com/user-attachments/assets/023ac622-4fad-4e95-96ce-ff41621e4c5d)

For me it's this: 

![image](https://github.com/user-attachments/assets/279977af-b455-4084-b4f4-43aa50a2a2d0)

Once completed it will appear here: 

![image](https://github.com/user-attachments/assets/0c276567-cd9e-470d-b62e-1d3bb067a063)

It is the multiple output:

 ![image](https://github.com/user-attachments/assets/e770d141-27c2-484c-9052-a879d63be986)

Then it looks like this: 

![image](https://github.com/user-attachments/assets/cb7fb77f-d251-49f0-bed0-4c098a581da2)

Add multiple "targets" as in Twitch, X, YouTube, [Zap.Stream](https://zap.stream/dashboard)

![image](https://github.com/user-attachments/assets/fc8d66a2-50fc-4841-9715-cb16f5c31292)


Now you can easily go live on multiple platforms with OBS-Studio at once, 


When you click start streaming it will go live with however you normally stream as the first platform such as Twitch or X, 

But then, clicking Start All will go live on all the other platforms you specify at once, as you so choose as shown:

![image](https://github.com/user-attachments/assets/583bb301-24c2-4bf6-aba0-f8bc978b5185)








More comments on this process below with background details...

(installation and source in the details: https://obsproject.com/forum/resources/multiple-rtmp-outputs-plugin.964/)
(curious if anyone uses another one?)

Elon tweeted steps here a while ago and streamed 3 times since this post and a few times since as well, this has gotten much better and many people are now streaming more often and it displays and is easily clickable on their avatar (luckily he was able to fix his audio problem he sounded like a chipmunk and was getting echo on the first one lol): https://x.com/marmars/status/1708195875510796673?s=20

I tried testing it once but I guess it uses the periscope backend, I think it's hard to connect and interact with a streamer/support them as there's no like easy way to subscribe/tip/bits etc. like easily in one about section and things now so feels like it's disjointed but definitely, X has potential: https://studio.twitter.com/producer/sources

I believe that is where you create a source, I've tested this multiple times now and it seems to want you to create a new source every time if you are doing this manually which is a bit of a UX issue having to click through too many screens-- my assumption X streaming is not yet popular because of many of these reasons (many UX improvements have occurred since, many popular journalists/media accounts have streamed now with better features including podcasts simultaneously with others... the platform on X also does allow you to create a source and stick to just one but there's two different modals you have to click through in your media producer tab) - but I believe it can show easily in your X feed, and then maybe from there could post links to Twitch too if you really wanted right now or to your other content etc. or have the old Periscope chat open/with that current tech it seems as though the chat is currently lacking in participation, as compared to live chat and monetary contributions made to streamers on other platforms- that's really an objective fact right now unfortunately on X for smaller-mid level streamers who are still attempting to build an audience.

i have confirmed this since you can simulcast to X, twitch, and Nostr/zap.stream at once and pop out and monitor all their chats on web 

The reliable multi-tool OBS plugin YouTube video with explanation: https://www.youtube.com/watch?v=8m-IQfA_LV8&pp=ygUYbXVsdGkgc3RyZWFtIHR3aXRjaCB0b29s
(installation and source in the details: https://obsproject.com/forum/resources/multiple-rtmp-outputs-plugin.964/)
(curious if anyone uses another one?)

If curious too https://zap.stream/ is another new platform you could multi-stream too that has a pretty niche streamer community there, the platform is not too saturated yet which could be a good thing for people streaming there (the new UX has since greatly improved with a new user dashboard, an old coworker created this platform https://git.v0l.io/Kieran), you have to login there with a Nostr pubkey, also if you leak your address or something by accident you can’t delete your Nostr broadcast (you can’t delete Nostr posts they’re hosted on multiple relays/servers, there’s no delete button)  But zap.stream uses AWS servers so I think it expires after 3 months… (Nostr caters to only text connections hosted in a decentralized/uncensored manner on its frontend, but can't store a lot of data so there is also like a streaming music service that uses AWS backend for the music being built on it as well as a ton of other projects, mostly all curated here if interested it is called wav.lake and there is an aggregation of all Nostr apps: https://github.com/aljazceru/awesome-nostr)  

The aforementioned observation is also resolved,  you don't have to record your broadcast if you don't want to either when going live on Nostr by adding the appropriate suffix as described here simply: https://github.com/v0l/zap.stream/issues/10#issuecomment-2265475048

It does incentivize ppl making/streaming micropayments there though which is cool (seems the market hasn't yet really accepted streaming payments imo), it starts you off with 1000 sats last time I checked at zap.stream and it’s 21/sats a min to upkeep the stream / about $1.50 - one of the wizards at my last job at Strike made zap.stream which is cool this Kieran fellow (https://x.com/_v0ld
https://github.com/v0l) I've made more $ on Zap.Stream in 2 years than X or Twitch, I never cashed out or made money on X and over 2 years ago I only ever made about $200 on Twitch

This is also a great interview between Odell and Kieran regarding the Zap.Stream platform and building it: https://www.youtube.com/watch?v=6wDrB3JvTss

Nostr user base kind of plateaued (I preface this from a normal/mainstream perspective only because nostr has had periods of growth to 35M users and slumps to what looks like 50k or less MAU from the numbers i can tell) though until maybe another killer app comes along, all the apps for those are interoperable though you login with the same pubkey for your account on all of them - Damus (if you're on Damus you see the same posts from popular users as users browsing on Iris, Amethyst, Snort.social, Astra.ninja interfaces too for the Nostr social feeds) Damus is the biggest one right now a Twitter clone on the App Store… it's a bit of an echo chamber for Bitcoin but people claim it's less toxic than X and you can't be banned there (a bit of a conundrum), one benefit is if you develop a social app or something similar you immediately connect to the 25 million or so userbase can login to your app and there's no KYC onboarding, IMHO...























# [Homepage / 主页](https://sorayuki.github.io/obs-multi-rtmp)

## 为什么首页是日语？ / Why is the homepage in Japanese?

因为最初是做给管人用的。

Because it's originally made for virtual Youtubers (VTubers).

# 声明 

近日发现百度贴吧有个叫 maggot 的用户在售卖此插件。咸鱼上也有，没得救了。 

本插件免费使用，作者不收取费用。 

举报之后百度贴吧找我要软件著作权证明，累不爱。 


# Announcement

This plugin is provided for free, without a fee. 

Recently a Baidu Tieba account 'maggot' is selling this plugin. Please, don't buy it.


# お知らせ

本プラグインは無償で提供されるものです。

最近、Baidu Tiebaに「maggot」というアカウント名のユーザーがこのプラグインを販売する行為をしています。

決して購入はしないでください。


# Donate

如果你觉得这个工具很有用想要捐赠，这里是链接。注意：这不是提需求的渠道。

このツールの開発に支援もとい投げ銭をしたいと思った方は以下のリンクからお願いします。(機能のリクエストは受け付けていません)

If you find this tool useful and want to doante, here is the link. (Please do not donate for feature requests.)

## [paypal / 贝宝](https://paypal.me/sorayuki0)

## alipay / 支付宝

![alipay](./docs/zhi.png) 

## wechat / 微信
![wechat](./docs/wechat.jpg)

## Build

This project uses obs-plugintemplate.   
Please refer to obs-plugintemplate to understand how it works.

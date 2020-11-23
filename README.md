# IPTV

Hi all,this is just a public list I compile in my hobby time. Feel free to fork or take whatever you want. I hope you all will be inspired to make more tidy playlists of your own.<br /> 

## Usage

All the M3U-playlist is very very experimental at the moment. The GoCast playlists is a public list of every link I have collect so far. No gurantee the link over there will work. Drop me a email if any of the links is not working. I don't expect any people to share their links although you are welcome too.<br />

At the moment I maintain 2 playlists at the GoCast2 section for an Malaysian/Singaporean audience:<br />

- https://exodiver.github.io/IPTV/Prototype/Gugong.m3u8 (Orient focused playlist - Chinese,Korean,Japanese)<br />
- https://exodiver.github.io/IPTV/Prototype/Istana.m3u8 (Malay/Indian  focused playlist - Malaysia,Indonesia,Major Thai/Arab/Turkish,Hindi/Bengali/Urdu/Malayalam/Punjabi,Tamil TV Channel)<br />

And an very very very very very very experiemental EPG:<br />
https://exodiver.github.io/IPTV/EPG/guide_71.xml<br />
https://exodiver.github.io/IPTV/EPG/guide_71.zip (In zip format)<br />

## Complaints FAQ

1. If link is down,do drop me a message. I have a day job too,so don't expect any quick support unless you want donate money or servers to me. <br />

2. I don't sell or trade IPTV list. If I don't share a link,it is because it does not work for me.<br />

3. Be considerate and civilised<br />

4. PLEASE don't rely it as your daily iptv day or use this list for your business. I change the contents of playlist all the time. So your channel goes missing,chances are that they link can't work for me and you.<br />

5. Some of the link (especially the Geo-Restricted link) can be play with tivimate/tvirl without the need for a VPN/Smart DNS. So if it can't be play with other iptv program,do consider using tivimate/tvirl. <br />

6. For sports channel lover,please support your cable tv provider. Their streams are the best,no doubt. I have never find a stable,fast and unofficial sports streaming link in my entire life,chances are you will feel the same <br />

7. None of the links is my work. I just choose to share my private collection of iptv links. <br />

## Playlist FAQs

1. Why the links can't work for me? <br />

Ans:<br />
a) Some links are locked to ip address of specific country. Which means you might been a vpn for the links to work.<br /> 
b) Some links are intently programmed by the tv station not to be play on media/iptv players like VLC.<br />
c) The tv station changes their link without notification. (They do all the time)<br />
d) Some TV station introduced DRM to their link to block non paying customers from watching their shows.<br />

2. Why the mediacorp links from singapore can't work for me? <br />

Ans:<br />
Mediacorp have implemented DRM for their links. Please use a IPTV players that supports playing DRM links.<br />

3. Why the links so slow or stuttering?  <br />

Ans:<br />
That is 100% the problem of the TV station. <br />

They might not have buy enough internet bandwidth to broadcast the links smoothly. <br />
They might not have designed the links to be watch by ten millions.<br />
They might not have protected the links from dddos attack by hackers<br />

Please understand the monthly cost of ensuring a smooth watching experience for a single channel often costs as much as buying a car in most countries. <br />

3. Any plans to create playlist in the MITV (chinese player format) that can be played in potplayer or any east asian media player?<br />

Ans:<br />
I love to but I am looking for a player that support epg in the xmltv format.<br />

4. Any plans to include p2p,rstp,vjms or whatever exotic links in the playlist?<br />

Ans:<br />
No.<br />

5. Any plans to create a new IPTV player based on the playlist?

Ans:<br /> 
No. I am not in the IPTV business. And there is so many players out there. Pick the favourite player or write your own player. <br />


6. What players do you recommend?<br />

Ans:<br />
Kodi with Addons or any player based on Google's Exoplayer <br />


7. What is this Referer=https://www.yahoo.com or |X-Forwarded-For<br />

Ans:<br />
To take advantage of Google's Exoplayer magic ability to create altered HTTP headers so that players can play some links that usually can't be played. 

They don't work for most IPTV players.<br />

8. Do you want to start an IPTV reseller business with me?<br />

Ans:<br />
No. I am not in the IPTV business. The profit are quite low plus you might find yourself in legal trouble<br />


9. Are you a IPTV reseller using this to promote your business? <br />

Ans:<br />
No. I am not in the IPTV business. I am just an office worker.<br />

10. Why are you doing all this? <br />

Ans:<br />
As a hobby<br />


## EPG FAQs

1. What software did you use to make the EPGs  <br />

Ans:<br /> Webgrabplus. It is 5 Euros a year.<br />

2. Why no tv guide for my channel?<br />

Ans:<br /> Because no one published a tv guide for your channel on the internet. If there isn't one,I can't do anything.<br />

3. Why the tv guide for my channel does not appear,despite it being in the EPG?

Ans:<br /> 
1) Please check that the address for EPG in your player is https://exodiver.github.io/IPTV/EPG/guide_71.xml <br />
2) Please keep and don't alter the tvg-id="". It is there for a reason. Only alter the tvg-id="" if you are not using the EPG @ https://exodiver.github.io/IPTV/EPG/guide_71.xml or https://exodiver.github.io/IPTV/EPG/guide_71.zip <br />


5. Why do I have to follow the tvg-id="" value?

Ans:<br /> 
To give flexbility to user who might want to use a different channel name.  <br />

Like maybe 動物星球頻道,instead of Animal Planet. <br />

Or maybe TV3,instead of TV3 (Lativa).<br />

This ensures that player is able to connect to the correct TV listing for the channel,regardless of the channel name.<br />

## Thanks

1. Collection of resources dedicated to IPTV: https://github.com/iptv-org<br />
The Russian Guy who started it all. And still the top dog.<br />

2. Boomski: https://github.com/boomski/TV<br />
The Belgium guy that is a legend in IPTV link Collection<br />

3. Bertperrisor: https://github.com/freeview/iptv<br />
Best Resource for Singapore,Malaysia TV<br />

4. Geonsey: https://github.com/geonsey/Free2ViewTV<br />
Best Collection of Legal IPTV Link for the north america stations.<br />

5. Billacablewala: https://github.com/billacablewala/m3u8<br />
Very Messy Indian List. But provide a hint to get Indian Channel<br />

6. Thanh51:https://github.com/thanh51/repository.thanh51<br />
Nuumber one guy for the vietnam links<br />

7. Fotvnet: https://github.com/fotvnetwork<br />
The site to go for pinoy channels.<br />

8. SPX372928: https://github.com/SPX372928/MyIPTV<br />
Best collection of all china iptv list that has ever been released to the internet. Lengendary kind soul within a chinese iptv community who tends to ask for money to share public iptv channels.<br />

9. Hououinkami: https://github.com/hououinkami/AppleTV<br />
Japanese/Japanophile who loves everything east asia. But his japanese links are recently screwed by encryption.<br />

10. LaQuay: https://github.com/LaQuay/TDTChannels <br />
Spain number one IPTV Resource <br />

11. NoMaN-IPTV: https://github.com/NoMaN-IPTV<br />
Very promising Astro Replacement,I learn a thing or two from looking at his/her link.<br />

12. JKN22: https://github.com/jnk22/kodinerds-iptv<br />
Decent German TV List<br />

13. Magic-Dust: https://github.com/Magic-Dust/MagicDust<br />
Mainly for kodi,but contains some rare american tv links<br />

14. A long running dicussion of german,swiss and italian iptv links<br />
https://www.rundfunkforum.de/viewtopic.php?f=9&t=55352<br />

15. Webgrabplus: http://www.webgrabplus.com/<br />
Mother of all non commerical epg making. It is not free software though.<br />

Shout out to EDMW,电视盒子tv box分享站 and TV Boxs app!!!<br />

Love you all,<br />
Shell Shock<br />

----------------------------------------------------------------------------------------<br />

Hall of shame:<br />

1. Rizaldi of https://rizaldi.web.id/! <br />
Directly linking my entire playlist for his zaltv code and pass it off as his list. Have the cheeks to email asking me to revert some changes I made of my own list.<br />

2. Remy Turkey of https://github.com/remytr-org <br />
Reselling the list to aliexpress iptv sellers......<br />

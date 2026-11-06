# TiviMate playlists

Free TV channels for Android TV. The lists are made for the TiviMate app.

- Every channel was tested from South Africa, right down to the video, before
  it was added.
- Most channels come from the iptv-org project and from free services such as
  Pluto TV, Samsung TV Plus, The Roku Channel, Tubi, LG Channels, Vidaa and Xumo.
- Every link is a secure (https) link. Many Android TV apps block normal (http)
  links. The channel then shows in the list, but it does not play.

## How to add the channels

This one address has all 303 channels, sorted into 20 groups:

```
https://cdn.jsdelivr.net/gh/lnazo/tivimate-lists@main/combined.m3u
```

In TiviMate:

1. Choose **Add playlist**.
2. Choose **M3U playlist**.
3. Type or paste the address above.
4. Choose **Next**.

If the first address does not work, use this backup address. It is the same
file:

```
https://raw.githubusercontent.com/lnazo/tivimate-lists/main/combined.m3u
```

Please do not use a short link (for example bit.ly or is.gd). Some apps read
the short link page instead of the real file, and then show only one channel.

## Only one channel shows

First test with a small list. It has only 3 channels: Al Jazeera English,
SABC 1 and KBS World.

```
https://cdn.jsdelivr.net/gh/lnazo/tivimate-lists@main/test.m3u
```

- **3 channels show:** the app works. The problem is with the big list.
- **Only 1 channel shows:** the problem is with the app. Remove TiviMate,
  install it again, then add the list again.

## Smaller lists

Do you only want some of the channels? Use one of these lists. Take the main
address and change `combined.m3u` to the file name you want.

For example, for South African channels only:

```
https://cdn.jsdelivr.net/gh/lnazo/tivimate-lists@main/south-africa.m3u
```

| File | Channels | What is in it |
|---|---|---|
| `south-africa.m3u` | 13 | South African channels, with SABC |
| `africa.m3u` | 4 | Africanews, News Central, K24, AfroLandTV |
| `news.m3u` | 22 | World news in English, and weather |
| `sports.m3u` | 26 | NFL, NBA, MLB, NHL, UFC, golf, rugby, cricket, FIFA+ |
| `movies.m3u` | 20 | Free movie channels |
| `entertainment.m3u` | 60 | Drama, reality and game shows, comedy, food and lifestyle |
| `true-crime.m3u` | 13 | Forensic Files, Dateline, 48 Hours and more |
| `documentary.m3u` | 17 | Nature, history and science |
| `kids.m3u` | 29 | Children's channels and anime |
| `music.m3u` | 22 | MTV, Vevo, Stingray, Trace |
| `us.m3u` | 10 | American network and local news channels |
| `canada.m3u` | 12 | CBC, Global, CTV, Radio-Canada |
| `mexico.m3u` | 15 | Las Estrellas, Azteca Uno, Imagen TV, Canal Once |
| `asia.m3u` | 40 | Korea, Japan, India, Singapore, Thailand, Taiwan, Vietnam, Indonesia |
| `everything.m3u` | 127 | An older list. Please use `combined.m3u` instead |

## About the TV guide

The lists do not come with a TV guide. This was done on purpose.

Free TV guides use different channel names from these lists. Because of this,
the guide is often empty or shows the wrong programme. A wrong guide is worse
than no guide.

The channels still play normally. Only the guide row will be mostly empty. If
you want, you can add a TV guide yourself in TiviMate. It will show what it can
match.

## Please note

Free channels sometimes stop working. When this happens, the lists are tested
and built again. The addresses stay the same, so you do not need to add them
again.

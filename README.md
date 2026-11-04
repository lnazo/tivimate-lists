# TiviMate playlists

Free TV channels for Android TV. The lists are made for the TiviMate app.

- Every channel was tested before it was added.
- Most channels come from the iptv-org project and from free services such as
  Pluto TV, Samsung TV Plus, LG Channels, Vidaa and Xumo.
- Every link is a secure (https) link. Many Android TV apps block normal (http)
  links. The channel then shows in the list, but it does not play.

## How to add the channels

This one address has all 215 channels, sorted into 12 groups:

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
| `news.m3u` | 26 | World news in English |
| `south-africa.m3u` | 17 | South African channels, with SABC |
| `us.m3u` | 28 | American channels |
| `canada.m3u` | 21 | CBC, Global, CTV, Radio-Canada |
| `mexico.m3u` | 15 | Las Estrellas, Azteca UNO, Canal Once, Imagen TV |
| `asia.m3u` | 30 | Korea, Japan, Hong Kong, Taiwan, Singapore, the Philippines, Indonesia, Vietnam, Thailand, India |
| `sports.m3u` | 18 | Free sport |
| `movies.m3u` | 13 | Free movie channels |
| `entertainment.m3u` | 13 | Series and general entertainment |
| `documentary.m3u` | 15 | Documentaries |
| `kids.m3u` | 10 | Children's channels |
| `music.m3u` | 15 | Music |
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

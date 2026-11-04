# TiviMate playlists

Small, tested M3U playlists for Android TV. Every stream answered when tested
before being added. Secure (https) streams only: Android TV apps often refuse
plain http streams, so those channels would list but not play.

Channels come mostly from the iptv-org project and free services such as Pluto TV, Samsung TV
Plus, LG Channels, Vidaa and Xumo.

## One address for everything

All 215 channels in one file, split into 12 groups.

```
https://cdn.jsdelivr.net/gh/lnazo/tivimate-lists@main/combined.m3u
```

Mirror, same file:

```
https://raw.githubusercontent.com/lnazo/tivimate-lists/main/combined.m3u
```

In TiviMate: Add playlist, M3U playlist, paste, Next.

Do not use a URL shortener. Some players read the redirect page instead of the
file behind it and end up with one channel.

## If only one channel shows

Try `test.m3u` first, it has 3 channels only:

```
https://cdn.jsdelivr.net/gh/lnazo/tivimate-lists@main/test.m3u
```

Al Jazeera English, SABC 1, KBS World. If that shows 3, the app is fine and the
big file is the problem.

## Separate lists

| File | Channels | Content |
|---|---|---|
| `news.m3u` | 26 | World news in English |
| `south-africa.m3u` | 17 | South Africa, SABC included |
| `us.m3u` | 28 | US networks and free channels |
| `canada.m3u` | 21 | CBC, Global, CTV, Radio-Canada |
| `mexico.m3u` | 15 | Las Estrellas, Azteca UNO, Canal Once, Imagen TV |
| `asia.m3u` | 30 | Korea, Japan, HK, Taiwan, Singapore, PH, ID, VN, TH, India |
| `sports.m3u` | 18 | Free sport |
| `movies.m3u` | 13 | Free movie channels |
| `entertainment.m3u` | 13 | General entertainment |
| `documentary.m3u` | 15 | Documentaries |
| `kids.m3u` | 10 | Kids |
| `music.m3u` | 15 | Music |
| `everything.m3u` | 127 | The genre lists only, older file. Use `combined.m3u` |

## About the TV guide

The files carry no EPG link on purpose. Free guide sources use different
channel IDs from these playlists, so the guide would either stay blank or show
the wrong programme. Wrong data is worse than none.

Channels play normally, the guide row will be mostly empty. You can add a guide
by hand in TiviMate and it will match whatever it can.

## Note

Free streams rot. When channels stop working the files need rebuilding.

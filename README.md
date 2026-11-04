# TiviMate playlists

Small, tested M3U playlists for Android TV. Every stream answered when tested
before being added.

Channels come mostly from the iptv-org project and free services such as Pluto TV, Samsung TV
Plus, LG Channels, Vidaa and Xumo.

## One address for everything

All 242 channels in one file, split into 12 groups.

```
https://raw.githubusercontent.com/lnazo/tivimate-lists/main/combined.m3u
```

Short form: `https://is.gd/lubatv`

In TiviMate: Add playlist, M3U playlist, paste, Next.

## Separate lists

| File | Channels | Content |
|---|---|---|
| `news.m3u` | 30 | World news in English |
| `south-africa.m3u` | 17 | South Africa, SABC included |
| `us.m3u` | 28 | US networks and free channels |
| `canada.m3u` | 21 | CBC, Global, CTV, Radio-Canada |
| `mexico.m3u` | 25 | Las Estrellas, Azteca, Canal Once, Telehit |
| `asia.m3u` | 32 | Korea, Japan, HK, Taiwan, Singapore, PH, ID, VN, TH, India |
| `sports.m3u` | 20 | Free sport |
| `movies.m3u` | 14 | Free movie channels |
| `entertainment.m3u` | 18 | General entertainment |
| `documentary.m3u` | 16 | Documentaries |
| `kids.m3u` | 12 | Kids |
| `music.m3u` | 16 | Music |
| `everything.m3u` | 143 | All the genre lists combined |

## About the TV guide

The files carry no EPG link on purpose. Free guide sources use different
channel IDs from these playlists, so the guide would either stay blank or show
the wrong programme. Wrong data is worse than none.

Channels play normally, the guide row will be mostly empty. You can add a guide
by hand in TiviMate and it will match whatever it can.

## Note

Free streams rot. When channels stop working the files need rebuilding.

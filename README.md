# TiviMate playlists

Small, tested M3U playlists for Android TV. Every stream was checked and
answered before being added.

Channels come mostly from the iptv-org project and the free streaming services (Pluto TV,
Samsung TV Plus, LG Channels, Vidaa, Xumo and similar).

## Playlists

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

## How to use

In TiviMate: Add playlist, M3U playlist, paste one of these:

```
https://raw.githubusercontent.com/lnazo/tivimate-lists/main/news.m3u
https://raw.githubusercontent.com/lnazo/tivimate-lists/main/south-africa.m3u
```

Swap the last part for any file name above.

Each file carries its own guide (EPG) link in the header, so TiviMate picks up
the TV guide automatically.

## Note

Free streams rot. If channels stop working the file needs rebuilding.

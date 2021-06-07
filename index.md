# The beautiful CLI of MrPlayer

![player](assets/main.png)

Suggested using windows terminal becuse it suports
many languages when extracting lyrics.

Terminal theme 'is One Half Dark'

---

## Playing Song

For playing song go to directory where the song is and type this command -

```powershell
mpc -ps "<song name.mp3>"
```

---

## Lyrics
MrPlayer-CLI gets lyrics by extracting it from Genius. com

You need to have a genius api key and in order to get it

you should have an account in Genius. com.

Just paste your api key in 'C:/Users/your username/.MrPLayer/api_ket.txt'


1. For getting lyrics type this command -

```powershell
mpc -gl "<song name>"
```
2. For singer specific song lyrics type this command -

```powershell
mpc -gl "<song name>" -si "<singer name>"
```
[Click here to know steps to get api key](Genius_api_key.md)

---

## Source Code

For knowing the source code of MrPlayer-CLI type this command -

```powershell
mpc -sc
```
---

## Adding sondtracks and folder to 'MrPlayer-songs'

1. To copy sountrack to MrPlayer-songs folder type this command -

```powershell
mpc -at "<path to track>"
```

2. To move sountrack to MrPlayer-songs folder type this command -

```powershell
mpc -m -at "<path to track>"
```

3. To copy all MP3 files inside a folder to MrPlayer-songs type this command-

```powershell
mpc -af "<path to folder>"
```

4. To move all MP3 files inside a folder to MrPlayer-songs type this command-

```powershell
mpc -m -af "<path to folder>"
```

---

## Version

To know the version type this command -

```powershell
mpc -v
```

---

### tinytag
---
https://github.com/devsnd/tinytag

```py
from tinytag import TinyTag
tag = TinyTag.get('/some/music.mp3')
print('This track is by %s.' % tag.artist)
print('It is %f seconds long.' % tag.duration)


tag.album
tag.albumartist
tag.artist
tag.audio_offset
tag.bitrate
tag.comment
tag.composer
tag.disc
tag.disc_total
tag.duration
tag.filesize
tag.genre
tag.samplerate
tag.title
tag.track
tag.track_total
tag.year

tag = TinyTag.get('/some/music.mp3', image=True)
image_data = tag.get_image()


```

```
```

```
```



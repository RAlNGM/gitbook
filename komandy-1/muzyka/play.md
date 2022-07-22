---
description: >-
  Воспроизведите треки из YouTube, SoundCloud, Spotify, Twitch, Message
  Attachments or HTTP url.
---

# Play

### Воспроизведение из YouTube

Вы можете предоставить ссылку, название или ссылку плейлист

```
!play <youtubeURL | songName | playlistURL>
```

> Пример:
>
> _**`!play petit poney`**_\
> _**`!play https://youtube.com/watch?v=ylORW5HCVxa`**_\
> _**`!play https://www.youtube.com/playlist?list=PLpGf9ti2mrOX8iHFjqmg0r8qBU7BV0GF4`**_

{% hint style="info" %}
Отправка ссылки на музыку из плейлиста не добавит ее полностью. Если вы хотите добавить полный плейлист, укажите исходную ссылку на плейлист, чтобы добавить его в очередь.
{% endhint %}

### Воспроизведение из SoundCloud

```
!play <soundCloudURL>
```

> Пример:
>
> _**`!play https://soundcloud.com/yungraptileontherun/sets/yung-bratz-lofi`**_

### Воспроизведение из Spotify

{% hint style="warning" %}
На данный момент недоступно из-за санкций против России.
{% endhint %}

```
!play <songURL | albumURL | playlistURL>
```

> Пример:
>
> `!play https://open.spotify.com/track/5wqFGXrd6gHaDcVMY5DDbd?si=ac579993a54b42f4`
>
> _**`!play https://open.spotify.com/album/4sA7IyvdIFpeOPBftpjetk?si=KcrQlofrTBuE8w_tBVzEFg`**_
>
> _**`!play https://open.spotify.com/playlist/0EWZfCi9rD9eswHPQAktvg?si=JD7aSii5SLusGpZ6DGeLYQ`**_

### Воспроизведение из прикреплённых файлов

```
!play <messageAtachment>
```

![A simple example](https://i.imgur.com/qnR0fSy.png)

![A simple example](https://i.imgur.com/r0L5564.png)

### Воспроизведение из HTTP URL

```
!play <url>
```

> e.g:\
> _**`!play http://cdn.nrjaudio.fm/audio1/fr/30001/mp3_128.mp3`**_

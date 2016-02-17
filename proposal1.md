#### GET users/hosts
Shows all featured channel hosts

```json
[
  {
    "id": 1,
    "name": "Mojo Pollo",
    "description": "Encounters Network unites and mobilizes the body of Jesus Christ by teaching and imparting the power of intercession, prophetic ministry, and life in the Spirit.",
    "keywords": null,
    "url": "http://xpmedia.com/channel/xptv"
  },
  {
    "id": 2,
    "name": "Mojo Pollo Jr.",
    "description": "Encounters Network unites and mobilizes the body of Jesus Christ by teaching and imparting the power of intercession, prophetic ministry, and life in the Spirit.",
    "keywords": null,
    "url": "http://xpmedia.com/channel/xptv"
  },
]
```


#### GET users/{id}/videos
Shows all videos from a specific user

```json
[
  {
    "id": 201,
    "title": "A cool video #1",
    "description": "This is my description",
    "duration": 1234,
    "author": "Mojo Pollo",
    "thumbnail": "http://xpmedia.com/a-thumbnail.jpg",
    "url": "http://xpmedia.com/a-video.mp4",
    "date": "2016-01-01 10:40:52"
  },
  {
    "id": 202,
    "title": "A cool video #2",
    "description": "This is my description 2",
    "duration": 1234,
    "author": "Mojo Pollo",
    "thumbnail": "http://xpmedia.com/a-thumbnail-2.jpg",
    "url": "http://xpmedia.com/a-video-2.mp4",
    "date": "2016-01-01 11:40:52"
  },
]
```


#### GET users/{id}/streams
Shows all current live streams from a specific user

```json
[
  {
    "title": "A cool stream #1",
    "description": "This is my description",
    "duration": null,
    "author": "Mojo Pollo",
    "thumbnail": "http://xpmedia.com/a-thumbnail.jpg",
    "url": "http://akamai-cdn-feed-url-or-similar",
    "date": "2016-03-01 10:40:52"
  },
  {
    "title": "A cool stream #2",
    "description": "This is my description 2",
    "duration": null,
    "author": "Mojo Pollo",
    "thumbnail": "http://xpmedia.com/a-thumbnail-2.jpg",
    "url": "http://akamai-cdn-feed-url-or-similar",
    "date": "2016-03-01 11:40:52"
  },
]
```

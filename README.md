# SnAPI
Documentation of Snapchat's Private API

## /bq/snaptag_download (POST)
###### Request
```json
  {"image": "qr-add/6ba8bcc94beab846813625522c7e3d2f", 
  "req_token": "3a897d9eed9139d547384e3be5f89cd4ccf040fb7b11ad9aa9950ea3404a483a",
  "timestamp": 1422412632422,
  "username": "neuegram"}
```

###### Response
  ![Snaptag](https://lh6.googleusercontent.com/X9ROX2BkYbyBF2xI889T3YGTCC2PD17M5I4wOVRC8rlnvBSMn58r8k_wxXxKQr_s3WodaZLqwdU=w1342-h523)

## /discover/channel_list?region={country_code} (GET)
###### Response
```json
  {"channels": [
    {"position": 0,
    "name": "CNN - US",
    "filled_icon": "https://feelinsonice-hrd.appspot.com/discover-icons/cnn_filled.png",
    "inverted_icon": "https://feelinsonice-hrd.appspot.com/discover-icons/cnn_inv.png",
    "loading_icon": "https://feelinsonice-hrd.appspot.com/discover-icons/CNN_loading.png",
    "intro_movie": "/discover/intro_videos?publisher\u003DCNN\u0026intro_video\u003D1cf6b4eb-7cd4-4a8a-9f62-e761a62095a6",
    "primary_color": "#CC0000",
    "secondary_color": "#FFFFFF",
    "edition_id":5757884394635264,
    "dsnaps_data" :[
      {"url": "/discover/dsnaps?edition_id=5757884394635264&dsnap_id=6247679780716544&hash=5d93d8ab7fd3f50e2a25f66f8f54f9116edfe58209518b046c67a78017739403&publisher=CNN",
      "dsnap_id": 6247679780716544,
      "hash": "5d93d8ab7fd3f50e2a25f66f8f54f9116edfe58209518b046c67a78017739403",
      "color": "#CC0000",
      "ad_type": 0, 
      "media_type": "video"},
      {"url": "/discover/dsnaps?edition_id=5757884394635264&dsnap_id=5171705647464448&hash=9f0471f9b854b274038425c932ddbdbc9c84b3bc41cf84cdc876fcb83cce05f9&publisher=CNN",
      "dsnap_id": 5171705647464448,
      "hash": "9f0471f9b854b274038425c932ddbdbc9c84b3bc41cf84cdc876fcb83cce05f9",
      "color": "#CC0000",
      "ad_type": 0,
      "video_id": "4013681568001",
      "media_type": "video"}
    ]}
  ]}
```

## /discover/video_catalog_v2?edition={edition_id}&platform={ios/android} (GET)
###### Response
```json
  {"results": [
    {"video_id": "4013774548001",
    "video_sequence": [
      {"type": "primary",
      "url": "https://c.brightcove.com/services/mobile/streaming/index/master.m3u8?videoId=4013774548001&pubId=3936484261001",
      "renditions": [
        {"bitrate": 487000,
        "height": 224,
        "width": 400,
        "size": 12630039,
        "url": "https://brightcove01-secure.brightcove.com/13/3936484261001/201501/837/3936484261001_4013801527001_L2FwcGhvc3RpbmdfcHJvZC9ibG9icy.mp4",
        "codec": "H264",
        "container": "MP4",
        "duration": 205952}
      ]}
    ]}
  ]}
```

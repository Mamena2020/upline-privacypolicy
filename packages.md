
``` yaml
name: upline
description: Songwriters App.
version: 1.2.3

environment:
  sdk: '>=3.0.1 <4.0.0'

dependencies:
  flutter:
    sdk: flutter


  # The following adds the Cupertino Icons font to your application.
  # Use with the CupertinoIcons class for iOS style icons.
  cupertino_icons: ^1.0.2
  
  # basic packages
  uuid: ^3.0.7
  path_provider: ^2.0.15
  permission_handler: ^10.2.0
  material_design_icons_flutter: ^6.0.7096
  dropdown_button2: ^2.1.3
  shimmer: ^3.0.0
  collection: ^1.17.0

  # persistence
  hive: ^2.2.3 # nosql database. stored all data 
  shared_preferences: ^2.0.18

  # networking
  dio: ^5.3.3 # network request
  udp: ^5.0.3 # realtime sound effect x ffmpeg

  # auth
  jwt_decode: ^0.3.1 # jwt decoding

  # image
  flutter_image_compress: ^2.0.4 # compress image 

  # audio 
  flutter_sound: ^9.2.13 #record & play audio
  ffmpeg_kit_flutter: ^6.0.2 # multimedia framework | audio effect | read media info etc..
  audio_session: ^0.1.16 # focusing audio session to the app
  
  # Audio compressing
  flutter_lame: ^1.0.2 # compress wav to mp3 
  wav: ^1.2.0  # compress wav to mp3 
  
  # ui 
  flutter_speed_dial: ^7.0.0 # floating menu
  animate_do: ^3.0.2  # animated any widget
  introduction_screen: ^3.1.8 # app guide 
  step_progress_indicator: ^1.0.2 # proggress indicator
  reorderable_grid_view: ^2.2.6 # re order grid
  flutter_xlider: ^3.5.0 # slider
  
  # file
  file_picker: ^5.3.1 # get file
  mime: ^1.0.4 # get file type from byte data
  open_file_plus: ^3.4.1 # open file in OS

  # ads
  google_mobile_ads: ^3.0.0 # admob ads

  # open store
  open_store: ^0.5.0 # open apps store
  
  # devices
  headset_connection_event: ^3.0.0 # headset detection

  # text editing 
  flutter_quill: ^8.0.0 # text editor

  # webview
  webview_flutter: ^4.4.1 # show web page, html 

```

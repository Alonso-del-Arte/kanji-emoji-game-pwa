# Kanji Emoji Game PWA

WORK IN PROGRESS

The kanji emoji game. This will be quick and dirty to serve as a proof of 
concept. Plain JavaScript only. Might use local storage to hold user scores.

I briefly considered using JSONC or JSONL, but decided that the original JSON 
format is perfectly fine for my purpose here.

This is going to be like those simple matching games, but instead of matching 
two of the same item, it's going to be kanji and emoji. For example, rather than 
matching '&#x5C71;' and '&#x5C71;', or '&#x1F3D4;' and '&#x1F3D4;', this game 
will be matching '&#x5C71;' and '&#x1F3D4;'.

For the Android version, I was using Kotlin Multiplatform, which I'm aware can 
also do iOS. But I might continue working on the iOS version separately in 
Xcode. Or maybe I'll just focus on this progressive web app and not worry about 
trying to do this native, especially because of all the Gradle headaches with 
Kotlin Multiplatform.

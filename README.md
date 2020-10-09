# UE4OculusQuestTemplate
UE4のVR TemplateをOculus Questで動作するように調整したものです。

# Oculus 公式のサンプルが公開されました
以下のRepositoryにて公式のサンプルが公開されています。<br>
ハンドトラッキングのサンプルも含まれていますので、そちらを試したい方にもオススメです。<br>
https://github.com/Oculus-VR/UnrealEngine
<br>詳しいアクセス方法などは下記を御覧ください。<br>
https://developer.oculus.com/documentation/unreal/unreal-samples/?locale=ja_JP

## UE4Version
4.22.2

4.23.1

4.24.3

4.25.0(master)

※ 4.25からSDK/NDKの設定が大きく変わりました。詳細は下部のError UE4.25をご覧ください


## Demo
![Quest](https://user-images.githubusercontent.com/8968076/59157831-7ae12080-8aec-11e9-8fd5-ea1dfeb05066.gif)

## Error
【UE4.22】 Accept SDK License押下時に Unable to read xxx/Android/package.xml と出た場合、GitのUE4.22からpackage.xmlを取得してください

【UE4.25】
Android SDK および NDK の更新
UE4.25からは従来のAndroidWorksからAndroid StudioでのSDK/NDKの設定となりました。
詳しくは下記のドキュメントにありますが、設定が少し複雑です。
https://docs.unrealengine.com/ja/Platforms/Mobile/Android/Setup/AndroidStudio/index.html

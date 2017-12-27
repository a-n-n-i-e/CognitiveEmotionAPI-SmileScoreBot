# CognitiveEmotionAPI-SmileScoreBot

## 概要 | Description

[Microsoft Cognitive Services Emotion API](https://www.microsoft.com/cognitive-services/en-us/emotion-api) および [Microsoft Bot Framework v3.0](https://www.botframework.com/) による 表情判定BOT サンプルです。
動作には Emotion API のサブスクリプションが必要です。
開発環境や作成方法については [5ステップでズバリ！笑顔判定BOT を作成しよう by Microsoft Bot Framework and Cognitive Services] (https://blogs.msdn.microsoft.com/bluesky/2016/11/15/5-step-tutorial-smilescorebot-bot-framework-cognitive-services-ja/) をご覧ください。

This is emotion auto-detect sample bot by [Microsoft Cognitive Services Emotion API](https://www.microsoft.com/cognitive-services/en-us/emotion-api) and [Microsoft Bot Framework v3.0](https://www.botframework.com/)
Emotion API Subscription needed to make this work.
Check 5 steps tutorial to prepare and build this app; [Just 5 Steps Tutorial: “Smile Score Bot” by Microsoft Bot Framework and Cognitive Services](https://blogs.msdn.microsoft.com/bluesky/2016/11/15/5-step-tutorial-smilescorebot-bot-framework-cognitive-services-en/)


## 使用環境 | Environment

Windows 10 (Anniversary Update), Visual Studio 2015 (Enterprise, Update 3), Microsoft Bot Framework v3.0 テンプレート で作成されています。
環境構成方法は上記チュートリアル、または [Bot Framework を使うための開発環境](http://qiita.com/annie/items/edc26c0ee9603e84a2e4#bot-framework-%E3%82%92%E4%BD%BF%E3%81%86%E3%81%9F%E3%82%81%E3%81%AE%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83) をご覧ください。

Developed on Windows 10 (Anniversary Update), Visual Studio 2015 (Enterprise, Update 3) and Microsoft Bot Framework v3.0 Template.
How to get envorpnment, please refer tutorial above or [Environment for Bot Framework development](http://qiita.com/annie/items/edc26c0ee9603e84a2e4#bot-framework-%E3%82%92%E4%BD%BF%E3%81%86%E3%81%9F%E3%82%81%E3%81%AE%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83).


## 利用方法 | How to Use
ダウンロード後、Visual Studio のソリューションファイル (SmileScoreBot) を開き、ビルドを行って必要なライブラリの読み込みを行ってください。
Controllers > MessagesController.cs を開き、47行目の YOUR_SUBSCRIPTION_KEY を Emotion Api のサブスクリプションキーをコピーして差し替えます。
メッセージを英語にする場合は /* [ja] */ の行ををコメントアウトし、/* [en] */ の行のコメントを外してください。

After download bits, open solution file (SmileScoreBot) and make build so to import nesessary libraries.
Open Controllers > MessagesController.cs, paste and replace YOUR_SUBSCRIPTION_KEY with Emotion API Subscription Key on line 47.
Comment out /* [ja] */ lines and clear commented lines /* [en] */ to change message to English.

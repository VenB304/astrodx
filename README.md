### *FROM MAY 2024, ISSUES WITHOUT ENGLISH TRANSLATION WILL BE CLOSED WITHOUT EXPLANATION*

# AstroDX
![GitHub release (latest by date)](https://img.shields.io/github/v/release/2394425147/maipaddx?label=stable)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/2394425147/maipaddx?include_prereleases)](https://github.com/2394425147/maipaddx/releases/latest)
[![Discord](https://dcbadge.vercel.app/api/server/6fpETgpvjZ?style=flat)](https://discord.gg/6fpETgpvjZ)

AstroDX (Formerly MaipadDX) is a mobile maimai simulator intended for those who do not yet have access to a cabinet, those who want to practice, and everyone interested in maimai who otherwise could not play the arcade game.

# Open-source status

We initially intended for AstroDX to be fully open-source after it has been uploaded to official app stores, but as the game contains paid assets, we may only be able to partially open-source AstroDX.

However, if you have issues, please don't hesitate to point it out in issues and we'll try to answer them as best as we can.

This game is a clean-room implementation of maimai, and has been developed without using any original arcade data.

- For simai interpreter and serializer used in AstroDX: [SimaiSharp](https://github.com/reflektone-games/SimaiSharp)
- For game open-source parts: [AstroDX core-dump](https://github.com/2394425147/maipaddx/tree/main/core-dump)

# Q&A

## Which version should I download?

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/2394425147/maipaddx?include_prereleases)](https://github.com/2394425147/maipaddx/releases/latest)  
v2.0 is the latest version cycle, with full support for FESTiVAL features, and a superset of simai3 syntaxes (deserialized via [SimaiSharp](https://github.com/reflektone-games/SimaiSharp)).  
v2.0 also includes performance optimizations, a better interface, and more customization. However, it's still in its pre-beta cycle, which means features are yet to be finalised, and very much prone to changes.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/2394425147/maipaddx?label=stable)  
If you prefer a stable build instead, v2.0.0.beta.pre.98.5 is the **latest stable version**. You should use this if you prefer a long-term support experience.

## Desktop version, and controller support

Currently, AstroDX hasn't release desktop (Windows/Linux/macOS) version, we also not release any official controller support yet.

Products like "ADX controller", "BDX", etc, some the name might sounds similar with AstroDX, are not associated with us.

We are developing our controller API for desktop version, and our API will public with desktop version as well, you may contact the controller's origial manufacturers to asking them support AstroDX afterward to enjoy our game.

## Wait, is there a version for iOS?
Well... It's a bit finnicky. There's a major change happening regarding TestFlight (which you can read more on our Discord server [here](https://discord.com/channels/892807792996536453/1210127565986205726/1238882652040200373)).

**TL;DR: AstroDX for iOS is migrating to a new developer account, and during this period we won't free up more tester slots. However, we hope to finish this transition soon.**

In the meantime, you will still be able to join the tests as per usual.

You can join the test at [TestFlight Group A](https://testflight.apple.com/join/rACTLjPL) or [TestFlight Group B](https://testflight.apple.com/join/ocj3yptn) or [TestFlight Group C](https://testflight.apple.com/join/CuMxZE2M) or [TestFlight Group D](https://testflight.apple.com/join/T6qKfV6f).

![TestFlight](https://img.shields.io/github/downloads/2394425147/maipaddx/total?label=TestFlight)

*Each public link only can hold 10k players (they counted by Apple ID, not devices), so please DO NOT rejoin the test if you already have AstroDX installed.*

## Are there any tutorials on importing?

Detailed guides for Android and iOS are available here:
- [Installation Guide for Android](https://sht.moe/adx-android)
- [Installation Guide for iOS/iPadOS](https://rentry.org/adx_ios)

## Can I use charts transcribed from the official arcade game maimai?

We **don't recommend** doing this, as it violates SEGA's policies.

## I'm having some issues...

You can open an issue [here](https://github.com/2394425147/maipaddx/issues).

**As of May 2024, an attached English translation of the issue is mandatory.**

We welcome issues written in Chinese, Japanese and English. However, it would be strongly suggested to provide translations (even using online translator) to English when submitting them, thus other people could understand as well.

When submitting issues, please always ensure that you are running the latest released version. We also recommend reviewing existing issues to avoid duplication of questions or concerns.

Alternatively, on our [Discord server](https://discord.gg/6fpETgpvjZ), we also have a help forum dedicated for issues, an faq, as well as a suggestions channel for feedback.

## 質問がある場合

イシューは[こちら](https://github.com/2394425147/maipaddx/issues)から提出できます。

中国語、日本語、英語でのイシュー投稿を大歓迎します。ただし、他の方も理解できるように、イシューを提出する際には英文への翻訳を（オンライン翻訳を使用しても）お願いいたします。

イシューを提出する際には、最新バージョンを使用していることチェックしてください。また、重複を避けるため、既存のイシューを確認することをおすすめします。

また、AstroDXの[Discordサーバー](https://discord.gg/6fpETgpvjZ)には、質問用、FAQ、フィードバックのための提案チャンネルもご用意しています。

## 當遇到了問題的時候

可以在[這裏](https://github.com/2394425147/maipaddx/issues)提出issue。

我們歡迎使用中文、日文和英文編寫的issue。然而，在提交問題時，強烈建議提供英文翻譯（甚至使用線上翻譯），以便其他人也能理解。

提交issue時，請務必確保您正在執行的是最新發布的版本。 我們也建議審查現有issue，以避免重複或疑慮。

此外，在我們的[Discord伺服器](https://discord.gg/6fpETgpvjZ)上，還有一個專門解決問題的幫助論壇、常見問題解答以及回饋及建議頻道。

Happy playing!

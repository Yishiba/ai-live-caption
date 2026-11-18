---
title: AI Live Caption — Privacy Policy
---

# AI Live Caption — Privacy Policy

**Effective date:** 2026-11-18

**App:** AI Live Caption (Android, package `com.fair.aitranslator`; iPhone, bundle ID `com.yishiba.ailivecaption`)

**Developer:** Yishiba · Contact: chuishuipeng+ailivecaption@gmail.com

[中文版本见下方](#中文版)

AI Live Caption turns speech, whether it plays on your phone or happens around you, into live captions and translations. It is built to work **on your device**. This policy explains what the app handles and why. Sections 1–5 describe the Android app; the iPhone app works differently in a few ways and is described in [section 6](#6-on-iphone).

## 1. Audio

- **What:** When you start captions, the app listens to one sound source you choose. That is either the microphone, or audio played by other apps (Android's audio playback capture, which asks for your consent every time).
- **How it is used:** Audio is turned into text on your device, in real time, by on-device speech recognition models.
- **What we don't do:** We do not record or save audio, and we never send audio off your device. The screen-capture permission is used only to capture *audio*. The app does not capture images of your screen.
- **Files you pick:** When you transcribe a recording or video, the app reads only the file you chose, on your device. The file is not uploaded or copied. Subtitles you export are saved or shared only where you choose.

## 2. Caption text and caption history

- Recognised text and its translation are shown on screen. The most recent captions (up to 500) are saved **only on your device**, so you can reread and copy them in "Caption history".
- You can clear the history in the app at any time. Uninstalling the app deletes it.
- Translation is done on your device by Google ML Kit's on-device translation. Caption text is not sent to us or to any server for translation.

## 3. Network connections

The app uses the internet only to:

- **Download speech models** the first time a language needs them: from Hugging Face (`huggingface.co`, or the mirror `hf-mirror.com` if that fails) and, for the voice-activity model, from GitHub (`github.com` release files);
- **Download translation models** through Google ML Kit (Google servers);
- **Send crash reports** (see section 4).

These downloads don't include your audio or captions. Like any internet request, they reveal technical information such as your IP address to the provider, under that provider's own privacy policy. On mobile data, the app asks before downloading large models.

## 4. Crash reports

To find and fix crashes, the app uses **Firebase Crashlytics** (Google). It collects technical data only:

- **When the app crashes:** the crash stack trace and the app's state at that moment;
- **Each time the app is opened:** app version, Android version, device manufacturer and model, network connection type, and when the session started (used to count how many users a crash affects);
- **Random installation identifiers** created by Firebase, which don't identify you or your device and change if you reinstall the app.

This data contains **no audio and no caption text**. See [Firebase's privacy information](https://firebase.google.com/support/privacy).

## 5. Permissions

| Permission | Why |
|---|---|
| Microphone (`RECORD_AUDIO`) | Recognise speech around you when you choose "Around you" |
| Audio playback capture (screen-capture consent) | Recognise audio from other apps when you choose "Phone audio". Audio only, no screen images |
| Display over other apps | Show captions on top of the app you are watching |
| Notifications, foreground service | Keep captions running while you use other apps, and let you stop them from the notification |
| Internet, network state | Download models; avoid large downloads on mobile data without asking |

<a id="6-on-iphone"></a>
## 6. On iPhone

The iPhone app uses Apple's own on-device frameworks and **collects no data at all**:

- **Audio:** the app listens only through the microphone, and only while captions are running. Speech is turned into text on your iPhone by Apple's on-device speech recognition. Audio is never recorded, saved or sent anywhere.
- **Translation and read-aloud:** done on your iPhone by Apple's Translation framework and the system voices. Caption text is not sent to us or to any server.
- **Downloads:** the speech assets, translation languages and voices are downloaded and managed by iOS itself from Apple, when you choose a language (the app explains each download first). The app makes no internet connections of its own.
- **Caption history:** up to 500 recent captions, stored only on your iPhone. You can clear it in the app; deleting the app deletes it.
- **Purchases:** handled entirely by Apple. We never see your payment details or Apple Account. To keep the free minutes from resetting, how much of them you have used is stored in your iPhone's keychain, on the device only.
- **No crash reporting, analytics or advertising SDKs** are included. If you choose to share crash data with developers in iOS settings, Apple provides it to us under Apple's privacy policy, without audio or captions.
- **Permission:** Microphone, to caption the speech around you.

## 7. What we don't collect

No account, no advertising, no analytics profiles, no contacts, no location, no payment details. We don't sell or share personal data.

## 8. Children

The app is not directed at children under 13 and doesn't knowingly collect their personal information.

## 9. Changes

If this policy changes, we'll update this page and its effective date.

## 10. Contact

Questions: chuishuipeng+ailivecaption@gmail.com

---

<a id="中文版"></a>

# AI 实时字幕 — 隐私政策

**生效日期：** 2026-11-18

**应用：** AI 实时字幕（Android，包名 `com.fair.aitranslator`；iPhone，Bundle ID `com.yishiba.ailivecaption`）

**开发者：** Yishiba · 联系方式：chuishuipeng+ailivecaption@gmail.com

AI 实时字幕把手机里播放的或身边的语音实时转成字幕和译文，设计上**尽可能在手机本地完成**。本政策说明应用会处理哪些信息、为什么。第 1–5 节说明的是 Android 版；iPhone 版有几处不同，见[第 6 节](#6-iphone-版)。

## 1. 音频

- **处理什么：** 开始字幕后，应用只收听你选择的一种声音来源：麦克风，或其他应用播放的声音（Android 的音频播放捕获，每次开始前都会征得你的同意）。
- **怎么使用：** 由手机上的离线语音识别模型实时转成文字。
- **不做什么：** 不录音保存，也不把音频发送到手机以外。屏幕共享授权**只用于采集声音**，应用不会截取屏幕画面。
- **你选择的文件：** 用「文件转字幕」时，应用只在手机上读取你选的那个文件，不会上传或复制它。导出的字幕只保存或分享到你指定的地方。

## 2. 字幕文字与字幕记录

- 识别出的文字和译文会显示在屏幕上。最近的字幕（最多 500 条）**只保存在你的手机里**，方便在「字幕记录」中回看和复制。
- 你可以随时在应用内清空；卸载应用会一并删除。
- 翻译由 Google ML Kit 的离线翻译在手机本地完成，字幕文字不会发送给我们或任何服务器进行翻译。

## 3. 网络连接

应用只在以下情况联网：

- 某种语言首次使用时**下载语音识别模型**：来自 Hugging Face（`huggingface.co`，失败时使用镜像 `hf-mirror.com`），语音活动检测模型来自 GitHub（`github.com` 发布文件）；
- 通过 Google ML Kit（Google 服务器）**下载翻译模型**；
- **发送崩溃报告**（见第 4 节）。

这些下载不包含你的音频或字幕。与任何联网请求一样，对方服务器会看到 IP 地址等技术信息，适用其各自的隐私政策。使用移动网络时，下载较大的模型前会先询问你。

## 4. 崩溃报告

为了发现和修复崩溃，应用使用 **Firebase Crashlytics**（Google 提供），只收集技术信息：

- **应用崩溃时：** 崩溃堆栈和当时的应用状态；
- **每次打开应用时：** 应用版本、Android 版本、设备厂商和型号、网络连接类型、会话开始时间（用于统计一次崩溃影响了多少用户）；
- **Firebase 生成的随机安装标识符**：不能识别你本人或你的设备，重装应用后会变。

这些数据**不包含音频或字幕内容**。参见 [Firebase 隐私说明](https://firebase.google.com/support/privacy)。

## 5. 权限说明

| 权限 | 用途 |
|---|---|
| 麦克风（`RECORD_AUDIO`） | 选择「周围的声音」时识别身边的语音 |
| 音频播放捕获（屏幕共享授权） | 选择「手机里的声音」时识别其他应用的声音，只采集声音、不截取画面 |
| 显示在其他应用上层 | 在你观看的应用上方显示字幕 |
| 通知、前台服务 | 使用其他应用时让字幕持续运行，并可从通知栏停止 |
| 网络、网络状态 | 下载模型；在移动网络下避免未经询问的大流量下载 |

<a id="6-iphone-版"></a>
## 6. iPhone 版

iPhone 版使用苹果自带的本机框架，**不收集任何数据**：

- **音频：** 只通过麦克风收听，且只在字幕运行期间。由苹果的离线语音识别在 iPhone 上转成文字，不录音保存，也不发送到任何地方。
- **翻译与朗读：** 由苹果的翻译框架和系统语音在 iPhone 上完成，字幕文字不会发送给我们或任何服务器。
- **下载：** 语音识别资源、翻译语言包和朗读语音，由 iOS 系统在你选择语言时从苹果下载和管理（每次下载前应用都会先说明）。应用本身不进行任何联网。
- **字幕记录：** 最近的字幕最多 500 条，只保存在你的 iPhone 上，可在应用内清空，删除应用会一并删除。
- **购买：** 完全由苹果处理，我们看不到你的支付信息或 Apple 账户。为避免免费时长被重置，已用的免费时长记在 iPhone 的钥匙串中，只存在本机。
- **不含任何崩溃收集、统计或广告 SDK。** 如果你在 iOS 设置中选择与开发者共享分析数据，苹果会按其隐私政策把崩溃信息提供给我们，其中不含音频和字幕。
- **权限：** 麦克风，用于为身边的语音生成字幕。

## 7. 我们不收集的信息

没有账号体系、没有广告、不做用户画像分析，不读取通讯录和位置，不接触支付信息。我们不出售或共享个人数据。

## 8. 儿童

本应用不面向 13 岁以下儿童，也不会有意收集其个人信息。

## 9. 政策变更

本政策如有变更，会更新本页面及生效日期。

## 10. 联系我们

如有疑问：chuishuipeng+ailivecaption@gmail.com

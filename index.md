---
title: オンラインでホストされる手順
permalink: index.html
layout: home
---

# コンテンツ ディレクトリ

このコースのデモは、アクセラレータ キットのデモ [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG) に基づいています。

このトレーニングを実施する前に、デモについて理解しておくことが重要です。 いくつかのラボでは、サンプル ドキュメントと事前に作成された Teams 会議およびメールを利用します。

- [こちら](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles)のサンプル ドキュメントをすべて事前にダウンロードします。
- [こちら](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)の手順に従って、Teams 会議とメール スレッドをセットアップします。
- [こちら](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf)で説明されている対話型エクスペリエンスをよく理解してください。

    > **注:** 対話型エクスペリエンスの PDF ファイルは、デバイス (ダウンロード フォルダー) に直接ダウンロードされます。

- [こちら](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx)の最新のトレーニング デッキを確認してください。

## コースの説明

Microsoft Copilot の潜在的な変革力と、それが組織の効率に及ぼす影響を調べます。 このエクスペリエンスは、Copilot ライセンスを持たないエグゼクティブやビジネス リーダー向けに設計されたもので、効果的なプロンプトを作成する技法を掘り下げ、対話型エクスペリエンスを提供し、Microsoft Copilot for Microsoft 365 を日常のビジネス ワークフローにシームレスに統合して生産性とイノベーションを促進する方法の実例を示します。

この配信の主な目的は、次のとおりです。

- 効果的なプロンプトを作成する方法を教える
- Microsoft Copilot (Web スコープ) のデモを行い、対話型エクスペリエンスの初めから終わりまで参加者をガイドする
- Microsoft Copilot for Microsoft 365 のデモ - Microsoft Copilot (作業スコープ)、Word、Outlook、および Teams
- 参加者に Microsoft Copilot for Mobile をダウンロードして試すように勧める

## コース スケジュール (未確定) 

| # | トピック                                 | 詳細                                                                                          | 合計時間      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Copilot for Microsoft 365 で効果的なプロンプトを作成する | - プロンプトの技法スライド <br> - プロンプト作成スライド <br> - Copilot ラボ スライド | 5 から 10 分    |
| 2 | Web 上の Microsoft Copilot          | - Microsoft Copilot (Web モード) のデモ <br> - 対話型エクスペリエンス  <br> - "感想をお聞かせください" スライド | 35 分      |
| 3 | 職場での Copilot for Microsoft 365     | - Microsoft Graph スライド <br> - Word の Copilot、Microsoft Copilot (作業モード)、Outlook の Copilot、および Teams の Copilot のデモ <br> - "ユーザーの声" スライド <br> - Microsoft Copilot on Mobile スライド | 25 分      |
|   |                                       |                                                                                                  | **合計時間が 70 分近くになる可能性があります** |


各デモへのハイパーリンクを以下に示します。

## デモ

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

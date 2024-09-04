---
demo:
  title: 'デモ: Microsoft Copilot (作業スコープ)'
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (作業スコープ)

## デモ セットアップ

このデモでは、サンプル ドキュメントには依存しません。 代わりに、ピアとの既存の通信に依存します。 

以下のプロンプトでは、機密情報を共有していない人物を参照します。

## テーマ

"Copilot for Microsoft 365 が作業スコープ内で動作している場合、Copilot は Microsoft 365 セキュリティを使用してデータを保護し、すべてのサービスを組織のコンプライアンス境界内で実行します。

ここでは、作業スコープで、Microsoft Graph からの情報を使用して Copilot を強化しています。 基本的な知識管理から始めましょう。 情報を入手できる場所と相手を見つけることは、知識管理の長年にわたる課題です。 組織の誰がグラウンディングと LLM について教えてくれるかを見てみましょう。

私の通信内容を要約し、私の同僚の 1 人と協力するように Copilot に頼むつもりです。 メール、チャット、およびドキュメント別に応答を整理するように依頼します。 作業スコープでは、Copilot は私のメール メッセージ、予定表、チャット、ドキュメントを参照できます。

Copilot は予定表について考える方法を学習しています。 その情報を処理して要約し、役に立つものを提供することができました。 また、私がその情報を見て、検証したり、詳細を取得したりできるように、リファレンスが含まれています。

私たちは常にプロンプトを見て、より複雑な情報の取得と自動化で Copilot の機能を向上させる方法を模索しています。"

## デモの手順

> **重要:** プロンプトをさらにカスタマイズするには、機密でないメールや会議を探し、内容の要約や実施項目の一覧表示を Copilot に依頼します。 重要: 人物を選択するときは、機密情報を共有しない人物を選択してください。

1. 左上で、トグルを **[作業]** に切り替えます。

1. **[何でも質問してください...]** テキスト ボックスに、プロンプトをコピーして貼り付けます。 

    ```text
    What is "grounding" for an LLM and how does it work? If I wanted to know more about it, who would be able to help me?
    ```

1. **[送信]** ボタンを選択します。

1. **[何でも質問してください]** テキスト ボックスに、次をコピーして貼り付けるか入力します。 

    ```text
    Can you summarize the last five emails from “/”.
    ```
    > **注:** スラッシュ記号を含める必要があります。

1. 同僚の名前を入力していきます。

    > **重要:** 機密情報を共有しない人物を選択します。

1. 人物の名前が表示されたら、それを選択します。
1. プロンプトの残りをコピーして貼り付けるか、入力します。

    ```text
    To be specific, look for the last five emails from this person over the last few days and stack rank them in order of most important to least important, based on your analysis of the contents.
    ```

1. **送信**を選択します。

1. **省略可能:** **[何でも質問してください]** テキスト ボックスに、次のプロンプトをコピーして貼り付けます。

    ```text
    Can you summarize the last five emails from my boss? To be specific, look for the last five emails from my boss over the last few days and stack rank them in order of most important to least important, based on your analysis of the contents.
    ```

    次に **[送信]** を選択します。

1. **省略可能:** *[何でも質問してください]* テキスト ボックスに、次のプロンプトをコピーして貼り付けます。

    ```text
    Review my meetings this week and create 5-7 categories that describe how I am spending my time. For each category, provide a short description and give me an approximate percentage of time I spent there.
    ```

    次に **[送信]** を選択します。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

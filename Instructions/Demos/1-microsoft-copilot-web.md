---
Layout: default
demo:
  title: 'デモ: Microsoft Copilot (Web スコープ)'
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (Web スコープ)

## Copilot と大規模言語モデル

### テーマ

Web 上の Microsoft Copilot では、質問に回答したり、一般的なタスクを手助けしたりできる AI 搭載のパーソナル アシスタントが提供されます。 Copilot に質問すると、Copilot は大学教育を受けた人並みの回答を提供します。

ユーザーまたは組織が商用データ保護で Copilot を使用している場合、チャットは保存されません。 すべてのデータは暗号化され、Microsoft はプロンプトや応答を保持しません。 これらはモデルのトレーニングには使用されないため、個人や組織の情報は機密扱いになっていると考えて間違いありません。

たとえば、このような一般的知識に関する質問をすると、多くの素晴らしい情報を得ることができます。 Copilot は、質問に答えるために使用できる世界中の基本的な概念モデルを持っています。

**例:**
- **プロンプト:** 象について何か教えてくれませんか?
- **応答:** (応答について話し合う)

Copilot では、Bing 検索や結果など、膨大な量の情報に基づいてトレーニングされた大規模言語モデル (LLM) が使用されます。 しかし、Copilot は単なるファクト チェッカーではありません。 Copilot には、質問を聞き、その質問について確率論的に考える能力があり、一般的な推論エンジンとして使用することができます。 業界では、これを推論を呼びます。

**例:**
- **プロンプト:** 象にどれくらいの力があるのかに興味があります。 象と綱引きをして勝つには何人くらいの人間が必要でしょうか? 注: 誰もが「綱引き」という用語を知っているわけではないので、地域と対象者に応じて用語を変更する必要があります。 
- **応答:** (応答について話し合う)

Copilot は仮定を立て、知識の端々の間のつながりを引き出して、質問に対するより細かい答えを出すことができました。 Copilot を改善する過程で、これらの LLM は何が得意で何が得意ではないかについて多くのことが判明しており、こうして得られた知見が製品に組み込まれています。

### デモの手順

> **注:** 独自のプロンプトを使用する場合は、自分や顧客にとって興味深い一般的な知識のトピックから始めます。

1. [Edge] タブに切り替えて、Copilot を開き、Web スコープを選択します。

    ![Microsoft Copilot の Web モードを示すスクリーンショット。](../Demos/Media/web_mode.png)

1. **[何でも質問してください...]** テキスト ボックスに、プロンプト ライブラリ ドキュメントからプロンプトをコピーして貼り付けるか、次のように入力します。

    ```text
    What can you tell me about elephants?
    ```
1. **[送信]** ボタンを選択します。
1. **[何でも質問してください...]** テキスト ボックスに、プロンプトをコピーして貼り付けます。

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. **[送信]** ボタンを選択します。

## グラウンディング

### テーマ

しかし、この力を次のレベルに引き上げるのは、外部データと知識を Copilot に教える能力です。 これは、取得拡張生成 (RAG) と呼ばれることもあります。 これは、手元のタスクに関連する言語モデルに追加情報を提供するプロセスです。

労働統計局の仕事レポートなど、あらゆる種類のデータやドキュメントに基づいて質問を行うことができます。 これは膨大なドキュメントで、毎年出版されており、米国全体の仕事と雇用の傾向に関するデータが豊富です。 Copilot は自ら出て行って、その情報を見つけ、それを理解し、質問に対する答えをリアルタイムで出すことができます。 また、Copilot は、労働統計局の Web サイトのどこからその情報を入手したのかを示す出典も提供します。 つまり、ユーザーは、Copilot が情報を入手した場所を確認して、より多くの背景情報を取得できます。これは Copilot がオートパイロットと異なる点です。

### デモの手順

1. **[新しいトピック]** をクリックして、新しいトピック開始します。

    ![Microsoft Copilot での新しいトピックを示すスクリーンショット。](../Demos/Media/new_topic.png)

1. **[何でも質問してください...]** テキスト ボックスに、プロンプトをコピーして貼り付けます。

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. **[送信]** ボタンを選択します。
1. 応答では、**[詳細情報]** の横で、1 つか 2 つの出典の上にマウスを置きます。

## Copilot のその他のスキル

### テーマ

これは素晴らしいことですが、本当はこのデータのグラフを見たいところです。 残念ながら、Copilot は今はグラフを描画できませんが、だからと言って困っているわけではありません。 Copilot を構築するにつれて、さまざまなスキルが追加されます。 スキルとは、Copilot が問題を解決するために推論力を利用する方法です。

私が知っている Copilot のもう一つの能力は、コーディング能力です。 コーディング方法を知っていることを Copilot に思い出させて、私が望むグラフの Python コードを Copilot に書かせることができるか確認するつもりです。

**例:**
- **プロンプト:** 過去 5 年間の労働統計局の労働参加率の一覧を教えてください。 また私は、あなたがコーディングできると聞きました。 bls.gov からデータを取得して、探しているグラフを生成する Python コードを記述できますか?
- **応答R:** (応答について話し合う)

時間が経つにつれて、この種のプロセスがより簡単になり、自動化されることを期待しています。

### デモの手順

1. **[新しいトピック]** をクリックして、新しいトピック開始します。

    ![Microsoft Copilot での新しいトピックを示すスクリーンショット。](../Demos/Media/new_topic.png)

1. **[何でも質問してください...]** テキスト ボックスに、プロンプトをコピーして貼り付けます。

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. **[送信]** ボタンを選択します。

## オプションのデモ手順

### 画像の認識

まず次のファイルをダウンロードします: [**what_is_this_image.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. **[新しいトピック]** をクリックして、新しいトピック開始します。

    ![Microsoft Copilot での新しいトピックを示すスクリーンショット。](../Demos/Media/new_topic.png)

1. ページの下部にある **[画像の追加]** アイコンを選択します。

    ![Microsoft Copilot での画像の追加を示すスクリーンショット。](../Demos/Media/add_an_image.png)

1. **[このデバイスからアップロード]** を選択します。
1. 画像のダウンロード先を参照し、**what_is_this_picture.png** を選択して、**[開く]** を選択します。
1. **[何でも質問してください]** テキスト ボックスにプロンプトを入力します。

    ```text
    What is this picture?
    ```

1. **[送信]** ボタンを選択します。

### Copilot で画像を作成する方法を示す

1. **[何でも質問してください...]** テキスト ボックスに、プロンプトをコピーして貼り付けます。

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. **[送信]** ボタンを選択します。

### Copilot で作曲する方法を示す

1. 個人用アカウントにログインしている新しいブラウザー セッションに切り替えます。

> **注:** この手順では、個人用アカウントを使用する必要があります。 業務用アカウントではうまくいきません。

1. 右上隅にある **[プラグイン]** を選択します。

    ![Microsoft Copilot での画像の追加を示すスクリーンショット。](../Demos/Media/copilot_plugins.png)

1. 使用可能なプラグインの一覧で、**[Suno]** を有効にします。

    ![Microsoft Copilot での画像の追加を示すスクリーンショット。](../Demos/Media/copilot_suno.png)

    > **注:** Suno を使用するには、Copilot で新しいトピックを開始してから、Suno を有効にする必要があります。

1. **[何でも質問してください...]** テキスト ボックスに、プロンプトをコピーして貼り付けます。

    ```text
    Write a country song about Microsoft Copilot, extolling its virtues as an AI companion. Make it catchy, upbeat, and a little quirky.
    ```

1. **[送信]** ボタンを選択します。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

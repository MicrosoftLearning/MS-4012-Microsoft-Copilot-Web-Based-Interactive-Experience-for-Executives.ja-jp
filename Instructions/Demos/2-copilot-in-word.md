---
demo:
  title: 'デモ: Word の Copilot'
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Word の Copilot

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles)の MS-4012 GitHub リポジトリにあります。

この演習で使用されている具体的なファイルは次のとおりです。

- [**ContosoLearn App Overview.docx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/ContosoLearn%20App%20Overview.docx)
- [**ContosoLearn Competitor SWOT.docx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/ContosoLearn%20Competitor%20SWOT.docx)
- [**ContosoLearn Value Proposition.docx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/ContosoLearn%20Value%20Proposition.docx)
- (省略可能 - 以下の手順を参照) [**Microsoft_FY24_Second_Quarter_Earnings_Conference_Call.docx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call.docx) 

> **注:** これらのファイルが OneDrive に同期されるまでに最大 10 分かかることがあります。 このプロセスを迅速化するには、ドキュメントを開いて閉じます。すると、最近使用した 項目 (MRU) の一覧に追加されます。

## テーマ

対話型エクスペリエンスでは、新しいアプリやサービスのアイデアをブレーンストーミングし、ブランド ID とマーケティング資産を作成し、市場の勢力図を分析しました。 しかし、これをさらに一歩進めるにはどうすればよいでしょうか?

Word の Copilot を使用すると、ドキュメントの作成と改善のプロセスを変革できるので、魅力的なコンテンツを簡単に作成できるようになります。

このデモでは、先ほど作成したドキュメントを取り上げ、それらをまとめて変換して戦略的分析レポートを作成します。 さらに、コンテンツが目的と完全に一致するように、形式とトーンを調整します。

## デモの手順

1. Microsoft Word をデスクトップで起動するか、新しい [Edge] タブに「**Word.new**」と入力して起動します。
1. ドキュメントの本文をクリックし、表示されている **Copilot アイコン**を選択します。

    ![Copilot アイコンが付いた下書きを示すスクリーンショット。](../Demos/Media/draft_with_copilot_icon.png)

1. Word では、**[Copilot を使って下書き]** ウィンドウが表示されます。 プロンプト フィールドに、次のプロンプトを入力します。

    ```text
    Create a comprehensive strategic analysis report for ContosoLearn using the following files as references: /ContosoLearn App Overview, /ContosoLearn Competitor SWOT, and /ContosoLearn Value Proposition. The strategic analysis report should include the following sections:
        
    Executive Summary
    App Overview
    Market Research
    Competitor SWOT Analysis
    Value Proposition
    Conclusion
    ```

    > **重要:** これを正しく機能させるには、"/" を再入力し、最近使用したファイル (MRU) 一覧から適切なファイルを選択する必要があります。

1. これで、指定したプロンプトに基づいて、Copilot が戦略的分析レポートの下書きを生成します。 Copilot が処理を完了すると、次のプロンプト ウィンドウが表示されます。

    ![Copilot での保持を示すスクリーンショット。](../Demos/Media/keep_it_or_modify.png)
    
    プロンプト フィールドに、次のように入力します。

    ```text
    Remove the "Market Research" section and add a "Competitive Landscape" section. Ensure the content is concise and aligns with the overall tone of the document.
    ```

    > **注:** Copilot for Word がうまく動作しない場合は、[**ContosoLearn Example Word Output**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Allfiles/Demo%20Sample%20Docs/ContosoLearn_Example_Word_Output.docx) リンクを使用して、生成されたドキュメントにアクセスできます。

## オプションのデモ手順

### 大きなドキュメントを要約する

1. デスクトップ上の Word で [**Microsoft_FY24_Second_Quarter_Earnings_Conference_Call.docx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call.docx) ファイルをダウンロードして開きます。
1. Word 内のリボンで、**Copilot アイコン**を選択します。

    ![Copilot での保持を示すスクリーンショット。](../Demos/Media/copilot_icon.png)

1. **[このドキュメントについて何でも質問してください]** フィールドにプロンプトをコピーして貼り付けるか入力します。 

    ```text
    Based on the document, how did AI impact Microsoft's earnings this year?
    ```

1. **[Send]** を選択します。  
1. **[このドキュメントについて何でも質問してください]** フィールドにプロンプトをコピーして貼り付けるか入力します。 

    ```text
    Copilot, generate a FAQ based on this document.
    ```
    
1. **[Send]** を選択します。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

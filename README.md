# AI技術による自然言語処理ツール入門（工学部）

信州大学「AI技術による自然言語処理ツール入門（工学部）」 教材リポジトリ

## 教材形式

* Google colab版: 直接colab環境で実行できる形式（変更したければ個々人のGoogleドライブへコピーが必要）
* HTML版: Jupyter Notebook版からのHTMLエクスポート (HTML)
* PDF版: Jupyter Notebook版からのPDFエクスポート (PDF)
* Reveal.js版: Jupyter Notebook版（Slide指定あり）からのReveal.js slides版をエクスポート (HTML)

## GitHubからeALPSへのデプロイ方法

1. 基本的に，Google colab版をmasterとしてから，Jupyter Notebook版としてコピー後 調整する． (.ipynb)
2. Jupyter Notebook : 印刷プレビュー経由でPDF保存する．(.pdf)
3. Jupyter Notebook : HTML版をエクスポートする． (.html)
4. Jupyter Notebook : Slide指定でRISEの動作を確認後， Reveal.js slides版をエクスポートする． (.slides.html) <https://revealjs.com/>

## 概要

近年，チャットサービスであるChatGPTが注目を浴びているように，AI技術による自然言語処理技術の高度化はとどまるところを知らない．これまでにも，AI技術による自然言語処理ツールとしてBERTやDoc2Vecなどが登場しているが，当然ながらそれぞれで機能は異なり，深く理解するにはまず実行環境を整えることが肝要である．ここでは，AI技術による自然言語処理が可能な様々な従来ツールについて，手元で動作させるための環境構築や具体例によるデモンストレーションを中心に紹介する．なお，旧来の自然言語処理ツールの用法についても，基礎的技術の位置づけとして紹介する．

## 目次

### Part-1 自然言語処理ツール（主要5プロジェクトの紹介）

1. MeCab (fugashi)：日本語の形態素解析を行うためのオープンソースのツール（fugashi：MeCabをPythonで利用するためのラッパーライブラリ）
2. Ginza：SpaCy自然言語処理ツールキットのための日本語言語モデル
3. GenSim：ピックモデリングや自然言語処理タスクを行うためのライブラリ
 - 3.1 Word2Vec：単語をベクトル化するための手法
 - 3.2 Doc2Vec：文章全体をベクトル化する手法（Word2Vecの拡張）
4. BERT：Bidirectional Encoder Representations from Transformers。Transformerアーキテクチャを基盤にした自然言語処理モデル
5. PaLM API：Pattern and Language Model API。テキスト分析、感情分析、意図推定などの自然言語処理タスクを行うためのインターフェースを提供

### Part-2 自然言語処理ツール（その他のプロジェクトの紹介）

Tentative：今後紹介記事を追加していきます。紹介内容は増減する可能性があります．また現在の表示順は順不同です．

旧来の自然言語処理ツール（一部はAI技術も利用できる）
* MeCab
* Juman
* KNP
* CaboCha
* Kuromoji
* Sudachi
* ChaSen
* Nagisa
* NLTK
* GinZa
* spaCy
* StanfordNLP
* OpenNLP
* Polyglot
* WordNet
* Pykakasi
* Mozc
* KyTea
* lindera
* KenLM

AIによる自然言語処理ツール
* word2vec
* fastText
* doc2vec
* BERT
* Transformers
* Spacy-Transformers
* ChatGPT
* Google Bard
* Rasa NLU
* AllenNLP
* Senna

TBA

# memo

2025.2.26 URL変更された (common, otherサーバ)

## 数理DS コア3科目（年度更新されない版） URL

* DS基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=87>
* DE基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=88>

* 新DS・DE基礎(構築中) <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=86>
* 新AI基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=89>

## 工学部 学部共通科目 データサイエンス科目（2023 R5年度版）　URL

* DS基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=413>
* DE基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=414>
* AI基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=415>

## 工学部 学部共通科目 データサイエンス科目（2024 R6年度版）　URL

* DS基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=594>
* DE基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=401>
* AI基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=595>

## 学外連携・その他 eALPS URL

### 経産省 共同研究講座

* 産学連携 / デジタル人材育成共同研究講座
<https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=15>

* データサイエンス(DS)概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=26>
* データエンジニアリング概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=27>
* 機械学習概論I
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=28>
* AIエンジニアリング概論（佐藤真平先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=29>

### 工学教育寄附講座

* 産学連携 / 工学教育寄附講座
<https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=16>

* データサイエンス概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=30>
* データエンジニアリング概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=31>
* データマイニングと機械学習概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=79>
* 画像認識へのAIの適用（宮尾先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=33>
* AI技術による自然言語処理ツール入門（小形先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=32>
* 基礎制御設計（千田先生）
<https://lms.ealps.shinshu-u.ac.jp/other/enrol/index.php?id=35>


# jupyter notebook viewer

* sec.3のノートブックを直接表示する例
https://nbviewer.org/github/MDASH-shinshu/MDASH-T-DS/blob/main/3/3_data_search_and_visualization_colab.ipynb

# 最終課題

もうすぐで1年間の講義が終わりとなります。みなさん、お疲れ様でした。現在のAIを支えている主要な技術のニューラルネットや強化学習について、春頃と比べると、ずっと理解が進んだことだことだと思います。

1年間のこの講義の集大成として、最終課題に取り組んでもらいます。レポートを作成して、講義で発表してもらいます。レポートの内容はニューラルネットや強化学習に関するものであれば、どのようなものでも構いません。関心のあるテーマを選んでください。

モデルについてですが、0から学習したり、もしくは Fine Tuning や Transfer Learning を行ってください。もしくは訓練済みのモデルを使ったアプリを作成してください。

それから最終課題は、友人と一緒に取り組んでも、一人でも構いません。ただし、レポートは一人ひとり作成してください。

レポートの詳細：
- 締切日：**第15回の講義日**
- レポートの形式は Notebook (.ipynb) や スクリプト (**.py) とします。
- 友人と一緒に最終課題に取り組んだ場合でも、レポートは一人ひとり作成してください。
- モデルやデータセットの説明を含めてください。

発表の詳細：
- 発表日：**第14・15回の講義日**
- 友人と取り組んだ場合、一緒に発表してください。
- 発表時間：一組あたり、発表を10分、質疑応答を5分とします。
- レポートの Notebook やスクリプトを使って発表して構いません。特にスライドの準備は必要ありません。

モデル例：
- Fully Connected Neural Network
    - データセットが単純であれば、GoogleColab 程度の計算資源で、0から学習可能。
    - 実装例：https://pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html
        - layer を変更したり、データセットを別のもので試してもよい。
- Convolutional Neural Network
    - データセットが単純であれば、GoogleColab 程度の計算資源で、0から学習可能。
    - CNNは画像データや時系列データに特に有効。
    - 最も簡単なCNNのコード例：https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
        - layer を変更したり、データセットを別のもので試してもよい。
    - 訓練済みモデルを Transfer Learning することは、よく行われる手法。https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html
- Transformer
    - GoogleColab 程度の計算資源では、0からの学習は難しい。学習を行うのであれば、Fine Tuning がおすすめ。
    - Hugging Face：https://huggingface.co/docs/transformers/
- Diffusion Model
    - GoogleColab 程度の計算資源では、0からの学習は難しい。また訓練済みモデルの推論だけでも、かなり厳しい。
    - Hugging Face
        - https://huggingface.co/learn/diffusion-course/
        - https://huggingface.co/docs/diffusers/
- 強化学習
    - 簡単な設定であれば、GoogleColab 程度の計算資源で、0から学習可能。
    - 強化学習のframeworkはGymnasiumがおすすめ。https://gymnasium.farama.org/
    - ゲームを自作する方法：https://gymnasium.farama.org/introduction/create_custom_env/

データセット例：
- Seaborn
    - https://github.com/mwaskom/seaborn-data
    - 容量が小さく、使いやすい形式のデータセットが多い。
- Scikit Learn
    - https://scikit-learn.org/stable/datasets.html
    - 容量が小さく、使いやすい形式のデータセットが多い。
- UCI Machine Learning Repository
    - https://archive.ics.uci.edu/
    - 論文でも使われるデータセット。信頼性の高いデータセットが多い。
- Kaggle
    - https://www.kaggle.com/datasets
    - 面白い、ユニークなデータセットが多い。使いやすい形式のものが多い。
    - 出どころが不明のデータセットも多いので、注意が必要。

予定：
- 第10回：データセット・モデル選定
- 第11回：データセット・モデル選定 (友人と取り組むか、一人で取り組むかを報告)
- 第12回：モデル作成・レポート作成
- 第13回：モデル作成・レポート作成 (使用するデータセット・モデルを報告)
- 第14回：発表
- 第15回：発表・レポート提出

その他
- なるべく講義時間内にレポートが作成できるように、時間を取ります。
- ニューラルネットの学習ですが、GPUを使うと高速に行えます。Google Colab 上で使えます。
- OpenAIやStableDiffusion、HuggingFaceなどのAPIを使うだけのレポートは、今回は禁止します。APIで間接的にではなく、直接、モデルを使う経験をしてほしいためです。
- この最終課題を行う上で、分析がうまくいかなかったとしても、それをレポートしてもらえればと思います。難しいタスクをこなそうとするほど、その可能性は高くなると思います。大切なのはなぜ上手くいかなったのかを考察することだと思います。それは重要な知見となります。実際の研究や開発の現場も同じで、上手くいかないことの方が多いです。
- データセットやモデルについて悩んだり相談したいことがあれば、ぜひ連絡ください。

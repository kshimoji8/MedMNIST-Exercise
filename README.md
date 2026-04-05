# MedMNIST Exercise

MedMNISTデータセットを用いた医療AI入門講義の演習教材です。Google Colab上で全5回の演習を行い、医用画像分類AIの構築から社会実装までを体験します。

## 講義資料

| 講義 | 主な内容 | Colab |
|------|----------|-------|
| 第1回：MedMNISTによる深層学習モデル入門 | CNN構築・学習・混同行列・特徴マップ可視化 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshimoji8/MedMNIST-Exercise/blob/main/01_cnn.ipynb) |
| 第2回：転移学習と不均衡データへの挑戦 | MobileNetV2転移学習・クラス重み・不均衡データ対策 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshimoji8/MedMNIST-Exercise/blob/main/02_transfer.ipynb) |
| 第3回：画像分類とGrad-CAMによるAI判断の可視化 | 二値分類・Grad-CAM・説明可能なAI | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshimoji8/MedMNIST-Exercise/blob/main/03_grad-cam.ipynb) |
| 第4回：医療AIの評価指標 | ROC/AUC・感度/特異度・閾値最適化・PR曲線 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshimoji8/MedMNIST-Exercise/blob/main/04_evaluation.ipynb) |
| 第5回：AIの社会実装（Webアプリ開発） | Gradio Webアプリ構築・公開URL発行 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshimoji8/MedMNIST-Exercise/blob/main/05_deploy.ipynb) |

## 各回の構成

各回のノートブックは以下の共通構成で設計されています。

1. **解説とコード実行** — 技術トピックをコードとともに体験
2. **練習問題** — パラメータ変更による挙動の観察
3. **設問演習** — シナリオに基づく判断・解釈・リスク分析
4. **考察課題** — 自由記述形式で深い思考を促す
5. **回答例** — 考察課題・設問演習それぞれの回答例を掲載

## 引用

本教材で使用しているMedMNISTデータセットを利用する場合は、以下の論文を引用してください。

> Jiancheng Yang, Rui Shi, Donglai Wei, Zequan Liu, Lin Zhao, Bilian Ke, Hanspeter Pfister, Bingbing Ni. "MedMNIST v2: A Large-Scale Lightweight Benchmark for 2D and 3D Biomedical Image Classification". *Scientific Data*, 2023.

> Jiancheng Yang, Rui Shi, Bingbing Ni. "MedMNIST Classification Decathlon: A Lightweight AutoML Benchmark for Medical Image Analysis". *IEEE 18th International Symposium on Biomedical Imaging (ISBI)*, 2021.

MedMNIST公式サイト: https://medmnist.com/

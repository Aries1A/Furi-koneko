# Furi-koneko
![thumb](https://user-images.githubusercontent.com/26866592/72219700-3a6ae900-358c-11ea-8522-9a417f4e5ccf.png)

## 概要
夜な夜な部屋に現れ、折れたポッキーのかけらで遊ぶ「ふりこねこ」。  
ポッキーのチョコの部分とポッキーの部分を重ねて、倒れないようにバランスを取ります。  

本作品はUnityのML-Agentsを使った倒立二重振り子の強化学習をテーマにしています。

## 動画(画像をクリックして再生)
[![main_visual](https://user-images.githubusercontent.com/26866592/72219684-17d8d000-358c-11ea-9446-a05b369d1098.png)](https://youtu.be/O4TRx_J__mA)

## 強化学習の実行/学習結果の確認
ターミナルにて以下を実行する。
```bash
git clone https://github.com/Aries1A/Furi-koneko.git
pip3 install git+git://github.com/openai/baselines
pip3 install -r requirements.txt
cd Furi-koneko/notebooks
juputer notebook
```

### 強化学習実行
`train.ipynb`を開いて最初のセルを実行する。

### 学習結果の確認
`inference.ipynb`を開いて最初のセルを実行する。

どちらもUnityアプリのウィンドウが立ち上がります。

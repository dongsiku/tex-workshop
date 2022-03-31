# TeX Workshop

知能機械制御学研究室にて，TeX講習会のために作成したTeXの資料と課題．

## 本資料のライセンス

知能機械制御学研究室での使用については，改変版の再配布を含みすべて許可し，クレジット表記も不要とする．他の目的での使用については，後述するライセンスを参照されたい．ただし，使用目的に関わらず，著者は本文書を使用することにより発生するいかなる不利益についても責任をとらないことに留意すること．

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/muneue-suwa/tex-workshop">TeX Workshop</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/muneue-suwa">Muneue Suwa</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>

## 学習目標

以下の文法を習得することを目標としている．

1. 別行立ての数式（\begin{align}~\end{align}）の入れ方．参考資料として\begin{case}などの使い方を記載する．[参考文献](https://qiita.com/t_kemmochi/items/a4c390b4967b13f3afb7)
1. 文章内での数式（$$）の入れ方
1. 式番号の入れ方（\ref）
1. 上付き，下付き文字（例：a_1^'）
1. 和・積分（シグマとインテグラル）
1. 分数
1. カッコ（例：`\left(\right)`）．参考資料にカッコを簡単につけれる（例：`\qty()`）physicsパッケージについて記載する．[参考文献](https://qiita.com/HelloRusk/items/ce9f49e9b3fc0344ae23)
1. ギリシア文字（`\alpha`, `\beta`, `\gamma`），演算子（`\leq`, `\geq`）．詳細はググれと明記する．
1. `\log`,`\ln`,`\sin`とか
1. `\lim`, `\mod`とか
1. アクセント（例：`\dot{a}`）
1. フォントを変える（例：`\mathbb{A}`）
1. 行列
1. 図と作画ソフト．pdfcropの使い方については動画（リアルタイムかオンデマンド）で説明する．
1. 表
1. その他：`\textit{}`,`\cite{}`,`\newcommand{}`
1. `\section`

## 課題

課題は，1-15を網羅することを目標に，指定されたテンプレートに5つほどの数式を記述する問題を出題する．ただし，1-3について，以下では記述していないが，適宜出題するものとする．なお，可能な限り，院試にて必要な公式を出題できるようにしたい．

- フーリエ級数，マクローリン展開 (4,5,6,7,8,9)
- フーリエ変換表．ただし，3つほどにする． (15)
- 余因子行列 (12,13)
- 力のつり合いの式（`F/\sin⁡(\pi-\theta) =const`）の図を描いて貼り付ける (14)
- ロピタルの定理 (10)

# WRIME: 主観と客観の感情分析データセット [[English]](https://github.com/ids-cv/wrime/blob/master/README.en.md)

感情分析の研究のために、テキストの筆者の感情を注釈付けしたデータセットを構築しました。<br>
本データセットの特徴は、以下の3点です。

- 主観（テキストの筆者1人）と客観（クラウドワーカ3人）の両方の立場から感情ラベルを付与しました。
- 8種類の多様な感情（喜び、悲しみ、期待、驚き、怒り、恐れ、嫌悪、信頼）を扱いました。
- 各感情の強度を4段階（0:無、1:弱、2:中、3:強）でラベル付けしました。

80人の筆者から収集した43,200件の投稿に感情強度をラベル付けして公開中です。

## テキストとラベルの例

投稿：タイヤがパンクしてた。。いたずらの可能性が高いんだって。。

||喜び|悲しみ|期待|驚き|怒り|恐れ|嫌悪|信頼|
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|主観 |0|3|0|1|3|0|0|0|
|客観A|0|3|0|3|1|2|1|0|
|客観B|0|2|0|2|0|0|0|0|
|客観C|0|2|0|2|0|1|1|0|

## 文献情報

- Tomoyuki Kajiwara, Chenhui Chu, Noriko Takemura, Yuta Nakashima, Hajime Nagahara. [WRIME: A New Dataset for Emotional Intensity Estimation with Subjective and Objective Annotations.](https://aclanthology.org/2021.naacl-main.169/) In Proceedings of the 2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2021), pp.2095-2104, 2021.
- 梶原智之, Chenhui Chu, 武村紀子, 中島悠太, 長原一. [主観感情と客観感情の強度推定のための日本語データセット.](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/P3-3.pdf) 言語処理学会第27回年次大会, pp.523-527, 2021.

本データセットを研究で利用された場合、論文情報をご連絡いただきましたらここに掲載させていただきます。

## 謝辞

本研究は、文部科学省による[Society 5.0 実現化研究拠点支援事業](https://www.ids.osaka-u.ac.jp/ildi/index.html)（グラント番号: JPMXP0518071489）の助成を受けたものです。

## ライセンス

本データセットは研究目的で利用可能です。再配布はご遠慮ください。

## 連絡先

- [梶原 智之](https://sites.google.com/site/moguranosenshi/)（愛媛大学 大学院理工学研究科 助教）
- [中島 悠太](https://www.n-yuta.jp/)（大阪大学 データビリティフロンティア機構 准教授）

sentiment-dataset *at* is.ids.osaka-u.ac.jp


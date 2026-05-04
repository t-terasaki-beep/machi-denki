# まちの電気屋さん（電材コンビニ）／ コンテンツ群

千葉エリア向け「まちの電気屋さん」ブランドのLP・ツール集。  
運営：株式会社シスコムネットダイレクト

## ディレクトリ構成

```
machi-denki/
├── sotsu-fit-lp/              卒FIT × おひさまエコキュート LP（明るい版）
│   └── index.html
└── ohisama-simulator/         おひさまエコキュート 交換シミュレーター（独立ツール）
    └── index.html
```

## 各コンテンツ

### sotsu-fit-lp
卒FIT・FIT終了世帯向けの相談誘導LP。LINE公式アカウント `@809xyxye` への登録を主CTAとする。  
配色はクリーム + 太陽オレンジ + 空色の「晴れた朝」パレット。地域密着・親しみやすさを重視。

### ohisama-simulator
深夜電力エコキュート vs おひさまエコキュートの年間電気代比較シミュレーター。  
シスコムサステナシールド版（syscom-sustaina-shield.live-in-japan0219.workers.dev）の  
計算ロジックを踏襲し、UIを「まちの電気屋さん」トーンに刷新した独立ツール。

入力：家族人数 / 太陽光kW / 月電気代 / 売電単価 / 給湯器使用年数 / [任意]年間平均日量kWh  
出力：年間削減額・経年劣化分の効果・3パターン棒グラフ・8段階の計算内訳

## 共通CTA
LINE公式アカウント：https://page.line.me/809xyxye

## 関連リンク
- 株式会社シスコムネット：https://syscomnet.co.jp/
- シスコムサステナシールド（卒FIT 蓄電池ユーザー向け）：https://syscom-sustaina-shield.live-in-japan0219.workers.dev/

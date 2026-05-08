# ShiosaiLearn Portal

> 自律した個人のための、静かな道具群。

[ShiosaiLearn](https://shiosailearn.com) のポータルサイトのソースコード。
2 つのプロジェクト（高認パス / Stellar）の入り口、思想の宣言、距離感の提示を行う場所。

---

## プロジェクト

- **高認パス**: 高卒認定試験の過去問データを、競争なく整理して提示する Web ツール
- **Stellar**: 文系研究のためのローカルファースト・デスクトップアプリ

詳細はサイト上で。

---

## 構成

```
.
├── index.html              # トップページ
├── about.html              # About / 5 つの約束
├── support.html            # Support / 5 つの距離感
├── projects/
│   ├── konin.html          # 高認パス紹介
│   └── stellar.html        # Stellar 紹介
├── assets/
│   └── logo/
│       └── mark.svg        # シンボルマーク (3 本の波)
├── LICENSE                 # MIT
├── README.md
└── .gitignore
```

静的 HTML / CSS のみ。ビルドは不要。
ブラウザで `index.html` を直接開けば動く。

---

## デザイン

- **カラー**: クリーム / ネイビー / 水色 / マスタード / バーントオレンジ
- **タイポ**: Inter (欧文) + Noto Sans JP (和文) + JetBrains Mono (記号系)
- **トーン**: ミッドセンチュリーモダン × ポップ × スペースエイジ
- **思想**: ローカルファースト、ユーザーを定義しない、励まさない

詳細は [About](https://shiosailearn.com/about.html) と [高認パス 設計思想書](https://shiosailearn.com/projects/konin.html) を参照。

---

## ライセンス

MIT — see [LICENSE](./LICENSE).

---

## 開発

特別な依存はなし。HTML / CSS / SVG のみ。

ローカルで確認するには:

```bash
# Python 簡易サーバー
python3 -m http.server 8000

# Node.js
npx serve .
```

---

© 2026 ShiosaiLearn — by Tami_tou

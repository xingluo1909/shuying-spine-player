<div align="center">
  <br />
  <h1>Spine Player</h1>
  <p>
    <strong>クロスプラットフォーム非公式 2D スケルタルアニメーションプレイヤー</strong>
    <br />
    マルチバージョン再生 · フォーマット変換 · スケルトンマージ · Live2D · 3D プレビュー · AI拡大
  </p>
  <p>
    <a href="#"><img src="https://img.shields.io/badge/バージョン-1.627.0-7c6af7?style=for-the-badge&labelColor=1a1a2e" alt="バージョン"></a>
    <a href="#"><img src="https://img.shields.io/badge/Spine-2.1%20%7C%203.x%20%7C%204.x-00d4aa?style=for-the-badge&labelColor=1a1a2e" alt="Spine"></a>
    <a href="#"><img src="https://img.shields.io/badge/Live2D-Cubism%202%20%7C%204-ff6b9d?style=for-the-badge&labelColor=1a1a2e" alt="Live2D"></a>
    <a href="#"><img src="https://img.shields.io/badge/多言語-中%20%7C%20EN%20%7C%20JP-4fc3f7?style=for-the-badge&labelColor=1a1a2e" alt="多言語"></a>
    <br />
    <a href="#"><img src="https://img.shields.io/badge/Tauri-ffc131?style=for-the-badge&labelColor=1a1a2e&logo=tauri" alt="Tauri"></a>
    <a href="#"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&labelColor=1a1a2e&logo=react" alt="React"></a>
    <a href="#"><img src="https://img.shields.io/badge/Rust-ed672f?style=for-the-badge&labelColor=1a1a2e&logo=rust" alt="Rust"></a>
    <a href="#"><img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&labelColor=1a1a2e&logo=three.js" alt="Three.js"></a>
    <a href="#"><img src="https://img.shields.io/badge/Pixi.js-B537B4?style=for-the-badge&labelColor=1a1a2e&logo=pixi.js" alt="Pixi.js"></a>
    <a href="#"><img src="https://img.shields.io/github/downloads/xingluo1909/shuying-spine-player/total?style=for-the-badge&labelColor=1a1a2e&color=brightgreen" alt="ダウンロード"></a>
  </p>
  <br />
</div>

<p align="center">
  🌐 <a href="README.md">中文</a> · <a href="README.en.md">English</a> · <a href="README.jp.md">日本語</a>
</p>

---

## 📖 はじめに

**再生、フォーマット変換、マージ、AI拡大**などを統合したクロスプラットフォーム非公式スケルタルアニメーションプレイヤー。macOS（D-01-releaseのみ）およびWindowsに対応。**Spine 2.1** から **3.x**、**4.x** までのマルチバージョン互換再生とフォーマット変換を実現。さらに Live2D Cubism 2/4 および Unity FBX 3D モデルのインポートをサポートしています。

<p align="center">
  <img src="IMG/MAIN.png" alt="スクリーンショット" width="800" />
</p>
  
## ✨ 機能

### 🎬 プレイヤーコア
| 機能 | 説明 |
|------|------|
| **Spine マルチバージョン** | 2.1 / 3.x / 4.x |
| **Live2D マルチバージョン** | Cubism 2 / 4 |
| **デュアルエンジン描画** | Enhanced（統一変換型）/ Native（デュアルプレイヤー互換型）|
| **マルチレイヤー重ね表示** | 複数のSpine/Live2Dファイルを同画面に表示、個別拡大縮小・ドラッグ並び替え |
| **アニメーション制御** | 再生/一時停止/停止、フレーム単位のシーク、ループモード切替 |
| **スキン/パーツ切替** | リアルタイムでキャラクタースキン切替、パーツ表示/非表示 |
| **エクスポート** | PNG単一フレーム出力、複数解像度プリセット、AI拡大エンハンス出力 |

---

## 🛠️ 技術スタック
| レイヤー | 技術 |
|---------|------|
| **デスクトップフレームワーク** | [Tauri 2](https://v2.tauri.app/)（Rust + WebView2） |
| **フロントエンドフレームワーク** | [React 19](https://react.dev/) + TypeScript |
| **バックエンド言語** | Rust |

---

## 🗺️ 更新履歴

### D-02
1. 多言語対応（中国語/英語/日本語）、切り替え即時反映。

2. Live2D サポート、プレイヤー関連コンポーネントを最適化し Spine + L2D 同画面再生を実現：

<p align="center">
  <img src="IMG/L2D+.png" alt="L2D スクリーンショット" width="800" />
</p>

3. FBX サポート：

<p align="center">
  <img src="IMG/FBX-FGO.png" alt="FBX スクリーンショット" width="800" />
</p>

4. エクスポート機能サポート。

### D-01
Spine バージョンサポート。マージモジュールは 3.8 かつ同源素材に限定。

| ソース ↓ ¥ ターゲット → | **3.8** | **4.0** | **4.1** | **4.2** |
|:---------------------:|:-------:|:-------:|:-------:|:-------:|
| **2.1** | ✅ | ✅ | ✅ | ✅ |
| **3.6** | ✅ | ✅ | ✅ | ✅ |
| **3.7** | ✅ | ✅ | ✅ | ✅ |
| **3.8** | ✅ | ✅ | ✅ | ✅ |
| **4.0** | ✅ | ✅ | ✅ | ✅ |
| **4.1** | ✅ | ✅ | ✅ | ✅ |
| **4.2** | ✅ | ✅ | ✅ | ✅ |

---

## 🔄 今後の計画
  現在テスト中のモジュール:
- [ ] 1. エクスポートモジュールの追加機能テスト。
- [ ] 2. ペットモードテスト。
- [ ] 3. マルチテーマテスト。

---

> 読み込みエラーや不具合が発生した場合は、お手数ですが Issue をお送りください（可能であればファイルを添付してください）。
> プロジェクトURL：https://github.com/xingluo1909/shuying-spine-player

---

> D-02 以降、基本機能は概ね完成しています。仕事の都合により、メンテナンスは当面休止する予定です。ご利用ありがとうございました。

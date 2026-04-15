# Voice Math - Audio Q / Visual A

音声で計算問題に答える、インタラクティブな計算トレーニングゲームです。
画面上のテキストを読むのではなく「耳で聞いて、声で答える」ことに特化しており、暗算能力の向上やハンズフリーでのトレーニングに適しています。

## ✨ 主な特徴
- **完全音声インターフェース**: 問題はブラウザの音声合成機能で読み上げられます。
- **音声認識による回答**: 答えを口に出すだけで正誤判定が行われます。
- **タイムアタック**: 90秒間で何問正解できるかに挑戦します。
- **レスポンシブ設計**: PC、タブレット（iPad等）、スマートフォンのいずれでも快適に動作します。
- **ハンズフリー操作**: 最初の画面タップ後は、声だけでゲームを進行できます。

## 🛠 動作環境
ブラウザの Web Speech API を使用しているため、以下の環境での利用を推奨します。
- **Google Chrome** (推奨)
- **Microsoft Edge**
- **Safari** (iOS/macOS)
※ 一部のブラウザや環境（プライベートブラウズ等）では、マイクの許可設定が必要です。

## 🎮 遊び方
1. 画面をタップしてゲームを開始します。
2. ブラウザから「マイクの使用」を求められた場合は「許可」を選択してください。
3. コンピュータが「5 足す 3 は？」のように問題を出題します。
4. 答え（例：「はち」）を声に出して伝えてください。
5. 正解するとスコアが加算され、次の問題が出題されます。

## 🔧 技術スタック
- **Frontend**: HTML5, CSS3 (Custom Properties), JavaScript (Vanilla JS)
- **APIs**: 
  - [Web Speech API (SpeechRecognition)](https://developer.mozilla.org/ja/docs/Web/API/SpeechRecognition) - 回答の音声認識
  - [Web Speech API (SpeechSynthesis)](https://developer.mozilla.org/ja/docs/Web/API/SpeechSynthesis) - 問題の読み上げ
  - [Web Audio API](https://developer.mozilla.org/ja/docs/Web/API/Web_Audio_API) - 正解時の効果音生成

## 📄 ライセンス
このプロジェクトは **MITライセンス** の下で公開されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。

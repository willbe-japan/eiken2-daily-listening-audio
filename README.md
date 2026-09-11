# eiken2-daily-listening-audio

英検2級「毎日のリスニング」の音声ファイル置き場。

- 音声は `audio/YYYY-MM-DD.mp3`（その日の10問を1本にまとめたもの、約8分）
- edge-tts（Microsoft Edge TTS）で合成。話者ごとに声を変え、2級の目安速度に調整している
- GitHub Pages経由で配信し、問題PDFのQRコードから再生する

配信URL: `https://willbe-japan.github.io/eiken2-daily-listening-audio/audio/{YYYY-MM-DD}.mp3`

生成元: `~/Claude/exam-question-generator/daily-listening/daily_listening.py`
（毎朝6:45、launchd `com.willbe.eiken2-daily-listening`）

音声の内容は合同会社WillBeが作成したオリジナルの練習問題です。
実際の試験問題を転載したものではありません。
「英検®」は公益財団法人 日本英語検定協会の登録商標です。

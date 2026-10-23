# おばけAR

壁に貼ったマーカーにスマホを向けると、ジャック・オ・ランタンが現れて、お化けが周りを飛び回るAR.jsのページです。

## 中身
- index.html … AR本体（かぼちゃ・Hiroのどちらのマーカーでも表示）
- marker-pumpkin.html / marker-hiro.html … マーカーを画面に大きく表示するページ（そのまま印刷も可）
- qr.png … ARページ（https://shuji4444.github.io/Halloween-AR/）を開くQRコード画像
- print.html … 印刷用シート（QR＋マーカー。QRは自動でこのフォルダのURLになります）
- pumpkin.glb / ghost.glb … 3Dモデル（自作なので自由に使えます）
- pumpkin-marker.png / patt.pumpkin … マーカー画像（かぼちゃのシルエット）と認識用データ
- hiro.png / patt.hiro … Hiroマーカーの画像と認識用データ
- camera_para.dat … カメラのパラメータ

## 公開手順（GitHub Pages）
1. GitHubのリポジトリで Settings → Pages を開く
2. Source を「Deploy from a branch」、Branch を公開したいブランチ / (root) にして Save
3. 数分後に https://shuji4444.github.io/Halloween-AR/ で公開されます
4. PCで https://shuji4444.github.io/Halloween-AR/print.html を開いてA4で印刷

`.nojekyll` を置いているので、ファイルはそのまま配信されます。

## 注意
- カメラを使うのでHTTPSが必須（GitHub Pagesは自動でHTTPS）
- iPhone(Safari) / Android(Chrome) どちらでも動作。カメラの許可を求められたら「許可」
- マーカーは壁に貼る前提で、かぼちゃとお化けがこちらを向くように表示します
- マーカーは黒枠の外に白い余白を残し、明るい場所で全体が映るようにすると安定します

﻿# レイトレーシングを実装してみる
CG概論の課題です（〆切：12/28）。

簡単なレイトレーシングのプログラムを作成しました。このファイルを自分が思ったように拡張してください。

[![Actions Status](https://github.com/nazonokouta0706/raytracer/workflows/CI/badge.svg)](https://github.com/nazonokouta0706/raytracer/actions)

![結果画像](https://github.com/nazonokouta0706/raytracer/raw/result/result.png)

このリポジトリは、プログラムを変更してGitHubにpushすると、自動的にプログラムをビルド・実行して、出力を(resultブランチへ)アップロードします。上げた後に実行が正常に終わると、そのうち画像が更新されます（キャッシュ等の影響があるので、すぐには結果が反映されないので注意してください）。

# 自分なりに変更した点
- バウンディングボリュームを空中の球(赤)や空中の球(屈折)、空中の球(反射)に追加しました。
- 各オブジェクトの色や反射、透過、屈折などの値を見やすいように調整しました。
- カメラの値を調整しました。

# 進め方
* 本リポジトリをforkしてください
* 上のGItHub Actions のリンクを変更してください(3か所)
* GItHub Actions を有効にしてください
* リポジトリをローカルにダウンロードしてください
* src/main.c 等を編集してください
* README.md に変更した内容を記述してください
* 更新内容をコミットしてください
* コミットした結果をGitHubにプッシュしてください
* しばらくして、結果が正常にレンダリングされるのを確認してください
* 本リポジトリにプルリクエストをしてください
 
  * 今回初めてGitHubのアカウントを取得した人(今まで、GitHubのアカウントを今給黎に知らせていない人)は、https://forms.gle/L7th7kM8xbn5tx537 から、アカウント名を連絡してください。

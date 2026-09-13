# 相根直樹 Profile Site

GitHub Pagesへ公開するための静的サイトデータです。

## ファイル構成

- `index.html`: サイト本体
- `assets/`: 背景画像・扉画像・スクロール連動動画
- `.nojekyll`: Jekyll処理を無効化する設定

## GitHub Pagesへの公開手順

1. GitHubで公開用リポジトリを開きます。
2. このフォルダ内のファイルを、フォルダ構成を変えずにリポジトリ直下へアップロードします。
3. リポジトリの「Settings」→「Pages」を開きます。
4. 「Build and deployment」のSourceで「Deploy from a branch」を選びます。
5. Branchを「main」、フォルダを「/(root)」に設定して「Save」を押します。
6. 数分後、GitHub Pagesの公開URLへアクセスします。

画像ファイルの場所や名前を変更すると表示されなくなるため、`assets`フォルダはそのままアップロードしてください。

扉が開いた後の森林動画は低速で常時再生されます。スクロール中は操作量と方向に合わせて映像が進行・逆戻りし、操作を止めると自然な低速再生へ戻ります。

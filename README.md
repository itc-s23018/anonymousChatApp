  # 変更分をpushする方法
  1, 変更したファイルをgit add と git commitする
  
  2, 次に git push origin [作業中のブランチ名]
  
  3, 自分のリポジトリに行きcreate pull requestを送る

  # フォーク元の変更をローカルに取り入れる(みんなやってほしい）
  1, git remote add upstream https://github.com/itc-s22017/anonymousChatApp.git
  
  2, git fetch upstream
  
  3, (今いるブランチがmainじゃない場合)git switch main
  
  4, git merge upstream/main


  # 手順
  1,リポジトリをフォークしてそれをクローン  
  
  2,クローンしたら __cd anonymousChatApp__ してそこで __npm i__ でエンター（ここでnodeがないってエラーが出たら __sudo apt install nodejs__ と __sudo apt install npm__ のコマンドを打つ 
  
  3,__~/anonymousChatApp/__ で __npm run dev__, __~/anonymousChatApp/backend__ で __npm start__ 
 
  4,__localhost:3000__ を開いて確認

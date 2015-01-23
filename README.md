# ForAssetServer
- ゲームジャムでUnity + AssetServerを使うときのための空プロジェクト
- Project Setting -> Editorのとこ設定しただけです
- 他に必要な設定あったら教えてください

## 注意
 - GameJamなどで配布されるUnity pro trial license、もしくはteam licenseをもっていないと使えません。
 - クライアントの設定です。別途AssetServerサーバーを立てる必要があります。
   - 管理者設定は以下あたり参照
   - http://www.slideshare.net/keigoando/asset-server-11215484 

## 設定されている項目
 - Edit -> Project Setting -> Editor
  - Version Control Mode : AssetServer
  - Asset Serialization Mode : ForceText
  - Default Behaviour Mode : 3D
    - 2D Projectなら2Dにしてください
 
## その他
 - commit時に日本語いれられなかったら以下を追加するといいかも
  - http://caitsithware.com/wordpress/archives/1362
 - リモートに建ててもいいけどローカルに建てると爆速
   - 当然ながら同じLAN内じゃないとサーバ見つけられない
     - 複数ルータがある場合に注意
   - サーバにしたマシンはスリープにならない設定にして置くこと。深夜にUSBデータ交換とかサーバ立て直しとかやるはめになる

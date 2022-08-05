# SuperNewHats-GM
## ハットの追加方法
### `CustomHats.json`にコードを追加する
```
        {
            "name": "題名",
            "author": "制作者名",
            "condition": "None",
            "resource": "ハットの画像名.png",
            "backflipresource": "ハットの_back_flip用の画像名.png",
            "backresource": "ハットの_back用の画像名.png",
            "flipresource": "ハットの_flip用の画像名.png",
            "climbresource": "ハットの_climb用の画像名.png",
            "bounce": true,
            "adaptive": true,
            "behind" : true
        },
```  
**※いらないコードは消してください**  
**※`,`を最後の行では削除してください**
#### コードの説明
`"name"` : 帽子の題名  
`"author"` : 制作者名   
`"resource"` : 帽子画像  
`"backflipresource"` : クルーの反対向きでの背面の帽子画像
`"backresource"` : クルーの背面の帽子画像
`"flipresource"` : クルーの反対向きでの帽子画像
`"climbresource"` : クルーの梯子の帽子画像
`"bounce": true` : 帽子を跳ねさせる。  
`"adaptive": true` : クルーの色に帽子画像を変える。  
`"behind": true` : メインの帽子画像を背面に変更する。

### 実装
フォークしいただき、このSuperNewHats-GMにプルリクエストしていただければSNR-GMで実装します。  

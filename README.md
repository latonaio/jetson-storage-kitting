## jetson-storage-kitting
Jetson 端末に外部拡張ストレージとして、SSDを装備する方法です。   
こちらはNVIDIA Jetson AGX Xavier 開発者キットでの例です。   

### ハードウェアの設定

[![JetsonStorageKitting](https://img.youtube.com/vi/zxjZqU0p2yY/0.jpg)](https://www.youtube.com/watch?v=zxjZqU0p2yY)

#### 手順
1. NVMe 接続のSSDディスクを用意します。
2. ドライバーでJetson AGX の裏側にある脚となっている部分のネジを4箇所外します。
3. キャリアボードを外し、裏返します。この時、内側でファンと繋がっている線が切断されないように注意します。
4. SSDディスクを装備できる部分にある、ネジを外します。
5. SSDディスクを設置し、ネジで留めます。
6. キャリアボードを元に戻します。
7. Jetson AGX の裏側にあった脚となっている部分のネジを4箇所、留めます。

### ソフトウェアの設定
[こちら](https://github.com/latonaio/jetson-disk-mounting)の手順でマウントをしてください。   

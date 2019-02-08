## 概要
このリポジトリはフロントエンドのパフォーマンス改善のための実験用です。  
    
題材のサイトに関しては、自作ではなく海外の学習サイトの「パフォーマンス最適化されていないサイトの見本」として公開されていたものを使用し、一部さらに遅く改造したりしたものです。  
    
それを自分のやり方で改善したものがfastフォルダの内容となります。

## デプロイ先
Fast:https://oimo-tools.com/frontend_performance/fast/  
     
Slow:https://oimo-tools.com/frontend_performance/slow/  
    
## 行ったこと
- webpackによるjs,cssファイルのbundle化,minify化  
- gzipによる配信  
- scriptタグのdefer/asyncの使用
- 画像の圧縮

## Lighthouseによる計測
### slow
<img width="1143" alt="2019-02-09 0 44 09" src="https://user-images.githubusercontent.com/18276888/52488822-0d87b680-2c04-11e9-9719-92d7ed816e52.png>
    
### fast
<img width="100%" alt="2019-02-09 0 45 00" src="https://user-images.githubusercontent.com/18276888/52488821-0d87b680-2c04-11e9-9ca6-9a2caea8a4cb.png">
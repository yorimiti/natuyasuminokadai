タイトル　pointgeter


---


### ゲーム概要
- プラットフォーム
webgl
- 画面解像度
960x600
- ゲーム概要
球を動かして黄色のオブジェクトを集める
赤いオブジェクトにあたるとやり直し

---


### 操作方法
- WASDで移動
- spaceでジャンプ


---


### ルール
- 球を動かして黄色のオブジェクトを集め,すべて集めるとクリア
赤いオブジェクト当たるか、ステージ外に出るとリセット

---
  void OnCollisionEnter(Collision other)
        // もしも「Floor」という「Tag」がついたオブジェクトにぶつかったら（条件）
        if (other.gameObject.CompareTag("Floor"))
        {
        
        }
---

### 使用したサイトなど
https://codegenius.org/open/courses/27/sections/155

https://unity3d.com/jp/learn/tutorials/projects/hajiuni/adding-obstacles-and-restart

http://sasanon.hatenablog.jp/entry/2017/09/17/041612

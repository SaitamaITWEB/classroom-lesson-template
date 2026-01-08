

# 手順：feedback ブランチの内容を main に反映する（fb → main）

この手順は、**先生から配布された更新内容（question.md など）を  
自分の作業ブランチ（main）に反映する方法**です。

---

## この手順が必要になるタイミング

- 授業中に「課題内容を更新しました」と案内があった
- GitHub 上で **feedback ブランチに変更が入った**
- Sync fork を実行した

👉 このとき、**まだ main には反映されていません**。

---

## 全体の流れ（先にこれだけ）
1. feedback ブランチに更新を取り込む  
2. feedback → main の Pull Request を作る  
3. Pull Request をマージする  

---

## 手順①：feedback に更新を取り込む（Sync fork）

1. 自分のリポジトリを開く
2. ブランチ一覧で **feedback** を選択
3. 表示される **Sync fork** ボタンをクリック
4. 更新が取り込まれたことを確認する

※ この時点では **main にはまだ反映されていません**

---

## 手順②：feedback → main の Pull Request を作成する

1. リポジトリ上部の **Pull requests** タブをクリック
2. **New pull request** をクリック
3. ブランチを次のように指定する  
   - base：`main`  
   - compare：`feedback`
4. 差分に更新内容（例：question.md）が表示されていることを確認
5. **Create pull request** をクリック

---

## 手順③：Pull Request をマージする

1. 作成した Pull Request を開く
2. 内容を確認する
3. **Merge pull request** をクリック
4. **Confirm merge**

これで、feedback の内容が **main に反映**されます。

---

## 注意事項（重要）

- ❌ feedback ブランチで作業しないでください  
- ❌ feedback ブランチを直接編集しないでください  
- ✅ 作業・提出は必ず main ブランチで行ってください  

feedback は **先生からの配布専用ブランチ**です。

---

## まとめ

- Sync fork：更新を「受け取る」
- Pull Request：更新を「確認する」
- Merge：更新を「反映する」

この3ステップを必ず守ってください。

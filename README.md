# 🎌『Frosthaven』日本語化手順ガイド（UABEAvalonia使用）

以下の手順で『Frosthaven』を日本語化できます。特別なツール「UABEAvalonia」を使用します。

---

## ✅ 必要なもの

- 『Frosthaven』本体（Steamでインストール済み）
- 日本語化ファイル（`I2Languages.txt`）
- UABEAvalonia（UnityAssetsBundleExtractor GUI版）

---

## 📥 Step 1: UABEAvaloniaをダウンロード

1. 以下のGitHubページにアクセスします  
   👉 [https://github.com/nesrak1/UABEA](https://github.com/nesrak1/UABEA)

2. 右側にある「**Latest**」の欄を探し、「**uabea-windows.zip**」をクリックしてダウンロードします。

3. ダウンロードしたzipファイルを解凍します。

---

## 🧰 Step 2: UABEAvaloniaを起動する

1. 解凍して出てきたフォルダの中にある `UABEAvalonia.exe` を実行します。

---

## 📦 Step 2.5: 日本語化ファイルをダウンロードする

1. このページの「**Latest**」の欄にある「**Source code (zip)**」をクリックしてダウンロードします。

2. ダウンロードしたzipファイルを解凍します。

3. 解凍されたフォルダの中にある `I2Languages.txt` を使います（このファイルが日本語翻訳データです）。

---

## 📂 Step 3: 『Frosthaven』のリソースファイルを開く

1. UABEA のメニューから「**File → Open**」を選択。

2. 以下のパスにあるファイルを指定して開きます：

   ```
   C:\Program Files (x86)\Steam\steamapps\common\Frosthaven\Frosthaven_Data\resources.assets
   ```

---

## 🔤 Step 4: I2Languagesを選択・置き換え

1. 読み込まれたアセット一覧の中から **`I2Languages`** を探します（名前の列でソートすると見つけやすいです）。

2. `I2Languages` を選択した状態で、画面右側の「**Import Dump**」をクリックします。

3. Step 2.5 で入手した `I2Languages.txt` を選択して開きます。

---

## 💾 Step 5: 上書き保存

1. メニューから「**File → Save**」を選びます。

2. 上書き保存が完了したら、UABEAvaloniaを閉じてもOKです。

---

## 🈂️ Step 6: ゲーム内で中国語（簡体字）を選択

1. 『Frosthaven』を起動します。

2. 言語設定で「**Chinese (Simplified)**」を選択してください。

3. ゲーム内の表示が日本語になっていれば成功です！

---

## 🔁 補足

- 元のファイルをバックアップしておくと安心です。
- ゲームがアップデートされると、再度日本語化が必要になる場合があります。

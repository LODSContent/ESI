## 後で使用するため Cloud Shell を準備する
1. 以下の資格情報を使用して Azure Portal +++https://portal.azure.com+++ にログインします。

    |||
    |--|--|
    |ユーザー名|+++@lab.CloudPortalCredential(User1).Username+++|
    |パスワード|+++@lab.CloudPortalCredential(User1).Password+++|

1. Azure portal の上部にあるツール バーで、[**Cloud Shell**] アイコンを選択します。

1. [Azure Cloud Shell へようこそ] ダイアログで、[**Bash**] を選択します。

1. [ストレージがマウントされていません] 画面で、[**詳細設定の表示**] を選択します。

1. [詳細設定] 画面で、次のフィールドに入力してから、[**ストレージの作成**] をクリックします。

    |||
    |--|--|
    |リソース グループ| 次の既存のリソース グループを使用する: **cloud-shell-storage-eastus**|
    |リージョン| **米国東部** |
    |ストレージ アカウント (新規作成)|+++cloudshell@lab.LabInstance.Id+++|
    |ファイル共有 (新規作成)|+++shellstorage+++|
    
  >[!知識] 「テナント ユーザーがクォータを超過しました」エラーが発生した場合は、[**Cloud Shell リージョン**] を代替リージョンに変更してください。

1. Cloud Shell が初期化し、テキスト プロンプトが表示されたら、Cloud Shell を終了します。

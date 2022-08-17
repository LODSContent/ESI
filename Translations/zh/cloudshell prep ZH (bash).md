## 准备 Cloud Shell 以供以后使用
1. 使用以下凭据登录 Azure 门户 (+++https://portal.azure.com/?l=zh-hans.zh-cn+++)：

    |||
    |--|--|
    |用户名|+++@lab.CloudPortalCredential(User1).Username+++|
    |密码|+++@lab.CloudPortalCredential(User1).Password+++|

1. 在 Azure 门户顶部的工具栏中，选择“Cloud Shell”图标。

1. 在“欢迎使用 Azure Cloud Shell”对话框中，选择“Bash”。

1. 在“你没有装载存储”屏幕上，选择“显示高级设置”。

1. 在“高级设置”屏幕中，填写以下字段，然后单击“创建存储”：

    |||
    |--|--|
    |资源组| 非 NetworkWatcherRG 的资源组|
    |存储帐户(新建)|+++cloudshell@lab.LabInstance.Id+++|
    |文件共享(新建)|+++shellstorage+++|
    
    >[!KNOWLEDGE] 如果收到“租户用户超出配额”错误，请将“Cloud Shell 区域”更改为备用区域。

1. Cloud Shell 初始化且出现文本提示后，退出 Shell。

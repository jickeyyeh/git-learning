# 學習Git的紀錄
## 1. Git初始設定
安裝Git(debian)
```
$ apt-get install git
```
### 讓 Git 知道這台電腦做的修改要連結到哪一個使用者
設定使用者名稱
```
$ git config --global user.name "<Your Name>"
```
設定電子郵件信箱
```
$ git config --global user.email "<your@gmail.com>"
```

### 將ssh pub key 上傳到Github

1. 在使用者大頭貼中, 點選Settings
2. 進入SSH and GPG keys目錄
3. 點選new SSH key
4. 將本機$USRE/.ssh目錄下的id\_{編碼方式}.pub內容貼上
5. 測試ssh 是否成功
```
ssh -T git@github.com
```
如果成功會看到下面字樣
```
The authenticity of host 'github.com (20.27.177.113)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,20.27.177.113' (ECDSA) to the list of known hosts.
Hi jickeyyeh! You've successfully authenticated, but GitHub does not provide shell access.
```

## 2. github上傳或下載
[從Github下載,更改後上傳](01.md)

---
[回目錄](README.md)

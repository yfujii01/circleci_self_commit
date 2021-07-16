# CricleCI Self Commit

CircleCIを使用して自身のリポジトリに自動でコミットする処理を実装するためのサンプル

## 初回実行時エラー

```shell
#!/bin/bash -eo pipefail
git push origin master;
ERROR: The key you are authenticating with has been marked as read only.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Exited with code exit status 128
CircleCI received exit code 128
```

## 参考

https://support.circleci.com/hc/ja/articles/360018860473-CircleCI%E3%81%AE%E3%82%B8%E3%83%A7%E3%83%96%E4%B8%8A%E3%81%A7%E3%83%AA%E3%83%9D%E3%82%B8%E3%83%88%E3%83%AA%E3%81%AB%E3%82%B3%E3%83%9F%E3%83%83%E3%83%88%E3%82%92%E3%83%97%E3%83%83%E3%82%B7%E3%83%A5%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95

https://qiita.com/yousan/items/08de8c3b81b21a57bd5c

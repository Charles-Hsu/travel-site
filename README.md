# 更改以及設定 remote 標籤 的 url 的方式

$ git remote -v
origin	https://github.com/LearnWebCode/travel-site-files.git (fetch)
origin	https://github.com/LearnWebCode/travel-site-files.git (push)
$ git remote set-url origin https://github.com/Charles-Hsu/travel-site.git
$ git remote -v
origin	https://github.com/Charles-Hsu/travel-site.git (fetch)
origin	https://github.com/Charles-Hsu/travel-site.git (push)
$ git push origin mater

# 這邊有一個介紹如何不要讓 git push pull 每次都問 username/password
[How do I avoid the specification of the username and password at every git push?
](https://stackoverflow.com/a/8588786).

$ npm init
$ npm install jquery --save
# ビルドからやる場合
```
# sudo yum install openssl
# sudo yum install gcc make git openssl-devel
# sudo yum install perl-IPC-Cmd
# make static
```
コンパイルに成功すると今いるディレクトリにsslscanが作成される。

※参考
- ubuntuであった「build-essentials」のRHEL版
https://blog.64p.org/entry/2013/07/22/142457
- 必要ないかも？
```
# sudo yum install zlib zlib-devel
```

# test_openssl

### 実行環境
OpenSSLは**1.0.2**を使用して下さい。

1.1.0だと```error: field ‘ctx’ has incomplete type```となります。

---

### コマンド
```
gcc -Wall -g test_aes_rsa.cpp -lcrypto
./a.out
```

---

### 参考サイト

- https://www.npcglib.org/~stathis/blog/precompiled-openssl/
- [OpenSSLを使ってC言語でAES暗号 - BlankTar](https://blanktar.jp/blog/2014/10/c_language-aes-with-openssl.html)
- [OpenSSL EVP](https://sehermitage.web.fc2.com/program/openssl_evp.html)
- [【C言語】OpenSSL による AES128-CBC 暗号化 - 猫ちゃんGo](https://gatito.hateblo.jp/entry/c/openssl/aes128cbc)
- [error: field ‘ctx’ has incomplete type を解決する - Qiita](https://qiita.com/ak1t0/items/8dbe79b2200e34590585)

# i2pgram
The central umbrella i2pgram repo

This currenly employs a client-server architecture. The server is https://github.com/i2pgram/chatengine and the client is https://github.com/i2pgram/i2pgram-desktop ; with potential future clients made from https://github.com/i2pgram/i2pgram-clients and https://github.com/i2pgram/webogram-flavors-umbrella .

## What is this and why

```
<x>

(re spiralnet [irc]: вот его - моя решил фигачить нашу собственную 
меритократию либертарианскую https://mastodon.ml/@math/106920789419104729 )

Что это и зачем

<spiralnet>

мессенжер, криптовалюты, обмен с деньгами
интеграция всего этого
то что хотел сделать пашка дуров и не смог
потому что чересчур жадный и сделал сам себя single point of failure
bisq эту проблему решает.
а я хочу его форкнуть потому как мне не нравится, что выплаченные 
девелуперам меритократические токены сжигаются.
```


A built image of i2pgram desktop client for Ubuntu 14.04+ http://hutor.i2p/i2pgram/

```
# ./Telegram --help
i2pgram.
options: --dchost= --dcport= --dcpubkey0file= --dcpubkey1file=
public keys must be in -----BEGIN RSA PUBLIC KEY----- format.
# cat nebuladckey0.pub 
-----BEGIN RSA PUBLIC KEY-----
MIIBCgKCAQEAvKLEOWTzt9Hn3/9Kdp/RdHcEhzmd8xXeLSpHIIzaXTLJDw8BhJy1
jR/iqeG8Je5yrtVabqMSkA6ltIpgylH///FojMsX1BHu4EPYOXQgB0qOi6kr08iX
ZIH9/iOPQOWDsL+Lt8gDG0xBy+sPe/2ZHdzKMjX6O9B4sOsxjFrk5qDoWDrioJor
AJ7eFAfPpOBf2w73ohXudSrJE0lbQ8pCWNpMY8cB9i8r+WBitcvouLDAvmtnTX7a
khoDzmKgpJBYliAY4qA73v7u5UIepE8QgV0jCOhxJCPubP8dg+/PlLLVKyxU5Cdi
QtZj2EMy4s9xlNKzX8XezE0MHEa6bQpnFwIDAQAB
-----END RSA PUBLIC KEY-----
# cat nebuladckey1.pub 
-----BEGIN PUBLIC KEY-----
MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAvKLEOWTzt9Hn3/9Kdp/R
dHcEhzmd8xXeLSpHIIzaXTLJDw8BhJy1jR/iqeG8Je5yrtVabqMSkA6ltIpgylH/
//FojMsX1BHu4EPYOXQgB0qOi6kr08iXZIH9/iOPQOWDsL+Lt8gDG0xBy+sPe/2Z
HdzKMjX6O9B4sOsxjFrk5qDoWDrioJorAJ7eFAfPpOBf2w73ohXudSrJE0lbQ8pC
WNpMY8cB9i8r+WBitcvouLDAvmtnTX7akhoDzmKgpJBYliAY4qA73v7u5UIepE8Q
gV0jCOhxJCPubP8dg+/PlLLVKyxU5CdiQtZj2EMy4s9xlNKzX8XezE0MHEa6bQpn
FwIDAQAB
-----END PUBLIC KEY-----

<-> крч лезьте на nebula.hutor.i2p port 12345
<-> БЕЗ прокси БЕЗ ипв6
<-> встроенных тележных
<-> т.е. и2пд прокси это норм, все остальные прокси это норм, а телеграмовские родные ВЫКЛ
<-> я себе завёл там номерок +7 964 00 00 01
<-> но там нада чинить парольную защиту она не пашет
<-> вот
<-> пишите там
<-> и ещё там океан просто глюков всё едва пашет, начиная с его мускуля
```


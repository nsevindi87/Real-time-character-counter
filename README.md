# Real-time-character-counter
With this project, it is aimed to write o project thar counts the number of simultaneous chracters and falls from the limit.

HEDEF: Text alanina yazilan yazinin uzunlugunu ölcme ve daha önceden tespit edilen uzunluktan kalan sayiyi gösterme.

JS Kismi:

 - Text alani - toplam yazilan - kalan kisim icin ayri ayri baglanti kurulur.
 - Text alanindaki degisiklige bir event atamasi yapilir. "KEYUP" özelligi kullanilmaktadir.
 - foksiyonda:
    - Toplam yazilana innerText ile atama yapilir. bu atama text alanindaki degerin uzunlugudur.
    -  kalan kisma innerText ile atama yapilir. Bu atama HTML kisminda maxLength ile atanan deger getAtribute ile alinir.
    -  Bu degerden textalaninda yazilan degerin uzunlugu cikarili ve sonunda kalan deger bulunur.

* Fonksiyor event atama haricinde tekrar cagrilir ki total kisminin 0 olmasi, kalan kismin maxLength kadar oldugu kendiliginden yazilsin.

# astro.dozi.app -> astro.bardino.app

Bu depo yalnizca eski adresi yeni adrese yonlendirir. Sitenin kendisi
https://astro.bardino.app adresinde, kaynagi astro-dozi-web deposunda.

- Her eski sayfa ayni yoldaki yeni sayfaya gider (JS + meta refresh); sorgu ve # korunur.
- Bilinmeyen yollar 404.html uzerinden ayni yol ve sorguyla yonlenir (paylasilan /refer/KOD ve /compat?code=... linkleri dahil).
- app-ads.txt burada 200 ile dogrudan sunulur. Magaza kaydindaki gelistirici web sitesi
  alani astro.dozi.app kaldigi surece AdMob bu dosyayi buradan okur; AdMob'un baska alan
  adina yonlendirmeyi izleyip izlemedigi belgelenmemis.
- .well-known/assetlinks.json bayt bayt kaynaktaki gibi. Astro Dozi Android uygulamasi
  (com.bardino.zodi) astro.dozi.app linkleri icin App Links dogrulamasini buradan yapar;
  dosya yonlendirilirse dogrulama duser.

Uygulamalardaki ve magaza kayitlarindaki linkler yeni adrese gecip dozi.app devredildiginde
bu depo silinebilir.

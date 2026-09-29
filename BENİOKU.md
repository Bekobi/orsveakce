# Örs ve Akçe · sürüm 1.2

Bu klasör oyunun telefona uygulama gibi kurulabilen (PWA) sürümüdür. GitHub Pages'e yükleyip telefondan ana ekrana ekleyebilirsin.

## GitHub Pages'e yükleme

1. GitHub'da yeni bir depo aç, örneğin `ors-ve-akce`. Herkese açık (Public) olsun.
2. Depo sayfasında **Add file → Upload files** seç.
3. Bu klasörün **içindeki** her şeyi sürükle: `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` ve `icons` klasörü. Klasörün kendisini değil, içindekileri yükle ki `index.html` deponun kökünde olsun. `.nojekyll` gizli dosya olduğu için görünmezse sorun değil, oyun onsuz da çalışır.
4. **Commit changes** ile kaydet.
5. **Settings → Pages** bölümüne git. *Source* olarak **Deploy from a branch**, dal olarak **main** ve klasör olarak **/(root)** seç, kaydet.
6. Bir iki dakika sonra sayfanın üstünde adres çıkar: `https://KULLANICI-ADIN.github.io/ors-ve-akce/`

## Telefona kurma

- **Android (Chrome):** Adresi aç, sağ üstteki menüden **Uygulamayı yükle** ya da **Ana ekrana ekle** seç.
- **iPhone (Safari):** Adresi aç, **Paylaş** düğmesine bas, **Ana Ekrana Ekle** seç.

Ana ekrandaki simgeden açınca oyun tarayıcı çubuğu olmadan, tam ekran açılır. Bir kez açıldıktan sonra internet olmadan da çalışır.

## Kayıt

Oyun 5 saniyede bir ve örste her basıştan sonra kendiliğinden kaydeder. Ayarlar menüsünden elle kaydedebilir ya da oyunu sıfırlayabilirsin.

Kayıt cihazın içinde tutulur. Claude'daki sürümün kaydı ile telefona kurduğun sürümün kaydı birbirinden ayrıdır.

## Güncelleme

Yeni bir sürüm geldiğinde `index.html` dosyasını depoda değiştir ve `sw.js` içindeki sürüm satırını artır, örneğin `orsakce-v1.2` yerine bir sonraki sürüm. Telefonda oyunu bir kez açıp kapattıktan sonra, sonraki açılışta yeni sürüm gelir. Kaydın silinmez.

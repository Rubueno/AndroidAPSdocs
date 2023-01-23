# Git'i kurun

## Windows

### 1. Git'i indir

- **Android Studio çeşitli güncellemeler indirdiği için her zaman çevrimiçi olmanız gerekir!**
- Herhangi bir git sürümü çalışması gerekir. Örneğin [https://git-scm.com/download/win](https://git-scm.com/download/win).
- Kurulum yerini not ettiğinizden emin olun. Bir sonraki adımda ihtiyacınız olacak.

```{image} ../images/Update_GitPath.png
:alt: Git kurulum yolu
```

### 2. Android Studio'da git yolunu ayarla

- Dosyayı Aç > Ayarlar

  ```{image} ../images/Update_GitSettings1.png
  :alt: "Android Studio - ayarlar\u0131 a\xE7"
  ```

- Alt menüyü açmak için Sürüm Kontrolü (1.) yanındaki küçük üçgene tıklayın.

- Git'e tıklayın (2.).

- Güncelleme yönteminin "Merge" (3.) seçili olduğundan emin olun.

- "Test" düğmesine tıklayarak Android Studio'nun git.exe yolunu otomatik olarak bulup bulamayacağını kontrol edin (4.)

  ```{image} ../images/AndroidStudio361_09.png
  :alt: "Android Studio ayarlar\u0131"
  ```

- Otomatik ayar başarılı olursa git versiyonu görüntülenecektir.

- İletişim kutusunda (1.) "OK" ve ayarlar penceresinde (2.) "OK" düğmesini tıklayın.

  ```{image} ../images/AndroidStudio361_10.png
  :alt: "Otomatik git kurulumu ba\u015Far\u0131l\u0131"
  ```

- git.exe dosyasının bulunamaması durumunda iletişim kutusundaki (1.) "OK" ve ardından üç noktalı (2.) düğmeyi tıklayın.

- Nerede bulunacağından emin değilseniz "git.exe"yi bulmak için Windows Gezgini'nde [arama işlevini](https://www.tenforums.com/tutorials/94452-search-file-explorer-windows-10-a.html) kullanın. binklasöründe bulunan git.exe'yi arıyoruz.

- git.exe yolunu seçin ve **\\bin\\** klasöründeki yolu (3.) seçtiğinizden emin olun ve "OK"e (4.) tıklayın.

- "OK" butonuna (5.) tıklayarak ayarlar penceresini kapatın.

  ```{image} ../images/AndroidStudio361_11.png
  :alt: "Otomatik git kurulumu ba\u015Far\u0131s\u0131z"
  ```

### 3. Yeniden başlat

- Sistemi güncellemek için bilgisayarınızı yeniden başlatın.

### 4. Android Studio'da git ayarlarını kontrol edin

- Android Studio'da Terminal penceresini açın

- `git --version` girin (tırnak işaretleri olmadan ve iki - \[eksi işareti\] arasında boşluk bırakmadan!) ve Return tuşuna basın

  ```{image} ../images/AndroidStudio_gitversion1.png
  :alt: git - -version
  ```

- Git düzgün bir şekilde kurulur ve bağlanırsa, kurulu sürüm hakkında aşağıdaki gibi görünen bir bilgi alacaksınız:

  ```{image} ../images/AndroidStudio_gitversion2.png
  :alt: git-version durumu
  ```

## Mac

- Herhangi bir git sürümü çalışması gerekir. Örneğin, [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
- Git'i kurmak için homebrew kullanın: `` `$ brew install git` ``.
- Git kurulumuyla ilgili ayrıntılar için `resmi git belgelerine <https://git-scm.com/book/en/v2/Getting-Started-Installing-Git>` bakın.
- Git'i homebrew aracılığıyla kurarsanız, herhangi bir tercihi değiştirmenize gerek yoktur. Her ihtimale karşı: Android Studio - Tercihler altında bulabilirsiniz.
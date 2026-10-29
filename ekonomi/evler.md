# Evler

Ev; eşyalarınızı sabitleyip saklayabildiğiniz, içinde banka açıp dirilebildiğiniz, carpentry ile dekore edebildiğiniz kalıcı bir yapıdır. Bu sayfada ev edinme, ev menüsü, ev komutları, ev boyama ve dekorasyon anlatılıyor.

## Ev kontratı edinmek

Ev kontratları Safe Alan'daki **Genel Satıcı**'dan **Çimento** karşılığında alınır. Çimento madende kazılır.

| Kontrat                                  | Çimento |
| ---------------------------------------- | ------- |
| Small Stone House                        | 50      |
| Two Story House (taş ve sıva, iki katlı) | 75      |
| Tower                                    | 100     |
| Keep                                     | 150     |
| Castle                                   | 250     |

## Evi kurmak

Ev kontratını oyuncular kendisi kuramaz; kontrata çift tıklayınca **"Kurulum yapmak için bir staff'dan yardım isteyiniz"** yazar. Kurmak istediğiniz yeri belirleyip bir yetkiliden yardım isteyin.

* Bir karakterin aynı anda **tek evi** olabilir. İkinci ev için önce diğer evi kaldırmanız gerekir.
* Kurulumda size **Kontrat Menüsü** açılır; **Kabul Ediyorum** derseniz ev sizin olur, **Vazgeç** derseniz kontrat çantanıza geri döner.
* Kurallara aykırı yere kurulan evler yetkililer tarafından **hatalı** olarak işaretlenir ve kaldırmanız için süre verilir. Süre içinde kaldırılmayan hatalı ev silinir.

Evin kurulacağı yer için kurallar:

| Yakınında ev kurulamayan şey | Mesafe  |
| ---------------------------- | ------- |
| Ağaç                         | 5 kare  |
| Kapı                         | 8 kare  |
| Başka ev, tabela             | 10 kare |
| Moongate                     | 15 kare |
| Spawn                        | 15 kare |
| Tower                        | 15 kare |
| Keep                         | 20 kare |
| Castle                       | 29 kare |

Ev kurulamaz olarak işaretli bölgelere ve "Ev Kurulmaz" uyarı işaretlerinin 10 kare yakınına ev kurulamaz.

## Ev menüsü

Evin **tabelasına** çift tıklayın. Ev sahibi, ortaklar ve dostlar ev menüsünü açar; diğer oyuncular ziyaretçi olarak sayılır.

| Bölüm        | İçerik                                                                          |
| ------------ | ------------------------------------------------------------------------------- |
| Genel        | Ev sahibi, evin durumu, kalan yenileme süresi, kuruluş tarihi, ziyaretçi sayısı |
| Güvenlik     | Ortak ve dost ekleme/silme, listeleri görme, evi halka açma                     |
| Depolama     | Güvenli depolama ve sabit eşya sınırları, kullanılan ve kalan yer               |
| Özelleştirme | Tabelayı değiştirme (sadece halka açık evde), evi yeniden adlandırma            |
| Mülkiyet     | Evi kaldırma, evi devretme                                                      |
| Banka        | Evin içindeyken bankanızı açar (tabelaya en fazla 15 kare)                      |

### Yetkiler

| Yetki            | Kim                                                         | En fazla |
| ---------------- | ----------------------------------------------------------- | -------- |
| Sahip            | Evi kuran karakter ve **aynı hesaptaki bütün karakterleri** | —        |
| Ortak (co-owner) | Sahibin davet ettiği oyuncular                              | 15       |
| Dost (friend)    | Sahip ya da ortakların davet ettiği oyuncular               | 30       |

Ortaklık ve dostluk davet ile olur; davet edilen oyuncunun ekranında açılan pencerede kabul etmesi gerekir.

| İşlem                                                  | Sahip | Ortak | Dost |
| ------------------------------------------------------ | ----- | ----- | ---- |
| Ev menüsünü açmak, evde banka ve res                   | ✔     | ✔     | ✔    |
| Evden birini atmak                                     | ✔     | ✔     | ✔    |
| Eşya sabitlemek / güvenli yapmak / sabitliği kaldırmak | ✔     | ✔     | —    |
| Çöp varili koymak, eşya yükseltmek/indirmek            | ✔     | ✔     | —    |
| Dost eklemek / silmek                                  | ✔     | ✔     | —    |
| Ortak eklemek / silmek                                 | ✔     | —     | —    |
| Evi kaldırmak, devretmek, adlandırmak, halka açmak     | ✔     | —     | —    |

Ev sahibi ve ortaklar canı %80'in altındayken ya da zehirliyken kendi evlerine giremez.

## Yenileme süresi

Evler **15 günde** bir yenilenmelidir.

* Sahip, ortak ya da dost **tabelaya çift tıklayınca** süre 15 güne yenilenir ("Evi yenilediniz").
* Sahip tabelaya **tek tıklayınca** da süre yenilenir. Tabelaya tıklayınca silinmeye kalan süre görünür.
* 15 gün boyunca yenilenmeyen ev **silinir ve kontrat geri verilmez**. Evdeki sabit eşyalar sabitliğini kaybeder ve zamanla yok olur.

{% hint style="warning" %}
Uzun süre oyuna girmeyecekseniz evinizi bir ortağa ya da dosta emanet edin; tabelaya çift tıklaması süreyi yeniler.
{% endhint %}

## Ev komutları

Bu komutlar evin içindeyken **normal konuşma** olarak yazılır (nokta olmadan). İngilizce ya da Türkçe yazabilirsiniz.

| Yazın                                                    | Ne yapar                                                                                       | Yetki  |
| -------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------ |
| `I wish to lock this down` / `sabitle`                   | Seçtiğiniz eşyayı eve sabitler                                                                 | Ortak  |
| `I wish to secure this` / `guvenli`                      | Seçtiğiniz kabı güvenli (kilitli) yapar                                                        | Ortak  |
| `I wish to release this` / `sabit kaldir`                | Sabitlenmiş eşyayı serbest bırakır                                                             | Ortak  |
| `I wish to place a trash barrel` / `barrel koy`          | Ayağınızın dibine çöp varili koyar (içine atılan eşyalar 3 dakika sonra kalıcı olarak silinir) | Ortak  |
| `barrel kaldir`                                          | Seçtiğiniz çöp varilini kaldırır                                                               | Ortak  |
| `item up` / `esya yukselt`                               | Sabit eşyayı yükseltir (canınız tam olmalı)                                                    | Ortak  |
| `item down` / `esya indir`                               | Sabit eşyayı alçaltır (canınız tam olmalı)                                                     | Ortak  |
| `I ban thee` / `evden at` / `Remove thyself` / `yasakla` | Seçtiğiniz kişiyi evden dışarı atar (geri girebilir)                                           | Dost   |
| `bank`                                                   | Bankanızı açar                                                                                 | Dost   |
| `res` / `resurrect`                                      | Ölüyken 10 saniye sonra evin içinde dirilirsiniz                                               | Dost   |
| `ev yardim` / `house help`                               | Ev komutları yardım penceresi                                                                  | Herkes |
| `evden ayril`                                            | 10 saniye sonra evden dışarı çıkarsınız                                                        | Herkes |

Evden çıkmak için **`.evcik`**, **`.evdencik`** ya da **`.ayril`** komutları da kullanılabilir. 10 saniye geri sayımdan sonra evin tabelasının bulunduğu yere çıkarsınız; geri sayım bitmeden evden kendiniz çıkarsanız işlem iptal olur.

Ölüyken bu komutlar (res hariç) kullanılamaz.

## Depolama

Bir evin güvenli depolama sınırı evin büyüklüğüne göre hesaplanır. Sabitlenebilen eşya sınırı bu değerin yarısıdır. Güvenli kaplara konan eşyalar da sınıra sayılır. Güncel değerleri ev menüsünün **Depolama** bölümünde görürsünüz.

{% hint style="warning" %}
Evin içinde **sabitlenmemiş** eşyalar normal dünyadaki gibi zamanla silinir. Saklamak istediğiniz eşyaları sabitleyin ya da güvenli bir kaba koyun.
{% endhint %}

## Evi kaldırmak ve devretmek

**Evi kaldırmak:** Mülkiyet → **Evi kaldır** → **Kabul Ediyorum**. Ev kontrata dönüşür ve çantanıza gelir.

* Evin içinde guild taşı ya da vendor varsa ev kaldırılamaz.
* Eve ya da tabelaya en fazla 15 kare uzakta olmalısınız.
* Evin içindeki sabit eşyalar sabitliğini kaybeder ve zamanla silinir; kaldırmadan önce eşyalarınızı alın.
* Evin boyası sıfırlanır.

**Evi devretmek:** Mülkiyet → **Evi devret** → evi vereceğiniz oyuncuyu seçin. Karşı tarafa bir onay penceresi gider, ardından takas penceresi açılır. İkiniz de takası onaylayınca ev el değiştirir. İkiniz de tabelanın yakınında durmalısınız. Vendor bulunan ya da hatalı işaretlenmiş ev devredilemez.

**Halka açmak:** Güvenlik → **Evi halka aç** (kapılarınızın herkese açık olması gerekir). Tabela sadece halka açık evlerde değiştirilebilir.

## Ev boyama

**Özel Ev Boyama Kiti** evinizin (ev, kule, kale) rengini değiştirir.

1. Kit çantanızdayken çift tıklayın, 15 renkten birini seçin.
2. **Seçili Rengi Evime Uygula**'ya basın.
3. Evin tabelasını ya da evin kendisini (duvar, zemin) seçin. Evin içindeyseniz kendinizi de seçebilirsiniz. Evin dışındaysanız tabelaya en fazla 10 kare uzakta olmalısınız.

| Renkler      |              |              |
| ------------ | ------------ | ------------ |
| Parlak Gri   | Koyu Gri     | Kahve Köpüğü |
| Koyu Kahve   | Turuncu      | Açık Kırmızı |
| Koyu Kırmızı | Açık Mavi    | Koyu Mavi    |
| Açık Yeşil   | Koyu Yeşil   | Mor          |
| Turkuaz      | Altın Sarısı | Gece Siyahı  |

* Kit **bir boyamada** harcanır.
* **Evin Boyasını Sil** evin rengini normale döndürür; kit harcanmaz (kit çantanızda olmalıdır).
* Sadece **kendi evinizi** (sahibi olduğunuz evi) boyayabilirsiniz.
* Ev kontrata dönüştürülürse renk sıfırlanır.

## Dekorasyon (Carpentry)

Evinizi mobilya ve dekorlarla döşemek için çantanızdaki bir **Saw**'a (testere) çift tıklayın. Carpentry menüsü açılır.

* Eşyalar **sadece bir evin içindeyken** üretilebilir.
* İki üretim arasında **5 saniye** beklemelisiniz.
* Bu menüden üretilen eşyalar **ev dışında yere bırakılırsa silinir**.

| Kategori          | Örnekler                                                                                                                                                  |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chairs            | Taht, sandalyeler, tabureler, bank                                                                                                                        |
| Containers        | Sandıklar, kasalar, fıçılar, sepetler                                                                                                                     |
| Tables            | Masalar, yazı masası, komodin                                                                                                                             |
| Weapons & Tools   | Club, staff'lar, olta, balta, tahta kalkan                                                                                                                |
| Bar               | Bar tezgâhı parçaları ve bar kapıları                                                                                                                     |
| Furnitures - 1    | Kitaplık, çekmeceli dolap, gardırop                                                                                                                       |
| Decorations       | Nota sehpası ve dekorlar                                                                                                                                  |
| Other - 1 / 2 / 3 | Boya küveti, maket gemi, dart tahtası, örs, ocak, dokuma tezgâhı, eğitim mankeni, erzak/malzeme/meyve/takım/iksir dolabı, piyano, saatli dolap, balkabağı |
| Mutfak            | Çeşme, mutfak dolapları, mutfak malzemeleri, tezgâh                                                                                                       |
| Banyo             | Ayna, lavabo, klozet, küvet, boy aynası                                                                                                                   |
| Araçlar           | Ocaklar (forge) ve tezgâhlar                                                                                                                              |
| Dekor / Dekor 2   | Sehpalar, silah ve kalkan dekorları, köpek kulübesi, kitaplık, akvaryum                                                                                   |
| Deed Ürün         | Pentagram kontratı                                                                                                                                        |

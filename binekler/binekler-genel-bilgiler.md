# Binekler: Genel Bilgiler

Rampage PvP'de binekler sadece ulaşım aracı değildir. Birçoğu binene özel bonus verir, bazılarının `.binekbonus` ile kullanılan yetenekleri vardır. Bu sayfada bineklerin nasıl edinildiği, figür sistemi, ortak komutlar ve binek ölümüyle ilgili kurallar anlatılıyor.

## Binek nasıl edinilir?

| Yol                          | Neler çıkar                                                                                       | Ayrıntı                                                                 |
| ---------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| Binek Taşı (gold)            | Cu Sidhe, Primal Raptor, N-Mandre, Ferrin, Kii Rin, Unicorn, Raptor, Arcane Ostard, Animal Book   | **Binek Taşı ve Yumurtalar** sayfası                                    |
| Yumurtalar                   | Random Egg, Olgun Ostard Egg, Special Egg, Soul Egg, Mother Ostard Egg                            | **Binek Taşı ve Yumurtalar** sayfası                                    |
| Evcilleştirme                | Random spawn binekleri, hazine bekçisinden çıkan binekler, Ghost Ostard                           | **Taming (Evcilleştirme)** ve **Random Spawn Binekleri** sayfaları      |
| Ruh Belgesi                  | Percheron                                                                                         | **Binek Taşı ve Yumurtalar** sayfası                                    |
| Koleksiyonlar ve etkinlikler | Armored Steed (Storm Puzzle), Ordeal (Ordeal Puzzle), Glacier Steed (balık etkinliği), yumurtalar | **Solo Dungeon ve Puzzle Koleksiyonları** sayfası ve etkinlik sayfaları |

Satın alınan ya da yumurtadan çıkan binek, hemen yanınızda **size ait** olarak belirir. Bineklerin yetenekleri **Özel Binekler** sayfasında.

## Binme ve inme

* Bineğe çift tıklayarak binersiniz. Binince ekranda bineğin canı (**Binek Hits**) ve açlığı (**Binek Food**) yazar.
* **Zehirli bir bineğe binemezsiniz.** Önce zehrini temizleyin (aşağıda `.binekcure`).
* Bindiğinizde bineğin açlığı tamamen dolar.
* Dismount bonusuyla bineğinizden düşürülürseniz birkaç saniye tekrar binemezsiniz.
* Savaş modundayken (war mode) kendinize çift tıklarsanız binekten inip hedefinize saldırmaya devam edersiniz.
* Bineğinizden indiğinizde ve savaş modundaysanız, bineğiniz hedefinize saldırır.

## Figür (küçültme ve çıkarma)

Bineklerinizi taşımak ya da saklamak için **Animal Deed (Binek Deed)** ile küçültüp figüre çevirirsiniz.

**Animal Deed nereden alınır?** Safe alandaki **Diğer Menü** taşından ücretsiz alınır (her tıklamada 5 adet).

**Küçültme şartları:**

* Binek size ait olmalı, en fazla 3 kare uzakta ve görüş alanınızda olmalı.
* Bineğin canı tam olmalı (yaralı binek küçültülemez).
* Binek zehirli, aç, felçli ya da bir büyünün (bless, strength vb.) etkisi altında olmamalı.
* Ghost Ostard'ın çantası boş olmalı.
* Deed çantanızda olmalı, görünmezken (hide/invis) kullanılamaz.

Figür bineğin bütün bilgilerini saklar: **statları, ismi, mavi/Lord görünümü ve geliştirmeleri**. Figüre tek tıklayınca bineğin statları görünür.

**Figürden binek çıkarma (figüre çift tıklama):**

* Figür çantanızda olmalı. Görünmezken ve evlerin içinde binek çıkarılamaz.
* Çantanızda **3'ten fazla figür** varsa binek çıkaramazsınız.
* Etrafınızda (25 kare) size ait **en fazla 3** canlı olabilir.
* İki binek çıkarma arasında **15 saniye** beklenir.
* Figürden binek çıkardıktan sonra **10 saniye** binek komutu kullanılamaz.

{% hint style="warning" %}
Yere bırakılan figürler bir süre sonra silinir. Figürlerinizi çantanızda, bankanızda ya da depoda tutun (**Eşya Deposu (.depo)** sayfası).
{% endhint %}

## Binek komutları

| Komut                 | Ne yapar                                                                                                                             |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `.bb` / `.binekbilgi` | Hedeflediğiniz bineğin bilgi menüsünü açar (aşağıda).                                                                                |
| `.binekbonus`         | Bindiğiniz bineğin özel yeteneğini kullanır. Her bineğin yeteneği farklıdır (**Özel Binekler** sayfası).                             |
| `.binekcure`          | 3 kare içindeki size ait **zehirli** bineğin zehrini temizler. Çantada 1 Greater Cure Potion harcar, **30 saniyede bir** kullanılır. |
| `.spawntakip`         | Haritada kaç aktif random spawn bineği olduğunu söyler.                                                                              |

Bazı bineklerin kendi adıyla da komutu vardır (`.savasborusu`, `.kankokusu`, `.ferrinheal`, `.unires`, `.cornres` vb.); hepsi **Özel Binekler** sayfasında yazıyor.

{% hint style="info" %}
Saldırı türü binek yeteneklerinin çoğu **safe alanda kullanılamaz** ve canınız **50'nin altındayken** çalışmaz.
{% endhint %}

## Binek bilgi menüsü (`.bb`)

`.bb` yazıp bir bineğe tıkladığınızda şunları gösterir:

* Binek adı ve statları
* Açlık seviyesi (Food)
* Bineğin sahibi (ya da "Sahipsiz")
* **Resleme bilgisi:** bineği diriltmek için kaç Binek Resurrection Scroll gerektiği (ya da reslenemez olduğu)
* Bineğin geliştirme sınırı
* Bineğin sahibine verdiği özellik ve bineğin vuruş özelliği

Menüdeki iki buton sadece **safe alanda** ve **kendi bineğinizde** çalışır, ücret bankanızdaki kumbaradan düşülür:

| Buton          | Ne yapar                     | Ücret        |
| -------------- | ---------------------------- | ------------ |
| Mavi yap       | Bineğin ismi mavi görünür    | 75.000 gold  |
| Lord ünvan ver | Bineğe "Lord" ünvanı verilir | 100.000 gold |

{% hint style="info" %}
`.bb` menüsündeki özellik yazıları her binek için güncel olmayabilir. Kesin bilgi için **Özel Binekler** sayfasına bakın.
{% endhint %}

## Bineğin açlığı ve Binek Silici

Bineğe tıklayınca üstünde sahibinin adı ya da "(Sahipsiz)" yazar. Bineğin silinmek üzere olduğu durumlarda **\[Silinecek: kalan süre]** de yazar.

| Durum                                            | Ne olur                                                         |
| ------------------------------------------------ | --------------------------------------------------------------- |
| **Safe alanda bineğinizden inerseniz**           | Binek **30 dakika** içinde tekrar binilmezse silinir.           |
| Size ait binek (binilmemiş) safe alana girerse   | 30 dakika sonra silinir. Safe alandan çıkınca sayaç iptal olur. |
| Sıradan at ya da llama'dan inerseniz (her yerde) | **5 dakika** içinde binilmezse silinir.                         |

Bineğe tekrar bindiğinizde silme sayacı iptal olur.

{% hint style="warning" %}
Safe alanda bineğinizden inip uzun süre ayrılmayın. İnecekseniz bineğinizi Animal Deed ile küçültün.
{% endhint %}

Binekli olarak safe alana girdiğinizde bineğinizin canı tamamen dolar.

## Binek ölünce

* Sahipli bir binek öldüğünde bütün sunucuya duyurulur.
* Binek ölünce cesedi kalır. Cesedi **Binek Resurrection Scroll** ile diriltebilirsiniz.

**Diriltme (Binek Res):**

1. Binek Res Scroll'a çantanızdayken çift tıklayın, bineğin cesedini seçin (en fazla 3 kare).
2. Her binek türü farklı sayıda scroll ister. Kaç scroll gerektiği `.bb` menüsünde "Resurrection Scroll" satırında yazar.
3. Scroll'lar harcanır, binek size ait olarak, eski rengiyle dirilir.

{% hint style="warning" %}
Diriltilen binek, o binek türünün **başlangıç statlarıyla** geri gelir. Sonradan basılan STR/DEX/armor belgeleri ve isim geri gelmez.
{% endhint %}

Bazı binekler reslenemez (Res Scroll satırında "Reslenemez" yazar).

Bineğe çok sayıda STR ya da DEX belgesi basılmışsa, binek öldüğünde basılan belgelerin bir kısmı cesetten geri düşebilir.

**Binek Res Scroll nereden çıkar?** Dungeon canavarları ve boss'lar, Solo Dungeon ve Zindan ödülleri ve çeşitli etkinlik ödülleri (**Bosslar** ve **Canavarlar** sayfaları).

## Bineklerin oyunculara vuruşu

Binilmemiş bir binek savaşırken oyunculara verdiği hasar, **bineğin STR'sine** ve **oyuncunun armoruna** göre belirlenir: güçlü binekler daha sert vurur, armoru yüksek oyuncular daha az hasar alır. Birçok bineğin ayrıca kendi vuruş özelliği (zehir, kanama, ek hasar, attan düşürme vb.) vardır; `.bb` menüsünde yazar.

**Animal Shield / Belt of Defence** özelliği olan eşyalar, binek vuruşlarını belli bir ihtimalle tamamen engeller.

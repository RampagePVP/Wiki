# Karakter

Bu sayfa karakterinizle ilgili sistemleri anlatır: fame, şöhret, rütbe ve PvP puanı, Honor Point, ölüm, isim/cinsiyet/saç değiştirme, boyalar, aile, Güç Yüzüğü, kelle sistemi ve hesap güvenliği.

## Karakter menüsü (profil)

Kendi paperdoll'unuzdaki **Profile** butonuna basınca Karakter Menü açılır: hesap adı, karakter adı, hesaptaki karakter sayısı, kayıt tarihi, toplam online süre (saat), fame/karma, kill/death, yetenek toplamı, statlar, ünvan, bulunduğunuz bölge ve toplam gold (banka + kumbara).

Başka bir oyuncunun bilgilerini görmek için `.kontrol` yazıp oyuncuyu hedefleyin.

## Fame

Fame en fazla **10.000** olabilir. Fame'i 10.000 olan oyuncunun adının başında **Lord** (kadın karakterlerde **Lady**) yazar.

| Nasıl değişir                | Miktar                                |
| ---------------------------- | ------------------------------------- |
| PvP öldürmesi (puan sayılan) | +250                                  |
| Kelle sallandırma            | +1.000 (düşük fame'li kellede +750)   |
| Fame Taşı                    | Her 10 dakikada oyundaki herkese +100 |
| Kellenizin sallandırılması   | -1.500                                |
| Deathmatch alanında ölmek    | -100 ile -500 arası                   |

{% hint style="info" %}
Fame önemlidir: fame'i **7.000**'in altındaki bir oyuncuyu öldürmek PvP puanı kazandırmaz.
{% endhint %}

## PvP öldürmeleri ve puanlar

Bir oyuncuyu öldürdüğünüzde ölüm bütün sunucuya duyurulur ("X, Y tarafından Z civarlarında öldürüldü"). Öldürmenin **puan sayılması** için:

* Öldüren bir oyuncu olmalı (bineğinizin ya da hayvanınızın öldürdüğü oyuncu puan getirmez).
* Ölen oyuncunun fame'i en az **7.000** olmalı.
* Ölen oyuncu son **5 dakika** içinde puan sayılan bir ölüm yaşamamış olmalı.
* İkiniz aynı guildde olmamalısınız.

Puan sayılan her öldürmede öldüren şunları kazanır:

| Ödül                      | Miktar                                  |
| ------------------------- | --------------------------------------- |
| Rütbe puanı (Action Puan) | +1                                      |
| Haftalık sıralama puanı   | +1                                      |
| Şöhret puanı              | +1                                      |
| Fame                      | +250                                    |
| Honor Point               | 5 adet                                  |
| Guild puanı               | +1 (iki oyuncu da farklı guildlerdeyse) |

Ölen oyuncu puan **kaybetmez**.

## Rütbe

Bir oyuncuya tıklayınca rütbesi ve puanı görünür, örneğin `[Yzb] [P:160]`.

| Rütbe           | Puan          |
| --------------- | ------------- |
| Er              | 0 - 20        |
| Onbaşı (Onb)    | 21 - 40       |
| Çavuş (Cvs)     | 41 - 60       |
| Başçavuş (Bcvs) | 61 - 90       |
| Teğmen (Tgm)    | 91 - 150      |
| Yüzbaşı (Yzb)   | 151 - 200     |
| Binbaşı (Bnb)   | 201 - 250     |
| Yarbay (Yb)     | 251 - 300     |
| Albay (Alb)     | 301 - 400     |
| General (Gen)   | 401 - 600     |
| Orgeneral (Org) | 601 - 800     |
| Mareşal         | 801 - 1.000   |
| Legend          | 1.001 ve üstü |

## Şöhret puanı

Şöhret puanı, puan sayılan öldürmelerinizin sayısıdır. `.sohret` ile görürsünüz. Şöhret arttıkça karakterinizin ten rengi değişir; yeni bir kademeye geçince üzerinizde "_Şöhret_" yazar.

| Şöhret puanı |                |
| ------------ | -------------- |
| 0 - 49       | Normal ten     |
| 50           | 1. kademe renk |
| 200          | 2. kademe renk |
| 400          | 3. kademe renk |
| 600          | 4. kademe renk |
| 800 ve üstü  | 5. kademe renk |

Kelleniz sallandırılırsa şöhret puanınız (5'ten fazlaysa) 2-4 azalır.

## Honor Point

Honor Point puan sayılan her PvP öldürmesinde 5 adet olarak çantanıza gelir (guild istilası gibi bazı etkinlikler de verir). Safe alandaki **Honor Point Stone**'da harcanır:

| Eşya                | Fiyat           |
| ------------------- | --------------- |
| Talisman of Mage    | 250 Honor Point |
| Talisman of Warlock | 250 Honor Point |
| Talisman of Warrior | 250 Honor Point |

Talismanlar **7 gün** sürer ve sadece kendi sınıfınız (ünvanınız) tarafından takılabilir. Takıldığında can yenileme etkisi verir; `.talismanpower` ile 10 dakikada bir sınıfa özel güç kullanılır (örneğin Talisman of Warrior can verir, zehri ve kanamayı temizler).

## Silver Coin

Sunucudaki Puan Taşı her 10 dakikada oyundaki (ölü olmayan) her oyuncuya **1 Silver Coin** verir; o anda Action Alan'daysanız **2**. Silver Coin'lerinizi eşya deposunda (`.depo`, Malzemeler bölümü) saklayabilirsiniz.

## Online Kredi

Oyunda geçirdiğiniz her dakika hesabınıza **1 Online Kredi** ekler ("Kredi Puan +1" mesajı). Kredi hesap geneldir, bütün karakterleriniz aynı krediyi kullanır. Safe alanda `.kredi` yazarak krediyi harcayabilirsiniz:

| Ödül                                           | Kredi |
| ---------------------------------------------- | ----- |
| 150 adet Str Deed Belgesi (çanta içinde)       | 600   |
| 5 Extremely Ingot (çanta içinde)               | 900   |
| Ender Hazine Haritası                          | 1.000 |
| 5M Gold Check                                  | 2.000 |
| 10.000 Binek Res Scroll (çanta içinde)         | 3.000 |
| 1 Hafta Abone Deed (7 günlük abonelik belgesi) | 6.000 |

## Ölüm

* Öldüğünüzde `.res` yazıp onaylayarak safe alanda tam canla dirilebilirsiniz.
* Ölünce zehir, kanama ve bazı geçici etkiler üzerinizden kalkar.
* Safe alanda ölünmez.
* Cesetleriniz 7 dakika sonra kaybolur; kaybolmaz (newbie) eşyalar üzerinizde kalır.

## İsim değiştirme

**İsim Değiştirme Belgesi** safe alandaki Genel Satıcı'dan alınır (50.000 gold). Belgeyi çantanızdayken çift tıklayın ve yeni isminizi yazın.

* 3 - 16 karakter, sadece harf (Türkçe karakter, rakam ve boşluk olmaz).
* Sunucuda başka bir karakterin kullandığı isim alınamaz.
* İsminiz otomatik olarak ilk harfi büyük, gerisi küçük olacak şekilde düzenlenir.
* Bir aileye üye olan karakter isim değiştiremez.
* Argo/küfürlü isimler yasaktır.

## Cinsiyet değiştirme

**Cinsiyet Belgesi** Genel Satıcı'dan alınır (50.000 gold). Çantanızdayken çift tıklayıp onaylarsanız erkekseniz kadın, kadınsanız erkek olursunuz. Kadın olunca sakalınız silinir.

## Saç ve sakal

**Hair Deed** ve **Beard Deed** safe alandaki Diğer Eşyalar Stone'dan ücretsiz alınır. Çift tıklayınca açılan menüden stil seçersiniz; her seçim bir belge harcar.

| Belge                     | Stiller                                                                             |
| ------------------------- | ----------------------------------------------------------------------------------- |
| Hair Deed                 | Short, Long, Pony Tail, Mohawk, Page Boy, Buns, Afro, Receding, 2 Pig Tails, Krisna |
| Beard Deed (sadece erkek) | Med Short, Med Long, Short, Long, Mustache, Vandyke, Goatee                         |

## Boyalar

Safe alandaki **Boya Tüpleri** ile eşyalarınızı boyayabilirsiniz. Her tüpün rengi farklıdır. Tüpe çift tıklayıp boyanacak eşyayı seçin; eşya üzerinizde ya da çantanızda olmalıdır.

Boyanabilen eşyalar: kıyafetler, deri zırhlar, Tessen, çanta (bag), Holy Robe ve spellbook.

## Aile

Aile kurmak için Genel Satıcı'dan **Aile Kurulum Belgesi** alın (25.000 gold), çantanızdayken çift tıklayıp aile (soy) isminizi yazın.

* Aile ismi 2 - 14 harf olmalı; rakam, boşluk ve sembol kullanılamaz.
* "GM", "Yetkili", "Owner", "Staff", "Admin" gibi kelimeler aile isminde geçemez.
* Aynı isimde ikinci bir aile kurulamaz. Küfürlü ya da kurallara aykırı aile isimleri yetkililer tarafından yıkılır.
* Aileyi kuran kişi **aile reisi** olur; aile ismi karakter isimlerinin sonuna eklenir.

`.aile` menüsünden:

| İşlem                                                                       | Kim yapabilir |
| --------------------------------------------------------------------------- | ------------- |
| Aileye üye al (oyuncuyu hedefleyin, o kabul etmeli)                         | Aile reisi    |
| Üyeyi aileden at                                                            | Aile reisi    |
| Aileyi yık (herkese duyurulur)                                              | Aile reisi    |
| Aileden ayrıl                                                               | Üyeler        |
| Üye listesi (online/offline durumu, bulunduğu yer, kill, fame, ölüm sayısı) | Herkes        |

* `.ac <mesaj>` ile sadece aile üyelerinin göreceği mesaj yazılır.
* İsmini gizlemiş (incognito) bir oyuncu aileye katılamaz ve aileden ayrılamaz.
* Aile üyeleri isim değiştirme belgesi kullanamaz.

## Güç Yüzüğü

Güç Yüzüğü sunucuda **tek** olan bir yüzüktür ve takana ek STR verir.

* **Güç Yüzüğü Dragonu** Moonglow bölgesinde çıkar (çıktığında duyurulur). Dragona **en çok hasarı veren** oyuncu yüzüğü alır.
* Yüzüğün bir **enerjisi** vardır (başlangıçta 600). Safe alanda ve evlerde durduğunuz her saniye 1 azalır; diğer yerlerde saniyede 3 artar (en fazla 3.600). Yüzüğe tıklayınca enerjisi görünür.
* Enerji biterse yüzük yerine döner ve dragon yeniden çıkar.
* Taşıyıcıyı bir **oyuncu** öldürürse yüzük o oyuncuya geçer. Taşıyıcı bir binek ya da NPC tarafından öldürülürse yüzük yerine döner.
* Taşıyıcı oyundan çıkıp **5 dakika** içinde geri gelmezse yüzük yerine döner.
* `.yuzukcikar` (sadece safe alanda) yüzüğü bırakır; 60 saniye içinde yüzük yerine döner.
* Yüzüğü taşıyanın adı, bölgesi ve koordinatı yardım menüsünde herkese görünür; bulunduğu bölge zaman zaman sunucuya duyurulur.
* Yüzük takılıyken stat değiştirilemez.

## Kelle sistemi

Safe alandaki **Kelle** (giyotin) ile öldürdüğünüz oyuncuların kellelerini sallandırabilirsiniz. Kelleyi bir cesetten kesip giyotinin yanına (en fazla 2 kare) gelin, giyotine çift tıklayıp kelleyi hedefleyin.

| Kellenin sahibi      | Siz kazanırsınız                                                            | Kellenin sahibi kaybeder                                                |
| -------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| Fame'i 4.000'den az  | +750 fame                                                                   | -                                                                       |
| Fame'i 4.000 ve üstü | +1.000 fame, kellenin sahibinin fame'inin 4 katı gold, +1 Head Hunter puanı | -1.500 fame, 1 Head Hunter puanı, şöhret puanından 2-4 (5'ten fazlaysa) |

* Fame'i 4.000 ve üstü kellelerin sallandırılması bütün sunucuya duyurulur.
* Head Hunter puanı 100'ü geçen oyuncunun adının sonuna **\[H.H]** eklenir; 100'ün altına düşen kaybeder.
* Kendi kellenizi sallandıramazsınız (kelle yok olur).
* Giyotine tek tıklayınca son kurban, kurban eden ve kendi Head Hunter puanınız görünür.

{% hint style="info" %}
Safe alanda ceset kesilemez; kelleyi safe alan dışında alın.
{% endhint %}

## Hesap güvenliği

### Şifre

`.sifre` menüsünden şifrenizi değiştirin: 4 - 15 karakter, sadece İngilizce harf ve rakam, boşluk olmadan. Başka sunucularda kullandığınız şifreyi kullanmayın.

### Pin

Pin, bankayı ve yardım menüsünü korur. Hesaptaki bütün karakterler için geçerlidir ve her oyuna girişte bir kez sorulur.

* Pin 2 - 9 haneli bir sayıdır, 0 ile başlayamaz.
* Pini belirlerken bir **gizli cevap** yazarsınız (2 - 19 harf; Türkçe karakter, boşluk ve rakam olmadan). Pininizi unutursanız bu cevapla yeni pin belirlersiniz.
* `.pin` menüsünden pin girişi, pin değiştirme, pin sistemini kapatma (pin ve gizli cevap gerekir) ve unutulan pini yenileme yapılır.
* Pin sistemini kullanmak istemezseniz kapatabilir, daha sonra `.pin` ile yeniden açabilirsiniz.

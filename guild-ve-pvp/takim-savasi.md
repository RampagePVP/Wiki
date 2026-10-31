# Takım Savaşı

Takım Savaşı, oyuncuların staff beklemeden kendi aralarında kurduğu takımlı savaştır. İki kaptan kuralları belirler, takımlarını safe alandan seçer ve arenada tek takım ayakta kalana kadar savaşırlar.

{% hint style="info" %}
GM'lerin açtığı Köprü Savaşı ayrı bir etkinliktir; onun için **Takım Savaşları** sayfasına bakın.
{% endhint %}

## Savaş kurma

1. Kaptan, safe alandaki **Savaş Komutanı**'na çift tıklar ve **Savaş Kur**'a basar.
2. Kuralları seçer (aşağıdaki tabloya bakın) ve rakip kaptanı hedefler. Rakip en fazla 10 kare uzakta olmalıdır.
3. Rakip kaptana kuralları gösteren bir teklif penceresi açılır ve 30 saniye içinde cevap vermesi gerekir. Kabul ederse savaş bütün sunucuya duyurulur. Teklif eden **Kırmızı**, kabul eden **Mavi** takımın kaptanı olur.
4. Kaptanlar sırayla (ilk sırayı sistem rastgele seçer) yanlarındaki oyunculardan birini hedefler. Seçilen oyuncuya kuralları gösteren bir davet açılır. 20 saniye içinde kabul ederse takıma girer ve sıra diğer kaptana geçer. Reddederse ya da cevap vermezse aynı kaptan başka birini seçer.
5. Takımların dolması için toplam **5 dakika** vardır. Süre dolarsa savaş iptal olur. Kaptanlar seçim menüsünden savaşı iptal edebilir.

Aynı anda yalnızca bir takım savaşı yapılabilir. Teklif gönderen kaptan yeni bir teklif için 1 dakika beklemelidir.

### Kaptanın belirlediği kurallar

| Kural                                                  | Seçenekler                                               |
| ------------------------------------------------------ | -------------------------------------------------------- |
| Takım büyüklüğü                                        | 2vs2 - 10vs10                                            |
| Pot (her türden, kişi başı)                            | 0 - 50                                                   |
| Bandaj (kişi başı)                                     | 0 - 100                                                  |
| Binek (kişi başı, bindiğiniz binek hariç)              | 0 - 3                                                    |
| Grav büyüleri (Fire, Poison, Paralyze ve Energy Field) | Serbest ya da yasak                                      |
| İddia                                                  | İsteğe bağlı. Gold iddiası kişi başı 50.000 - 10.000.000 |

### Kimler katılabilir?

Kaptanlar dahil her oyuncu için:

* Oyunda, hayatta ve safe alanda olmalıdır.
* Düelloda ya da başka bir takımda olmamalıdır. GM modundaki karakterler katılamaz.
* Aynı bilgisayardan bağlı iki karakter aynı savaşa giremez.
* İddia konduysa kumbarasında iddia miktarı kadar gold bulunmalıdır.

Takımlar dolunca herkes yeniden kontrol edilir. Hazır olmayan oyuncu takımdan çıkarılır, kaptanı yerine yeni birini seçer. Kaptan hazır değilse savaş iptal olur.

## Savaş başlarken

* Herkesin buff'ları silinir. Can, mana ve stamina doldurulur.
* Çantadaki pot, bandaj, Trapped Pouch ve oil silinir. Yerine şunlar verilir:
  * Greater Heal, Greater Cure, Total Refresh, Hallucination ve Bleed potionlarından ayardaki sayı kadar (warrior'lara ayrıca Deadly Poison ve Greater Agility)
  * Ayardaki sayıda bandaj
  * 5 Trapped Pouch ve 50 oil
* Yanınızdaki (12 kare içindeki) binekleriniz, ayardaki sayı kadar sizinle arenaya gelir. Bindiğiniz binek bu sayıya dahil değildir.
* Her oyuncunun binek hakkı, ayardaki sayının bir fazlasıdır (bindiğiniz binek için). Hakkınız kaldıysa çantanızdaki figürden binek açabilirsiniz. Savaşta ölen binekler de haktan düşer.
* Takımlar arenadaki kendi başlangıç noktalarına ışınlanır. **10 saniyelik geri sayım** boyunca yürüyemezsiniz ve kimse kimseye vuramaz; sadece destek büyüsü atılabilir.

## Savaş

* Savaş, ayakta tek takım kalana kadar sürer. Ayakta sayılmak için oyunda, hayatta ve arenada olmanız gerekir.
* Res serbesttir. Diriltilen takım arkadaşı yeniden ayakta sayılır.
* Savaş en fazla **20 dakika** sürer. Süre dolarsa ayakta daha çok oyuncusu olan takım kazanır; eşitse savaş berabere biter.
* Sol üstteki küçük pencerede iki takımın ayaktaki oyuncu sayısı ve kalan süre görünür. Pencereyi kapattıysanız `.tsavas` ile yeniden açabilirsiniz.
* Her ölüm savaştakilere duyurulur. Savaştaki öldürmeler açık dünyadaki gibi PvP puanı verir.

### Kurallar

| Konu                 | Kural                                                                                                                                                                                                       |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Takım arkadaşı       | Takım arkadaşınıza ve onun bineklerine vuramaz, zararlı büyü (alan büyüleri dahil) atamazsınız. Takım arkadaşınıza sadece destek büyüleri (Heal, Cure, Bless, Protection, Reflect, Resurrection vb.) gider. |
| Binekler             | Binekler birbirine saldırmaz ve birbirine hasar veremez; rakip oyunculara saldırabilir.                                                                                                                     |
| Loot                 | Loot ve ceset kesme serbesttir.                                                                                                                                                                             |
| Her zaman yasak      | Recall, Mark, Gate, Invisibility, Blade Spirits, Energy Vortex, Summon Creature ve elementaller; hiding ve stealth                                                                                          |
| Arenada kullanılamaz | Golem, Animal Deed ve runebook. Binek res sadece savaş bittikten sonraki loot süresinde kullanılabilir.                                                                                                     |
| Arena                | Recall ve gate'e kapalıdır. Savaşta olmayan oyuncu arenaya girerse safe alana atılır.                                                                                                                       |

* Savaş sırasında arenadan çıkan oyuncu savaş dışı kalır.
* Oyundan çıkan oyuncu ayakta sayılmaz. Savaş bittikten sonra oyuna girerse safe alana alınır.
* Savaştayken `.reslen` ve Help menüsündeki stuck seçenekleri çalışmaz.

## Savaş bitince

* **Kaybeden takımın arenada hayatta kalan binekleri sahipsiz kalır.** Bineğine binmiş kaybeden oyuncu önce bineğinden indirilir.
* Kaybedenler hemen safe alana ışınlanır. Ölü olanlara res menüsü açılır.
* Kazananlar **90 saniyelik loot süresi** boyunca arenada kalır. Bu sürede cesetleri yağmalayabilir, sahipsiz kalan binekleri evcilleştirebilir ve ölen kendi bineklerini binek res ile diriltebilirler. Süre bitince kazananlar ve sahipli binekleri safe alana ışınlanır. Sahipsiz binekler arenada kalır.
* **Ölen binekler:** Kaybeden takımın ölen bineklerinin cesetleri savaş biter bitmez safe alana taşınır, böylece kazananlar onları diriltip alamaz. Arenada kalan diğer binek cesetleri loot süresinden sonra safe alana taşınır. Sahipleri safe alanda binek res ile diriltebilir.
* **Beraberlik:** Kimse binek kaybetmez. İki takım da loot süresinden sonra safe alana çıkar.

{% hint style="danger" %}
Takım Savaşı'na getirdiğiniz binekleri kaybedebilirsiniz. Savaşı kaybederseniz arenada hayatta kalan binekleriniz sahipsiz kalır ve rakip takım tarafından evcilleştirilebilir.
{% endhint %}

### İddia

* Kaptan iddia koyduysa iki takımdaki herkes (kaptanlar dahil) aynı miktarı öder. Gold bankadaki kumbaradan alınır.
* Para, takımlar arenaya ışınlanmadan hemen önce alınır. Parası yetmeyen oyuncu takımdan çıkarılır ve kaptanı yerine başkasını seçer. Kaptanın parası yetmezse savaş iptal olur.
* Kazanan takım, havuzun tamamını (ödeyen sayısı × iddia miktarı) savaşta kalan üyeleri arasında eşit paylaşır. Ölmüş ya da oyundan çıkmış üyeler de pay alır; arenadan çıkıp savaş dışı kalan üye pay almaz.
* Gold kumbaranıza yatar. Kumbaranız yoksa ya da doluysa bankanıza çek olarak bırakılır.
* Savaş berabere biter ya da iptal olursa herkesin parası geri verilir.
* Sunucu iddiadan pay almaz; para sadece oyuncular arasında el değiştirir.

## İstatistik

Galibiyet, mağlubiyet ve beraberlik sayılarınız Savaş Komutanı'nın menüsünde görünür. Takım Savaşı'nın iddia dışında bir ödülü yoktur.

## Komut

| Komut     | Ne yapar                                                                    |
| --------- | --------------------------------------------------------------------------- |
| `.tsavas` | Takım seçimi sürerken seçim menüsünü, savaş sırasında skor penceresini açar |

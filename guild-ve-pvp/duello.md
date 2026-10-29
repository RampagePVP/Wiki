# Düello

Düello, iki oyuncunun gold bahsiyle birebir dövüştüğü sistemdir. Düellolar safe alanın yanındaki düello alanında yapılır ve kazanan bahsin tamamını alır.

## Düello nasıl başlatılır

1. Safe alandaki düello alanının yanında duran **Duello Hakemi (Lord British)**'e en fazla 4 kare yaklaşıp çift tıklayın. **Rampage - Duello Menü** açılır.
2. Ayarları yapın:

| Ayar           | En az  | En fazla   | Varsayılan                      |
| -------------- | ------ | ---------- | ------------------------------- |
| Bahis (gold)   | 50.000 | 10.000.000 | 50.000                          |
| Potion sayısı  | 3      | 25         | 10                              |
| Bandaj sayısı  | 15     | 75         | 25                              |
| Poison (zehir) | —      | —          | Yasak (butonla Serbest yapılır) |

3. **RAKİP SEÇ!** butonuna basıp rakibinizi hedefleyin. Rakip en fazla 3 kare uzakta olmalıdır.
4. Rakibe bir teklif penceresi açılır. Rakip **30 saniye** içinde kabul etmezse teklif kendiliğinden kapanır.

## Şartlar

Teklif gönderirken ve kabul ederken şunlar kontrol edilir:

* İki oyuncunun da **canı tam** olmalı.
* İki oyuncunun da bankasında **kumbara** olmalı ve kumbarada bahis kadar gold bulunmalı.
* İkiniz de **safe alanda** olmalı ve birbirinize yakın durmalısınız.
* İkiniz de **binekten inmiş** olmalısınız.
* Rakip başka bir düelloda ya da başka bir teklifle meşgul olmamalı.
* Aynı anda tek bir düello yapılabilir; düello alanı doluysa düello iptal edilir.

## Düello sırasında

* Teklif kabul edilince **bahis iki oyuncunun kumbarasından da düşülür** ve ikiniz düello alanına ışınlanırsınız.
* **35 saniyelik geri sayım** başlar. Bu sürede hareket edemezsiniz ve etrafınızda bir kafes olur. Hakem geri sayımı yapar, "Başla!" deyince dövüş başlar.
* Düello başlarken üzerinizdeki şu eşyalar silinir ve yerine ayarlanan sayı kadar verilir: **Greater Heal, Greater Cure, Bleed, Total Refresh ve Greater Agility potionları** (her birinden "potion sayısı" kadar) ve **bandaj** ("bandaj sayısı" kadar).
* Düellodaki oyuncuya tıklanınca kalan heal/cure potion ve bandaj sayısı görünür.

{% hint style="warning" %}
Poison **yasak** ayarlıysa düello sırasında zehirli bir silahı kuşandığınızda silahtaki zehir **kalıcı olarak silinir**. Zehirli silahınızı kaybetmek istemiyorsanız düelloda kullanmayın.
{% endhint %}

### Düelloda kullanılamayanlar

**Yasaklı büyüler:** Wall of Stone, Arch Protection, Fire Field, Recall, Blade Spirits, Summon Creature, Explosion, Invisibility, Mark, Paralyze Field, Reveal, Chain Lightning, Energy Field, Gate Travel, Mana Vampire, Mass Dispel, Meteor Swarm, Polymorph, Earthquake, Energy Vortex, Resurrection ve bütün elemental / daemon çağırma büyüleri.

**Yasaklı eşyalar:** Runebook, Animal Deed, golem ve binek figürleri.

## Düellonun sonu

* Ölen oyuncu **gerçekten ölmez**: canı dolar ve iki oyuncu da düello alanının dışına ışınlanır. Eşya kaybı (loot) yoktur.
* Kazanana **bahsin iki katı** (iki oyuncunun bahsi) gold check olarak çantasına verilir. Sonuç bütün sunucuya duyurulur.
* Düellodan sonra iki oyuncuya da standart potion ve bandaj seti yeniden verilir.
* Düello sırasında oyundan çıkan oyuncu **30 saniye** içinde geri dönmezse düelloyu kaybeder.

### Düello puanı ve fame

Kaybeden oyuncunun fame'i **6000 veya üstündeyse**:

|                          | Kazanan | Kaybeden                       |
| ------------------------ | ------- | ------------------------------ |
| Düello puanı             | +3      | -1 (0'ın altına inmez)         |
| Kaybedilen düello sayısı | —       | +1                             |
| Fame                     | —       | Fame'inin **%90'ını kaybeder** |

Kaybedenin fame'i 6000'in altındaysa düello puanı ve fame değişmez; sadece bahis el değiştirir.

Düello puanları `.top10` menüsündeki **Duello Sıralaması**'nda görünür (bkz. **Sıralamalar** sayfası).

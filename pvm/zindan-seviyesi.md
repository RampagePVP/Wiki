# Zindan Seviyesi

Dungeonlarda yaratık kestikçe **Zindan Tecrübesi** kazanır, **30 seviyeye** kadar yükselirsiniz. Seviyeniz arttıkça zindan yaratıklarına karşı güçlenir, seviye ödüllerini alır, sonunda zindan bineği **Baihu**'yu kazanabilirsiniz. Yaratıkların kendi ganimetleri değişmedi; zindan seviyesi bunun üstüne gelir.

Sistem şu dungeonlarda geçerlidir: **Despise, Deceit, Destard, Shame, Wrong, Hythloth, Covetous, Ice Dungeon, Fire Dungeon**.

## Komutlar

| Komut        | Ne yapar                                                                           |
| ------------ | ---------------------------------------------------------------------------------- |
| `.zindan`    | Zindan Rehberi: seviyeniz, tecrübeniz, bonuslarınız ve her dungeonun uyanış durumu |
| `.seviye`    | Seviye ödülleri ve Baihu (ödüller ve Baihu sadece safe alanda alınır)              |
| `.seviyebar` | Seviye çubuğunu kapatır ya da yeniden açar                                         |

## Yaratık seviyeleri

Her zindan yaratığının bir seviyesi vardır. Yaratığa tıklayınca adının üstünde seviyesi görünür:

* **Yeşil:** sizden 8 ya da daha fazla seviye düşük, yarım puan verir.
* **Sarı:** sizin seviyenize yakın.
* **Kırmızı:** sizden 5 ya da daha fazla seviye yüksek.

| Yaratık                                                                 | Seviye |
| ----------------------------------------------------------------------- | ------ |
| Dark Blood Monk                                                         | 27–30  |
| Daemon of Might                                                         | 30     |
| Hazine Ejderhası                                                        | 22–26  |
| Planar, Hashade, Reglor                                                 | 18–22  |
| Gyrados, Brahman, Penon                                                 | 14–18  |
| Rotting Corpse, Mummy, Kraken                                           | 8–12   |
| Orc Bomber, Harpy, Giant Spider, Lizardman, Troll, Gazer, Giant Serpent | 3–6    |

Seviye hiçbir yaratığı kilitlemez: her seviyede her yaratığı kesebilirsiniz.

## Tecrübe ve seviye

* Bir yaratık öldüğünde **yaratık seviyesi × 3** puan verir (boss **× 15**).
* Yaratığa vuran **ilk 5 oyuncunun her biri** puanın tamamını alır (son vuruşunuzun üstünden 2 dakika geçmemiş olmalı). Silah da büyü de sayılır.
* Yaratık sizden 8 ya da daha fazla seviye düşükse **yarım puan** alırsınız.
* Kazandığınız her puan aynı zamanda **Zindan Puanı** olarak biriktirilir. Seviye 30'da tecrübe durur, Zindan Puanı birikmeye devam eder. Baihu bu puanla alınır; harcamak seviyenizi düşürmez.

Seviye atlamak giderek zorlaşır; ara seviyeler uzun sürer:

| Seviye geçişi | Gereken puan    |
| ------------- | --------------- |
| 1 → 5         | 1.800 – 7.200   |
| 5 → 10        | 10.800 – 19.800 |
| 10 → 16       | 21.600 – 30.600 |
| 16 → 21       | 32.400          |
| 21 → 24       | 34.200          |
| 24 → 27       | 36.000          |
| 27 → 29       | 39.600          |
| 29 → 30       | 43.200          |

Seviye 30 için toplam **748.800** puan gerekir.

## Seviye bonusları

Seviyeniz arttıkça, **sadece zindan yaratıklarına ve bosslarına karşı**:

* Verdiğiniz hasar artar (silah ve büyü).
* Aldığınız hasar azalır.
* Boss ödül şansınız artar.

Bonusların oyunculara, düelloya ve PvP'ye hiçbir etkisi yoktur.

## Seviye çubuğu

Bir zindan yaratığına vurmaya başlayınca ekranın sol altında **seviye çubuğu** açılır: rozetinizde seviyeniz, yanında tecrübe çubuğu, yüzde ve son kazandığınız puan görünür. Her kesimde yenilenir; seviye atlayınca "Seviye Atladın!" yazar. Rozet seviye 15'te kırmızıya, 30'da yeşile döner. Kapatıp açmak için `.seviyebar`.

## Seviye ödülleri

`.seviye` menüsünden, safe alanda alınır. Her ödül **hesap başına bir kez** alınır. Rampage Coin hesabınıza eklenir; eşyalar bankanızdaki "Zindan Seviye N Ödülü" çantasına konur.

| Seviye | Ödül                                                             |
| ------ | ---------------------------------------------------------------- |
| 5      | 10.000.000 gold, 2 Random Egg, 1 Ender Hazine                    |
| 10     | 50 Rampage Coin, 20.000.000 gold, 2 Ender Hazine                 |
| 15     | 75 Rampage Coin, 3 Random Egg, 3 Ender Hazine                    |
| 20     | 100 Rampage Coin, 50.000.000 gold, 4 Ender Hazine                |
| 25     | 150 Rampage Coin, 5 Random Egg, 5 Ender Hazine                   |
| 30     | 300 Rampage Coin, 100.000.000 gold, 5 Random Egg, 6 Ender Hazine |

Toplam: **675 Rampage Coin**, 180.000.000 gold, 15 Random Egg, 21 Ender Hazine.

## Uyanış ve bosslar

Bir dungeonda yaratık kestikçe o dungeonun **uyanış** sayacı dolar. Sayaç dolunca o dungeonda **Dungeon Boss** uyanır ve bütün sunucuya duyurulur. Boss **20 dakika** içinde öldürülmezse derinliklere çekilir. Sayaçları `.zindan` menüsünden takip edebilirsiniz.

9 dungeonun hepsinde aynı boss çıkar: **Dungeon Boss**, yeşil gövdeli, kızıl kanatlı dev bir ejderha. Uyandığı yerden uzaklaşmaz, peşinize düşüp zindanı dolaşmaz.

| Dungeon      | Uyanış için kesim |
| ------------ | ----------------- |
| Despise      | 150               |
| Deceit       | 120               |
| Destard      | 100               |
| Shame        | 80                |
| Wrong        | 80                |
| Hythloth     | 80                |
| Covetous     | 50                |
| Ice Dungeon  | 60                |
| Fire Dungeon | 60                |

Bütün bosslar seviye 30'dur ve çok güçlüdür; grupla gidin.

**Boss ödülleri** (bossa vuran ilk 5 oyuncunun her birine ayrı ayrı):

* Zindan Puanı (boss seviyesi × 15)
* **1.000.000 gold** çeki
* Şansınız yaver giderse **2–5 Rampage Coin** (seviyeniz arttıkça şansınız artar)
* Çantanıza **Zindan Boss Ganimeti** çantası:
  * Her zaman: 150 Lanetli Kemik, 10 Binek Resurrection Scroll, 1 Ender Hazine, 1 Random Egg
  * Ana ödüller: Random Egg, Ranger set parçası, Godness set parçası, Ender Hazine, Upgrade Scroll, Str/Dex/Armor binek deed'leri, Armor Helm Upgrade Scroll, Stat Full Deed. Her birinin şansı ayrı atılır, birkaçı birlikte çıkabilir; hiçbiri tutmazsa biri kesin verilir. Yani her bosstan **en az bir** ana ödül alırsınız.
  * Ek şans (ana ödülün üstüne): **Critical Stone**, **+15 silah** ve büyük ikramiye (Ender Hazine ve Random Egg)
* **Despise, Deceit ve Destard** bosslarında "her zaman" kısmı **iki katıdır** ve bu bosslardan nadiren **Baihu** düşer (boss başına bir tane; kazanan, ödül alanlar arasından rastgele seçilir).

## Baihu (zindan bineği)

Zindanların beyaz kaplanı **Baihu**, iki yoldan alınır:

1. **Satın alma:** Seviye 30'da, safe alanda `.seviye` menüsünden. Bedeli:
   * **750.000 Zindan Puanı**
   * **10.000 Lanetli Kemik** (sırt çantanızda olmalı; depodaki sayılmaz)
   * **100.000.000 gold** (kumbaradan) Bedeli her topladığınızda bir Baihu daha alabilirsiniz; sınır yok. Seviye 30'a gelene kadar biriken puan ilk Baihu'ya aşağı yukarı yeter.
2. **Boss:** Despise, Deceit ve Destard bosslarından nadiren düşer.

Baihu'nun yetenekleri için **Özel Binekler** sayfasına bakın.

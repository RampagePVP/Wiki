# Eşya Deposu (.depo)

Eşya deposu; scroll, belge, hazine sandığı, set parçası, silah, golem ve binek figürü gibi eşyalarınızı çantanızı ve bankanızı doldurmadan saklamanızı sağlar. Her karakterin kendi deposu vardır.

## Depoyu açmak

* **Safe Alan**'dayken **`.depo`** yazın. Depo safe alan dışında açılmaz.
* Ölüyken depo kullanılamaz.
* Bankanızı hiç açmadıysanız önce bir bankacıdan bankanızı bir kez açın.
* `.depo` komutu saniyede en fazla bir kez kullanılabilir.

Depo menüsü şu durumlarda kendiliğinden kapanır (en geç 1 saniyede):

* Bir adım attığınızda ya da ışınlandığınızda,
* Safe alandan çıktığınızda,
* Öldüğünüzde,
* Başka bir menü açıldığında.

Tekrar açmak için `.depo` yazmanız yeterlidir.

## Menü

| Bölge | İçerik                                                                                                                                                      |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sol   | Kategoriler; taşıdığınız ağırlık; ayrı saklanan özel eşya sayınız (en fazla 300); depodaki binek sayınız (en fazla 1000)                                    |
| Sağ   | Seçili kategorideki eşyalar: resim, ad, **Depoda** ve **Çanta+Banka** sayıları, **Yatır** / **Çek** butonları. Sayfa başına 8 satır, sağ üstte sayfa okları |
| Alt   | Çekilecek miktar kutusu, **Hedefleyerek Yatır**, **Bu Kategoriyi Yatır**, **Hepsini Yatır**, **Kapat**                                                      |

Kategoride depoda da çantada da olmayan türler gri yazılır.

## Kategoriler

| Kategori             | İçindekiler                                                                                                                                                                                 |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scrolllar            | Upgrade Scroll (+18, +21, +24), Helm Absorb (Dismount, Parablow, Bleed), Mage Scroll (Arch, Corruptor, Felheart), Holy Scroll, Binek Res Scroll, Repair Scroll                              |
| Belgeler             | Devil, Dragon, Gold, Diablo ve Ranger Set Deed; Binek Armor, Stat Full, Str, Dex ve Animal Deed; Deed of Storm                                                                              |
| Kutu ve Çantalar     | Belirsiz Sandık, Değerli Hazine Sandığı, Ender Hazine, Silah Çantası (+18, +21, +24), Extremely Box, Puzzle Parça Çantası, Random Egg                                                       |
| Potionlar            | Event Potion (Parablow, Bleed, Dismount)                                                                                                                                                    |
| Malzemeler           | Magic Log, Magic Ingot, Ghost Ingot, Dragon Blood, Maden Ingotu, Çimento, Honor Point, Hediye Bileti, Silver Coin, Rampage Balığı, Solo Dungeon Key, Party Statue ve bazı etkinlik eşyaları |
| Warrior Setleri      | Godness, Dragon, Diablo ve Blackrock set parçaları ve kalkanları                                                                                                                            |
| Warlock/Mage Setleri | Ranger, Devil, Gold ve Dragonic set parçaları                                                                                                                                               |
| Helm ve Kalkanlar    | Armorer Helm (Orc ve Bone), Ice Shield, Mage Shield                                                                                                                                         |
| Silahlar             | Bütün +24 (Damned) silahlar                                                                                                                                                                 |
| Robeler ve Diğer     | High Mage Robe, Perfect Robe, Notum Robe, Holy Robe                                                                                                                                         |
| Golemler             | Advanced Golem ve Tinker Golem figürleri, küçültülmüş golemler                                                                                                                              |
| Binekler             | Küçültülmüş binek figürleri                                                                                                                                                                 |

Sadece depo menüsünde listelenen eşyalar depoya konabilir.

## Eşyalar nasıl saklanır?

**Sayılan eşyalar:** Scroll, belge, sandık, malzeme, potion ve golem figürleri depoda sadece **adet** olarak tutulur. Yatırınca eşya silinir, çekince yenisi oluşturulur.

**Zırh, silah ve robeler:**

* **Değişmemiş** (yeni çıktığı haliyle aynı) zırh, silah ve robeler de sayılarak saklanır. Depodan **orijinal renginde** çıkar; üzerindeki boya kaybolur.
* **Özel** eşyalar (upgrade/absorb'lu, zehirli, şarjı kullanılmış, adı değiştirilmiş, tamirle en yüksek dayanıklılığı düşmüş) **olduğu gibi** saklanır ve aynen geri gelir. Menüde kendi türünün altında **sarı** satırda, dayanıklılığıyla görünür. Depoda en fazla **300** özel eşya olabilir.
* Depodan çekilen +24 silahlar tam dayanıklılıkla gelir.

**Küçültülmüş golemler ve binek figürleri** statları, armoru, adı ve geliştirmesiyle olduğu gibi saklanır.

## Depoya konamayanlar

| Durum                      | Açıklama                                                                                                                                                        |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Hasarlı zırh/silah/robe    | Dayanıklılığı en yüksek değerinin altındaysa önce tamir ettirin.                                                                                                |
| Süreli eşya                | Extremely silahlar gibi süreli eşyalar konamaz.                                                                                                                 |
| Değiştirilmiş sayılan eşya | Boyanmış, sigortalı/kaybolmaz yapılmış ya da özelliği değişmiş scroll, belge, sandık vb. konamaz.                                                               |
| Yanlış yerdeki eşya        | Sadece **çantanızdaki ve bankanızdaki** (ve içlerindeki kaplardaki) eşyalar yatırılır. Giyili, elinizdeki, takas penceresindeki ve yerdeki eşyalar yatırılamaz. |
| Listede olmayan eşya       | "Bu eşya depoya konamaz" uyarısı çıkar.                                                                                                                         |

## Yatırmak

| Buton                   | Ne yapar                                                                                                                      |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Satırdaki **Yatır**     | Çantanızdaki ve bankanızdaki o türün hepsini yatırır                                                                          |
| **Hedefleyerek Yatır**  | Seçtiğiniz eşyayı yatırır; her eşyadan sonra hedef imleci yeniden açılır. Bitirmek için ESC'ye basın ya da boş yere tıklayın. |
| **Bu Kategoriyi Yatır** | Açık kategorideki bütün eşyalarınızı yatırır                                                                                  |
| **Hepsini Yatır**       | Depoya konabilen bütün eşyalarınızı yatırır (binek figürleri hariç)                                                           |

Toplu yatırmada bir tıklamada en fazla 100 eşya ya da yığın yatırılır; fazlası için tekrar basın.

## Çekmek

1. Alttaki **Çekilecek miktar** kutusuna sayıyı yazın (1–99999; 0 ile başlayamaz).
2. Satırdaki **Çek**'e basın.

Çekme **ya hep ya hiç** çalışır. Şu durumlarda hiç eşya verilmez ve sebebi yazılır:

| Durum                | Sınır                                                                                                                                                  |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Depoda o kadar yoksa | —                                                                                                                                                      |
| Tek seferlik sınır   | Yığılan eşyalar 60.000; sandık, çanta, zırh ve silah 50; golem 3                                                                                       |
| Çanta dolu           | Çantanızın ana bölümünde en fazla 200 eşya olabilir; yığılmayan eşyalar tek tek yer kaplar                                                             |
| Ağırlık              | Çekilen eşyalar taşıyabileceğiniz ağırlığı aşamaz. Menüde "Taşıdığınız ağırlık: X / Y taş" yazar. Sığmazsa en fazla kaç adet çekebileceğiniz söylenir. |

Çekilen eşyalar **çantanıza** gelir. Özel (sarı) eşyalar satırdaki **Çek** ile tek tek çekilir.

## Binekler

Animal Deed ile küçültülmüş binek figürlerinizi bu bölümde saklayabilirsiniz (süreli figürler hariç).

* **Tür listesi:** Her binek türü bir satırdır (depodaki ve çanta+bankadaki adet). **Aç** o türdeki figürleri listeler, **Yatır** çanta ve bankadaki o türün hepsini koyar.
* **Figür listesi:** Her figür STR/DEX, armor ve geliştirme seviyesiyle görünür. **Çek** figürü çantanıza verir. Başlıktaki **Geri** tür listesine döner.
* Depoda en fazla **1000** binek figürü olabilir.
* **Hepsini Yatır** binekleri almaz; binekler için Binekler bölümündeyken **Bu Kategoriyi Yatır** ya da satırdaki **Yatır**'ı kullanın.

{% hint style="warning" %}
Çantanızda 3'ten fazla figür varken binek ya da golem çıkaramazsınız. Figür çektikten sonra fazlasını depoya ya da bankaya koyun.
{% endhint %}

## Bekleme süreleri

| İşlem                           | Bekleme                                   |
| ------------------------------- | ----------------------------------------- |
| İki yatırma işlemi arası        | 0,4 saniye                                |
| İki çekme işlemi arası          | 3 saniye                                  |
| Kategori ya da sayfa değiştirme | 1 saniye ("Bu kadar hızlı yapamazsınız.") |
| `.depo` komutu                  | 1 saniye                                  |

## Listeden çıkarılan eşyalar

Oil Cloth, Pouch Trapped ve Bandage artık depoya konamaz. Bunlardan depoda kalanlar depoyu açtığınızda **bankanıza** geri konur ve size bilgi verilir.

{% hint style="info" %}
Depodaki eşyalar bankanızdaki eşyalar gibi kalıcıdır; karakterle birlikte saklanır. Boyalı zırh ve silahlarınızın rengini korumak istiyorsanız onları depoya koymayın; değişmemiş zırhlar depodan orijinal renginde çıkar.
{% endhint %}

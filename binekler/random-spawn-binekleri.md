# Random Spawn Binekleri

Random spawn, dünya haritasında rastgele bir yerde beliren güçlü bir vahşi binektir. Onu ilk bulup evcilleştiren alır. Her evcilleştirilen random spawn ayrıca **random spawn puanı** kazandırır.

## Ne zaman ve nerede çıkar?

* Sistem **4 saatte bir** kontrol eder. Haritada **2'den az** random spawn varsa **1 yeni binek** çıkar. Aynı anda en fazla 2 random spawn olur.
* Çıktığında bütün sunucuya duyurulur: "RANDOM SPAWN: 1 adet random spawn dünya haritasında aktif olmuştur."
* Binek, dünya haritasında rastgele bir **açık arazide** (çimenlik bir yerde) belirir. Şehirler, korumalı bölgeler, safe alan, evler, zindanlar ve etkinlik alanlarında çıkmaz. Belirdiği yerin çevresinde dolaşır.
* Evcilleştirilmezse yaklaşık **8 saat** sonra ölür ("ehlileştirilemediği için açlıktan hayatını kaybetti" duyurusu).

`.spawntakip` yazarak haritada kaç aktif random spawn olduğunu öğrenebilirsiniz.

## Çıkan binekler

Her seferinde aşağıdaki 6 binekten biri eşit şansla çıkar. Random spawn binekleri, aynı türün normal halinden daha güçlü statlarla gelir.

| Binek        | Geliştirilebilir mi? |
| ------------ | -------------------- |
| Silvercorn   | Evet                 |
| Silver Steed | Evet                 |
| Fire Steed   | Evet                 |
| N-Mandre     | Evet                 |
| Unicorn      | Hayır                |
| Raptor       | Evet                 |

Bineklerin yetenekleri (Silvercorn `.cornres`, Fire Steed `.steedfire`, Silver Steed `.steedlight`, Unicorn `.unires`) **Özel Binekler** sayfasında anlatılıyor.

## Evcilleştirme

* **100 Taming** ve **100 Animal Lore** gerekir. Evcilleştirme kuralları **Taming (Evcilleştirme)** sayfasında.
* Normal taming sopasıyla evcilleştirme şansa bağlıdır, **Master Taming Staff** ile her zaman başarılı olur.
* **Master Taming Staff bonusu:** Staff'ta şarj varsa bineğin STR, DEX ve armoru ayrıca artar (1 şarj harcanır). Bundan sonra belgelerle sınıra kadar geliştirilebilir (Unicorn hariç; **Binek Geliştirme** sayfası).
* Evcilleştiren oyuncu **+1 random spawn puanı** ve taming puanı kazanır (**Taming (Evcilleştirme)** sayfası).

{% hint style="info" %}
Taming setinin (Master Taming Staff, Taming Robe, Glasses, Boots) her parçası Tracking menzilinizi artırır. Bineği tracking ile ararken işinize yarar.
{% endhint %}

## Spawn Bulucu

**Spawn Bulucu**, aktif random spawn binekleri hakkında bilgi veren tek kullanımlık bir kitaptır.

* **Nereden:** Safe alandaki **Animal Vendor**'ın Master Taming Menüsü, **50.000 gold** (bankadaki kumbaradan).
* **Kullanım:** Çantanızdayken ve **safe alandayken** çift tıklayın.
* Menüde en fazla **2 aktif spawn** için şunlar görünür: binek türü, statları, açlık seviyesi ve **bulunduğu bölge**.
* Kitap bir kez kullanılır.
* Haritada aktif spawn yoksa kitap kullanılmaz ve **harcanmaz**.

## Master Taming Menü (random spawn puanı)

Safe alandaki **Animal Vendor**'a çift tıklayınca açılır. Random spawn puanlarınızı burada harcarsınız. Alışveriş sadece safe alanda yapılır.

| Ödül                      | Bedel       |
| ------------------------- | ----------- |
| Değerli Hazine            | 2 puan      |
| Full Stat Belgesi (binek) | 25 puan     |
| Taming Robe               | 25 puan     |
| Taming Boots              | 25 puan     |
| Taming Glasses            | 25 puan     |
| Master Taming Staff       | 50 puan     |
| Taming Staff Şarj (+10)   | 30 puan     |
| Spawn Bulucu              | 50.000 gold |

Menünün üstünde harcanabilir puanınız yazar.

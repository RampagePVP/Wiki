# Kurallar ve Cezalar

Bu sayfa sunucuda uyulması gereken temel kuralları ve bunlara bağlı sistemleri anlatır: küfür filtresi ve küfür bildirme, hapis (jail), yetkili çağrısı (page) ve günlük oyunda karşılaşacağınız diğer kısıtlamalar.

## Küfür filtresi

Sohbette küfür ve argo kelimeler otomatik olarak yakalanır.

* Küfürlü mesajınız kimseye gösterilmez.
* **5 dakika** konuşma cezası alırsınız ve bu bütün sunucuya duyurulur ("Küfür Duyuru: ... konuşma cezası almıştır").
* Cezalıyken konuşamazsınız (hayvanlara verilen "all come", "all kill" gibi komutlar hariç) ve `bank` yazarak bankanızı açamazsınız. Konuşmaya çalışınca kalan ceza süreniz yazar.
* Size tıklayan oyuncular adınızın üstünde **\[Konuşma Cezalısı]** görür.
* Ceza bitince "Konuşma cezanız sona ermiştir" mesajı gelir.

## Küfür bildirme

Size küfreden ya da hakaret eden bir oyuncuyu bildirmek için `.kufur` (ya da `.ihbar`, `.bildir`) yazıp oyuncuyu hedefleyin.

* Hedeflediğiniz oyuncu oyunda olmalı; kendinizi bildiremezsiniz.
* Bildirimden sonraki **80 saniye** boyunca hem sizin hem de bildirdiğiniz oyuncunun yazdıkları kaydedilir ve yetkililere iletilir.
* Aynı oyuncunun konuşmaları zaten kaydediliyorsa yeni bildirim yapılamaz.
* Oto PvP'de ve PvP izleme odasında bildirim yapılamaz.

Yetkililer kayıtları inceler. Küfür ettiği anlaşılan oyuncu **5 saat** konuşma cezası alır ve bu sunucuya duyurulur. Oyuncu o sırada oyunda değilse ceza ilk girişinde başlar.

{% hint style="warning" %}
Asılsız ihbar da cezalandırılır: yetkililer bildiren kişiye de konuşma cezası verebilir. Kayıt iki tarafın da yazdıklarını içerdiği için bildirim yaptıktan sonra karşılık olarak küfür etmeyin.
{% endhint %}

## Hapis (jail)

Kural ihlali yapan oyuncular yetkililer tarafından hapse atılır ve bu bütün sunucuya duyurulur. Hapse giren oyuncu ceza bölgesine ışınlanır ve çantasına bir **Kazma** ile bir **Ceza Deed** konur.

### Hapisten çıkmak

1. Kazma ile demir cevheri kazın ve **Iron Ingot**'a çevirin.
2. Ceza Deed'e çift tıklayıp ingotlarınızı hedefleyin; ingotlar deed'e eklenir.
3. Deed'e tek tıklayınca gereken ve eklenen miktar görünür.
4. Gereken miktara ulaşınca deed'e tekrar çift tıklayın. Cezanız biter ve safe alana ışınlanırsınız; kazma, deed, cevher ve ingotlar silinir.

### Ceza türleri

Hapisteki bir oyuncuya tıklayınca cezasının türü ve kaçıncı kez aldığı görünür, örneğin **\[2. Hakaret]**.

| Ceza                 | İlk seferde gereken ingot |
| -------------------- | ------------------------- |
| Alan ihlali          | 10                        |
| Yazı tekrarı (flood) | 50                        |
| Hakaret              | 100                       |
| Hatalı page          | 150                       |
| Speed (hız hilesi)   | 250                       |
| Küfür                | 400                       |
| En ağır ceza         | 500                       |

Aynı türden ceza her tekrarlandığında gereken ingot artar: ikinci seferde 2 katı, üçüncüde 3 katı vb.

### Hapisteyken

* Saldıramaz, büyü atamaz, yetenek kasamazsınız; size de saldırılamaz, ölmezsiniz.
* Sadece kazma, ceza deed'i, çantanız ve demir cevheri kullanılabilir.
* Yere attığınız eşyalar 15 saniye sonra silinir; kazma ve deed yere atılamaz.
* Oyundan çıkıp girmek cezayı bitirmez, girişte tekrar ceza bölgesine dönersiniz.

## Yetkili çağrısı (page)

Bir sorun yaşadığınızda paperdoll'daki **Help** butonuyla açılan yardım menüsünden **Yetkili Çağrısı**'na basın, sorununuzu kısa ve net yazın.

* Yetkili çağrısı sadece oyunda bir yetkili varken açılır. Yetkili yoksa Discord adresinden iletişime geçin.
* İki çağrı arasında **1 dakika** beklemeniz gerekir.
* Çağrınız henüz cevaplanmadıysa yeni yazdığınız mesaj eskisinin yerine geçer (çağrınız güncellenir).
* Yetkili size ekranda açılan bir pencereyle cevap verebilir.
* Yardım menüsünde o an bekleyen çağrı sayısı görünür.

{% hint style="warning" %}
Gereksiz ya da hatalı çağrılar silinir ve size uyarı mesajı gelir. Bunu tekrarlayan oyunculara **1 saat** çağrı yasağı verilebilir; hatalı page ayrıca hapis sebebidir.
{% endhint %}

## Diğer kurallar ve kısıtlamalar

| Durum                                    | Kural                                                                                         |
| ---------------------------------------- | --------------------------------------------------------------------------------------------- |
| Büyü atarken                             | Yazı yazılamaz                                                                                |
| PvP izleme odaları, bekleme salonu       | Seyirciler konuşamaz                                                                          |
| Ölüyken                                  | Sadece "resurrect", "resle" ve "all come" yazılabilir                                         |
| Hayvan isimleri                          | Hayvanların (binek, pet) isimleri değiştirilemez                                              |
| Karakter ve aile isimleri                | Argo, küfür ve yetkili gibi görünen isimler yasaktır                                          |
| Hazine sandıkları, Order/Chaos kalkanlar | Yere atılamaz; Order/Chaos kalkanlar başkasına verilemez                                      |
| Safe alan                                | Saldırı yoktur; yere atılan eşya 20 saniyede silinir; başkasının cesedi açılamaz ve kesilemez |
| Bazı bölgeler                            | Yere atılan eşya 10 saniye sonra silinir (oyun sizi uyarır)                                   |
| Evlerin dışı                             | Bazı eşyalar ev dışında yere bırakılınca hemen silinir (oyun uyarır)                          |

{% hint style="info" %}
Kurallarla ilgili sorularınız ya da itirazlarınız için yetkili çağrısını ya da Discord sunucusunu kullanın.
{% endhint %}

# PvP Ligi ve Kral

PvP Ligi haftalık bir yarıştır: hafta boyunca 1vs1 PvP turnuvalarında puan toplanır, haftanın birincisi bir hafta boyunca **Kral (Pvp Commander)** olur.

## Lig puanı nasıl kazanılır

Lig puanı sadece her gün saat **23:00**'te yapılan **1vs1 Otomatik PvP Turnuvası**'ndan gelir:

| Durum                                                   | Lig puanı         |
| ------------------------------------------------------- | ----------------- |
| Turnuvaya katılmak (turnuva başladığında kayıtlı olmak) | +1                |
| Turnuvada bir turu kazanmak                             | +1 (her tur için) |
| Turnuvanın birincisi olmak                              | +3                |

Turnuvanın kendisi (kayıt, kurallar, turnuva ödülleri) **PvP Turnuvası** sayfasında anlatılıyor.

## Lig sıralaması

Lig sıralaması `.top10` menüsündeki **Pvp Lig Sıralaması** sekmesinde görünür. İlk 10 oyuncu; guildi, bu hafta kaç turnuvaya katıldığı ve toplam lig puanıyla listelenir. Menünün altında kendi puanınız ve sıranız yazar.

## Haftalık sıfırlama

* Lig her **Pazar saat 23:59**'da sıfırlanır.
* O anda sıralamanın **birincisi** haftanın kralı olur ve ödülleri bankasına gönderilir; bütün sunucuya duyurulur.
* Ardından herkesin lig puanı ve katılım sayısı sıfırlanır (oyunda olmayanlar dahil).
* Sunucu Pazar 23:59'da kapalıysa sıfırlama hafta içinde ilk fırsatta yapılır.
* O hafta sıralamaya kimse girmediyse kral seçilmez.

## Kral ödülleri

Haftanın birincisi şunları alır:

| Ödül                                                                      | Nereye gelir |
| ------------------------------------------------------------------------- | ------------ |
| "Pvp lig Birinciliği" çantası: **1.000.000 gold check** ve **Random Egg** | Banka        |
| **Pvp Commander kanadı**                                                  | Banka        |
| Kral unvanı ve kral komutları (bir hafta)                                 | Karakter     |

### Pvp Commander kanadı

* Giyilince bütün statlarınıza bonus verir.
* Sadece kral giyebilir. Güç yüzüğü takılıyken ve dungeon etkinliği alanında giyilemez.
* Yere atılırsa bankanıza gider, başka oyuncuya verilemez.
* Krallık bitince kanat silinir.

### Kral unvanı

* Krala tıklanınca isminin üstünde **"(Pvp Commander)"** yazar ve ismi kırmızı görünür. Guildi varsa guild yazısı da görünür.
* Safe alandaki **Pvp Commander heykeline** tıklayınca kralın adı görünür.

## Kral komutları

| Komut                 | Ne yapar                                                                                    | Bekleme   |
| --------------------- | ------------------------------------------------------------------------------------------- | --------- |
| `.kralduyuru <mesaj>` | Bütün sunucuya "KRAL DUYURU" başlığıyla mesajınızı yayınlar                                 | 30 dakika |
| `.kralres`            | Ölüyken kendinizi diriltir: 50 can, tam mana ve stamina ile kalkarsınız. Evde kullanılamaz. | 30 dakika |

Bekleme sürerken komutu yazarsanız kalan süre gösterilir.

## Krallığın bitmesi

Bir sonraki haftalık sıfırlamada yeni bir kral seçilince eski kralın unvanı, komutları ve kanadı kalkar. Eski kral o sırada oyunda değilse bunlar oyuna girdiğinde kalkar ve "Krallığınız sona ermiştir." mesajı çıkar. Aynı oyuncu üst üste birinci olursa krallığı devam eder.

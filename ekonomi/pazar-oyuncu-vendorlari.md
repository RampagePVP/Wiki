# Pazar (Oyuncu Vendorları)

Pazar alanında bir vendor (tezgâhtar) kiralayıp eşyalarınızı başka oyunculara gold karşılığında satabilirsiniz. Alıcılar ödemeyi kumbaralarından yapar, satış parası vendorunuzda birikir.

## Vendor kiralamak

Safe Alan'daki pazar alanında **Vendor** taşları bulunur. Taşa tıklayınca kiralanmış olup olmadığı yazar.

1. Boş bir vendor taşının yanına gidin (en fazla 1 kare uzakta durun; vendor durduğunuz yerde oluşur).
2. Taşa çift tıklayın ve **"Burayı 1 haftalığına bana kirala!"** butonuna basın.
3. Vendorunuz yanınızda belirir.

| Kural           | Değer             |
| --------------- | ----------------- |
| Süre            | 7 gün             |
| Karakter başına | En fazla 1 vendor |

## Eşya satışa koymak

1. Vendorunuza çift tıklayın; vendorun çantası açılır. Satmak istediğiniz eşyaları bu çantaya koyun.
2. **`.fiyat <miktar>`** yazın (örnek: `.fiyat 1000000`) ve fiyat vermek istediğiniz eşyayı seçin.
   * Fiyat en az **100**, en fazla **999.999.999** gold olabilir.
   * Fiyatı olmayan eşya satılmaz.
   * O sırada bir alıcının onay penceresi açık olan eşyanın fiyatı değiştirilemez.

## Eşya satın almak

1. Vendora çift tıklayın, çantasındaki eşyaları görün.
2. **`.satinal`** yazın (ya da yanında **satin al** deyin) ve almak istediğiniz eşyayı seçin.
3. Açılan pencerede **Ürünü Al !**'a **10 saniye içinde** basın.
4. Fiyat kumbaranızdan düşülür, eşya çantanıza gelir.

* Kumbaranızda fiyattan **fazla** gold olmalıdır.
* Onay penceresi açıkken o eşyayı başka bir oyuncu alamaz ve vendor sahibi fiyatını değiştiremez.
* Kendi vendorunuzdan eşya alamazsınız.

## Global Vendor (eşya arama)

Safe Alan'daki **Global Vendor** NPC'sine çift tıklayın (en fazla 2 kare uzaktan) ve aradığınız eşyanın adını yazın (en az 3 harf, sadece harf ve rakam).

* Bütün vendorlarda o isimde satılan eşyalar **en ucuzdan başlayarak** listelenir (en fazla 10 sonuç).
* Bir sonuca tıklayınca eşyanın ayrıntıları (satıcı, fiyat, vendorun konumu ve eşyanın özellikleri) görünür.
* **Satıcıya Git**: vendorun yerini gösteren bir ok açar. Oku iptal etmek için oka sağ tıklayın.
* **Ürünü Satın Al**: vendora gitmeden eşyayı oradan satın alırsınız; fiyat kumbaranızdan düşer, eşya çantanıza gelir.

## Vendor yönetimi

Kiraladığınız vendorun **taşına** çift tıklayınca yönetim menüsü açılır:

| Seçenek                | Açıklama                                                                                                                      |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Bir \[gün] daha kirala | Süreyi 1 gün uzatır. Vendora en fazla 2 kare yakın olmalısınız.                                                               |
| Vendoru terket         | Vendor birkaç saniye içinde kaldırılır; çantasındaki eşyalar bankanıza gönderilir. Vendora en fazla 2 kare yakın olmalısınız. |
| Banka                  | Bankanızı açar (vendora en fazla 4 kare yakın).                                                                               |
| Hasılat                | Vendorda biriken satış parasını görür ve çekersiniz.                                                                          |
| Yardım                 | Komutların kısa açıklaması.                                                                                                   |

Taşa tıklayınca vendorun kalan süresi de yazar.

### Hasılat

* Her satışta fiyatın **tamamı** vendorunuzun hasılatına eklenir; pazar kesinti almaz.
* Hasılat menüsünde çekmek istediğiniz tutarı yazıp **"Vendordaki hasılatı çek!"**'e basın. Para **banka çeki** olarak bankanıza konur (250.000.000'dan büyük tutarlar birden fazla çeke bölünür). Bir seferde en fazla 999.999.999 gold çekilebilir; tutar 0 ile başlayamaz.
* Bir vendorda en fazla 2.000.000.000 gold hasılat birikebilir; dolarsa vendordan alışveriş yapılamaz.

## Süre bitince

Vendorun süresi dolduğunda (ya da vendoru terk ettiğinizde):

* Vendorun çantasındaki bütün eşyalar **bankanıza** gönderilir.
* Çekilmemiş hasılat **banka çeki** olarak bankanıza konur.
* Vendor taşı yeniden kiralanabilir hale gelir.

{% hint style="info" %}
Vendor süresini taştan takip edin. Süre bittiğinde eşyalarınız kaybolmaz ama satıştan kalkar ve bankanıza gider.
{% endhint %}

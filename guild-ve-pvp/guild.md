# Guild

Guild, oyuncuların birlikte savaştığı, ortak kudret kazandığı ve özel eşyalara eriştiği topluluktur. Bu sayfada guild kurmaktan guild marketine kadar her şeyi bulabilirsiniz.

## Guild kurma

1. Safe alandaki satıcı NPC'ye çift tıklayıp açılan menüden **Guild Belgesi** satın alın: **250.000 gold** (bankanızdaki kumbaradan düşülür).
2. Belgeye çift tıklayınca kurulumun yetkili tarafından yapıldığı yazar. Oyun içinde bir yetkili çağırın; guild taşınız yetkili tarafından yerleştirilir.

{% hint style="info" %}
Faction üyeleri guild kuramaz ve guilde katılamaz.
{% endhint %}

## Guild taşı ve guild menüsü

Guild menüsünü açmak için guild taşına en fazla 2 kare yaklaşıp çift tıklayın. Guild taşına tek tıklayınca guildin puanları, master'ı, adı ve kısa adı görünür.

Ana menüde şunlar bulunur:

| Bölüm                       | Kim kullanabilir                | Ne yapar                                                                             |
| --------------------------- | ------------------------------- | ------------------------------------------------------------------------------------ |
| Haberler                    | Herkes görür, guildmaster yazar | Guild haberi ve guild taşının yıkılmasına kalan süre                                 |
| Üye listesi (sağ üst buton) | Üyeler                          | Üyelerin adı, rütbe puanı ve son giriş tarihi. Oyunda olanlar farklı renkte görünür. |
| Üye Davet Et                | Guildmaster                     | Hedeflediğiniz oyuncuya guild daveti gönderir                                        |
| Guild Eşyaları              | Üyeler                          | Guild kalkanı, pelerini ve bayrağı                                                   |
| Guild Market                | Üyeler                          | Guild kudretine göre açılan eşyalar                                                  |
| Master Menü                 | Guildmaster                     | İsim, kısa isim, destek yönü, devretme, yıkma, haber, nick rengi                     |
| Guildden Ayrıl              | Üyeler                          | Guildden çıkar                                                                       |

Menünün üst kısmında guild başkanı, destek yönü, **kudret seviyesi** (ilerleme çubuğuyla), üye sayısı ve guildin savaş puanı yazar.

{% hint style="warning" %}
**Guild taşının süresi 30 gündür.** Süre dolarsa taş silinir ve guild dağılır. Guildmaster, Haberler sayfasındaki "Guildstone yıkılmasına kalan süre" yazısının yanındaki butona basarak süreyi tekrar 30 güne çıkarabilir. Bunu düzenli olarak yapmayı unutmayın.
{% endhint %}

## Üyelik

* Bir guildde en fazla **75 üye** olabilir.
* **Davet:** Guildmaster "Üye Davet Et" ile bir oyuncuyu hedefler. Oyuncu canlı olmalı ve başka bir guildde olmamalıdır. Oyuncuya bir davet penceresi açılır; kabul ederse guilde girer.
* **Ayrılma:** Menüden "Guildden Ayrıl" ya da şu komutlardan biri: `.guilddencik`, `.guildcik`, `.guildayril`, `.guilddenayril`. Guildmaster guildden ayrılamaz; önce guildi devretmelidir.
* **Atma:** Guildmaster üye listesinde oyuncunun yanındaki butonla üyeyi guildden atar.
* Guildden ayrılan ya da atılan oyuncunun üzerindeki guild pelerini, guild kalkanı ve bayrağı çantaya düşer. Menüden ayrılırken ya da atılınca Order/Chaos kalkanları silinir.

## Guildmaster menüsü

| Seçenek                 | Açıklama                                                                                  |
| ----------------------- | ----------------------------------------------------------------------------------------- |
| Guildin ismini değiştir | 4-18 karakter                                                                             |
| Kısa ismi değiştir      | 2-5 karakter                                                                              |
| Destek yönünü değiştir  | Tarafsız, Order ya da Chaos. **4 saatte bir** değiştirilebilir, bütün sunucuya duyurulur. |
| Guild devret            | Hedeflediğiniz guild üyesi yeni guildmaster olur                                          |
| Guildi Yık              | Onay ister, geri alınamaz. Bütün sunucuya duyurulur.                                      |
| Haber ekle              | Haberler sayfasındaki yazıyı değiştirir                                                   |
| Guild nick rengi seç    | Aşağıdaki "Guild nick rengi" bölümüne bakın                                               |

## Destek yönü (Order / Chaos / Tarafsız)

Destek yönü, guildin hangi guild eşyalarını kullanabileceğini belirler:

|                | Tarafsız | Order        | Chaos        |
| -------------- | -------- | ------------ | ------------ |
| Guild kalkanı  | Yok      | Order Shield | Chaos Shield |
| Guild pelerini | Yok      | Var          | Var          |
| Guild bayrağı  | Yok      | Var          | Var          |

## Guild kudreti

Guild kudreti guildin seviyesidir (1-10). Kudret arttıkça Guild Market'te yeni eşyalar açılır ve guild pelerini güçlenir. Kudret yükselince bütün sunucuya duyurulur.

**Kudret nasıl kazanılır:** Guild üyeleri canavar (NPC) öldürdükçe guilde kudret puanı kazandırır. Hayvanlar (binekler) puan vermez. Öldüren oyuncu ayrıca kazandığı kudret puanının üçte biri kadar fame alır (guildi olmasa da).

| Öldürülen NPC   | Kudret puanı    |
| --------------- | --------------- |
| Semidar         | 30.000 - 80.000 |
| Daemon of Might | 25.000 - 30.000 |
| 2000+ STR       | 400 - 600       |
| 1500 - 1999 STR | 350 - 450       |
| 1000 - 1499 STR | 250 - 300       |
| 500 - 999 STR   | 150 - 250       |
| 500'den az STR  | 70 - 125        |

**Bir sonraki seviyeye gereken puan** (seviye atlayınca puan sıfırdan başlar):

| Seviye | Gereken puan |
| ------ | ------------ |
| 1 → 2  | 165.000      |
| 2 → 3  | 455.620      |
| 3 → 4  | 2.043.752    |
| 4 → 5  | 5.185.087    |
| 5 → 6  | 9.896.870    |
| 6 → 7  | 18.068.793   |
| 7 → 8  | 26.192.547   |
| 8 → 9  | 38.047.809   |
| 9 → 10 | 25.057.890   |

Kudret 10 en yüksek seviyedir. Guild kudret sıralaması `.top10` menüsünden görülebilir.

## Guild eşyaları

Guild menüsünde "Guild Eşyaları" bölümünden ücretsiz alınır. Sadece Order ya da Chaos guildleri alabilir.

| Eşya           | Kim alabilir       | Açıklama                                                                                                                                                           |
| -------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Guild Kalkanı  | Bütün üyeler       | Guildin yönüne göre Order ya da Chaos Shield. **24 saatte bir** alınabilir; yenisi alınınca eskileri silinir. Sadece aynı yöndeki guildlerin üyeleri kullanabilir. |
| Guild Pelerini | Bütün üyeler       | Giyince statlarınıza bonus verir; bonus guildin kudret seviyesiyle birlikte artar. Giyilince guildin adını alır.                                                   |
| Guild Bayrağı  | Sadece guildmaster | Guildmaster'ın tutabileceği, guildin adını taşıyan bayrak. Yere atılırsa bankaya gider.                                                                            |

{% hint style="info" %}
Order ve Chaos kalkanları sadece ana çantanızda taşınabilir; sandıklara ya da çanta içindeki çantalara konamaz.
{% endhint %}

### Kalkana bonus ekleme (Shield Bonus Book)

Guild Market'ten alınan **Shield Bonus Book** ile Order/Chaos kalkanınıza 24 saatlik bir koruma bonusu eklenir.

* Kitap safe alanda, çantanızdayken ve **Strengthening Force taşının** yanında kullanılır.
* Her ekleme için kumbaranızda **2.000.000 gold** bulunmalıdır (işlemde düşülür, kitap da harcanır).
* Seçilebilen bonuslar: Bleeding Block, Paradarbe Block, Stun Block, Disarm Block, Critical Block, Binek Defence, Stam Shot Block.
* Bir kalkanda aynı anda tek bonus olabilir. 24 saat dolunca bonus kalkar, kalkan kalır.

## Guild Market

Guild menüsündeki "Guild Market" bölümüdür. Ücret bankanızdaki **kumbaradan** düşülür (kumbarada fiyattan fazla gold olmalıdır). Eşyalar guildin kudret seviyesine göre açılır.

| Kudret | Eşya               | Fiyat   | Açıklama                                                                                               |
| ------ | ------------------ | ------- | ------------------------------------------------------------------------------------------------------ |
| 2      | Cleaver (guild)    | 250.000 | 7 günlük. Sadece guild üyeleri kullanır, sadece NPC'lere vurulur. Vurdukça canınızı biraz yeniler.     |
| 3      | Shield Bonus Book  | 500.000 | Order/Chaos kalkanına 24 saatlik bonus ekler (yukarıya bakın)                                          |
| 5      | 5 adet Stat Potion | 250.000 | Aşağıdaki "Guild stat potion" bölümüne bakın                                                           |
| 6      | Super Npc Bow      | 500.000 | 7 günlük. Sadece NPC'lere vurulur; NPC'lere ekstra hasar verir, arada bir çok güçlü bir vuruş çıkarır. |

## Guild stat potion

Guild Market'ten 5'li paket halinde alınır (kudret 5, 250.000 gold).

* İçince **10 dakika** boyunca statlarınızı artırır.
* Sadece **Warrior** ve **Warlock** kullanabilir.
* Çantanızda olmalıdır. Etkisi sürerken ikinci potion içilemez; kalan süre yazılır.
* 1vs1 PvP turnuvasına girerken etkisi kalkar.

## Guild nick rengi

Guildmaster, Master Menü'deki **"Guild nick rengi seç"** ile guildine bir renk seçer. Üyelere tıklanınca guild yazısı ve isim bu renkte görünür.

* Ücretsizdir. Her renk aynı anda tek bir guilde ait olabilir. Başka guildin kullandığı renk "Dolu" olarak görünür.
* "Guild rengini kaldır" ile renk bırakılır. Guild yıkılınca rengi boşa çıkar.
* Renk seçmemiş guildler normal guild renginde görünür.
* Oyuncu incognito kullanıyorsa ya da Oto PvP, sosyal, balık, kazı veya quest etkinliğindeyse renk görünmez.

## Guild puanı

Guild puanı (menüde "Savaş Puanı") guildin PvP başarısını gösterir.

* Bir guild üyesi, **başka bir guildin** üyesini öldürünce guildi **+1 puan** kazanır (öldürmenin puan sayılma şartları için **Sıralamalar** sayfasındaki "PvP öldürme puanı" bölümüne bakın).
* Britain Mezarı'nı ele geçiren guild +1 puan kazanır (**Guild Savaşları** sayfası).
* Guildin bir "genel" bir de "aylık" puanı vardır. Guild sıralaması aylık puana göre yapılır. Aylık puan her ayın 1'inde sıfırlanır ve birinci guildin üyeleri ödül alır (**Sıralamalar** sayfası).

## Guild komutları

| Komut                                                        | Ne yapar                                                                                                                   |
| ------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| `.g <mesaj>` ya da `.gc <mesaj>`                             | Oyundaki bütün guild üyelerine mesaj gönderir                                                                              |
| `.gonline`, `.gtakip`, `.guildonline`                        | Oyundaki guild üyelerini ve bulundukları bölgeyi listeler. Bir üyenin yanındaki butona basınca ok ile onu takip edersiniz. |
| `.takipiptal`                                                | Takibi bitirir                                                                                                             |
| `.guilddencik`, `.guildcik`, `.guildayril`, `.guilddenayril` | Guildden ayrılma onay penceresini açar                                                                                     |

{% hint style="success" %}
Moongate menüsündeki **"Guilde git!"** butonu sizi guild taşınızın yanına ışınlar.
{% endhint %}

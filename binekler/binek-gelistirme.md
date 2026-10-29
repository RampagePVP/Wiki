# Binek Geliştirme

Bineklerin STR, DEX ve armor değerleri belgelerle yükseltilebilir. Bu sayfada hangi bineklerin nasıl geliştirildiği anlatılıyor.

## Hangi binekler geliştirilebilir?

Belgeler sadece **geliştirilebilir** türdeki bineklere basılır. Diğerlerinde "Belirlenen listede yoktur." mesajı çıkar.

| Geliştirilebilir                                                                                                                                                                                                           | Geliştirilemez                                                                                                                                                                                                                                         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Raptor, N-Mandre, Fire Steed, Silver Steed, Silvercorn, Cu Sidhe (Wolf), Kii Rin, Tartarus, Manticore, Numa, Indra, Orn, Typhaon, Chimaira, Beetle Wert, Wendigo, Glacier Steed, Arcane Ostard, Arcane Horse, Arcane Llama | Simurg, Huma, Nemea, Bloodwing, Armored Steed, Grayer, Gryphon, Hipogrif, Pixiu, T-Rash, Mysterious Horn, Fiura, Lamassu, Unicorn, Nightmare, Ferrin, Primal Raptor, Percheron, Ordeal, Arctic Bear, Evil Wolf, Evil Horse, Shire, Mustang, Mid Ostard |

{% hint style="info" %}
Random spawn binekleri (Unicorn hariç) geliştirilebilir türdedir. **Random Spawn Binekleri** sayfasındaki Master Taming Staff bonusuyla birlikte en çok geliştirilen binekler bunlardır.
{% endhint %}

## Binek belgeleri

| Belge                           | Etkisi                                        |
| ------------------------------- | --------------------------------------------- |
| **Str Deed** (Str belgesi)      | Bineğin STR'sini artırır                      |
| **Dex Deed** (Dex belgesi)      | Bineğin DEX'ini artırır                       |
| **Armor** (Armor belgesi)       | Bineğin armorunu artırır                      |
| **Stat Full** (Binek Full Stat) | STR, DEX ve armoru tek seferde sınıra çıkarır |

Her bineğin STR, DEX ve armor için bir üst sınırı vardır; sınır `.bb` menüsünde yazar.

**Kullanım:** Belgeye çift tıklayın, bineğinizi seçin.

* Sadece **safe alanda** kullanılır.
* Belge **çantanızda**, binek **size ait** ve en fazla **3 kare** uzakta olmalı.
* Binek bir büyünün etkisi altındayken (bless vb.) belge basılamaz.
* Sınıra ulaşan binekte "MAX ... ulaşmıştır" mesajı çıkar ve belge harcanmaz.
* **Stat Full** belgesi, bineğin STR, DEX ya da armorundan **biri bile** sınırdaysa kullanılamaz. Kullanırken üçü birden sınıra çekilir.

{% hint style="info" %}
Armor sınırı belgelerle **eklenen** armor içindir. Bazı bineklerin kendi doğal armoru vardır; `.bb` menüsünde ikisinin toplamı görünür.
{% endhint %}

### Belgeler nereden çıkar?

| Belge                     | Nereden                                                                                                          |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Str, Dex, Armor belgeleri | Zindan canavarları ve boss'lar, hazine sandıkları, Solo Dungeon ve Zindan ödülleri                               |
| Stat Full                 | Master Taming Menü (**25 random spawn puanı**), Sargeras, Daemon Blood Champion, Solo Dungeon ve Zindan ödülleri |

### Binek ölünce belgeler

Bineğe çok sayıda Str ya da Dex belgesi basılmışsa, binek öldüğünde basılan belgelerin bir kısmı cesetten geri düşebilir.

{% hint style="warning" %}
Ölen binek Binek Res Scroll ile diriltilirse **başlangıç statlarıyla** geri gelir; basılan belgeler geri gelmez (**Binekler: Genel Bilgiler** sayfası).
{% endhint %}

## Random spawn bonusu (Master Taming Staff)

Random spawn bineklerini **Master Taming Staff** ile evcilleştirirseniz, staff'ta şarj varsa bineğin STR, DEX ve armoru ayrıca artar ve 1 şarj harcanır. Ayrıntılar **Random Spawn Binekleri** sayfasında.

## Bineğin görünüşü (`.bb` menüsü)

`.bb` menüsünden, safe alanda kendi bineğinize:

* **Mavi yap:** Bineğin ismi mavi görünür. **75.000 gold**.
* **Lord ünvan ver:** Bineğe "Lord" ünvanı verilir. **100.000 gold**.

Ücretler bankadaki kumbaradan düşülür. Bu görünüm figüre çevrilince de korunur.

## Ghost Ostard

Ghost Ostard belge ile değil, **siz üzerindeyken öldürdüğünüz canavarlarla** güçlenir. Ayrıntılar **Binek Taşı ve Yumurtalar** sayfasında.

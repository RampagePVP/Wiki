# Kalkan ve Savunma

Set korumasının dışında aldığın hasarı azaltan her şey bu sayfada: kalkanların Parry Blow'u, Protection ve Reactive Armor bonusu, büyü hasarına karşı koruma ve büyü bağışıklıkları.

## Bir silah vuruşunda hasar sırası

Bir oyuncu sana sunucu silahıyla (`+9`, `+12`, `+15` vb.) vurduğunda hasar şu sırayla hesaplanır:

1. Silahın hasar aralığından rastgele bir değer seçilir.
2. **PvP hasar indirimi** düşülür: setin, setsiz armorun ya da Armored Steed korumandan en iyisi + warlock/mage için büyü bonusu (bkz. **Setler**).
3. Vuranın bufu varsa hasar artar: Simurg'un **Savaş Borusu** ve Nemea binicisinin canı azalmış oyunculara karşı **Avcı İçgüdüsü**.
4. Elinde kalkan varsa **Parry Blow** hasarın bir kısmını daha emer.

## Parry Blow

Elinde **herhangi bir kalkan** varsa, oyuncuların silah vuruşlarından her seferinde hasarın bir kısmı emilir.

* Emilen miktar **Parrying** yeteneğine bağlıdır: Parrying ne kadar yüksekse o kadar çok emilir.
* Engellenen miktar sol altta "Parry Blow! (X hasar engellendi)" diye yazar.
* Nemea'nın Parçalayan Pençe yeteneğini yiyen oyuncunun kalkanı bir süre Parry Blow yapamaz.

Kalkan, warrior'ların warlock ve mage'lere karşı en büyük savunma üstünlüğüdür. Ayrıca kalkan bazen darbeyi tamamen savuşturabilir; o zaman "Darbeyi kalkanınızla savuşturdunuz." mesajı çıkar.

## Kalkanlar

| Kalkan               | Kim kullanabilir                        | Özellik                                                                        |
| -------------------- | --------------------------------------- | ------------------------------------------------------------------------------ |
| Godness Shield       | Warrior                                 | Godness setiyle gelir.                                                         |
| Dragon Shield        | Warrior                                 | Zaman zaman aldığın hasarın tamamı engellenir ("Damage Absorb Edildi!").       |
| Order / Chaos Shield | Order ya da Chaos taraflı guild üyeleri | Shield Bonus Book ile 24 saatlik koruma bonusu eklenebilir (bkz. **Upgrade**). |
| Mage Shield          | Mage                                    | Deniz Kıyısı bölgesinde giyilemez.                                             |

## Protection ve Reactive Armor

Bu iki büyü PvP'de warlock ve mage'e (Magery 20 ve üstü) oyuncuların silah vuruşlarına karşı **ek koruma** verir; ikisi birden açıkken koruma en yüksektir.

* **Protection** en iyi set/armor korumanın üstüne ek indirim verir ve armorunu artırır. **250 saniye** sürer.
* **Reactive Armor** sınırlı sayıda silah isabeti dayanır: bu vuruşların bir kısmında (hangileri olduğu rastgele) hasarın büyük kısmı emilir ve sana "Reactive Armor: N hasar emildi" yazar. Hakkı dolunca "Reactive Armor sona erdi." yazar ve büyü kalkar; yeniden atınca sayım baştan başlar. Süresi (250 saniye) daha önce dolarsa da kalkar.
* Iskalanan vuruşlar, büyüler ve canavar vuruşları Reactive Armor'ın hakkından düşmez.
* Reactive Armor'lı oyuncu oyuncudan vuruş yediğinde her vuruşta efekti görünür.
* **Geri yansıtma:** Üzerinde Reactive Armor olan oyuncu yakından (2 kare) silahla vurulunca, o vuruşta gerçekten kaybettiği canın küçük bir kısmını vurana geri yansıtır ("Reactive Armor: N hasar yansıdı"). Bu özellik Magery şartı aramaz, wand ile Reactive açan warrior'da da çalışır. Oklar yansımaz, yansıma vuranı öldürmez. Mirror Robe giyiliyken Reactive yansıtmaz.
* Warrior'lar (Magery 20 altı) bu büyüleri wand ya da upgrade yoluyla alsa da ek korumayı almaz.
* Notum Robe giyilirken üzerindeki Protection ve Reactive Armor silinir.

Huma bineğinin **Koruyucu Aura** yeteneği de binene ve yakındaki guild üyelerine kısa süre ek koruma verir.

## Büyü hasarına karşı koruma

Bazı eşyalar, oyunculardan gelen saldırı büyülerinin (Flamestrike, Lightning, Chain Lightning, Earthquake, Energy Bolt, Fireball) hasarını azaltır. Birden fazla kaynağın varsa **toplanmaz, en güçlüsü** uygulanır. Engellenen miktar sol altta "… sayesinde X büyü hasarı engellendi." diye yazar.

| Kaynak                               | Not                                     |
| ------------------------------------ | --------------------------------------- |
| High Mage Robe, Mirror Robe          | Saldırı büyülerine karşı                |
| 2. seviye geliştirilmiş guild bineği | Saldırı büyülerine karşı                |
| Perfect Robe (Warlock)               | Fireball hariç saldırı büyülerine karşı |

* **Setler büyü koruması vermez.** Godness ve Dragon setinin büyü koruması kaldırıldı; bu setleri giyen warrior saldırı büyülerine karşı yalnızca Magic Resistance'ın kendi direnciyle korunur. Warrior için ek büyü korumasının tek yolu geliştirilmiş guild bineğidir.
* Koruma **Magic Resistance** yeteneğine bağlıdır; yeteneğin düşükse koruma azalır ya da hiç çalışmaz.
* Numa bineğindeyken Perfect Robe'un korumasının bir kısmı çalışmaz.
* Magic Reflection açıkken koruma hesaplanmaz.
* Flamestrike, Lightning, Chain Lightning ve Earthquake'te koruma, hasardan **önce** uygulanır; yani seni ölümden de kurtarabilir. Fazladan can kazanmazsın.

## Mind Blast

Mind Blast'ın oyunculara verdiği hasar, hedefin **DEX'inin INT'inden ne kadar yüksek olduğuna** bağlıdır: DEX'i yüksek, INT'i düşük oyuncular (çoğunlukla warrior) çok hasar alır; INT'i DEX'inden düşük olmayan oyuncu (mage gibi) hiç hasar almaz, atana "… Mind Blast'tan etkilenmedi" yazar. Büyü ve eşyayla değişen statlar da sayılır.

* Hiçbir set, robe ya da binek Mind Blast hasarını azaltmaz.
* **Notum Robe** şarjı Mind Blast'ı tamamen engeller (her şarj bir kez).

## Büyü bağışıklıkları

Bazı eşyalar bir büyüden **tamamen** etkilenmemeni sağlar (`* Etkilenmez *`).

| Kaynak                     | Etkilenmediğin büyüler                  |
| -------------------------- | --------------------------------------- |
| High Mage Robe             | Clumsy, Feeblemind, Magic Arrow, Weaken |
| Notum Robe, 1vs1 Pvp Ödülü | Clumsy, Feeblemind, Magic Arrow, Weaken |
| Notum Robe şarjı           | Mind Blast (her şarj bir kez)           |

Silah bonuslarına (Parablow, Bleeding, Dismount …) karşı korunma yolları **Silah Bonusları** sayfasında.

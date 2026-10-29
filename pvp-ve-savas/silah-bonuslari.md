# Silah Bonusları

Sunucu silahlarının her türünün vuruş sırasında şansla tetiklenen bir bonusu vardır. Bu sayfada her bonusun ne yaptığı, hangi silahlarda olduğu ve nasıl korunacağın var.

## Bonus listesi

| Bonus               | Etkisi                                                                                 | Gereken (vuran)  | Hangi silahlar                                                                                                          |
| ------------------- | -------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Bleeding**        | Ek hasar ve kanama: hedef bir süre aralıklarla can kaybeder                            | Swordsmanship 98 | Scimitar, Katana, Bladed Staff, Extremely Broadsword / Longsword / Cutlass, Fire Katana                                 |
| **Parablow**        | Ek hasar, hedef kısa süre felç olur                                                    | Fencing 98       | Spear, Short Spear, Pike, Extremely Pike / Short Spear, Fire Spear                                                      |
| **Dismount**        | Hedef binekten düşer ve ek hasar alır                                                  | —                | Halberd, Pitchfork, Axe türleri (+24), Quarter Staff (+24), Axe ve Bladed Staff (Vanquishing), Extremely Pike / Halberd |
| **Extra Hasar**     | Ek hasar                                                                               | Swordsmanship 98 | Axe, Battle Axe, Double Axe, Two Handed Axe                                                                             |
| **Kendine Çeker**   | Hedef yanına çekilir, ek hasar alır, yaptığı işlem bozulur                             | —                | Bardiche, Extremely Bardiche                                                                                            |
| **Critical Shoot**  | Ek hasar                                                                               | Fencing 98       | Kryss                                                                                                                   |
| **Critical Damage** | Ek hasar                                                                               | Fencing 98       | Bütün Extremely silahlar                                                                                                |
| **Stamshot**        | Her vuruşta hedefin staminası düşer                                                    | —                | Club, War Mace, Quarter Staff, Black Staff (+24), Extremely Maul / War Axe                                              |
| ↳ Stam Shot         | Ek hasar, hedefin staminası çok daha fazla düşer, yaptığı işlem bozulur (`Stam Shot!`) | —                | (Stamshot'lı silahlar; Black Staff'ta daha sık)                                                                         |
| **Sakatlar**        | Ek hasar, hedef yavaşlar                                                               | Macefighting 98  | Hammer Pick, War Hammer, Extremely Maul                                                                                 |
| **Parçalama**       | Hedefin giydiği zırh parçalarından biri kırılıp yok olur                               | Macefighting 98  | Club, War Mace                                                                                                          |
| **Halüsinasyon**    | Hedef bir süre halüsinasyon görür                                                      | —                | Black Staff (+24)                                                                                                       |
| **Yakar**           | Ek hasar                                                                               | Fencing 98       | Fire Spear, Fire Katana                                                                                                 |

### Bonusların ayrıntıları

* **Hedefin canı az olunca bonus çıkmaz.** Bonusların çoğu sadece hedefin canı belli bir seviyenin üstündeyken tetiklenir; böylece bonus tek başına öldürmez.
* **Bleeding**: Kanayan hedefe tekrar Bleeding çıkmaz. Kanama Bleed Potion ya da bandajla (Healing ve Anatomy 70) durdurulur. Kanaman varken Greater Heal içemezsin, Holy Robe'u kullanamazsın.
* **Parablow**: Felçli hedef bu sürede hasar alırsa felç hemen çözülür. Felçliyken bandaj kullanılamaz.
* **Dismount**: Düşen oyuncu kısa bir süre tekrar binemez ("Binekten düşürüldünüz, X saniye binemezsiniz").
* **Stamshot**: Sadece elinde topuz türü silah varken çalışır. Art arda vuruşlarla hedefin staminası hızla sıfırlanır.
* **Sakatlar**: Hedef birkaç saniye yavaşlar, bir süre sonra kısa bir süre daha yavaşlar ("Yürümekte Zorlanır").
* **Parçalama**: Bonus çıkınca kalkan, eldiven, kask, gorget, gövde ve kol arasından rastgele bir yer seçilir; orada giyili bir parça varsa yok olur (`* Seti Parçalanır *`). Safe alanda ve Oto PvP'de çalışmaz.
* **Halüsinasyon**: Hallucination Potion ile geçer.

## Bonus bekleme süreleri

* Bleeding, Parablow veya Dismount çıkaran oyuncu **5 saniye** boyunca bu üç bonustan hiçbirini tekrar tetikleyemez.
* Sakatlar, Stun veya Disarm çıkaran oyuncu **15 saniye** boyunca bu bonusları tekrar tetikleyemez.

## Event Potionlar (bonus potionları)

Event Potion içince **10 dakika** boyunca ilgili bonusun çok daha sık çıkar:

* Event Potion (Bleed): Bleeding
* Event Potion (Parablow): Parablow
* Event Potion (Dismount): Dismount

Aynı anda sadece **bir** Event Potion etkisi olabilir. Mage'ler Event Potion kullanamaz. Çantanda içmen gerekir. 10 Dragon Blood'a çift tıklayıp istediğin Event Potion'ı yapabilirsin (safe alanda).

## Bineklerin bonuslara etkisi

| Binek  | Etkisi                                                                  |
| ------ | ----------------------------------------------------------------------- |
| Grayer | Bleeding daha sık çıkar. Dismount ve Earth Bow seni binekten düşüremez. |
| T-Rash | Parablow ve Stun daha sık çıkar.                                        |

## Silahsız bonuslar (Wrestling)

Elinde silah yokken wrestling vuruşlarında çalışan iki bonus komutla açılıp kapatılır:

| Komut     | Gereken                   | Etkisi                                                                                                                          |
| --------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| `.stun`   | Wrestling ve Anatomy 80   | Hedef kısa süre sersemler ("Sersemler"). Sersemlemenin ilk anlarında vuruş alırsa erken çözülebilir.                            |
| `.disarm` | Wrestling ve Arms Lore 80 | Hedefin iki elindeki eşyalar çantasına düşer ("Silahsizlandirilir"). Hedef en fazla 1 kare uzakta ve iki elinde de eşya olmalı. |

Hedefin canı çok azken bu bonuslar çıkmaz. Komutu tekrar yazınca bonus kapanır.

## Yay bonusları

| Yay        | Etkisi                                                                  |
| ---------- | ----------------------------------------------------------------------- |
| Fire Bow   | Hedef birkaç saniye içinde birkaç kez yanma hasarı alır ("Yanar").      |
| Earth Bow  | Hedef binekten düşer. Grayer binicisi etkilenmez.                       |
| Ice Bow    | Hedef can kaybeder ve çok kısa süre donar ("Ice Shoot").                |
| Energy Bow | Hedef hasar alır ve staminası düşer, sen can kazanırsın ("Stam Shoot"). |

Yay bonusları sadece oyunculara çıkar.

## Bonuslardan korunma

| Bonus             | Korunma yolu                                                                                                              |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Bleeding          | Armorer Helm **Bleed Absorb** şarjı; Order/Chaos Shield'da **Bleeding Block**                                             |
| Parablow          | Armorer Helm **Parablow Absorb** şarjı; Order/Chaos Shield'da **Paradarbe Block**                                         |
| Dismount          | Armorer Helm **Dismount Absorb** şarjı; Grayer bineği                                                                     |
| Critical Damage   | Order/Chaos Shield'da **Critical Darbe Block** ("Critical Absorb")                                                        |
| Binek saldırıları | Order/Chaos Shield'da **Binek Defence** ya da Animal of Belt: binek vuruşlarının bir kısmı engellenir ("Belt of Defence") |

* Armorer Helm absorb şarjı bonus çıktığında bir kez emer ve 1 şarj gider ("Bleeding Absorb !", "Parablow Absorb !", "Dismount Absorb !"). Bir helme sadece bir tür absorb eklenebilir, en fazla 5 şarj.
* Order/Chaos Shield bonusu **Shield Bonus Book** ile eklenir ve 24 saat sürer. Ayrıntılar **Upgrade** sayfasında.

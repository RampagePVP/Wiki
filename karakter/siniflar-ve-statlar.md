# Sınıflar ve Statlar

Rampage PvP'de üç sınıf var: **Warrior**, **Warlock** ve **Mage**. Sınıfını ve statlarını safe alandaki taşlardan seçersin; giyebileceğin set, robe ve silahlar sınıfına göre değişir.

## Sınıf seçimi

Sınıfını ilk girişte Başlangıç taşından, sonradan da safe alandaki **Skill Stone**'dan seçersin. Sınıf değiştirmek sadece safe alanda yapılabilir.

| Sınıf   | Yetenekler                                                                                                     | Seçince gelen statlar (STR / DEX / INT) |
| ------- | -------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| Warrior | Bütün yetenekler 100. Magery, Meditation ve Evaluating Intelligence 0.                                         | 100 / 100 / 25                          |
| Warlock | Bütün yetenekler 100 (hem savaş hem büyü).                                                                     | 90 / 90 / 45                            |
| Mage    | Bütün yetenekler 100. Savaş yetenekleri (Wrestling, Fencing, Archery, Swordsmanship, Macefighting, Tactics) 0. | 100 / 25 / 100                          |

* Snooping ve Stealing her sınıfta 0'dır.
* Skill Stone'dan sınıf değiştirince üzerindeki büyüler silinir, giyili eşyaların çantana düşer ve binekten inersin. Safe alanda inilen binek 30 dakika içinde tekrar binilmezse silinir; sınıf değiştirdikten sonra bineğine tekrar binmeyi unutma.
* **Skill Book** ile 110.0'a çıkardığın yetenek (Fencing, Swordsmanship, Macefighting, Evaluating Intelligence, Archery) sınıf değiştirdiğinde kaybolmaz; o sınıfta yetenek açık olduğu sürece yine 110.0 olur. Ayrıntılar **Upgrade** sayfasında.
* Seçtiğin sınıf karakterinin ünvanı olur (Warrior / Warlock / Mage). Bazı eşyalar (ör. Stat Potion) ve Deadly Poison'un warrior bonusu bu ünvana bakar.

## Eşyalar sınıfı nasıl tanır?

Eşyalar ünvana değil, çoğunlukla yeteneklerine bakar:

| Sınıf eşyası                                                   | Aranan şart                                                                              |
| -------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Warrior eşyaları (Godness, Dragon, Diablo setleri, Notum Robe) | Tactics yaklaşık 100, Magery ve Meditation yaklaşık 0                                    |
| Warlock eşyaları (Perfect Robe, Ice Shield)                    | Magery ve Tactics 99.1 üstü                                                              |
| Mage eşyaları (High Mage Robe, Mage Shield, Mana Sandals)      | Magery, Meditation, Evaluating Intelligence 99.1 üstü ve bütün savaş yetenekleri 20 altı |
| Warlock/Mage setleri (Ranger, Devil Özel) ve Armorer Helm      | Magery (setlerde 40 üstü, helmde 99.1 üstü)                                              |

{% hint style="info" %}
Hasar sistemindeki **büyü bonusu** (Protection ve Reactive Armor) ve warlock/mage'e özel koruma kuralları **Magery 20 ve üstü** olan herkese uygulanır. Yani warlock ve mage aynı kurallara tabidir.
{% endhint %}

## Stat menüsü

Statlarını safe alandaki **Stat Stone**'a çift tıklayarak ya da `.stat` komutuyla açılan menüden ayarlarsın.

* STR, DEX ve INT toplamı **tam 225** olmalı (az ya da çok olursa kabul edilmez).
* Her stat en az 10, en fazla **100** olabilir.
* Onaylama sadece **safe alanda** yapılır.
* Onaylayınca üzerindeki büyüler silinir ve giyili eşyaların çantana düşer (binekten inmezsin). Sonra eşyalarını tekrar giyersin.
* Onaylanan statlar korumaya alınır; yetenek kullanırken ya da bölge değiştirirken kendiliğinden değişmez.
* Üzerinde stat veren bir eşya ya da stat büyüsü varken `.stat` menüsü açılmaz.

### Mage DEX kuralı

**Mage'ler en fazla 35 DEX alabilir.** STR en fazla 100 olduğu için bu, INT'in en az 90 olması demektir.

* Bu kuralda "mage", Magery 99.1 ve üstü olup bütün savaş yetenekleri (Fencing, Swordsmanship, Macefighting, Archery, Wrestling, Tactics) 20 altında olan karakterdir. Warlock ve warrior etkilenmez.
* Stat menüsü mage'e 35'ten fazla DEX yazdırmaz.
* Kuralı aşan mage'de **mana bot** (Mana Sandals'ın düzenli mana vermesi) çalışmaz; oyuna girişte de uyarı çıkar. Statlarını menüden düzeltince mana bot tekrar çalışır.
* Kanat, pelerin gibi eşyaların verdiği DEX bu sınıra sayılmaz; kural sadece menüde seçtiğin DEX'e bakar.

### Fazla stat kontrolü

Oyuna girişte statlarının toplamı, 225'i ve giydiğin stat eşyalarının bonusunu belirgin şekilde aşıyorsa stat menüsü kendiliğinden açılır ve statlarını yeniden seçene kadar kapanmaz. Safe alanda statlarını seçmen, sonra eşyalarını tekrar giymen yeterli.

## Stat veren eşyalar

Bu eşyalar giyildiğinde stat verir, çıkarıldığında ya da süresi dolduğunda verdiği statı geri alır.

| Eşya                                   | Bonus                              | Not                                                    |
| -------------------------------------- | ---------------------------------- | ------------------------------------------------------ |
| Shirt of Stat Defense                  | STR ve INT                         | 7 gün süreli                                           |
| Earrings of Stat Defense (Stat Küpesi) | STR ve INT                         | 7 gün süreli                                           |
| Guild Pelerin                          | Guild kudretine göre bütün statlar | Sadece taraf seçmiş guildlerin üyeleri giyebilir       |
| Pvp Commander kanadı                   | Bütün statlar                      | Sadece PvP lig kralı giyebilir                         |
| Stat Potion                            | Bütün statlar, 10 dakika           | Sadece Warrior ve Warlock içebilir; aynı anda bir tane |
| Godness seti                           | STR                                | Bütün parçalar giyiliyken                              |

## Mana bot

**Mana Sandals** (sadece mage giyebilir) giyiliyken birkaç saniyede bir manan kendiliğinden dolar. Mage DEX kuralını aşan mage'de mana bot çalışmaz.

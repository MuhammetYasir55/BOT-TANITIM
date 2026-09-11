# **Pokémon Discord Bot**

Python ve Discord.py kullanılarak geliştirilmiş bir Pokémon Discord botudur.

Bu bot sayesinde Discord sunucusunda Pokémon oluşturabilir, Pokémon bilgilerini görüntüleyebilir, Pokémon'unu besleyebilir ve diğer Pokémonlarla savaşabilirsin.

---

## **Özellikler**

* Rastgele Pokémon oluşturma
* Wizard Pokémon türü
* Fighter Pokémon türü
* Pokémonlarla savaşma
* Pokémon sağlık (HP) sistemi
* Pokémon güç sistemi
* Pokémon besleme
* Pokémon seviye sistemi
* Nadir Pokémon bulma şansı
* Pokémon görsellerini gösterme
* Pokémon bilgilerini görüntüleme
* PokeAPI kullanımı

---

## **Komutlar**

| Komut                | Açıklama                                        |
| -------------------- | ----------------------------------------------- |
| `!go`                | Rastgele bir Pokémon oluşturur.                 |
| `!attack @kullanıcı` | Başka bir Pokémon'a saldırır.                   |
| `!besle`             | Pokémon'un seviyesini artırır.                  |
| `!seviye`            | Pokémon'un seviyesini gösterir.                 |
| `!yakala`            | Nadir Pokémon bulma şansı verir.                |
| `!info`              | Pokémon'un adını, gücünü ve sağlığını gösterir. |
| `!feed`              | Pokémon'un sağlığını yeniler.                   |

---

## **Pokémon Türleri**

### **Wizard**

Wizard türündeki Pokémon savaş sırasında bazen kalkan kullanabilir.

Ayrıca daha kısa sürede tekrar beslenebilir.

### **Fighter**

Fighter türündeki Pokémon saldırı sırasında süper saldırı kullanabilir.

Saldırı sırasında ekstra güç kazanarak rakibine daha fazla hasar verebilir.

---

## **Pokémon Sistemi**

Her Pokémon'un aşağıdaki özellikleri bulunur:

* HP (sağlık)
* Power (güç)
* Rastgele Pokémon numarası
* Pokémon adı

Pokémon adı ve görseli PokeAPI üzerinden alınır.

---

## **Besleme Sistemi**

Pokémon'u besleyerek sağlığını yenileyebilirsin.

Ayrıca botta Pokémon seviyesi için ayrı bir sistem bulunmaktadır.

Örnek:

```text
Pokémonun beslendi!

Yeni seviye: 2
```

---

## **Savaş Sistemi**

Bir Pokémon başka bir Pokémon'a saldırabilir.

Örneğin:

```text
!attack @kullanıcı
```

Saldırı sonucunda rakibin HP değeri azalır.

Rakibin HP'si 0 olduğunda Pokémon yenilir.

---

## **Nadir Pokémon Sistemi**

`!yakala` komutuyla Pokémon bulabilirsin.

Her denemede nadir Pokémon bulma ihtimali vardır.

Örnek:

```text
Tebrikler! Nadir Pokémon buldun!
```

---

## **Ekran Görüntüleri**

### **Botun Çalışması**

Botun Discord'da çalışırken çekilmiş ekran görüntüsü burada gösterilebilir.

### **Pokémon Bilgisi**

`!info` komutunun sonucunun ekran görüntüsü burada gösterilebilir.

### **Pokémon Savaşı**

`!attack` komutunun sonucunun ekran görüntüsü burada gösterilebilir.

---

## **Kullanılan Teknolojiler**

* Python
* Discord.py
* PokeAPI
* aiohttp
* random
* asyncio

---

## **Proje Dosyaları**

```text
Pokémon Discord Bot
│
├── main.py
├── logic.py
├── config.py
└── README.md
```

### **main.py**

Discord botunun komutlarını ve botun çalışmasını kontrol eder.

### **logic.py**

Pokémon, Wizard ve Fighter sınıflarını içerir.

Pokémonların saldırı, beslenme, bilgi ve görsel özellikleri burada bulunur.

### **config.py**

Discord botunun token bilgisini içerir.

> Bot tokenini GitHub'a açık şekilde yüklememeye dikkat et.

---

## **Projenin Amacı**

Bu proje ile Python, sınıflar, kalıtım, asenkron programlama, Discord botları ve API kullanımı gibi konularda pratik yapılmıştır.

Aynı zamanda Discord üzerinde eğlenceli ve etkileşimli bir Pokémon sistemi oluşturulmuştur. 🎮

---

## **Geliştirici**

**Pokémon Discord Bot Projesi**

⭐ Projeyi beğendiysen GitHub'da yıldız bırakmayı unutma!

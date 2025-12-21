
# Get Started with Python - Key Concepts

This section covers the fundamental building blocks of programming within the Google Advanced Data Analytics Professional Certificate.

---

## 🛠️ Core Programming Definitions (Temel Programlama Tanımları)

### 🧩 Functions (Fonksiyonlar)
**Functions** (Fonksiyonlar) are reusable pieces of code that perform a specific task, allowing for **modular programming** (modüler programlama) and **code efficiency** (kod verimliliği).

### 📝 Python Syntax (Python Sözdizimi)
**Python Syntax** (Python Sözdizimi) refers to the set of rules that define the combinations of symbols that are considered to be correctly structured programs in Python.

### 🏗️ Object-Oriented Programming (Nesne Yönelimli Programlama)
**Object-Oriented Programming - OOP** (Nesne Yönelimli Programlama) is a **programming paradigm** (programlama paradigması) that uses "objects" to represent data and methods to manipulate that data, promoting **code reusability** (kodun yeniden kullanılabilirliği) and organization.

---

## 📊 Data Management (Veri Yönetimi)

### 🔠 Data Types (Veri Tipleri)
**Data Types** (Veri Tipleri) in Python specify the type of data that can be stored and manipulated. Key types include:
* **Integers** (Tam Sayılar)
* **Floats** (Ondalıklı Sayılar)
* **Strings** (Metin Dizileri)
* **Booleans** (Mantıksal Değerler)

### 🗄️ Data Structures (Veri Yapıları)
**Data Structures** (Veri Yapıları) are used to store and organize data efficiently. Common structures in Python include:
* **Lists** (Listeler)
* **Tuples** (Demetler)
* **Dictionaries** (Sözlükler)

---
> *Documentation generated for the Google Advanced Data Analytics Series.*

# [Introduction to Python](https://en.wikipedia.org/wiki/Monty_Python)

 <img width="827" height="413" alt="image" src="https://github.com/user-attachments/assets/c61ea5f5-a6fc-448d-8478-2480c87ddf05" />

# 🐍 Python vs. Diğer Programlama Dilleri: Veri Bilimi Perspektifi

Veri profesyonelleri için doğru aracı seçmek, projenin başarısı için kritiktir. Python, "okunabilirliği" ve "esnekliği" sayesinde modern veri biliminin kalbinde yer almaktadır. Bu dökümanda, Python'un rakipleriyle olan teknik karşılaştırmasını ve temel programlama kavramlarını inceleyeceğiz.

---

## 🚀 Programlama Dillerini Değerlendirme Kriterleri (Five Considerations)

Bir dilin veri analizindeki etkinliğini ölçmek için 5 ana kriteri baz alıyoruz:

1.  **Hız (Speed):** Programın yürütülme süresidir. Derleme süresi (compile time) ve çalışma süresi (runtime) gibi faktörlerden etkilenir. Düşük seviyeli diller (C++ gibi) genelde daha hızlıdır.
2.  **Erişilebilirlik (Approachability):** Yeni öğrenenler için öğrenme eğrisidir. Python'un **Sözdizimi (Syntax)** konuşma diline yakın olduğu için bu konuda liderdir.
3.  **Değişkenler (Variables):** Bilginin bellekte nasıl saklandığıdır. **Statik (Static)**, **Dinamik (Dynamic)** veya **Bildirimsel (Declarative)** olabilirler.
4.  **Veri Bilimi Odağı (Data Science Focus):** Dilin veri analizi, istatistik ve makine öğrenimi kütüphaneleri açısından ne kadar zengin olduğudur.
5.  **Programlama Paradigması (Programming Paradigm):** Kodun çözüm stili. **Nesne Yönelimli (Object-Oriented)**, **Fonksiyonel (Functional)** veya **Emredici (Imperative)** olabilir.

---

## 📊 Karşılaştırmalı Analiz Tablosu (Comparative Analysis)

Aşağıdaki tablo, Python'u veri biliminde sık kullanılan diğer dillerle teknik olarak kıyaslar:

| Dil | Hız (Speed) | Erişilebilirlik | Değişken Tipi | Paradigma | Kullanım Amacı |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Python** | Orta (Yavaş) | Çok Yüksek | Dinamik | Nesne Yönelimli | Makine Öğrenimi, Otomasyon |
| **R** | Orta | Orta | Dinamik | Fonksiyonel | İstatistiksel Analiz, Görselleştirme |
| **Java** | Hızlı | Orta | Statik | Nesne Yönelimli | Büyük Veri (Hadoop/Spark), Uygulama Geliştirme |
| **C++** | Çok Hızlı | Düşük | Statik | Çoklu (Multi) | Yüksek Performanslı Hesaplamalar |

---

## 🔍 Temel Teknik Kavramlar ve Eksik Bölümler

### 1. Fonksiyonlar (Functions)
Kodun belirli bir görevi yerine getiren, yeniden kullanılabilir parçalarıdır. 
* **Veri Biliminde Kullanımı:** Veri temizleme adımlarını (data cleaning) bir fonksiyon içine alarak binlerce satır veri üzerinde aynı işlemi saniyeler içinde tekrar edebilirsiniz.

### 2. Değişkenler (Variables)
Bellekte (RAM) değerleri saklayan isimlendirilmiş konteynerlardır. 
* **Python Farkı:** Python dinamik bir dildir; yani `x = 5` dediğinizde tipini belirtmeniz gerekmez, Python bunu otomatik anlar. C++'ta ise `int x = 5` şeklinde belirtmek zorunludur.



### 3. Programlama Paradigmaları (Programming Paradigms)
* **Nesne Yönelimli (Object-Oriented):** Veriyi "nesneler" üzerinden modeller. Python bu konuda çok güçlüdür.
* **Fonksiyonel (Functional):** Matematiksel fonksiyonlara odaklanır (R dili bu yapıdadır).
* **Emredici (Imperative):** Bilgisayara adım adım ne yapması gerektiğini söyleyen komut satırlarıdır.

---

## 💡 Neden Python? (Expert Conclusion)

Python, bazen C++ kadar hızlı olmasa da (çünkü yorumlanan -interpreted- bir dildir), **Geliştirme Hızı** açısından rakipsizdir. 

* **Nerede Kullanılır?** Tahminleme modelleri, otomasyon sistemleri ve web tabanlı veri panelleri.
* **Hangi Yöntemle?** `Pandas` (Veri manipülasyonu), `Scikit-learn` (Makine öğrenimi) ve `TensorFlow` (Derin öğrenme) kütüphaneleri aracılığıyla.

**Sonuç:** Veri dünyasına yeni adım atıyorsanız, Python "en az dirençle en çok verim" alabileceğiniz dildir. Dinamik değişken yapısı ve geniş topluluk desteğiyle otomasyon ve yapay zeka projelerinde altın standarttır.

---
*Bu döküman Veri Bilimi uzmanları ve GitHub topluluğu için hazırlanmıştır.*

# 📓 Jupyter Notebook: Veri Bilimi İçin İnteraktif Geliştirme Rehberi

Jupyter Notebook, canlı kod (live code), denklemler, görselleştirmeler ve açıklayıcı metinler içeren dökümanlar oluşturmanıza olanak tanıyan açık kaynaklı bir web uygulamasıdır.

---

## 🏗️ Temel Bileşenler ve Teknik Detaylar

### 🔋 Modüler Hesaplama: Hücreler (Cells)
Jupyter'in kalbi **Hücreler (Cells)**'dir. Kodunuzu devasa bir script olarak değil, yönetilebilir bloklar halinde yazarsınız.
* **Avantajı:** Bir hatayı düzeltmek için tüm programı baştan çalıştırmanıza gerek kalmaz; sadece ilgili hücreyi güncelleyip tekrar çalıştırmanız (Shift + Enter) yeterlidir.

### 🧠 Kernel Kavramı (Teknik Tamamlama)
Metinde eksik olan en kritik parça **Kernel**'dır. 
* **Kernel (Çekirdek):** Kodunuzu arka planda çalıştıran "motordur". Python kodunu gönderdiğinizde Kernel bunu işler ve sonucu hücrenin hemen altına döndürür. Eğer kodunuz sonsuz döngüye girerse, "Kernel -> Restart" yaparak sistemi sıfırlayabilirsiniz.

### 📝 Markdown ve Belgeleme
Jupyter, analizinize bağlam kazandırmak için **Markdown** dilini kullanır. Bu, kodun ne yaptığını sadece yorum satırlarıyla (#) değil, profesyonel başlıklar, listeler ve linklerle açıklamanızı sağlar.

---

## 🕹️ Kullanım Modları ve Kısa Yollar

Jupyter iki temel modda çalışır:

1.  **Komut Modu (Command Mode):** Hücrelerin bütünüyle etkileşime girilir (Kenar çubuğu MAVİ'dir).
    * `A`: Üste hücre ekle (Above)
    * `B`: Alta hücre ekle (Below)
    * `D + D`: Seçili hücreyi sil
    * `M`: Hücreyi Markdown moduna al
    * `Y`: Hücreyi Kod (Code) moduna al
2.  **Düzenleme Modu (Edit Mode):** Hücre içine kod yazılır (Kenar çubuğu YEŞİL'dir).
    * `Esc`: Komut moduna döner.
    * `Ctrl + Enter`: Hücreyi çalıştırır.

---

## 📊 Karşılaştırmalı Analiz: Jupyter vs. Geleneksel IDE (PyCharm/VS Code)

| Özellik | Jupyter Notebook | Geleneksel IDE (Scripting) |
| :--- | :--- | :--- |
| **Geri Bildirim** | Anlık (Hücre bazlı çıktı) | Gecikmeli (Tüm dosya çalışmalı) |
| **Görselleştirme** | Grafik ve tablolar satır içinde (inline) | Ayrı bir pencerede veya dosyada |
| **Kullanım Amacı** | Veri analizi, Deneyler, Eğitim | Yazılım geliştirme, Büyük projeler |
| **Format** | JSON tabanlı `.ipynb` | Düz metin `.py` |



---

## 🛠️ Sorun Giderme (Troubleshooting) ve Bakım

Analiziniz sırasında donma veya hata ile karşılaşırsanız şu adımları izleyin:

* **Tarayıcı Uyumluluğu:** Chrome, Firefox veya Edge kullanın.
* **İnternet Kararlılığı:** Coursera gibi bulut tabanlı platformlarda kopmalar "Autosave Failed" hatasına yol açar.
* **Kernel Reset:** Eğer bir hücre saatlerce "çalışıyor" (`[*]`) görünüyorsa, Kernel'ı durdurup yeniden başlatın.
* **Checkpoint (Teknik Not):** Jupyter düzenli olarak "Checkpoints" oluşturur. Bir hata yaparsanız `File -> Revert to Checkpoint` ile önceki sağlıklı sürüme dönebilirsiniz.

---
> **Not:** Bu döküman Google Advanced Data Analytics sertifika programı standartlarına uygun olarak hazırlanmıştır.


# 🧩 Nesne Yönelimli Programlama (Object-Oriented Programming - OOP)

Veri biliminde Python'u bu kadar güçlü kılan şey, her şeyin bir **Nesne (Object)** olarak tasarlanmış olmasıdır. OOP, veriyi (attributes) ve o veriyle yapılacak işlemleri (methods) tek bir çatı altında toplar.

---

## 🏗️ Temel Yapı Taşları: Sınıflar ve Nesneler

### 1. Sınıf (Class) vs. Nesne (Instance)
* **Sınıf (Class):** Bir nesnenin "taslak planı" veya "mavi kopyasıdır" (blueprint). Örneğin; `Spaceship` (Uzay Gemisi) bir sınıftır.
* **Nesne (Instance/Object):** Bu plandan üretilen somut örnektir. Örneğin; `Enterprise` veya `Millennium Falcon` birer nesnedir.



### 2. Öznitelikler (Attributes)
Nesnenin **özelliklerini** veya **karakteristiklerini** temsil eder. Parantez kullanılmadan erişilir.
* **Örnek:** `planets.shape`, `spaceship.speed`
* **Veri Bilimi Odağı:** Bir DataFrame'in kaç satır/sütun olduğunu anlamak için `.shape` özniteliğini kullanırız.

### 3. Metotlar (Methods)
Nesnenin gerçekleştirebileceği **eylemleri** temsil eder. Fonksiyonlar gibi çalışırlar ve her zaman parantez `()` ile çağrılırlar.
* **Örnek:** `magic.replace()`, `spaceship.warp(7)`, `df.dropna()`
* **Veri Bilimi Odağı:** Veriyi temizlemek için `.dropna()` metodunu çağırmak, nesneye "eksik verileri sil" emrini vermektir.

---

## 🛠️ OOP'nin 4 Temel Kavramı (Missing Technical Sections)

Metinde bahsi geçen ancak detaylandırılmayan, OOP'yi oluşturan dört ana direk şunlardır:

1.  **Kapsülleme (Encapsulation):** Verilerin ve metotların bir sınıf içinde gizlenerek dış müdahalelerden korunmasıdır.
2.  **Kalıtım (Inheritance):** Bir sınıfın özelliklerini başka bir sınıfa aktarmasıdır (Örn: `Transport` sınıfından `Spaceship` türetmek).
3.  **Çok Biçimlilik (Polymorphism):** Farklı nesnelerin aynı isimli metotlara farklı tepkiler vermesidir.
4.  **Soyutlama (Abstraction):** Karmaşık detayları gizleyip kullanıcıya sadece gerekli arayüzü sunmaktır.



---

## 📊 Karşılaştırmalı Analiz: Öznitelik vs. Metot

| Özellik | Öznitelik (Attribute) | Metot (Method) |
| :--- | :--- | :--- |
| **Tanım** | Nesnenin durumu/verisi | Nesnenin davranışı/aksiyonu |
| **Sözdizimi (Syntax)** | `nesne.oznitelik` | `nesne.metot()` |
| **Parantez** | Kullanılmaz ❌ | Kullanılır ✅ |
| **Değişim** | Bilgi verir, değiştirmez | Genellikle bir işlem yapar/durumu değiştirir |

---

## 🚀 Veri Biliminde Uygulama: Pandas Örneği

Bir veri bilimci olarak en çok karşılaşacağınız OOP yapısı `pandas` kütüphanesidir:

```python
import pandas as pd

# 'df' burada DataFrame sınıfının bir örneğidir (Instantiation)
df = pd.read_csv("data.csv") 

# ATTRIBUTE kullanımı (Verinin şeklini öğrenme)
print(df.shape) 

# METHOD kullanımı (Veriyi manipüle etme)
df_clean = df.drop_duplicates()
```

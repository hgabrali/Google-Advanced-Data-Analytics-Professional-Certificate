
# 🚀 PACE Metodolojisine Giriş

<img width="657" height="383" alt="image" src="https://github.com/user-attachments/assets/5d907f3c-3c46-491d-bee7-919ece4341db" />

[The PACE Stages](https://medium.com/@andersongimino/the-pace-stages-12206e1ea536)

## 🎯 PACE Çerçevesi: Tanım, Uygulama ve Zorluklar
PACE, projelerde Amaç (Purpose), Yaklaşım (Approach), Kısıtlamalar (Constraints) ve Beklenen Sonuç (Expected Outcome) bileşenlerini netleştiren bir metodolojidir.

# 📊 PACE Framework Analysis: Definition, Application, and Challenges

This comparative table summarizes the core aspects of the **PACE** (Purpose, Approach, Constraints, Expected Outcome) project management framework. 
| Soru Kategorisi | 1. PACE Çerçevesi Nedir? (Tanım) | 2. PACE Çerçevesi Projelerde Nasıl Uygulanır? (Uygulama) | 3. PACE Kullanımında Hangi Zorluklar Ortaya Çıkabilir? (Riskler) ⚠️ |
| :--- | :--- | :--- | :--- |
| **Kapsam** | Çerçevenin dört ana bileşenini ve temel amacını açıklar. | Her bileşenin projenin başlangıcında nasıl tanımlandığını ve kullanıldığını gösterir. | Çerçevenin uygulanması sırasında ortaya çıkabilecek yaygın hataları ve direnç noktalarını belirtir. |
| **Ana Bileşenler** | P, A, C, E kısaltmalarının ne anlama geldiği. | P, A, C, E'ye dair somut proje ifadeleri (örneğin, **P** için iş hedefi, **E** için MAE değeri). | Belirsizlik, değişen kapsam, gizli maliyetler ve paydaş direnci. |
| **Açıklama** | Projenin nedenini, yöntemini, sınırlamalarını ve hedefini belirleyen bir yol haritasıdır. | Bir proje başlatılırken, bir toplantı belgesi veya sözleşme taslağı olarak kullanılır. Önce **Amaç (P)** tanımlanır, sonra **Yaklaşım (A)** ve **Kısıtlamalar (C)** belirlenir. | En büyük zorluk, tüm paydaşların **C (Kısıtlamalar)** üzerinde anlaşmasını sağlamak ve **P (Amaç)** net olmadığında sürekli **kapsam kaymasını (scope creep)** önlemektir. |
| **Temel Çıktı** | Net ve yapılandırılmış bir proje planı tanımı. | Projenin başında elde edilen, tüm ekip ve paydaşlar tarafından onaylanan **4 maddelik kesin bir plan**. | Proje başarısızlığına yol açabileceği veya kaynakları boşa harcayabileceği potansiyel risklerin listesi. |

# 🔍 1. PACE Çerçevesi Nedir? (Detailed Explanation)

PACE, özellikle veri projelerinde, analizin teknik karmaşıklığı ile iş gereksinimleri arasındaki boşluğu doldurmayı amaçlayan bir **proje yönetim ve iletişim aracıdır**. Amacı, bir projeye başlamadan önce tüm paydaşların **ne, neden, nasıl ve ne zaman** sorularına aynı cevabı vermesini sağlamaktır. 
---

| Kısaltma 🏷️ | İngilizce Terim | Türkçe Anlamı | Açıklama |
| :--- | :--- | :--- | :--- |
| **P** | **Purpose** | **Amaç** | Neden yapılıyor? Hangi iş sorununu çözüyor? |
| **A** | **Approach** | **Yaklaşım** | Nasıl yapılacak? Hangi teknik ve veriler kullanılacak? |
| **C** | **Constraints** | **Kısıtlamalar** | Neler engelliyor? Bütçe, zaman, etik sınırlamalar? |
| **E** | **Expected Outcome** | **Beklenen Sonuç** | Başarı neye benzeyecek? Model, rapor, hangi metriklerle ölçülecek? |

# 🛠️ 2. How to Apply the PACE Framework in Projects

The PACE framework is typically implemented during a project's "Kick-off" meeting to ensure alignment and clarity on the four core components. 

## Application Steps:

| Step 🔢 | PACE Element 🏷️ | Action and Goal | Example / Context |
| :--- | :--- | :--- | :--- |
| **1.** | **Define P (Purpose)** | Connect the project goal to a clear business objective. **This is the project's reason for existence.** | *Example:* "Tie the sales forecast to the business goal of **increasing the product's sales by 15%**." |
| **2.** | **Define E (Expected Outcome)** | Determine the success metrics (e.g., "MAE < 10%") and the output format (e.g., "Live Dashboard"). **This is the targeted finish line.** | *Example:* "The output must be a **Live Dashboard** with a required **MAE less than 10%**." |
| **3.** | **Determine A (Approach)** | Specify the technical paths required to reach P and E. **This is the project's roadmap.** | *Example:* "Use an **XGBoost model** and implement it with **Python**." |
| **4.** | **Determine C (Constraints)** | List all limitations that might be encountered while implementing A. **This is risk and limitation management.** | *Example:* "The project must be completed within **4 weeks**, and costs cannot exceed **X amount**." |


# ⚠️ 3. PACE Kullanımında Hangi Zorluklar Ortaya Çıkabilir?

PACE, projeleri kolaylaştırsa da, uygulama sırasında bazı yaygın zorluklarla karşılaşılabilir. 
| Zorluk Alanı 🛑 | Açıklama | Bağlantılı PACE Bileşeni |
| :--- | :--- | :--- |
| **Amaç Belirsizliği (P)** | Paydaşlar, projenin gerçek iş hedefini (**Purpose**) netleştiremezse, **A, C ve E** maddeleri anlamını yitirir ve proje sürekli yön değiştirir. | **P** (Purpose) |
| **Kapsam Kayması (Scope Creep)** | **Kısıtlamalar (C)** yeterince sıkı tanımlanmazsa, paydaşlar sürekli yeni özellikler talep eder, bu da **zaman ve bütçe kısıtlarını aşar.** | **C** (Constraints) |
| **Yetersiz Yaklaşım (A)** | Teknik ekip, **Yaklaşım (Approach)** maddesinde taahhüt edilen sonuca (E) ulaşamayacak kadar iddialı bir yöntem seçebilir. | **A** (Approach) |
| **Ölçülemeyen Sonuç (E)** | **Beklenen Sonuç (Expected Outcome)**, ölçülemeyen (örneğin, "satışları biraz artırmak") veya öznel (örneğin, "güzel bir rapor") ifadelerle tanımlanırsa, projenin başarılı olup olmadığı asla anlaşılamaz. | **E** (Expected Outcome) |

---

**PACE**, Veri Bilimi ve Analitik projelerde karar alma sürecini yapılandırmak, proje yönetimini netleştirmek ve ekipler arası işbirliğini geliştirmek için kullanılan bir kısaltmadır. Bu metodoloji, özellikle Büyük Dil Modelleri (LLM'ler) ve diğer AI araçlarıyla çalışırken, proje hedeflerinin, kısıtlamalarının ve çıktıların netleştirilmesine yardımcı olur.

PACE, dört temel bileşeni temsil eder:

## 🚀 PACE Metodolojisi: Veri Projesi Çerçevesi

**PACE**, analitik projelerde netlik ve işbirliği sağlamak için kullanılan dört temel bileşeni tanımlayan bir kısaltmadır. 
| Kısaltma 🏷️ | İngilizce Terim | Türkçe Anlamı | Amaç ve Rolü |
| :--- | :--- | :--- | :--- |
| **P** | **Purpose** | **Amaç** | Projenin **neden** yapıldığını ve hangi iş hedefine hizmet ettiğini tanımlar. |
| **A** | **Approach** | **Yaklaşım** | Projenin **nasıl** yapılacağını, hangi veri setlerinin, algoritmaların veya tekniklerin kullanılacağını belirler. |
| **C** | **Constraints** | **Kısıtlamalar** | Projenin başarılı olması için dikkate alınması gereken **sınırlayıcı** faktörleri (bütçe, zaman, etik kurallar, teknik sınırlamalar) listeler. |
| **E** | **Expected Outcome** | **Beklenen Sonuç** | Proje tamamlandığında **ne** elde edileceğini, başarı kriterlerini ve çıktıların (model, rapor, dashboard) formatını netleştirir. |


# 🛒 PACE Methodology in Practice: E-commerce Sales Forecasting

Imagine you are a data scientist at an e-commerce company tasked with forecasting sales for the holiday season. The following illustrates the application of the PACE framework to this scenario.

## Scenario: Holiday Season Sales Forecast 🎄

| PACE Element 🏷️ | Definition | Statement in the Context of the Project |
| :--- | :--- | :--- |
| **1. P (Purpose)** | **Definition:** This prediction model will be used to determine which products the company should stock and where marketing budgets should be allocated. | **Purpose Statement:** "To create a 3-month sales forecast at the SKU (Stock Keeping Unit) level to ensure stock optimization and accurate allocation of marketing expenditures during the holiday season." |
| **2. A (Approach)** | **Definition:** Which methods and data will be used to generate the forecast. | **Approach Statement:** "Utilize the past 3 years of sales data, seasonality indices, and competitor pricing data. Plan to use a **Prophet time series model** or develop an XGBoost regression that accurately captures seasonal components." |
| **3. C (Constraints)** | **Definition:** Factors that limit the project and affect its success. | **Constraint Statement:** "We have a maximum of 6 weeks for model development. The model must have **low latency** to run only on our existing servers. Furthermore, we cannot use customer personal data due to EU privacy regulations (GDPR)." |
| **4. E (Expected Outcome)** | **Definition:** The tangible output to be delivered upon project completion. | **Expected Outcome Statement:** "A model that outputs daily forecasts for the next 90 days for every SKU, operating with a Mean Absolute Error (MAE) of less than 10%. Model results will be published in a dedicated **Tableau Dashboard** for the Supply Chain Manager." |

---

## ✨ Benefits of Using PACE for a Data Scientist 🧠

The PACE framework provides a Data Scientist with crucial advantages:

* **Alignment:** Ensures you are on the same page with stakeholders from the start and manage expectations correctly.
* **Focus:** Prevents scope creep throughout the project duration, directing time and resources straight toward the objective.
* **Error Reduction:** Pre-defining constraints (C) helps you spot ethical or technical errors early in the project.
* **Success Measurement:** Allows you to measure success objectively using defined criteria (E).


# 🚀 Applying the PACE Framework in Business Intelligence (BI)

Here’s a real-life example that illustrates how the **PACE** framework can be applied in a **Business Intelligence Analyst** role for a new product launch. 

---

## Example: Launching a New Product 💡

### Plan Stage (P) 📝

As a business intelligence analyst, you start by defining the scope of the project to launch a new product. You gather information on market trends, customer needs, and competitor analysis.

* **Questions to consider:** What are the goals of the product launch? What strategies will be needed to reach the target audience? What are the expected business impacts?

---

### Analyze Stage (A) 🔍

You collect data from various sources, such as customer surveys, sales data, and market research reports.

* You clean and organize this data, then conduct **exploratory data analysis (EDA)** to identify patterns and insights that could inform the product features and marketing strategies.

---

### Construct Stage (C) 🏗️

Based on the insights from your analysis, you collaborate with product managers and marketing teams to develop a prototype of the product.

* You might also work with data scientists to build **predictive models** that forecast sales and customer engagement.

---

### Execute Stage (E) 🎯

Finally, you present your findings and recommendations to stakeholders, including the marketing team and upper management.

* You share insights on the expected performance of the product and suggest strategies for a successful launch, while also being open to feedback and ready to iterate on your plans.

---

## Relevance to You: The BI Analyst Role 🧑‍💼

This example is relevant because it showcases how the PACE framework can guide you through a structured approach to project management in your role as a **business intelligence analyst**. By following these stages, you can ensure that you are not only prepared but also adaptable to changes and feedback, which is crucial in a dynamic business environment.




# 🔬 Advanced Data Science Application Reflection

## **Scenario & Prompt Summary**

**Scenario:** Advanced data analytics and data science are used to solve complex, real-world problems and help businesses gain a competitive edge. These solutions go beyond basic data summaries and visualizations.

**Prompt:** Reflect on a real-world problem you think advanced data science could solve. Then, complete the following:
1. Describe a real-world problem that you believe requires advanced data analysis to solve.
2. Identify one specific advanced data concept (e.g., predictive modeling, machine learning, deep learning) that would be necessary to solve this problem.
3. Explain why this advanced concept is required and how it goes beyond what can be accomplished with basic data analytics tools like spreadsheets.
4. Describe one potential ethical consideration or bias you might need to address when working on this problem.

---

## **Answer: Dynamic Pricing Optimization**

### **1. 🍎 Real-World Problem Requiring Advanced Data Analysis**

The problem is **Optimizing Dynamic Pricing and Inventory Allocation for Perishable Goods** in the e-commerce grocery sector.

* **Description:** Grocery retailers struggle to simultaneously maximize revenue and minimize **waste (shrinkage)** for highly perishable items (e.g., fresh produce, baked goods). This requires continuously adjusting prices and warehouse inventory levels based on unpredictable variables like supplier fluctuations, local weather, competitor pricing, and, crucially, the rapidly approaching expiration dates. Basic static pricing or simple moving averages are ineffective against this highly dynamic and high-stakes problem.

---

### **2. 🧠 Specific Advanced Data Concept**

The necessary advanced data concept is **Reinforcement Learning (RL)**.

---

### **3. ⚙️ Why this Advanced Concept is Required**

**Reinforcement Learning (RL)** is essential because the problem involves **sequential decision-making under uncertainty** in a dynamic environment, which goes far beyond static analysis.

* **Why RL is required:** Traditional predictive modeling (like standard regression) can forecast demand or waste, but it cannot actively suggest the **optimal action** (e.g., "reduce price by 15% AND move 50 units to a specific store location") and learn from the subsequent revenue/waste outcomes. RL uses an **agent** (the pricing/inventory model) that interacts with an **environment** (the market/warehouse system). The agent receives a **reward** (e.g., high profit, low waste) or a penalty for its actions and adjusts its strategy over time to **maximize the cumulative reward**. This adaptive, trial-and-error, self-optimizing nature is indispensable for dynamic pricing/inventory.
* **Beyond Basic Analytics:** Spreadsheets can calculate past profit margins or display historical sales trends. They **cannot** simulate future market states, explore billions of possible pricing/inventory combinations, or iteratively learn the best policy (sequence of actions) to execute in real-time, which is the core capability of an RL-based solution.

---

### **4. ⚖️ Potential Ethical Consideration or Bias**

A critical ethical consideration is **Algorithmic Price Discrimination and Fairness Bias**.

* **Bias Description:** The RL agent might inadvertently learn that certain demographic areas (e.g., lower-income neighborhoods) are less price-sensitive or have fewer competing options, leading it to consistently recommend **significantly higher prices** in those locations compared to wealthier areas, thereby creating or exacerbating **economic inequity**.
* **Addressing the Bias:** To mitigate this, **fairness constraints** must be explicitly integrated into the RL model's reward function. For instance, the model could be penalized if the pricing disparity between predefined socioeconomic regions exceeds a certain threshold, forcing the algorithm to prioritize **fairness** alongside profit maximization.

---

## 1. 🍎 Real-World Problem Requiring Advanced Data Analysis

The problem is **Optimizing Dynamic Pricing and Inventory Allocation for Perishable Goods** in the e-commerce grocery sector.

* **Description:** Grocery retailers struggle to simultaneously maximize revenue and minimize **waste (shrinkage)** for highly perishable items (e.g., fresh produce, baked goods). This requires continuously adjusting prices and warehouse inventory levels based on unpredictable variables like supplier fluctuations, local weather, competitor pricing, and, crucially, the rapidly approaching **expiration dates**. Basic static pricing or simple moving averages are ineffective against this highly dynamic and high-stakes problem.

---

## 2. 🧠 Specific Advanced Data Concept

The necessary advanced data concept is **Reinforcement Learning (RL)**.

---

## 3. ⚙️ Why this Advanced Concept is Required

**Reinforcement Learning (RL)** is essential because the problem involves **sequential decision-making under uncertainty** in a dynamic environment, which goes far beyond static analysis.

* **Why RL is required:** Traditional predictive modeling (like standard regression) can forecast demand or waste, but it cannot actively suggest the **optimal action** (e.g., "reduce price by 15% AND move 50 units to a specific store location") and learn from the subsequent revenue/waste outcomes. RL uses an **agent** (the pricing/inventory model) that interacts with an **environment** (the market/warehouse system). The agent receives a **reward** (e.g., high profit, low waste) or a penalty for its actions and adjusts its strategy over time to **maximize the cumulative reward**. This adaptive, trial-and-error, self-optimizing nature is indispensable for dynamic pricing/inventory.
* **Beyond Basic Analytics:** Spreadsheets can calculate past profit margins or display historical sales trends. They **cannot** simulate future market states, explore billions of possible pricing/inventory combinations, or iteratively learn the best policy (sequence of actions) to execute in real-time, which is the core capability of an RL-based solution.

---

## 4. ⚖️ Potential Ethical Consideration or Bias

A critical ethical consideration is **Algorithmic Price Discrimination and Fairness Bias**.

* **Bias Description:** The RL agent might inadvertently learn that certain demographic areas (e.g., lower-income neighborhoods) are less price-sensitive or have fewer competing options, leading it to consistently recommend **significantly higher prices** in those locations compared to wealthier areas, thereby creating or exacerbating **economic inequity**.
* **Addressing the Bias:** To mitigate this, **fairness constraints** must be explicitly integrated into the RL model's reward function. For instance, the model could be penalized if the pricing disparity between predefined socioeconomic regions exceeds a certain threshold, forcing the algorithm to prioritize **fairness** alongside profit maximization.

---

# 📊 Geniş (Wide) ve Uzun (Long) Veri Açıklaması

Bir veri kümesinin geniş veya uzun formatta olması, veriyi organize etme şeklimizi belirtir.

| Özellik | ➡️ Geniş (Wide) Veri | ⬇️ Uzun (Long) Veri |
| :--- | :--- | :--- |
| **Temel Yapı** | Her satır bir gözlemi (subject) temsil eder. Değişkenler, farklı sütunlara dağılmıştır. | Her gözlem birden fazla satıra yayılmıştır. Bir sütun değişkenin adını, başka bir sütun ise o değişkenin değerini tutar. |
| **Örnek** | Bir kişinin adı ve o kişinin Ocak, Şubat ve Mart aylarındaki harcamaları **üç ayrı sütunda** (Ocak\_Harcama, Şubat\_Harcama, Mart\_Harcama) yer alır. | Aynı harcama verisi, tek bir "Harcama" sütununda yer alır, ancak harcamanın hangi aya ait olduğunu belirten ek bir "Ay" sütunu bulunur. Bu, bir kişi için **üç ayrı satır** (Ocak, Şubat, Mart) anlamına gelir. |
| **Sütun Sayısı** | Yüksek | Düşük |
| **Satır Sayısı** | Düşük | Yüksek |
| **Kullanım Alanı** | İstatistiksel yazılımlarda (SPSS gibi) veya veri girişi için daha yaygın. | Görselleştirme (Tableau, ggplot2) ve çoğu modern analiz kütüphanesi (R, Python) için ideal ve gereklidir. |

---

# 💾 Yapılandırılmış Veri Açıklaması

**Yapılandırılmış Veri (Structured Data)**, kolayca tanımlanabilen ve organize edilebilen, genellikle satır ve sütun formatında düzenlenmiş verilerdir. Bu veriler, ilişkisel veritabanı yönetim sistemleri (RDBMS) tarafından kolayca işlenebilir ve aranabilir. Yapılandırılmış verinin temel özellikleri şunlardır:

* **Önceden tanımlanmış bir şemaya (schema) veya modele sahiptir.**
* **Genellikle sayısal değerler veya net kategorik (metinsel) değerler içerir.**
* **SQL kullanılarak kolayca sorgulanabilir.**

---

# 🎯 SMART Metodolojisi ve Değişim Açıklaması

SMART, hedeflerin belirlenmesinde kullanılan bir kısaltmadır ve genellikle şunları temsil eder:

* **S**pecific (Spesifik/Belirli)
* **M**easurable (Ölçülebilir)
* **A**chievable (Ulaşılabilir)
* **R**elevant (İlgili)
* **T**ime-bound (Zamansal Sınırlı)

---

Veri analizi bağlamında, bir **SMART Sorusunun** amacı, net, ölçülebilir ve eyleme geçirilebilir bir yanıt alarak projenin ilerlemesini sağlamaktır. Değişime yol açan sorular, bir durumun sadece tanımlanmasından ziyade, **ne yapılacağını** sormaya odaklanmalıdır.

# 📈 Metrik (Metric) Açıklaması

**Metrik (Metric)**, bir iş sürecinin, ürünün veya hedefin ilerlemesini ve performansını izlemek ve değerlendirmek için kullanılan, **nicelleştirilmiş (ölçülebilir) bir değerdir**.

Metrikler, sadece ham veriler (**facts**) değil, bu ham verilerden türetilmiş, bağlamı olan ve anlamlı bir karşılaştırmaya olanak tanıyan hesaplamalardır.

---

### 📝 Örnek

| Kategori | Açıklama |
| :--- | :--- |
| **Ham Veri (Fact)** | Bir web sitesine gelen günlük ziyaretçi sayısı. |
| **Metrik** | **Dönüşüm Oranı (Conversion Rate)** = (Satın alma yapan ziyaretçi sayısı / Toplam ziyaretçi sayısı) &times; 100. |

## 📚 Course 1, Module 1: Temel Terimler ve Tanımlar

| Kavram | Açıklama |
| :--- | :--- |
| 🧑‍💻 **Data professional (Veri Profesyoneli)** | Veriyle çalışan ve/veya veri becerilerine sahip herhangi bir kişi. |
| 🔬 **Data science (Veri Bilimi)** | Veriyi kullanışlı hale getirme disiplini. |
| 🛡️ **Data stewardship (Veri Yönetimi)** | Bir kuruluşun verinin erişilebilir, kullanılabilir ve güvenli olmasını sağlayan uygulamaları. |
| 🌐 **Edge computing (Uç Bilişim)** | Hız ve esneklik için iyi olan ve tek bir hesaplama kaynağına bağlı olmayan, hesaplama görevlerini bir grup yakındaki işlemciye (yani, bilgisayarlara) dağıtma yöntemidir. |
| 📓 **Jupyter Notebook** | Canlı kod, denklemler, görselleştirmeler ve anlatı metinleri içeren belgeler oluşturmak ve paylaşmak için kullanılan açık kaynaklı bir web uygulaması. |
| 🤖 **Machine learning (Makine Öğrenimi)** | Bilgisayar sistemlerine verideki örüntüleri analiz etmeyi öğretmek için algoritmaların ve istatistiksel modellerin kullanılması ve geliştirilmesi. |
| 📉 **Metrics (Metrikler)** | Veriyi değerlendirmek için kullanılan yöntemler ve kriterler. |
| 🐍 **Python** | Genel amaçlı bir programlama dili. |

## 👥 Data Professional Roles Overview: A Career Map

| Role Category | 🎯 Key Focus (What They Do) | 🛠️ Methods (How They Do It) | 💼 Sample Job Titles |
| :--- | :--- | :--- | :--- |
| 📊 **Data Scientist & Data Analyst** | Uncover **trends, patterns, and insights** from data. These roles gather, clean, analyze, and share insights with stakeholders. | Employ **advanced modeling** and **statistical analytics** techniques. | Data Scientist, Marketing Analyst, Data Analyst, AI Analyst, Business Analyst. |
| ⚙️ **Data Management & Infrastructure** | Manage **data sources** and the overall **data infrastructure**. Ensure functionality of data systems and compliance with security/ethics regulations. | Work with the **tools and databases** used to manage data within a business. | Data Engineer, Technology Engineer, Data Manager, Data Steward, IT Architect. |
| 📈 **Business Intelligence (BI)** | Perform **predictive analysis** that enables organizations to determine likely future trends. Focus is on transforming relevant data into accessible channels. | Create **tables, reports, and dashboards** that empower stakeholders and inform the entire decision-making process continually. | BI Architect, BI Analyst, BI Solution Developer, BI Software Engineer, Data Viz & BI Analyst. |
| 💡 **Product Development Teams** | Manage **analytical strategy** within a project team. Manage a portfolio of customer and stakeholder analytic projects. | Less hands-on with data analysis, serving as the person a Data Scientist or Analyst would **report to** (management role). | Product Manager, Product Developer, Product Lead, Digital Product Manager, Customer Product Manager. |
| 👑 **C-Suite (Executives)** | Responsible for **data and data professionals** across an entire organization. Build data-driven decision-making into top-level processes. | They are **decision makers** found at the top end of a company’s hierarchy. | Chief Marketing Officer (CMO), Chief Data Officer (CDO), Chief Analytics Officer (CAO), Chief Information Officer (CIO), Chief Data Scientist. |

---

### Key Takeaways

* The data professional space is vast, offering a **wide variety of roles and responsibilities**.
* Understanding these roles helps inform your **job search** and clarifies company expectations.
* The trend is toward high-ranking executives (**C-suite**) being familiar with data and analytics to ensure **data-driven decision-making**.

* ## 🚀 Where Data Makes a Difference: Industries & Future Trends

---

### 🌐 Part 1: Industries Leveraging Data Analytics

| Industry | 📜 Overview | 📈 How Data Is Used |
| :--- | :--- | :--- |
| 📱 **App-driven business (Sharing Economy)** | Facilitates users acquiring, providing, or sharing access to goods and services, often through online or app-based communities. | Maintaining functioning mobile applications; Delivering customized content (e.g., discounts) based on user history; Using machine learning models to send notifications at key times or even locations. |
| 🚗 **Automotive** | Includes industries associated with the production, wholesaling, retailing, and maintenance of motor vehicles. | Gaining greater control over their supply chains; Improving production line performance; Designing new and more efficient vehicles; Enhancing vehicle safety and new features. |
| 🔒 **Cybersecurity** | Protects networks, devices, and data from unauthorized access or criminal use; maintaining confidentiality, integrity, and availability of information. | Locating weak points within networks and systems using predictive analytics; Defending against security attacks; Detecting data breaches through logic, models, and data tools; Improving the ability to identify attacks and respond to them with Artificial Intelligence (AI). |
| 📣 **Digital Marketing** | Assists in advertising and promotional efforts of companies using the internet and online technologies. | Translating customer interaction into actionable business data; Predicting user behaviors to personalize content and offers; Identifying patterns and trends that guide innovations; Determining the return on investment (ROI) of marketing efforts. |
| ⚡ **Energy** | Includes companies that explore, produce, refine, market, store, and transport both renewable and non-renewable energy resources. | Analyzing real-time data from power systems and monitoring devices; Optimizing technologies, monitoring power grids, and predicting failures; Preventing accidents and malfunctions. |
| 🎮 **Gaming** | Hosts an estimated 2.7 billion gamers worldwide, facilitating the interaction of players across the globe. | Designing world-building and character creation systems; Monitoring character engagement and how the environment reacts to player input; Optimizing game-play by identifying potential new features or upgrades; Regulating in-game purchases and fraud detection systems; Personalizing marketing campaigns. |
| 🎬 **Streaming Media & Entertainment** | Provides access to live and recorded content on-demand, delivered via the internet to computers, smart devices, and mobile devices. | Analyzing and monitoring user interactions to better understand customer sentiment; Matching users with advertisers with real-time analytics; Guiding future content decisions; Personalizing marketing campaigns. |
| 📞 **Telecommunications** | Primarily involves operating and providing access to facilities for the transmission of voice, data, text, sound, and video. | Assisting the deployment, optimization, and predictive maintenance of telecommunications networks; Optimizing pricing models; Targeting advertisement and incentive campaigns, as well as detecting fraudulent activity; Analyzing customer data to customize subscriber plans. |
| 🗺️ **Travel and Tourism** | Encompasses a variety of services from transportation, accommodations, attractions, booking, and much more. | Marketing to individuals based on their previous travel or searched destinations; Directing machine learning systems that can adjust a traveler’s itinerary based on set factors (e.g., weather and availability); Generating recommendations based on personal preferences and location-based discounts; Managing reservations and processing transactions. |

---

### 🔮 Part 2: Data Trends for the Future

| Concept | 💡 Key Trend / Innovation | 🔄 Impact on the Field |
| :--- | :--- | :--- |
| **Data Volume & Demand** | **Big data is getting bigger**; the need to understand, prioritize, manage, and analyze information is not slowing down in any industry. | Businesses will continue to rely on **data-driven decision-making**, fueled by simple trend analyses and complex techniques (predictive modeling, forecasting). |
| **Data Repositories** | More companies are storing **all of their raw data** within large repositories accessible across the organization. | Creates opportunities for data professionals to use skills to **organize information and make it useful**. |
| **Artificial Intelligence (AI)** | AI will continue to have a large impact on business, helping to streamline many areas. | Helps companies ensure warehouse supply, keep items in stock, reduce delivery time, and **boost operational efficiency** through automating processes. |
| **Personalization** | AI will combine with machine learning, business intelligence, and automation to deliver **more personalized services to customers**. | Pushes forward innovation, bringing computer applications and stored data sources **physically closer together**. |
| **💻 Edge Computing** | Bringing computer applications and the sources of stored data closer together physically to **close the gap between data and computation**. | **Speed improves**, resulting in greater support of **real-time analytics** and automation necessary to support the increasing number of devices linked through the **Internet of Things (IoT)**. |
| **Automation** | An increasing number of data analytics tasks will be **automated** by creating, managing, and analyzing data in edge environments. | Requires data professionals to focus on the **equity and inclusiveness** of the systems they create and train. |

---

### Key Takeaways for Data Professionals

* You must **stay up-to-date** with the latest trends and technologies across different industries.
* The certainty of the future is that an **increasing amount of data** will be generated, and **new systems and innovations** will continue to be developed.
* This presents a constant opportunity for data professionals to **learn, grow, and develop new skills**.


# 📚 Veri Bilimi ve Analitik Terimleri Sözlüğü

Bu tablo, Veri Bilimi ve Analitik alanındaki temel terimleri ve tanımlarını organize etmektedir.

| Terim (İngilizce) | 💡 Açıklama (İngilizce) |
| :--- | :--- |
| **Aggregate information** | Data from a significant number of users that has eliminated personal information. |
| **Artificial intelligence (AI)** | Refers to computer systems able to perform tasks that normally require human intelligence. |
| **Data anonymization** | The process of protecting people's private or sensitive data by eliminating PII. |
| **Data professional** | Any individual who works with data and/or has data skills. |
| **Data science** | The discipline of making data useful. |
| **Data stewardship** | The practices of an organization that ensure that data is accessible, usable, and safe. |
| **Edge computing** | A way of distributing computational tasks over a bunch of nearby processors (i.e., computers) that is good for speed and resiliency and does not depend on a single source of computational power. |
| **Hackathon** | An event where programmers and data professionals come together and work on a project. |
| **Jupyter Notebook** | An open-source web application used to create and share documents that contain live code, equations, visualizations, and narrative text. |
| **Machine learning** | The use and development of algorithms and statistical models to teach computer systems to analyze patterns in data. |
| **Metrics** | Methods and criteria used to evaluate data. |
| **Nonprofit** | A group organized for purposes other than generating profit; often aims to further a social cause or provide a benefit to the public. |
| **Open data** | Data that is available to the public and free to use, with guidance on how to navigate the datasets and acknowledge the source. |
| **Personally identifiable information (PII)** | Information that permits the identity of an individual to be inferred by either direct or indirect means. |
| **Python** | A general-purpose programming language. |
| **Sample** | A segment of a population, often used to infer parameters of the whole population. |
| **Tableau** | A business intelligence and analytics platform that helps people visualize, understand, and make decisions with data. |

---

# 🛠️ Data Tools Today: Essential Skills for Data Professionals

This table outlines the core tools and skills necessary for data professionals, covering everything from spreadsheets to machine learning languages and dashboards.

| Tool 🔧 | Definition | Examples | Transferable Skills |
| :--- | :--- | :--- | :--- |
| **Spreadsheets** 📊 | A digital worksheet where data can be manipulated and used for calculations. | * Google Sheets<br>* Microsoft Excel | * Data entry<br>* Mathematical calculations<br>* Manage datasets<br>* Task automation<br>* Data manipulation<br>* Data analysis |
| **Databases** 💾 | A collection of data stored in a computer system. | * Google Cloud SQL<br>* CloudSQL<br>* Oracle<br>* Microsoft SQL Server | * Database design<br>* Data storage management<br>* Data integrity |
| **Programming Languages** 💻 | A system of words and symbols used to write instructions that computers follow. | * SQL<br>* R<br>* Python<br>* Java<br>* C++ | * Communicate with computer systems<br>* Write and input commands<br>* Manage datasets<br>* Data manipulation<br>* Data analysis |
| **Data Visualization** 📈 | The graphical representation of data. | * Tableau<br>* matplotlib<br>* Seaborn<br>* Google Charts<br>* Infogram<br>* Chartricks | * Communicate data insights<br>* Design compelling visuals<br>* Identify key metrics |
| **Dashboards** ⏱️ | A tool that monitors live, incoming data. | * Tableau<br>* LookerStudio<br>* Microsoft Power BI | * Communicate data insights<br>* Monitor real-time data<br>* Develop data visualizations<br>* Design filters and custom calculations |

# 🚀 Useful Prompts for Data Science Workflows

Large Language Models (LLMs) are becoming powerful tools to automate and enhance various stages of the data science process. Here are some examples of how LLMs can be utilized:

| Workflow Stage 🛠️ | LLM Capability & Description | Example Prompt Usage |
| :--- | :--- | :--- |
| **Data Cleaning** 🧹 | LLMs can automate tasks such as data cleaning and coding. | "For example, you can ask an LLM to clean a dataset by removing missing values, outliers, and duplicate data." |
| **Exploratory Data Analysis (EDA)** 🔍 | LLMs can perform exploratory data analysis (EDA) on datasets. | "For example, you can ask an LLM to create data visualizations, identify patterns and trends, and calculate summary statistics." |
| **Modeling** 🤖 | LLMs can build and evaluate models. | "For example, you can ask an LLM to build a machine learning model to predict an outcome, and evaluate the performance of the model." |
| **Interpreting Results** 🧠 | LLMs can interpret the results of models. | "For example, you can ask an LLM to explain the features that are most important for a model, or generate insights from the results of a model." |
| **Collaboration** 🤝 | LLMs can help you collaborate with teammates. | "For example, you can ask an LLM to create a shared document for a brainstorming session with a team of data professionals." |


# ✍️ Best Practices for Writing Effective LLM Prompts

Crafting high-quality prompts is essential to getting the most accurate and useful responses from Large Language Models (LLMs). Follow these best practices to optimize your data science workflows:

---

## General Prompting Guidelines

| Guideline ✨ | Description | Why It Matters |
| :--- | :--- | :--- |
| **Be Clear and Concise** | It is important to be clear and concise in your instructions so the LLM can understand how to help you. Details are great—just make sure they’re useful and relevant. Avoid giving the LLM unnecessary information. | Clarity minimizes misunderstanding and generates relevant output. |
| **Be Precise** | When posing a question to an LLM, be precise about the input (if any) and the desired output. | Specificity ensures the LLM focuses on the exact task and delivers the required format (e.g., Python code, JSON, or plain text). |
| **Include a Role Description** | Include a description of the LLM’s role. This reinforces the purpose of your prompt. | Framing the LLM as an expert (e.g., "Act as a data scientist") influences the **tone, vocabulary, and relevance** of the generated response. |
| **Provide Context** | Providing context allows the LLM to understand the nuances of the relevant issue and generate more informed responses. | Context helps the model avoid generic answers and tailor its output to your specific scenario. |
| **Try Multiple Prompts** | Trying different prompts can provide different perspectives on a problem and enable the LLM to generate a variety of useful responses. | Testing variations helps you converge on the most effective instruction set for complex tasks. |

---

## Specific Prompt Examples for Data Professionals 📊

| Example Prompt | LLM's Role | Core Task |
| :--- | :--- | :--- |
| **"Act as a data scientist and write a detailed plan for a credit card fraud detection project.”** | Data Scientist | Project planning and strategy. |
| **“I have a dataset of customer purchases at an online retail store. Act as a data scientist and write Python code for data visualization and exploration.”** | Data Scientist | Exploratory data analysis (EDA) and code generation. |
| **“I have a dataset of customer characteristics and churn for an online video streaming service. Act as a data scientist and create a shared document for a team meeting.”** | Data Scientist | Team collaboration and documentation structure. |
| **“Act as a data generator and use Python code to generate a CSV file that contains mock employee data for a restaurant chain named Fast. The dataset has 100 rows and 5 columns. The columns are name, address, employee\_id, department\_id, email.”** | Data Generator | Mock data creation and synthetic dataset generation. |
| **“Act as a communications expert and share best practices for explaining a data science report to a business executive with no technical background.”** | Communications Expert | Translating complex technical findings into business insights. |

# 💡 Workplace Scenario: Using Gemini for Data Science Workflows

This document outlines a fictional data project scenario at a healthcare company and provides examples of practical prompts a new data professional can give to Gemini (or another LLM) at different stages of the project.

## 🏥 Scenario Context

**Company:** A healthcare company selling sustainable medical devices to hospitals and clinics in urban communities.

**Goal:** Develop a machine learning model to accurately predict future sales to inform inventory management, resource allocation, and overall sales strategy.

---

## Data Project Stages and LLM Prompts

| Project Stage 🎯 | Task Description | Prompt Given to Gemini 🗣️ |
| :--- | :--- | :--- |
| **Project Proposal (Kickoff)** | The manager asks the new data professional to organize a kickoff meeting and needs help creating a document to outline the project workflow and timeline. | **Ask Gemini for instructions to create a shared document to facilitate a brainstorming session among a team of data professionals.** |
| **Data Cleaning** 🧹 | The team has collected the relevant data, and the next step is cleaning the dataset using Python. The new professional volunteers for this task and needs coding suggestions. | **Ask Gemini to write Python code to clean data by removing missing values, outliers, and duplicate data.** |
| **Data Visualization** 📈 | The team needs to explore and visualize the data to better understand the relationships between key sales variables. | **Ask Gemini to suggest useful data visualizations for sales data.** |
| **Build & Test ML Models** 🤖 | Although not directly involved in writing the ML code, the new professional wants to learn more about the use of machine learning for future career development and better project understanding. | **Ask Gemini about the main uses and benefits of machine learning for data work.** |
| **Executive Summary** 💼 | The model is successful. The new professional is asked to help draft an executive summary for a meeting with non-technical company leadership and needs best practices for creation. | **Ask Gemini about best practices for creating an executive summary for business executives without a technical background.** |

---

## ⚠️ Important Note: LLM Limitations

It’s crucial to remember that Gemini and other LLMs are not infallible. As a data professional, it is your responsibility to verify the accuracy and suitability of any output generated by these tools.

| Limitation | Description |
| :--- | :--- |
| **Infallibility** | Gemini can sometimes make mistakes, such as providing inaccurate information or generating incorrect code. |
| **Expertise** | Gemini is not an expert in any particular field. It does not have the same level of understanding as an experienced human data professional. |
| **Reasoning** | Gemini cannot fully explain its reasoning (why it’s doing what it’s doing), which can make it difficult to fully trust its results without verification. |
| **Bias** | As an LLM, Gemini is trained on a massive dataset of text and code, and it is likely to reflect the biases that are present in that dataset. |


# 🧑‍💻 Essential Data Team Roles and Terms

This table provides key terms and definitions frequently used in data professions, covering roles, core concepts, and collaboration tools.

---

## Data Roles and Leadership 👑

| Term 👤 | Definition | Key Responsibility |
| :--- | :--- | :--- |
| **Chief Data Officer (CDO)** | An executive-level data professional who is responsible for the consistency, accuracy, relevancy, interpretability, and reliability of the data a team provides. | Data quality and reliability at the executive level. |
| **Analytics Team Manager** | A data professional who supervises analytical strategy for an organization, often managing multiple groups. | Analytical strategy and team oversight. |
| **Data Scientist** | A data professional who works closely with analytics to provide meaningful insights that help improve current business operations. | Generating meaningful insights for business improvement. |
| **Data Engineer** | A data professional who makes data accessible, ensures data ecosystems offer reliable results, and manages infrastructure for data across enterprises. | Data accessibility and infrastructure management. |
| **Business Intelligence Engineer (or Analyst)** | A data professional who uses their knowledge of business trends and databases to organize information and make it accessible; also referred to as a Business Intelligence Analyst. | Organizing and visualizing business data. |

---

## Core Concepts and Collaboration Tools 🤝

| Term 🧠 | Definition | Context |
| :--- | :--- | :--- |
| **Data Cleaning** 🧼 | The process of formatting data and removing unwanted material. | Ensuring data quality and usability. |
| **Active Listening** | Refers to allowing team members, leadership, and other collaborative stakeholders to share their own points of view before offering responses. | Effective communication and collaboration. |
| **Interpersonal Skills** | Traits that focus on communicating and building relationships. | Team dynamics and stakeholder management. |
| **RACI Chart** 📝 | A visual that helps to define roles and responsibilities for individuals or teams to ensure work gets done efficiently; lists who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for project tasks. | Project management and efficiency. |


----

# Data Professionals İçin İletişim Mimarisi ve En İyi Uygulamalar

> **Özet:** Bu doküman, Veri Bilimi projelerinde (özellikle PACE döngüsü içerisinde) teknik çıktıların paydaşlara aktarılması, sunum teknikleri ve iletişim stratejilerini ele alır. Zaman serisi analitiği gibi karmaşık alanlarda teknik jargon ile iş hedefleri arasındaki köprüyü kurmak için hazırlanmıştır.

## 1. Giriş: İletişim Neden PACE'in Yakıtıdır?

[cite_start]Veri projelerinde **PACE** (Planlama, Analiz, Oluşturma, Yürütme) aşamalarının her birinde iletişim kritik bir rol oynar. Bir zaman serisi projesinde "Planlama" aşamasında mevsimselliği (seasonality) anlamak için alan uzmanlarıyla konuşmak ne kadar önemliyse, "Yürütme" aşamasında modelin tahmin aralığını (confidence interval) yönetime sunmak da o kadar kritiktir. [cite_start]İletişim becerisi, teknik yeteneklerinizle birleştiğinde kariyer başarısını belirler.

## 2. Etkili İletişim İçin 7 Temel Prensip (Teknik Derinlik Eklenmiş)

Bir veri profesyonelinin günlük iş akışında e-postalar, toplantılar ve sunumlar yer alır. [cite_start]İşte bu etkileşimleri optimize etmek için 7 kural:

### 2.1. Hedef Kitlenin Dilini Konuşun (Speak the language of your audience)
[cite_start]Paydaşınızın teknik derinliğini analiz edin. Bir CTO ile konuşurken "Modelin MAPE değeri %5" diyebilirsiniz, ancak Pazarlama Müdürü ile konuşurken "Tahminlerimiz %95 oranında isabetli" demelisiniz.
* [cite_start]**Soru:** Paydaş bu etkileşimden ne bekliyor? 
* [cite_start]**Strateji:** Teknik konseptleri basitleştirin (örn: "Hiperparametre optimizasyonu" yerine "Ayarların ince ayarı").
* [cite_start]**Pro Tip:** Jargon, kısaltmalar (örneğin: "Heteroskedastisite var") ve teknik "moda sözcüklerden" kaçının.

### 2.2. Soruları Davet Edin ve Geri Bildirimi Kucaklayın
Geri bildirim (Feedback), modelinizdeki "Loss Function" gibidir; hatanızı minimize etmenizi sağlar.
* [cite_start]Tutkunuzu proje hedefleriyle birleştirin.
* **Analiz:** Gelen geri bildirim geçerli mi? Paydaş veri analitiği sürecini tam anlamış mı? [cite_start]Eğer anlamadıysa, ek bir toplantı ile (örneğin modelin varsayımlarını açıklamak için) netleştirin.

### 2.3. Veri ile Bağlantı Kurun (Be the connection to the data)
[cite_start]Siz, ham veri yığınları ile işgörü (insight) arasındaki köprüsünüz.
* [cite_start]Verinin hikayesini, kopuk olmayan bir anlatı (narrative) ile sunun.
* **Zaman Serisi Örneği:** Sadece "Satışlar düşecek" demeyin; "Geçmiş 3 yılın trend verisine ve mevsimsel etkilere dayanarak, önümüzdeki çeyrekte %10 daralma öngörüyoruz" diyerek veriyi konuşturun.

### 2.4. Görselleştirmelerin Hikaye Anlatmasına İzin Verin
[cite_start]Büyük veri (Big Data) ile çalışırken görselleştirme en güçlü silahtır.
* [cite_start]**Erişilebilirlik:** Renk körü dostu paletler kullanın, yüksek kontrast sağlayın.
* **Sadeliği Koruyun:** Grafikleri karmaşıklaştırmayın. [cite_start]Bir grafikte sadece tek bir ana fikir olmalıdır.
* [cite_start]**Etiketleme:** Metinleri, grafiği boğmak için değil, netleştirmek için kullanın.

### 2.5. Pozitif Profesyonel İlişkiler Kurun
[cite_start]Güvenilir bir "Konu Uzmanı" (SME - Subject Matter Expert) olun.
* [cite_start]İnsanların sorumluluklarını ve hedeflerini dikkate almak, iş yerinde itibarınızı artırır.
* [cite_start]Ulaşılabilir ve ilgili olun.

### 2.6. Veri Varsayımlarını Tanımlayın (Identify Assumptions)
[cite_start]*Burası teknik olarak kritik bir bölümdür.* Veri içindeki önyargıları (bias) ve varsayımları tespit etmelisiniz.
* [cite_start]**Genel Soru:** "Neyi kanıksıyorum?" veya "Hangi önyargıya sahibim?".
* **Teknik Ekleme (Time-Series):** Verinin "Durağan" (Stationary) olduğunu mu varsayıyorsunuz? Geçmişteki bir anomalinin (örn. COVID dönemi verisi) gelecekte tekrar etmeyeceğini mi varsayıyorsunuz? Bu varsayımları paydaşlara şeffafça açıklayın.

### 2.7. Veri Kısıtlamalarını Tanımlayın (Identify Limitations)
[cite_start]Analizi engelleyebilecek sınırları belirleyin ve iletin.
* Veri seti tamamlanmış mı? [cite_start]Eksik değerler (missing values) var mı? 
* [cite_start]Örneklem büyüklüğü (sample size) tüm popülasyonu temsil ediyor mu? 
* [cite_start]Kişisel Verilerin Korunması (PII - Personally Identifiable Information) ihlali var mı? 
* **Teknik Ekleme:** Modelin tahmin ufkundaki (forecast horizon) belirsizliğin zamanla arttığını (varyansın büyümesi) paydaşlara mutlaka belirtin.

---

## 3. Bulguları Paylaşma ve Sunum Mimarisi

[cite_start]Bulguları paylaşmak, analiz sonuçlarını daha geniş kitleler için "tercüme etmek" anlamına gelir.

### Sunum Stratejileri
1.  [cite_start]**Hiyerarşi:** En önemli bilgi en üstte ve erişilebilir olmalı, detaylar için alt katmanlara inilmelidir.
2.  [cite_start]**Basitlik:** Görsel olarak çekici ama basit bir tasarım her zaman en iyisidir.
3.  [cite_start]**Hikaye Yapısı:** Sunumunuzun bir başı, ortası ve sonu olmalıdır. [cite_start]Slaytlar senaryo metni değildir; paragrafları slaytlara kopyalamayın.
4.  [cite_start]**Odak:** Her bir grafikte "Aha!" anlarını (önemli içgörü bölgelerini) görsel olarak vurgulayın.

---

## 4. Karşılaştırmalı Analiz: Teknik vs. Stratejik İletişim

| Özellik | Teknik İletişim (Ekip İçi) | Stratejik İletişim (Paydaşlar/Yönetim) |
| :--- | :--- | :--- |
| **Odak** | Algoritmalar, Hiperparametreler, Veri Temizliği | ROI (Yatırım Getirisi), İş Hedefleri, Riskler |
| **Dil** | Python, SQL, İstatistiksel Jargon (P-value, RMSE) | Doğal Dil, İş Dünyası Terimleri (KPI, Büyüme) |
| **Görsel** | Scatter plotlar, Residual analizleri, Loglar | Trend çizgileri, Bar chartlar, Dashboardlar |
| **Amaç** | Modeli optimize etmek, hatayı çözmek | Karar almayı sağlamak, bütçe onayı almak |
| **PACE Aşaması** | Analyze & Construct | Plan & Execute |

---

## 5. Sonuç ve Temel Çıkarımlar

Etkili iletişim, veri profesyonelleri için bir lüks değil, zorunluluktur. [cite_start]Rolünüz; veri, teknoloji ve paydaşlar arasındaki bağlantıyı kurmaktır.

* [cite_start]**Görselleştirme:** Karmaşık veriyi anlaşılır kılmak için araçtır.
* [cite_start]**Kitle Farkındalığı:** Kiminle konuştuğunuzu bilin ve dili ona göre ayarlayın.
* [cite_start]**Sınırlamalar:** Verinin ve modelin sınırlarını dürüstçe paylaşın.

> *Unutmayın: En iyi model, kimsenin kullanmadığı değil, işletmenin kararlarını iyileştiren modeldir.*


# Detaylı Analiz: Veri Biliminde İletişim Stratejileri
> **Bağlam:** Bir Zaman Serisi Uzmanı (Time Series Expert) perspektifinden iletişim yöntemlerinin pratik uygulaması.

Aşağıdaki analiz, iletişim becerilerinin teknik süreçlere nasıl entegre edildiğini; nerede, ne amaçla ve hangi yöntemlerle kullanıldığını detaylandırır.

---

## 1. Nerede Kullanılır? (Context)
Bu iletişim yöntemleri, **PACE** (Plan, Analyze, Construct, Execute) modelinin her aşamasında kritik bir rol oynar:

* **Plan (Planlama):**
    * İş birimleri (Business Units) ile hedefleri belirlerken kullanılır.
    * *Örnek:* "Stok optimizasyonu (Inventory Optimization) mu yapacağız yoksa sadece talep tahmini (Demand Forecasting) mi?" sorusunun yanıtını ararken.
* **Analyze (Analiz):**
    * Verideki gürültüyü (Noise) veya eksiklikleri (Missing Values) veri mühendislerine (Data Engineers) raporlarken kullanılır.
* **Construct (Oluşturma):**
    * Modelin başarısını, örneğin Doğruluk (Accuracy) oranlarını, teknik lidere (Tech Lead) sunarken kullanılır.
* **Execute (Yürütme):**
    * Sonuçları ve işe etkisini C-Level (Üst Yönetim) yöneticilere sunarken kullanılır.

## 2. Ne Amaçla Kullanılır? (Purpose)

* **Güven İnşası (Trust Building):**
    * "Black Box" (Kara Kutu) modeller yerine, mantığı açıklanabilir modeller (Explainable AI - XAI) sunarak paydaşların yapay zekaya güvenmesini sağlamak.
* **Risk Yönetimi (Risk Management):**
    * Metinde belirtilen "Varsayımları ve Kısıtlamaları Tanımlama" (Identifying Assumptions & Limitations) maddesi hayati önem taşır. Gelecekte model başarısız olduğunda (örneğin pandemi gibi beklenmedik bir durumda - *Black Swan Event*) "Biz bunu öngörmemiştik" demek yerine, "Modelimizin kısıtları bunlardı, bu senaryo kapsam dışıydı" diyebilmek içindir.
* **Karar Destek (Decision Support):**
    * Yöneticilerin sadece ham veriye bakmasını değil, veriden aksiyon alınabilir içgörü (Actionable Insight) çıkarmasını sağlamak.

## 3. Hangi Yöntemlerle Kullanılır? (Methods)

* **Tableau / PowerBI (Görselleştirme Araçları):**
    * Görselleştirme maddesinde bahsedilen BI (Business Intelligence) araçlarıdır. Zaman serileri için interaktif panolar (Dashboard) hazırlayarak kullanıcının veriyi yakınlaştırıp uzaklaştırabilmesini (Zoom-in/Zoom-out) sağlamak.
* **Storytelling (Hikayeleştirme):**
    * Veriyi sadece "Geçen ay X oldu" diye sunmak yerine, nedensellik (Causality) bağlarıyla sunmak: *"X kampanyası nedeniyle Y artışı gözlemledik, bu da stoğu Z kadar eritti."*
* **Feedback Loops (Geri Bildirim Döngüleri):**
    * Sunum sonrasında paydaşlardan gelen soruları, yeni bir "Feature" (Öznitelik) olarak modele geri beslemek ve modeli iyileştirmek.

---

> **Sonuç:** Bu yapı, bir veri bilimcinin sadece kod yazan biri (Coder) değil, işletmeye yön veren stratejik bir danışman (Strategic Consultant) gibi konumlanmasını sağlar.


# Veri Profesyonelleri İçin Başarılı İletişim Mimarisi (Elements of Successful Communication)

> **Doküman Özeti:** Bu rehber, PACE (Plan, Analyze, Construct, Execute) döngüsünde veri profesyonellerinin paydaşlarla olan etkileşimini optimize etmek için hazırlanmıştır. [cite_start]İletişim, veri biliminde sadece "soft skill" değil, projenin başarısını belirleyen teknik bir parametredir[cite: 1].

## 1. Giriş: PACE Döngüsünde İletişimin Rolü
İletişim, PACE modelinin arkasındaki itici güçtür. Bir veri bilimci olarak sadece Python veya R bilmek yetmez; analizinizin sonuçlarını, engelleri ve veri hikayesini proje yaşam döngüsünün her aşamasında aktarabilmeniz gerekir.

## 2. İletişimin "Neden"ini Anlamak (Understanding Why)

İletişime başlamadan önce net bir vizyona sahip olmak şarttır. Sizin "neden"iniz, çalıştığınız işletmenin bağlamına ve projenin hedeflerine bağlıdır[cite: 1].

### Teknik Derinlik: İş Problemi Tanımı
Veri biliminde bu aşama, **Business Problem Definition** olarak adlandırılır. İletişiminizin amacı şunları netleştirmelidir:
* **Proje Hedefleri (Project Goals):** İletişimini kurduğunuz proje neyi başarmayı amaçlıyor? 
* **Beklenen Aksiyon (Call to Action):** Hedef kitlenizden ne yapmalarını istiyorsunuz? 
* **Kazanım (Gain):** Bu iletişimden ne elde etmeyi umuyorsunuz? 

> **Uzman Notu:** "Neden" sorusunu sormak, teknik borcu (Technical Debt) azaltır. Yanlış anlaşılmış bir hedef üzerine kurulan model, ne kadar doğru çalışırsa çalışsın, işletme için başarısızdır.

## 3. Sahneyi Ayarlamak (Set the Stage)

İletişim sadece "ne" söylediğinizle değil, "nerede" söylediğinizle de ilgilidir; ortam (setting), mesajın nasıl iletildiği ve şekillendirildiği üzerinde doğrudan etkiye sahiptir[cite: 1].



### Senaryo Bazlı İletişim Modelleri
Veri profesyonelleri farklı ortamlarda farklı stratejiler uygulamalıdır:

| Ortam (Setting) | Örnek Durum | İletişim Stratejisi |
| :--- | :--- | :--- |
| **Öğle Yemeği / Gayri Resmi** | Bir iş arkadaşından tavsiye istemek  | Samimi, düşük jargon, keşif odaklı. |
| **E-posta / Asenkron** | Paydaşlara proje güncellemesi geçmek  | Yapılandırılmış, net, belge niteliği taşıyan. |
| **Haftalık Toplantı (Stand-up)** | Ekiple ilerlemeyi paylaşmak | Hızlı, engel (blocker) odaklı, teknik detay içerebilen. |
| **Yönetim Kurulu (Boardroom)** | Analiz sonuçlarını sunmak | Sonuç odaklı (Result-oriented), stratejik, teknik detaydan arındırılmış. |

## 4. Zaman Yönetimi ve Verimlilik (All About Time)

Profesyonel dünyada zaman bir para birimidir; bu nedenle paydaşların mesajınızı hızlıca kavramasını sağlamak için verimli olmalısınız.

### Veri Bilimciler İçin "Clean Code" Gibi "Clean Communication"
Kodunuzu nasıl optimize ediyorsanız, iletişiminizi de optimize etmelisiniz:
* **Doğrudan Dil (Direct Language):** Gereksiz detaylardan kaçının ve dolaylı anlatımı bırakın.
* **Basitleştirme (Simplification):** Teknik dili ve jargonu (örneğin: "Multicollinearity sorunu var" demek yerine "Değişkenler birbirini tekrar ediyor") en aza indirin.
* **Parçalara Bölme (Chunking):** Karmaşık fikirleri daha kısa cümlelere bölerek anlaşılmasını ve hatırlanmasını kolaylaştırın.
* **Dil Bilgisi (Grammar):** Düzgün dil bilgisi ve noktalama işaretleri kullanın; bu, profesyonelliğin göstergesidir.

## 5. Birebir ve Küçük Gruplarda Çalışma

Bu ortamlar, genellikle "Code Review" seansları veya "Stakeholder Interview" (Paydaş Görüşmeleri) şeklinde gerçekleşir.
* **Zamana Saygı:** Toplantıyı önceden planlayarak meslektaşlarınızın zamanına saygı gösterin.
* **Hizalanma Kontrolü (Alignment Check):** Karşı tarafın anladığından emin olmak için sorular sorun.

## 6. Aktif Dinleme (Active Listening)

Bir veri profesyoneli olarak toplantılarda topladığınız bilgiler, modelinizin "Feature Engineering" (Öznitelik Mühendisliği) aşaması için ham maddedir.
* **Amaç:** Başkalarının bakış açısını anlamak ve daha iyi sorular sormak için çaba gösterin.
* **Empati ve Güven:** Aktif dinleme, iş arkadaşlarınızla bağlantı kurmanızı sağlar ve güveni teşvik eder.
* **Domain Knowledge (Alan Bilgisi):** İşletmenin nasıl çalıştığını ve hedeflerini anlamak için paydaşları aktif olarak dinlemeniz gerekir.

## 7. Soru Sorma Sanatı (Asking Questions)

Veri profesyonelleri otomatik çözüm makineleri değildir; etkili analiz için doğru soruları sormaları gerekir.

### Soru Sorma Stratejileri
* **Büyük Resim (Big Picture):** Projenin genel vizyonunu ortaya çıkaran sorular sorun.
* **Risk Azaltma (Risk Mitigation):** Doğru sorular, öngörülemeyen tuzakları ve tehlikeleri ortaya çıkararak iş risklerini azaltmaya yardımcı olabilir.
* **Yanlış Anlaşılmaları Giderme:** Belirsizlikleri netleştiren sorular sorun.
* **Tekrardan Kaçınma:** Daha önce cevaplanmamış sorulara odaklanın.

---

## 8. Karşılaştırmalı Analiz: Geleneksel vs. Modern Veri İletişimi

| Özellik | Geleneksel Yaklaşım | Modern Veri Profesyoneli Yaklaşımı |
| :--- | :--- | :--- |
| **Odak** | Teknik detaylar ve metodoloji. | İş değeri, "Neden" ve Hedef Kitle. |
| **Dinleme** | Cevap vermek için dinleme. | Anlamak ve empati kurmak için Aktif Dinleme (Active Listening). |
| **Soru Sorma** | Sadece teknik gereksinimleri sorma. | İş risklerini ve büyük resmi ortaya çıkaran sorular sorma. |
| **Zaman Kullanımı** | Uzun ve detaylı açıklamalar. |Kısa, öz ve verimli (Concise) iletişim. |

## Temel Çıkarımlar (Key Takeaways)

1. **Amaç (Purpose):** İletişiminizin "neden"ini anlayarak düşüncelerinizi organize edin.
2. **Ortam (Setting):** İletişimin gerçekleştiği bağlam (öğle yemeği vs. sunum), mesajın iletilme şeklini belirler.
3. **Soru Sorma:** Doğru sorular inovasyonu teşvik eder ve analitik süreci yönlendirir.
4. **Aktif Dinleme:** Paydaşların perspektifini anlamak, güven ve empati inşa eder.

---

# PACE Strateji Dokümanı: Veri Biliminde Yapılandırılmış Başarı ve Dokümantasyon

> **Özet:** Bu doküman, veri analitiği projelerinde yalnızca teknik kodlamanın değil, stratejik planlama ve iletişimin önemini vurgulayan **PACE Strateji Dokümanı**'nın (PACE Strategy Document) mimarisini, kullanım alanlarını ve kariyer gelişimine etkisini analiz eder.

## 1. PACE Strateji Dokümanı Nedir? (What is the PACE Strategy Document?)

PACE Strateji Dokümanı, **PACE** (Plan, Analyze, Construct, Execute) iş akışını uygularken size rehberlik etmek, ilerlemenizi kaydetmek ve düşünce süreçlerinizi yapılandırmak için tasarlanmış canlı bir kaynaktır. Bu doküman, sadece bir ödev veya kontrol listesi değil, veri analitiği sürecine yapı kazandıran temel bir araçtır.

### Neden İhtiyaç Duyulur? (Why is it Needed?)
Veri biliminde başarı, Python/R/SQL yeteneklerinin ötesindedir. Veri profesyonelleri genellikle organizasyonel karar alma süreçlerine dahil olurlar ve bulgularını çeşitli paydaşlarla (stakeholders) paylaşmak zorundadırlar.
* **İletişim Köprüsü:** Teknik analizler ile iş kararları arasındaki boşluğu doldurur.
* **Karar Destek Mekanizması:** Yönetici özetleri (executive summaries) oluşturarak karar vericileri bilgilendirmenizi sağlar.
* **Gelişim Takibi:** Yeni beceriler edinirken kişisel gelişiminizi ve proje ilerlemenizi izlemenize olanak tanır.

---

## 2. Dokümanın Anatomisi ve Bileşenleri (Components)

Her bir proje için özelleştirilmiş olsa da, PACE strateji dokümanları tutarlı bir yapıya sahiptir. Bir endüstri standardı olan "Design Doc" (Tasarım Dokümanı) ile benzerlik gösterir.

### 2.1. Talimatlar ve Proje Özeti (Instructions & Recap)
* **Amaç:** Proje hedeflerinin, o kursta edinilen bilgi ve becerilerle (Knowledge base) hizalanmasını sağlar.
* **İşlevi:** Hangi iş senaryosunu seçerseniz seçin, hedeflerin net kalmasını garanti eder.

### 2.2. İlgili Mülakat Soruları (Relevant Interview Questions)
Bu bölüm, teknik mülakatlara (Technical Interviews) hazırlık niteliğindedir.
* **Bağlam Oluşturma:** Veri görevleri etrafında bağlam kurarak, mülakatlarda karşılaşabileceğiniz soru tiplerine hazırlar.
* **Profesyonel Dil:** Kurs bitiminde bir veri profesyoneli gibi konuşabilme yetisi kazandırır.

### 2.3. Referans Rehberi (Reference Guide)
* Bu bölüm, projeyi tamamlamak için gereken görevlerin bir taslağını ve her bir görevin hangi PACE aşamasına (Plan, Analyze, Construct, Execute) karşılık geldiğini içerir.
* **Kariyer Değeri:** İleride iş hayatında benzer görevlerle karşılaştığınızda başvurabileceğiniz bir kılavuz görevi görür.

### 2.4. Veri Projesi Soruları ve Hususlar (Data Project Questions & Considerations)
Bu sorular, PACE iş akışının farklı aşamalarına özgüdür ve Jupyter Notebook'lardaki sorularla doğrudan eşleşir.
* **Düşünce Süreci Haritası:** Projenin her aşamasında zihinsel sürecinizi (Thought Process) haritalandırmanıza yardımcı olur.

---

## 3. Jupyter Notebook Entegrasyonu ve Sinerji

PACE strateji dokümanı ve Jupyter Notebook'lar (Kodlama Defterleri) birbirinden bağımsız değildir; birbirini tamamlar.
* **Ortak Sorular:** Her iki dokümanda da yer alan sorular, projenin en kritik noktalarını işaret eder.
* **Yürütme (Execute) Aşaması:** Kodlama (Notebook) ve Strateji (Doküman) birleştirilerek, paydaşlara sunulacak nihai **Yönetici Özeti** (Executive Summary) oluşturulur.

---

## 4. Detaylı Analiz: Endüstriyel Kullanım ve Yöntemler

Bir veri bilimi uzmanı olarak, bu dokümanın "gerçek dünya"daki (Real-world application) karşılığı ve teknik tamamlayıcıları şunlardır:

### Nerede Kullanılır? (Context)
* **Proje Başlangıç Toplantıları (Kick-off Meetings):** "Plan" aşamasındaki sorular, projenin kapsamını (Scope) belirler.
* **Kod İncelemeleri (Code Reviews):** "Reference Guide" bölümü, kodun iş mantığına uygunluğunu denetlemek için kullanılır.
* **Model Dokümantasyonu (Model Governance):** Modelin neden ve nasıl kurulduğuna dair "karar kayıtlarını" (Decision Logs) tutmak için kullanılır.

### Ne Amaçla Kullanılır? (Purpose)
* **Tekrarlanabilirlik (Reproducibility):** Sadece kodun değil, *kararların* da tekrarlanabilir olmasını sağlar.
* **Portföy Geliştirme (Portfolio Development):** Karar alma süreçlerinizi detaylı bir şekilde kaydederek, işverenlere gösterebileceğiniz güçlü ve markalı bir portföy oluşturmanızı sağlar.
* **Motivasyon:** Günlük ilerlemenin takibini zorlaştıran kademeli gelişim sürecinde, somut bir ilerleme kaydı tutarak motivasyon sağlar.

### Hangi Yöntemlerle Kullanılır? (Methods)
* **Yansıtıcı Sorgulama (Reflective Inquiry):** Dokümandaki sorular, analistin "Bu veriyi neden temizliyorum?" veya "Bu modeli neden seçtim?" gibi soruları kendine sormasını zorunlu kılar.
* **Meta-Data Yönetimi:** Proje hakkındaki üst verilerin (Meta-data) yönetimini sağlar.

---

## 5. Karşılaştırmalı Analiz: Kod Odaklı vs. Strateji Odaklı Yaklaşım

Aşağıdaki tablo, sadece kod yazmaya odaklanan bir yaklaşım ile PACE Strateji Dokümanı kullanan bir yaklaşım arasındaki farkı göstermektedir:

| Özellik | Sadece Jupyter Notebook (Kod Odaklı) | PACE Strateji Dokümanı + Notebook |
| :--- | :--- | :--- |
| **Odak** | Sözdizimi (Syntax), Hata Ayıklama (Debugging) | İş Problemi, Çözüm Mimarisi, İletişim |
| **İletişim** | Yorum satırları ile sınırlı (# comments) | Yapılandırılmış "Yönetici Özeti" ve anlatı |
| **Mülakat Hazırlığı** | Sadece teknik kodlama sorularına hazırlık | Hem teknik hem davranışsal/stratejik sorulara hazırlık |
| **Paydaş Değeri** | Düşük (Teknik olmayanlar anlamaz) | Yüksek (İş diliyle açıklanmış sonuçlar) |
| **Sürdürülebilirlik** | Kodu yazan gidince bilgi kaybolabilir | Karar süreçleri kayıt altına alındığı için kurumsal hafıza korunur |

---

## 6. Uzman Görüşü ve Temel Çıkarımlar (Key Takeaways)

PACE strateji dokümanı, veri analizi sürecini derinleştiren ve kişisel iş akışınıza (Personal Workflow) dair içgörü sağlayan kritik bir araçtır.

* **Portföyünüzün Bel Kemiği:** İyi bir portföy sadece bitmiş modelleri değil, o modellere giden yoldaki zorlu kararları da göstermelidir. Bu doküman o kararların kanıtıdır.
* **Mülakat Simülasyonu:** Dokümandaki soruları yanıtlamak, gerçek bir iş görüşmesinde projenizi savunmanın provasıdır.
* **Profesyonelleşme Adımı:** Bu dokümanı kullanmak, sizi "kod yazan öğrenci" statüsünden, "iş değeri üreten veri profesyoneli" statüsüne taşır.

  # PACE ve Yönetici Özetleri: Karar Vericiler İçin Veri İletişimi

> **Doküman Özeti:** Bu rehber, teknik veri projelerinin karmaşık çıktılarını, karar vericiler (Decision Makers) için anlaşılır, eyleme geçirilebilir ve kısa formatlara dönüştürme sanatı olan **Yönetici Özetleri**'ni (Executive Summaries) inceler. PACE iş akışının bu özetleri nasıl beslediğini analiz eder.

## 1. Yönetici Özeti Nedir ve Neden Kritiktir?

Yönetici özeti, bir projenin en önemli noktalarını özetleyen ve karar vericilere en ilgili bilgilerin kısa bir genel bakışını sunan stratejik bir belgedir.

* **Zaman Yönetimi:** Yöneticilerin tüm raporu okuyacak zamanı olmayabilir; bu format onların sorumluluklarına ve zaman kısıtlarına saygı duyar.
* **Onboarding:** Yeni ekip üyelerinin projeye hızla aşina olmasını sağlamak için de kullanılır.
* **Format:** Genellikle sunum slaytlarında "tek sayfalık" (one-page) bir format olarak karşımıza çıkar.


---

## 2. Bir Yönetici Özetinin 5 Temel Elementi (Anatomy of an Executive Summary)

Endüstride standartlaşmış bir yönetici özeti şu bileşenleri içerir:

### 2.1. Proje Başlığı (Project Title)
Projenin teması başlığa entegre edilerek hedef kitle ile anında bir bağlantı kurulmalıdır.

### 2.2. Problem (The Problem / Hypothesis)
Projenin hedeflediği ihtiyaç veya endişeye odaklanan ifadedir.
* **Teknik Not:** Veri biliminde bu, aynı zamanda veri analizi yoluyla kanıtlamaya çalıştığınız **hipotez** (hypothesis) olarak da adlandırılır.
* *Örnek:* "Müşteri terk oranının (Churn Rate) %5 artması gelir kaybı yaratıyor."

### 2.3. Çözüm (The Solution)
Projenin ana hedefini özetler. Sorun bildiriminde özetlenen endişeleri ele alan eylemler burada tanımlanır.
* *Örnek:* "XGBoost tabanlı bir tahminleme modeli ile riskli müşterileri tespit etmek."

### 2.4. Detaylar ve Temel İçgörüler (Key Insights)
Hedef kitlenin projenin amaçlarını anlamasına yardımcı olacak ek arka plan bilgileri ve analiz bulgularıdır.
* *Örnek:* "En büyük terk sebebi %40 ile fiyatlandırma politikasıdır."

### 2.5. Sonraki Adımlar ve Öneriler (Next Steps / Recommendations)
Ekibin almayı planladığı aksiyonları ve karar vericiler için önerileri içerir.
* **Kural:** En az bir öneri ve bir sonraki adım maddesi içermelidir.
* *Örnek:* "Sadakat programının revize edilmesi (Öneri) ve A/B testine başlanması (Sonraki Adım)."

---

## 3. PACE İş Akışı ve Yönetici Özeti Entegrasyonu



Bir veri profesyoneli olarak, PACE döngüsünün her aşaması Yönetici Özetinin bir parçasını oluşturur:

| PACE Aşaması | Yönetici Özeti Karşılığı | Açıklama |
| :--- | :--- | :--- |
| **Plan (Planlama)** | **The Problem & Title** | İş problemini ve hipotezi tanımladığınız yerdir. |
| **Analyze (Analiz)** | **Key Insights** | Veriyi keşfederek (EDA) elde ettiğiniz bulgular buraya girer. |
| **Construct (Oluşturma)** | **The Solution** | Geliştirdiğiniz model veya algoritma çözümün kendisidir. |
| **Execute (Yürütme)** | **Recommendations** | Model sonuçlarına dayanarak yönetime sunduğunuz aksiyon planıdır. |

---

## 4. Detaylı Analiz: Nerede, Ne Amaçla ve Hangi Yöntemle?

### Nerede Kullanılır? (Context)
* **QBR (Quarterly Business Reviews):** Çeyreklik iş incelemelerinde üst yönetime sunum yaparken.
* **Yatırımcı Sunumları (Pitch Decks):** Projeye bütçe veya kaynak (Resource Allocation) isterken.
* **Proje Kapanışları (Post-Mortem):** Proje bittiğinde nelerin başarıldığını arşivlemek için.

### Ne Amaçla Kullanılır? (Purpose)
* **Hizalanma (Alignment):** Projeye doğrudan dahil olmayan paydaşları aynı sayfada tutmak için.
* **Onay Alma (Buy-in):** Teknik detaylarda boğulmadan, projenin iş değerini (Business Value) göstererek onay almak için.
* **Özetleme:** Karmaşık analitik süreçleri "Sadeleştirilmiş Gerçeklik" (Simplified Reality) olarak sunmak için.

### Hangi Yöntemlerle Kullanılır? (Methods)
* **BLUF (Bottom Line Up Front):** En önemli sonucu en başta söyleme prensibi.
* **Görselleştirme:** Slayt içinde metni destekleyen tek bir vurucu grafik (Hero Chart) kullanımı.
* **Yazılım Araçları:** PowerPoint, Google Slides veya bu amaç için özel üretilmiş yazılımlar.

---

## 5. Karşılaştırmalı Analiz: Yönetici Özeti vs. Teknik Rapor vs. Dashboard

| Özellik | Yönetici Özeti (Executive Summary) | Teknik Rapor (Technical Report) | Dashboard (Gösterge Paneli) |
| :--- | :--- | :--- | :--- |
| **Hedef Kitle** | C-Level, VP, Direktörler | Veri Bilimciler, Mühendisler | Operasyonel Yöneticiler |
| **İçerik** | Stratejik, Eylem Odaklı, Özet | Kod, Metodoloji, Hiperparametreler | Canlı Metrikler, Filtreler |
| **Format** | 1-2 Sayfa / Slayt | 10+ Sayfa / Jupyter Notebook | Tableau / PowerBI Ekranı |
| **Sıklık** | Proje Dönüm Noktalarında | Proje Bitiminde | Günlük / Anlık |
| **Amaç** | Karar Aldırmak | Dokümantasyon / Tekrarlanabilirlik | İzleme (Monitoring) |

---

## 6. Uzman Tavsiyeleri (Pro-Tips)

1.  **Süslemeden Kaçının:** Bölümler kısa ifadelerle, süslemesiz (without embellishment) sunulmalıdır.
2.  **Hikaye Anlatıcılığı:** Veriyi kuru rakamlar yerine, bir problem-çözüm hikayesi olarak kurgulayın.
3.  **Hedef Kitle Odaklılık:** Detay seviyesini belirlerken hedef kitlenin kim olduğunu (Teknik mi? Finansal mı?) baz alın.

> **Unutmayın:** İyi bir yönetici özeti, karmaşık bir analizi "Evet" veya "Hayır" kararına dönüştürebilen en güçlü araçtır.

  [Link to sample executive summary: 
Visitation prediction project executive summary](https://docs.google.com/presentation/d/1MQ2cXMvsWQfzTD6iAJqnj5Tvynrv4RCZQUnZie1ZuMo/template/preview?resourcekey=0-_Ck9PU4Bw_JHxrLqobHWXw)

# PACE ve Yönetici Özetleri: Stratejiden Sunuma Dönüşüm

> **Doküman Özeti:** Bu rehber, **PACE** (Plan, Analyze, Construct, Execute) iş akışında üretilen strateji dokümanlarının, karar vericiler için hazırlanan **Yönetici Özetleri**'ne (Executive Summaries) nasıl dönüştürüldüğünü analiz eder. Veri biliminde "Internal Documentation" (İç Dokümantasyon) ile "External Reporting" (Dış Raporlama) arasındaki köprüyü kurar.

## 1. Bağlam: PACE ve Özet Arasındaki Simbiyotik İlişki

Bu kursta PACE iş akışının projeleri nasıl yönlendirdiğini keşfettiniz. PACE strateji dokümanları, proje boyunca alınan kararların ve çıktıların kaydedildiği "log" dosyaları gibidir.



Ancak bu dokümanlar sadece arşiv için değildir; yönetici özetleri üzerinde çalışırken harika bir referans kaynağıdır. Projenizi planlarken, analiz ederken, oluştururken ve yürütürken (PACE) bu dokümanlardaki sorulara verdiğiniz detaylı cevaplar, yönetici özetini yazarken ihtiyaç duyacağınız tüm bilgiyi size hazır sunar.

> **Uzman Görüşü:** Bir yönetici özeti yazmak için boş bir sayfaya bakmak zordur. Ancak elinizde dolu bir PACE strateji dokümanı varsa, yapmanız gereken tek şey "Copy-Paste-Refine" (Kopyala-Yapıştır-İyileştir) işlemidir.

---

## 2. Detaylı Analiz: PACE Aşamalarından Özete Veri Akışı

Bir veri bilimci olarak, PACE dokümanındaki teknik notlarınızı yönetici özetinin iş diline (Business Language) nasıl çevireceğinizi aşağıda haritalandırdım:

### 2.1. Plan (Planlama) -> The Problem (Problem Tanımı)
* **PACE Dokümanı:** "Projenin kapsamı ne?", "Hangi metrikleri optimize ediyoruz?", "Paydaşlar kim?" sorularına verdiğiniz yanıtlar.
* **Yönetici Özeti:** Tanımlanmış problemi ve neden çözülmesi gerektiğini net bir dille raporlar.

### 2.2. Analyze (Analiz) -> Key Insights (Temel İçgörüler)
* **PACE Dokümanı:** EDA (Keşifsel Veri Analizi) sırasında bulunan aykırı değerler, veri kalitesi notları ve korelasyonlar.
* **Yönetici Özeti:** Veriden elde edilen ve stratejik öneme sahip "Aha!" anları.

### 2.3. Construct (Oluşturma) -> The Solution (Çözüm)
* **PACE Dokümanı:** Model seçimi, hiperparametre optimizasyonu, doğruluk (accuracy) skorları.
* **Yönetici Özeti:** Problemi çözmek için kullanılan yöntemlerin (modellerin) ve çözümlerin ana hatları.

### 2.4. Execute (Yürütme) -> Results & Recommendations (Sonuçlar ve Öneriler)
* **PACE Dokümanı:** Modelin canlıya alınması, A/B testi planları, izleme (monitoring) stratejileri.
* **Yönetici Özeti:** Temel içgörülerin ve sonuçların paylaşıldığı, "Ne yapmalıyız?" sorusunun cevaplandığı bölüm.

---

## 3. Karşılaştırmalı Analiz: Strateji Dokümanı vs. Yönetici Özeti

| Özellik | PACE Strateji Dokümanı | Yönetici Özeti (Executive Summary) |
| :--- | :--- | :--- |
| **Hedef Kitle** | Veri Ekibi, Teknik Liderler, Kendiniz | Karar Vericiler (Decision Makers), Müşteriler, Yöneticiler |
| **İçerik Derinliği** | Yüksek (Her adımı ve soruyu detaylandırır) | Düşük (Sadece en önemli bilgileri özetler) |
| **Dil** | Teknik, Süreç Odaklı | Stratejik, Sonuç Odaklı |
| **İşlev** | Rehberlik ve Kayıt (Reference & Guide) | Bilgi Paylaşımı ve İkna (Share Information) |
| **Zamanlama** | Proje boyunca sürekli güncellenir | Proje sonunda veya kilometre taşlarında oluşturulur |

---

## 4. Temel Çıkarımlar (Key Takeaways)

1.  **Veri Kaynağı:** PACE strateji dokümanı, yönetici özetinizin veri ambarıdır. Sorulara ne kadar detaylı yanıt verirseniz, özeti oluşturmak o kadar kolay olur.
2.  **Köprü Görevi:** Yönetici özetleri, teknik ekip ile karar vericiler, müşteriler ve yöneticiler arasında bilgi paylaşmanın en etkili yoludur.
3.  **Odak:** Tipik bir yönetici özeti, tanımlanmış bir problemi rapor eder ve bu problemi ele almak için kullanılan çözümleri ana hatlarıyla belirtir.

> **Pro Tip:** Projenin sonunda yönetici özetini yazarken "Ben bu projede ne yapmıştım?" diye hatırlamaya çalışmak yerine, PACE dokümanınızı açın. Cevaplar zaten orada, sizin tarafınızdan yazılmış durumda bekliyor olacak.

# Create a project proposal

<img width="600" height="710" alt="image" src="https://github.com/user-attachments/assets/1d129f3d-84f6-45f4-9a91-25b2cd982df4" />

# Activity: Create a Project Proposal (Proje Teklifi Oluşturma)

## Activity Overview (Etkinlik Genel Bakış)

As you have learned, a **project proposal** (proje teklifi) is a plan of action that describes what needs to be accomplished in order to achieve a project’s intended goals and outcome. The main function of this resource is to outline a project’s **objectives** (hedefler) and **requirements** (gereksinimler). Project proposals are typically generated at the beginning of a project and are used by team members throughout the project’s duration.

In this activity, you will create a project proposal based on a fictional workplace scenario.

> **Note:** To review tips for creating an effective project proposal, refer to the reading about communicating objectives with a project proposal.

Be sure to complete this activity before moving on. The next course item will provide you with a completed **exemplar** (örnek/model) to compare to your own work. You will not be able to access the exemplar until you have completed this activity.

---

## Scenario (Senaryo)

Review the following scenario. Then complete the step-by-step instructions.

You are a **data professional** (veri profesyoneli) working for an international delivery company. Company leadership has asked the data team to develop a **machine learning model** (makine öğrenimi modeli) for **predictive maintenance** (kestirimci bakım) on its fleet of delivery vehicles.

**Predictive maintenance** uses machine learning to help predict equipment failures before they occur. The ML model analyzes both **historical data** (geçmiş veriler) such as performance and maintenance records, and **real-time data** (gerçek zamanlı veriler) collected from sensors placed on vehicles.

Leadership wants to use the power of predictive maintenance to:
* Monitor the performance of delivery vehicles.
* Identify and fix issues before they cause costly downtime or delays.

*Example:* If the engine of a delivery vehicle breaks down, the company has to deal with delivery delays, dissatisfied customers, vehicle repair or replacement, and potential safety issues.

**Benefits of Predictive Maintenance:**
* Optimized delivery (Optimize edilmiş teslimat)
* Increased safety (Artırılmış güvenlik)
* Improved customer service (Geliştirilmiş müşteri hizmetleri)
* Reduced costs (Azaltılmış maliyetler)

Your manager asks you to create a **project proposal** to identify and organize key **milestones** (kilometre taşları) and **deliverables** (teslimatlar) for the project.

* **Proposed Timeline (Önerilen Zaman Çizelgesi):** 12 weeks
* **Goal (Hedef):** To build a model with at least 90% accuracy.

---

## Step-By-Step Instructions (Adım Adım Talimatlar)

Follow the instructions to complete each step of the activity. Then, answer the five questions at the end of the activity before going to the next course item to compare your work to a completed exemplar.

### Step 1: Access the Template (Şablona Erişim)

To use the supporting materials for this course item, click the following link and select “Use Template.”

* **Link to supporting materials:** [Predictive maintenance project proposal]

**OR**

If you don’t have a Google account, you can download the supporting materials directly from the attachment provided in the course platform.

### Step 2: Complete the Project Proposal (Proje Teklifini Tamamlama)

Review the scenario and think about the **objective** (amaç), **scope** (kapsam), **timeline** (zaman çizelgesi), and **key tasks** (ana görevler) of the project.

The project proposal should include the following tasks:
1.  **Data collection** (Veri toplama)
2.  **Data cleaning** (Veri temizleme)
3.  **Data exploration** (Veri keşfi/analizi)
4.  **Building and testing of ML models** (ML modellerinin oluşturulması ve test edilmesi)
5.  **Sharing results/insights with stakeholders** (Sonuçların/içgörülerin paydaşlarla paylaşılması)

Consider what information would be most relevant to the data team. Then complete the project proposal with that information.

**Note:** The project template has been organized according to the **PACE framework** (Plan, Analyze, Construct, Execute). Be sure to address the following elements in your completed project proposal:

* A **project title** (proje başlığı)
* An **objective statement** (amaç bildirimi) that describes the goal of the project
* A list of **key tasks and deliverables** (ana görevler ve teslimatlar listesi) to be completed for each project milestone
* A **time estimate** (tahmini süre) for achieving each project milestone

---
# Proje Teklifi ve PACE İş Akışı Dokümantasyonu
> **Özet:** Bu doküman, bir uluslararası teslimat şirketi için geliştirilecek "Tahminleyici Bakım" (Predictive Maintenance) projesinin teklif taslağını ve ilgili PACE (Plan, Analyze, Construct, Execute) modeli değerlendirme sorularını içerir.

---

## Bölüm 1: Teslimat Filosu İçin Tahminleyici Bakım Proje Teklifi (Project Proposal)

Aşağıdaki tablo, yönetim tarafından talep edilen ve araç filosundaki arızaları önceden tespit etmeyi amaçlayan makine öğrenimi projesi için hazırlanmıştır.

**Proje Başlığı:** Delivery Fleet Predictive Maintenance Initiative (Teslimat Filosu Tahminleyici Bakım Girişimi)

### **Hedef (Objective)**
Veri ekibinin hedefi, teslimat araçlarının performansını izlemek ve %90 doğruluk oranıyla (accuracy rate) olası ekipman arızalarını önceden tahmin eden bir makine öğrenimi modeli (Machine Learning Model) geliştirmektir. Bu sayede maliyetli kesintilerin ve teslimat gecikmelerinin önüne geçilecektir.

### **PACE Aşamalarına Göre Kilometre Taşları (Milestones)**

| Kilometre Taşı (Milestone) | Görevler (Tasks) | Çıktılar/Teslimatlar (Deliverables) | Tahmini Süre (Estimated Time) |
| :--- | :--- | :--- | :--- |
| **Milestone 1: Planlama (Planning)** | • Proje iş akışını (workflow) ana hatlarıyla belirle<br>• Bakım kayıtları ve sensör verilerini (sensor data) topla<br>• Gerekli yazılım/donanım ihtiyaçlarını belirle | • Paydaşlar bilgilendirildi (Stakeholders updated)<br>• Veri toplama planı onaylandı | **2 Hafta** |
| **Milestone 2: Analiz (Analyzing)** | • Veriyi temizle (Data cleaning) ve dönüştür<br>• Keşifsel Veri Analizi (Exploratory Data Analysis - EDA) yap<br>• Veri tutarsızlıklarını gider | • Modellemeye hazır veri seti (Data ready for modeling)<br>• EDA Raporu | **3 Hafta** |
| **Milestone 3: Oluşturma (Constructing)** | • Modelleme stratejilerini kesinleştir<br>• Makine öğrenimi modellerini inşa et<br>• Modeli test et ve %90 doğruluk (accuracy) için optimize et | • Eğitilmiş Makine Öğrenimi Modeli (Trained ML Model)<br>• Performans metrikleri raporu | **5 Hafta** |
| **Milestone 4: Yürütme (Executing)** | • Sonuçları kesinleştir<br>• Bulguları ve içgörüleri (insights) paydaşlarla paylaş<br>• Geri bildirimleri (feedback) entegre et | • Veri Görselleştirmeleri (Visualizations)<br>• Yönetici Özeti (Executive Summary)<br>• Canlıya alma planı | **2 Hafta** |

> **Toplam Proje Süresi:** 12 Hafta

---

## Bölüm 2: PACE Modeli Değerlendirme Soruları (Quiz Answers)

Aşağıdaki cevaplar, PACE modelinin aşamalarını ve iletişim stratejilerini test eden sorulara aittir.

### Soru 1: Veri İnceleme Aşaması
**Soru:** In the \_\_\_\_\_ stage of the PACE model, a methodical examination of the data is conducted.
* **Cevap:** `Analyze`
* **Açıklama:** Verinin temizlendiği, düzenlendiği ve sistematik olarak incelendiği aşama **Analiz (Analyze)** aşamasıdır.

### Soru 2: Yürütme Aşamasında Paylaşım
**Soru:** In the execute stage of the PACE model, what is shared with stakeholders?
* **Cevap:** `The story told by the data`
* **Açıklama:** Yürütme (Execute) aşamasında, paydaşlar genellikle ham kodlarla değil, verinin anlattığı hikaye ve sonuçlarla ilgilenirler.

### Soru 3: Yeni Veri Uzmanına E-posta
**Soru:** What information is most relevant to include in the email to the new data professional?
* **Doğru Seçenekler:**
    * `[x]` The accuracy goal for the visitation prediction model (Ziyaret tahmin modeli için doğruluk hedefi)
    * `[x]` An overview of the data team’s workflow (Veri ekibinin iş akışına genel bakış)
    * `[x]` An invitation to ask follow-up questions (Takip soruları sormaya davet)
* **Açıklama:** Yeni bir ekip üyesine projenin hedefi (%90 doğruluk), nasıl çalışılacağı ve iletişime açık olunduğu bildirilmelidir. "ML modelleri nasıl çalışır" gibi temel bir bilgiye profesyonel bir uzmanın ihtiyacı yoktur.

### Soru 4: İletişimin Nedeni
**Soru:** Which element of communicative exchange involves thinking about the reason why the communication is taking place?
* **Cevap:** `Purpose`
* **Açıklama:** İletişimin neden gerçekleştiğini sorgulamak, doğrudan **Amaç (Purpose)** ile ilgilidir.

---

## Bölüm 3: Temel Çıkarımlar (Key Takeaways)

1.  **Yapılandırılmış Yaklaşım:** Proje teklifleri (Project Proposals), PACE çerçevesini kullanarak belirsizliği azaltır ve kilometre taşlarını (milestones) netleştirir.
2.  **Hedef Odaklılık:** İyi bir teklif, "Neden yapıyoruz?" sorusuna net bir cevap verir (Örn: %90 doğruluk ile arıza tahmini).
3.  **İletişim:** Teknik detaylar (Construct aşaması) ile iş sonuçları (Execute aşaması) arasındaki dengeyi kurmak, proje başarısı için kritiktir.


# Data Analytics Glossary & PACE Framework

This document contains key terms and definitions related to data analytics, specifically focusing on the PACE workflow and foundational concepts.

> **Note:** Terms are provided in **English** with their **(Turkish)** equivalents.

## 📌 PACE Workflow (PACE İş Akışı)

**PACE workflow (PACE İş Akışı)**
A framework that provides an initial structure to guide the process of data analytics; PACE stands for **P**lan, **A**nalyze, **C**onstruct, and **E**xecute.

* **Plan stage (Planlama Aşaması)**
    Stage of the PACE workflow where the scope of a project is defined and the informational needs of the organization are identified.

* **Analyze stage (Analiz Aşaması)**
    Stage of the PACE workflow where the necessary data is acquired from primary and secondary sources and then cleaned, reorganized, and analyzed.

* **Construct stage (İnşa Etme / Oluşturma Aşaması)**
    Stage of the PACE workflow where data models and machine learning algorithms are built, interpreted, and revised to uncover relationships within the data and help unlock insights from those relationships.

* **Execute stage (Uygulama Aşaması)**
    Stage of the PACE workflow where a data professional will present findings with internal and external stakeholders, answer questions, consider different viewpoints, and make recommendations.

---

## 📚 General Terms & Definitions (Genel Terimler ve Tanımlar)

### A
* **Active listening (Aktif Dinleme)**
    Refers to allowing team members, bosses, and other collaborative stakeholders to share their own points of view before offering responses.
* **Aggregate information (Toplu / Kümülatif Bilgi)**
    Data from a significant number of users that has eliminated personal information.
* **Analytics Team Manager (Analitik Ekip Yöneticisi)**
    A data professional who supervises analytical strategy for an organization, often managing multiple groups.
* **Artificial intelligence (AI) (Yapay Zeka)**
    Refers to computer systems able to perform tasks that normally require human intelligence.

### B
* **Business Intelligence Analyst (İş Zekası Analisti)**
    (Refer to Business Intelligence Engineer).
* **Business Intelligence Engineer (İş Zekası Mühendisi)**
    A data professional who uses their knowledge of business trends and databases to organize information and make it accessible; also referred to as a Business Intelligence Analyst.

### C
* **Chief Data Officer (Veri İşleri Müdürü / CDO)**
    An executive-level data professional who is responsible for the consistency, accuracy, relevancy, interpretability, and reliability of the data a team provides.

### D
* **Data anonymization (Veri Anonimleştirme)**
    The process of protecting people's private or sensitive data by eliminating Personally Identifiable Information (PII).
* **Data cleaning (Veri Temizleme)**
    The process of formatting data and removing unwanted material.
* **Data Engineer (Veri Mühendisi)**
    A data professional who makes data accessible, ensures data ecosystems offer reliable results, and manages infrastructure for data across enterprises.
* **Data professional (Veri Uzmanı)**
    Any individual who works with data and/or has data skills.
* **Data science (Veri Bilimi)**
    The discipline of making data useful.
* **Data Scientist (Veri Bilimcisi)**
    A data professional who works closely with analytics to provide meaningful insights that help improve current business operations.
* **Data stewardship (Veri Yöneticiliği)**
    The practices of an organization that ensure that data is accessible, usable, and safe.

### E
* **Edge computing (Uç Bilişim)**
    A way of distributing computational tasks over a bunch of nearby processors (i.e., computers) that is good for speed and resiliency and does not depend on a single source of computational power.

### H
* **Hackathon (Hackathon / Yazılım Maratonu)**
    An event where programmers and data professionals come together and work on a project.

### I
* **Interpersonal skills (Kişilerarası Beceriler)**
    Traits that focus on communicating and building relationships.

### J
* **Jupyter Notebook (Jupyter Notebook)**
    An open-source web application used to create and share documents that contain live code, equations, visualizations, and narrative text.

### M
* **Machine learning (Makine Öğrenimi)**
    The use and development of algorithms and statistical models to teach computer systems to analyze patterns in data.
* **Mentor (Mentor / Akıl Hocası)**
    Someone who shares knowledge, skills, and experience to help another grow both professionally and personally.
* **Metrics (Metrikler)**
    Methods and criteria used to evaluate data.

### N
* **Nonprofit (Kâr Amacı Gütmeyen Kuruluş)**
    A group organized for purposes other than generating profit; often aims to further a social cause or provide a benefit to the public.

### O
* **Open data (Açık Veri)**
    Data that is available to the public and free to use, with guidance on how to navigate the datasets and acknowledge the source.

### P
* **Personally identifiable information (PII) (Kişisel Tanımlanabilir Bilgiler)**
    Information that permits the identity of an individual to be inferred by either direct or indirect means.
* **Python (Python)**
    A general-purpose programming language.

### R
* **RACI chart (RACI Tablosu)**
    A visual that helps to define roles and responsibilities for individuals or teams to ensure work gets done efficiently; lists who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for project tasks.

### S
* **Sample (Örneklem)**
    A segment of a population that is representative of the entire population.

### T
* **Tableau (Tableau)**
    A business intelligence and analytics platform that helps people visualize, understand, and make decisions with data.

---

# End-of-course portfolio project introduction

Each course in the **Google Advanced Data Analytics Certificate** concludes with a project that provides hands-on opportunities to practice your knowledge. These end-of-course portfolio projects build across courses to simulate the **full lifecycle of a data project**, just like job tasks that you will encounter as a data professional.

---

### Portfolio Compilation & Career Prep

[Course 1 PACE strategy document](https://docs.google.com/document/d/1vQAji1vQtK1-IdypxBg1g3K-dTu4mXcBlxC572eSwZM/template/preview)

[Automatidata project proposal](https://docs.google.com/document/d/1ru7p_XahBMHah9ELzSIoEcBzsWdMp0SGczI19EgP7XI/template/preview)



After completing all of the courses in this certificate program, you are encouraged to compile the projects in a portfolio that highlights your **data analytics skills**. 

> **Note:** You will learn how to create a portfolio in the final course of this certificate program: **Google Advanced Data Analytics Capstone**.

In addition, the end-of-course projects can also be used to help you prepare for **job applications and interviews** since they showcase the valuable skills that you bring to the world of data analytics.

<img width="978" height="321" alt="image" src="https://github.com/user-attachments/assets/074fc9ee-343c-49da-a6da-6ad3883144f5" />


# Explore your Course 1 workplace scenarios

## Overview

This certificate offers you a choice of several different workplace scenarios to use when completing each end-of-course project:

* **Automatidata**: featuring a fictional data consulting firm
* **TikTok**: created in partnership with the short-form video hosting company
* **Waze**: created in partnership with the realtime driving directions app

Each scenario offers you an opportunity to apply your skills and create work samples to share when applying for jobs; so, you will be practicing similar skills regardless of the workplace scenario. It is recommended that you work with the **same scenario** for each end-of-course project to have a cohesive experience. However, you are welcome to investigate any of the workplace scenarios you are interested in as you progress through the program.

> **Reminder:** We recommend that you choose **one workplace scenario** to follow for all end-of-course projects to ensure end-to-end project development.

---

### Minimum Requirements & Additional Practice

The **minimum requirement** to earn your **Advanced Data Analytics Certificate** is to complete the end-of-course project, using one workplace scenario, for each course. 

You may complete the project for as many of the workplace scenarios as you wish. Completing the project for more than one workplace scenario in a single course offers you:
* Additional practice
* Work examples you can add to your **portfolio**
* More content to share with prospective employers during your job search

This reading offers an overview of all available workplace scenarios. **Before moving on, identify the scenario you would like to complete for the Course 1 end-of-course project.**


<img width="557" height="466" alt="image" src="https://github.com/user-attachments/assets/27f9a901-60e6-47b3-a423-7fa6bc9f0b40" />


# Project Scenario: Automatidata

## Project Goal
In this fictional scenario, the **New York City Taxi and Limousine Commission (TLC)** has approached the data consulting firm **Automatidata** to develop an app that enables TLC riders to estimate the taxi fares in advance of their ride.

## Background
Since 1971, TLC has been regulating and overseeing the licensing of New York City's taxi cabs, for-hire vehicles, commuter vans, and paratransit vehicles.

## Scenario
You are a newly-hired **data professional** at **Automatidata**, a fictional data consulting firm. Automatidata’s focus is to help clients transform their unused and stored data into useful solutions. 

In this scenario, you will consult with The New York City Taxi & Limousine Commission to develop an app that will help users (TLC riders) estimate their taxi fares before their ride. Your first responsibility as a data analytics consultant will be to structure the necessary tasks into a **project proposal** that establishes **milestones** for the ride fare data project.

### Course 1 Tasks
* Gather information from the notes from the last executive meeting of Automatidata
* Assign **PACE stages** (Plan, Analyze, Construct, Execute) to the requested tasks
* Organize tasks into **milestones**
* Create a **project proposal** for the executive team’s approval

---

> **Note:** The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes.


<img width="809" height="234" alt="image" src="https://github.com/user-attachments/assets/6751c5d9-f9ce-4aae-9aee-d60fb52919fc" />


# Project Scenario: TikTok

## Project Goal
The **TikTok data team** is developing a **machine learning model** for classifying claims made in videos submitted to the platform.

## Background
TikTok is the leading destination for short-form mobile video. The platform is built to help imaginations thrive. TikTok's mission is to create a place for inclusive, joyful, and authentic content–where people can safely discover, create, and connect.

## Scenario
As a **data analyst** on TikTok's data team, with new considerations from the leadership team, you will create a **project proposal** by assigning the required data analytical tasks into realistic **milestones** that will advise future steps in the claims classification project.

### Course 1 Tasks
* Gather information from stakeholder notes from within TikTok
* Assign **PACE stages** (Plan, Analyze, Construct, Execute) to the requested tasks for the classification project
* Organize tasks into **milestones**
* Create a **project proposal** for the TikTok data team

---

> **Note:** The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes.



<img width="637" height="245" alt="image" src="https://github.com/user-attachments/assets/bc4180ae-deb4-46a2-9e84-e0c2fd8d853f" />

# Project Scenario: Waze

## Project Goal
**Waze leadership** has asked your data team to develop a **machine learning model to predict user churn**. 

* **Churn** quantifies the number of users who have uninstalled the Waze app or stopped using the app. 
* This project focuses on **monthly user churn**. 
* An accurate model will help prevent churn, improve user retention, and grow Waze’s business.

## Background
Waze’s free navigation app makes it easier for drivers around the world to get to where they want to go. Waze’s community of map editors, beta testers, translators, partners, and users helps make each drive better and safer.

## Scenario
You are the newest member of **Waze’s data team**. Your team is about to begin their user churn project. The first step is to create a **project proposal**. The proposal will clearly define the overall goal of the project, and identify key tasks, milestones, and stakeholders.

### Course 1 Tasks
* Assign **PACE stages** (Plan, Analyze, Construct, Execute) to the requested tasks for the user churn project
* Organize tasks into **milestones**
* Create a **project proposal** for the Waze data team

---

> **Note:** The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes.

# Course 1 End-of-Course Portfolio Project Overview: Automatidata

## Learn about the Course 1 Automatidata workplace scenario!

The end-of-course project in Course 1 focuses on your ability to **plan for data projects** and create a **project proposal**. The end-of-course projects were designed with you in mind, offering an opportunity for you to practice and apply your data analytic skills. The materials provided here will guide you through discussions with co-workers, internal team members, and external stakeholders.

---

## Background on the Automatidata Scenario

Congrats on your new job as a **data analyst** at a data consulting firm called **Automatidata**. 

* **Automatidata** works with its clients to transform their unused and stored data into useful solutions, such as performance dashboards, customer-facing tools, strategic business insights, and more. They specialize in identifying a client’s business needs and utilizing their data to meet those business needs.
* **The Client (NYC TLC):** Automatidata is consulting for the **New York City Taxi and Limousine Commission (TLC)**. New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. 
* **The Goal:** The agency has partnered with Automatidata to develop a **regression model** that helps estimate taxi fares before the ride, based on data that TLC has gathered. 

**Data Context:**
The TLC data comes from over **200,000 taxi and limousine licensees**, making approximately **one million combined trips per day**.

> **Note:** This project's dataset was created for pedagogical purposes and may not be indicative of New York City taxi cab riders' behavior.

---

## Project Background

Automatidata is in the **earliest stages** of the TLC project. The following tasks are needed before the team can begin the data analysis process:

1.  A **project proposal** identifying the following:
    * Organize project tasks into **milestones**
    * Classify tasks using the **PACE workflow** 
    * Identify relevant **stakeholders**

### Your Assignment
For your first assignment, Automatidata will need a **project proposal** that will create milestones for the tasks within the TLC project. Remember to take into account your audience, team, project goal, and PACE stages of each task in planning your project deliverable.

---

## Team Members at Automatidata and the New York City TLC

### Automatidata Team Members
*Your teammates at Automatidata have technical experience with data analysis and data science. Keep summaries and messages to these team members concise and to the point.*

| Name | Role |
| :--- | :--- |
| **Udo Bankole** | Director of Data Analysis |
| **Deshawn Washington** | Data Analysis Manager (Your Supervisor) |
| **Luana Rodriquez** | Senior Data Analyst |
| **Uli King** | Senior Project Manager |

### New York City TLC Team Members
*The TLC team members are program managers who oversee operations at the organization. Their roles are not highly technical, so be sure to adjust your language and explanation accordingly.*

| Name | Role |
| :--- | :--- |
| **Juliana Soto** | Finance and Administration Department Head |
| **Titus Nelson** | Operations Manager |

> **Note:** The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred. The data shared in this project has been altered for pedagogical purposes.

---

## Meeting Notes

Now that you are working as Automatidata’s latest data analytics professional, you are given access to the company network and set up with a company email account (your first initial and last name, followed by @automatidata.org).

Opening your inbox, you notice an email from your supervisor, Deshawn.

> **From:** Deshawn Washington
> **Subject:** Review meeting notes
>
> If you are able to read this, then your company accounts have been created! Now is the perfect time to get started. 
>
> Last week, I attended an internal meeting with our leadership team about a new project we are about to begin. You’ll receive more information in the next few days, but I would like you to be aware of some needs that were identified by our leadership team. 
>
> Here is an excerpt from the notes I took during the Automatidata leadership team meeting. I’ve organized the points by the person who made them.
>
> **Uli King (Senior Project Manager)**
> * The data team will need a global-level project document to outline the goals and milestones.
> * I am working closely with **Titus Nelson** over at the New York City Taxi and Limo Commission. He has requested some visuals to share with TLC’s executives.
>
> **Luana Rodriquez (Senior Data Analyst)**
> * The dataset from TLC has to be inspected before any analysis can begin.
> * Our team needs to determine what information the TLC data provides through **exploratory data analysis (EDA)**.
> * Eventually, our team will need to test to find if the model is delivering consistent results.
>
> **Udo Bankole (Director of Data Analysis)**
> * Before we present any insights to TLC, we'll need to determine whether or not the model we produce meets the project requirements.
> * Once we have a final model, I'll need to know the main talking points going into our presentation with TLC.
>
> **My thoughts and concerns… (Deshawn Washington)**
> * I think it's best to use **Python** for the TLC project. I'll have someone on my team set that up as soon as we have the plan in place.
> * It will be important to establish the relationship between any variables within the TLC data. I'd suggest the data team consider **A/B testing**, since that will analyze the relationship between the two most useful variables and subsequently provide data-driven support for future business decisions.
>
> Review the meeting notes above to become familiar with the project’s context. I’ll ask you to identify project tasks and come up with a structure to guide the data team through this project. After our discussion about your experience in the certificate program offered by Google, I know that your efficient communication style and problem-solving will enhance the abilities of the data team.
>
> There will be more details sent to you very soon.
>
> Welcome to the team,
>
> **Deshawn Washington**
> Data Analysis Manager
> Automatidata
>
> *(P.S. There will be muffins in the break room every Tuesday morning. Be early…unless you like bran muffins. LOL)*

---

## Specific Project Deliverables

With this end-of-course project, you will gain valuable practice and apply your new skills as you complete the following:

1.  **Course 1 PACE Strategy Document**: To plan your project while considering your audience members, teammates, key milestones, and overall project goal.
2.  **Create a project proposal**: For the data team.

---

## Key Takeaways

The **Google Advanced Data Analytics Certificate** end-of-course project is designed for you to practice and apply course skills in a fictional workplace scenario. By completing each course’s end-of-course project, you will have work examples that will enhance your portfolio and showcase your skills for future employers.

| Term | Definition |
| :--- | :--- |
| **Exploratory Data Analysis (EDA)** | A process to inspect and analyze datasets to summarize their main characteristics, often using visual methods. |
| **Automatidata** | A fictional data consulting firm that transforms unused data into useful solutions for clients. |
| **New York City TLC** | The agency responsible for regulating taxi services in NYC, partnering with Automatidata for data analysis projects. |
| **Project Proposal** | A document outlining project milestones, tasks, and stakeholder identification necessary for project planning. |
| **PACE Workflow** | A framework used to classify tasks and organize project activities into manageable stages. |


# PACE Strategy Document: NYC TLC Project

## **P**lan Stage
**Goal:** Define the project scope, identify stakeholders, and determine data requirements.

* **What is the business task?**
    * The goal is to develop a machine learning model (specifically a regression model) to predict taxi cab fares in advance based on trip data (distance, time of day, etc.). This will help the NYC TLC improve user experience and operational efficiency.

* **Who are the stakeholders?**
    * **Internal (Automatidata):**
        * Udo Bankole (Director of Data Analysis)
        * Deshawn Washington (Data Analysis Manager)
        * Luana Rodriquez (Senior Data Analyst)
        * Uli King (Senior Project Manager)
    * **External (NYC TLC):**
        * Juliana Soto (Finance & Administration Dept Head)
        * Titus Nelson (Operations Manager)

* **What are the initial requirements?**
    * Create a global project document (Project Proposal).
    * Set up the Python environment for analysis.
    * Acquire the NYC TLC dataset.

## **A**nalyze Stage
**Goal:** Understand the data, clean it, and explore relationships between variables.

* **What data is required?**
    * The NYC TLC dataset containing trip details (distance, time, fare amount, etc.).
    * *Note:* Data covers 200,000+ licensees and ~1 million trips/day.

* **What specific analysis steps are needed?**
    * **Data Cleaning:** Inspect data for duplicates, missing values, and outliers (as requested by Luana).
    * **EDA (Exploratory Data Analysis):** Visualize distributions and correlations to understand the data structure.
    * **A/B Testing:** Investigate relationships between key variables (e.g., payment type vs. fare amount) as suggested by Deshawn.

## **C**onstruct Stage
**Goal:** Build and validate the machine learning model.

* **What modeling techniques will be used?**
    * **Regression Analysis:** Since the target variable (fare amount) is continuous, we will build a regression model. 

[Image of linear regression graph]

    * **Tooling:** Python (Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn).

* **How will we evaluate the model?**
    * We need to test the model to ensure it delivers consistent results (per Luana).
    * Verify if the model meets the initial project requirements before presenting to the client (per Udo).

## **E**xecute Stage
**Goal:** Present findings and implement the solution.

* **What are the final deliverables?**
    * A working regression model for fare prediction.
    * Visualizations of key insights for TLC executives (requested by Titus).
    * A final presentation summarizing the model's performance and business value.

* **Who is the audience for the presentation?**
    * The technical team at Automatidata (for model validation).
    * The non-technical leadership at NYC TLC (Juliana and Titus) – requiring concise, non-jargon language.
 
  # Project Proposal: NYC TLC Trip Fare Prediction

**Document Status:** Draft
**Prepared By:** [Your Name], Data Analyst
**Client:** New York City Taxi and Limousine Commission (TLC)

## 1. Project Background
The New York City Taxi and Limousine Commission (TLC) has been collecting data on taxi and rideshare trips since 1971. The agency wants to modernize its approach by leveraging this data to improve rider experience. Specifically, they aim to provide riders with an estimated fare *before* the ride begins.

## 2. Project Goal
The primary goal is to build a **regression model** that predicts the fare amount for a taxi ride.
* **Target Variable:** Fare Amount ($)
* **Predictor Variables:** Trip distance, time of day, pickup/drop-off locations, and other relevant factors found in the dataset.

## 3. Scope & Deliverables
The Automatidata team will be responsible for the end-to-end data lifecycle, structured as follows:

| Milestone | Deliverable | Description |
| :--- | :--- | :--- |
| **1. Planning** | Project Proposal | Define goals, stakeholders, and timeline. |
| **2. Analysis** | EDA Report | Summary of data quality, cleaning steps, and initial visualizations. |
| **3. Construction** | Regression Model | A Python-based machine learning model to predict fares. |
| **4. Execution** | Executive Presentation | A deck containing insights, model performance metrics, and recommendations for TLC leadership. |

## 4. Methodology & Tools
* **Framework:** PACE (Plan, Analyze, Construct, Execute) 
* **Language:** Python
* **Key Techniques:**
    * Exploratory Data Analysis (EDA)
    * A/B Testing (to determine variable relationships)
    * Multiple Linear Regression

## 5. Stakeholders
* **Automatidata (Internal):**
    * Udo Bankole (Director) - *Requires confirmation of model requirements.*
    * Deshawn Washington (Manager) - *Project lead; requested Python & A/B testing.*
    * Luana Rodriquez (Snr Analyst) - *Lead on data inspection & EDA.*
    * Uli King (Snr PM) - *Client liaison.*
* **NYC TLC (Client):**
    * Juliana Soto (Finance)
    * Titus Nelson (Operations) - *Requires visual insights for executives.*

## 6. Assumptions & Risks
* **Assumption:** The provided dataset is representative of typical NYC traffic and pricing patterns.
* **Risk:** The dataset is large (200k licensees); efficient code will be necessary to handle processing time.

---

# Project Proposal: NYC TLC Taxi Fare Prediction

**Project Title:** New York City TLC Taxi Fare Prediction Model
**Prepared By:** [Your Name/Data Team]
**Date:** [Current Date]
**Status:** Draft

---

## Project Overview
The New York City Taxi and Limousine Commission (TLC) has partnered with Automatidata to develop a machine learning regression model. The primary objective is to predict the estimated fare amount for a taxi ride prior to the trip, based on historical trip data (distance, time, pickup/drop-off locations). 

This project will enable the TLC to improve rider transparency and operational efficiency. The Automatidata team will handle the full data lifecycle, from data ingestion and cleaning to model construction and final executive presentation.

---

## Project Tasks & Milestones (PACE Workflow)

The following table outlines the chronological order of tasks, their associated milestones, the PACE stage, and the primary stakeholder driving the requirement.

| Order | Task Description | Milestone | PACE Stage(s) | Assigned Stakeholder |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Draft Project Proposal** <br> *Define goals, scope, and timeline based on initial meetings.* | **Planning** | **Plan** | **Deshawn Washington** <br> *(Supervisor)* |
| **2** | **Data Ingestion & Inspection** <br> *Import TLC dataset and check for missing values, duplicates, and outliers.* | **EDA** | **Analyze** | **Luana Rodriquez** <br> *(Req. Inspection)* |
| **3** | **Exploratory Data Analysis (EDA)** <br> *Visualize distributions and identify key variables affecting fare amounts.* | **EDA** | **Analyze** | **Luana Rodriquez** |
| **4** | **A/B Testing** <br> *Test relationships between variables (e.g., payment type vs. fare amount) to select model features.* | **Model Building** | **Analyze** / **Construct** | **Deshawn Washington** <br> *(Suggested strategy)* |
| **5** | **Build Regression Model** <br> *Develop the machine learning model using Python to predict fare amounts.* | **Model Building** | **Construct** | **Data Team** |
| **6** | **Model Validation** <br> *Test model consistency and verify it meets client requirements.* | **Model Building** | **Construct** / **Execute** | **Udo Bankole** <br> *(Director)* |
| **7** | **Create Visualizations** <br> *Generate clear charts and graphs for non-technical audiences.* | **Presentation** | **Execute** | **Titus Nelson** <br> *(Client - Ops Manager)* |
| **8** | **Final Executive Presentation** <br> *Summarize insights, model performance, and business recommendations.* | **Presentation** | **Execute** | **Uli King** <br> *(Project Manager)* |

---

## PACE Stage Definitions

* **[P]lan:** Establish the framework, scope, and goals of the project.
* **[A]nalyze:** Understand the data through cleaning and exploration.
* **[C]onstruct:** Build and train the machine learning models. 
* **[E]xecute:** Present findings and deploy the solution to stakeholders.

## Key Stakeholders

* **Internal (Automatidata):** Udo Bankole, Deshawn Washington, Luana Rodriquez, Uli King.
* **External (NYC TLC):** Titus Nelson, Juliana Soto.

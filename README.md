# 🏛️ Smarticle Open Citations - Community Edition

<p align="center">
  <b><a href="#english-version">English Version</a></b> | 
  <b><a href="#arabic-version">النسخة العربية</a></b>
</p>

---

<a id="english-version"></a>
## 🌍 English Version

This repository contains the official open-source database of structured academic references, books, and scientific papers cited across the bilingual encyclopedia **[Smarticle](https://smarticle.tech)**. All references are mapped directly to their corresponding academic concepts.

### 📊 Dataset Statistics
* **Covered Concepts / Articles**: 290 Academic Concepts.
* **Total Citations**: 2190+ Verified References.
* **Disciplines**: 11 Academic Fields (Science, Medicine, Tech, History, Philosophy, and more).

### 📂 Repository Structure

The database is divided into folders representing academic disciplines. Each folder contains a detailed sub-README with backlinks and the citations dataset in three versions:
1. **English Version (`data-en.json` / `data-en.csv`)**: Clean English datasets mapping academic concepts to references.
2. **Arabic Version (`data-ar.json` / `data-ar.csv`)**: Clean localized Arabic datasets mapping concepts to Arabic references.
3. **Bilingual Version (`data-bilingual.json` / `data-bilingual.csv`)**: Full side-by-side bilingual mapping.

| Directory | Academic Discipline | Concepts | Citations | Source Section on Smarticle |
| :--- | :--- | :--- | :--- | :--- |
| **Total** | **All Disciplines** | **290** | **2190** | **[smarticle.tech](https://smarticle.tech/en)** |
| [`/arts`](./arts) | 🎨 Arts & Literature | 26 | 215 | [smarticle.tech - Arts](https://smarticle.tech/en/category/arts) |
| [`/business`](./business) | 💼 Business & Finance | 25 | 211 | [smarticle.tech - Business](https://smarticle.tech/en/category/business) |
| [`/geography`](./geography) | 🌍 Geography & Earth Sciences | 25 | 201 | [smarticle.tech - Geography](https://smarticle.tech/en/category/geography) |
| [`/history`](./history) | 📜 History & Civilizations | 23 | 155 | [smarticle.tech - History](https://smarticle.tech/en/category/history) |
| [`/languages`](./languages) | 🗣️ Languages & Linguistics | 24 | 171 | [smarticle.tech - Languages](https://smarticle.tech/en/category/languages) |
| [`/medicine`](./medicine) | 🩺 Medicine & Pharmacy | 30 | 239 | [smarticle.tech - Medicine](https://smarticle.tech/en/category/medicine) |
| [`/philosophy`](./philosophy) | ⚖️ Philosophy & Logic | 25 | 179 | [smarticle.tech - Philosophy](https://smarticle.tech/en/category/philosophy) |
| [`/religion`](./religion) | 🕌 Religion & Comparative Studies | 24 | 201 | [smarticle.tech - Religion](https://smarticle.tech/en/category/religion) |
| [`/science`](./science) | 🔬 Science & Mathematics | 28 | 201 | [smarticle.tech - Science](https://smarticle.tech/en/category/science) |
| [`/society`](./society) | 👥 Society & Social Sciences | 31 | 204 | [smarticle.tech - Society](https://smarticle.tech/en/category/society) |
| [`/tech`](./tech) | 💻 Technology & Computing | 29 | 213 | [smarticle.tech - Tech](https://smarticle.tech/en/category/tech) |

### 📊 Dataset Schema

#### 1. English Dataset Headers (`data-en.csv`)
* `Academic Concept`: The cognitive concept/subject name on Smarticle.
* `Concept URL`: The direct URL of the semantic analysis on Smarticle.
* `Subcategory`: The academic sub-discipline.
* `Reference Title`: Title of the cited paper, book, or source.
* `Reference URL`: DOI or digital link pointing to the original publication.
* `Citation`: Formatted academic citation (Harvard/APA style).

#### 2. Bilingual Dataset Headers (`data-bilingual.csv`)
* `Academic Concept (EN)`: Concept name in English.
* `Academic Concept (AR)`: Concept name in Arabic.
* `Concept URL (EN)`: Link to the English semantic analysis.
* `Concept URL (AR)`: Link to the Arabic semantic analysis.
* `Subcategory`: Academic sub-discipline.
* `Reference Title`: Reference title.
* `Reference URL`: External publication URL.
* `Citation (EN)`: Formatted English citation.
* `Citation (AR)`: Formatted Arabic citation.

### 📖 Access & Usage

This data is provided under open-source terms. If you use this dataset in your scientific research, academic project, or software application, please cite our platform as the source:

> **To read the full semantic analyses, interactive concept networks, and detailed maps, visit [Smarticle](https://smarticle.tech/en).**

---

<a id="arabic-version"></a>
## 🇸🇦 النسخة العربية

يحتوي هذا المستودع على قاعدة البيانات المفتوحة الرسمية للمصادر الأكاديمية، الكتب، والأوراق البحثية الموثقة في موسوعة **[سمارتيكل](https://smarticle.tech/ar)** ثنائية اللغة، حيث يتم ربط كل مرجع مباشرة بمفهومه المعرفي المقابل.

### 📊 إحصائيات النسخة الحالية
* **المفاهيم / المقالات المغطاة**: 290 مفهوماً أكاديمياً.
* **إجمالي المصادر**: 2190+ مرجعاً موثقاً.
* **التخصصات**: 11 تخصصاً أكاديمياً (العلوم، الطب، التقنية، التاريخ، الفلسفة، والمزيد).

### 📂 هيكل المستودع

تُقسّم قاعدة البيانات إلى مجلدات تمثل التخصصات الأكاديمية الرئيسية. يحتوي كل مجلد على ملف README فرعي مستقل يربط المفاهيم والروابط، بالإضافة إلى البيانات بثلاث نسخ:
1. **النسخة العربية (`data-ar.json` / `data-ar.csv`)**: بيانات عربية بالكامل تربط المفاهيم بمراجعها باللغة العربية.
2. **النسخة الإنجليزية (`data-en.json` / `data-en.csv`)**: بيانات إنجليزية بالكامل تربط المفاهيم بمراجعها باللغة الإنجليزية.
3. **النسخة الثنائية (`data-bilingual.json` / `data-bilingual.csv`)**: مطابقة كاملة جنباً إلى جنب للغتين.

| المجلد | التخصص الأكاديمي | المفاهيم | المراجع | القسم على موقعنا |
| :--- | :--- | :--- | :--- | :--- |
| **المجموع الكلي** | **جميع التخصصات** | **290** | **2190** | **[smarticle.tech](https://smarticle.tech/ar)** |
| [`/arts`](./arts) | 🎨 الفنون والآداب | 26 | 215 | [سمارتيكل - 🎨 الفنون والآداب](https://smarticle.tech/ar/category/arts) |
| [`/business`](./business) | 💼 الأعمال والتمويل | 25 | 211 | [سمارتيكل - 💼 الأعمال والتمويل](https://smarticle.tech/ar/category/business) |
| [`/geography`](./geography) | 🌍 الجغرافيا وعلوم الأرض | 25 | 201 | [سمارتيكل - 🌍 الجغرافيا وعلوم الأرض](https://smarticle.tech/ar/category/geography) |
| [`/history`](./history) | 📜 التاريخ والحضارات | 23 | 155 | [سمارتيكل - 📜 التاريخ والحضارات](https://smarticle.tech/ar/category/history) |
| [`/languages`](./languages) | 🗣️ اللغات واللسانيات | 24 | 171 | [سمارتيكل - 🗣️ اللغات واللسانيات](https://smarticle.tech/ar/category/languages) |
| [`/medicine`](./medicine) | 🩺 الطب والصيدلة | 30 | 239 | [سمارتيكل - 🩺 الطب والصيدلة](https://smarticle.tech/ar/category/medicine) |
| [`/philosophy`](./philosophy) | ⚖️ الفلسفة والمنطق | 25 | 179 | [سمارتيكل - ⚖️ الفلسفة والمنطق](https://smarticle.tech/ar/category/philosophy) |
| [`/religion`](./religion) | 🕌 الأديان والدراسات المقارنة | 24 | 201 | [سمارتيكل - 🕌 الأديان والدراسات المقارنة](https://smarticle.tech/ar/category/religion) |
| [`/science`](./science) | 🔬 العلوم والرياضيات | 28 | 201 | [سمارتيكل - 🔬 العلوم والرياضيات](https://smarticle.tech/ar/category/science) |
| [`/society`](./society) | 👥 المجتمع والعلوم الاجتماعية | 31 | 204 | [سمارتيكل - 👥 المجتمع والعلوم الاجتماعية](https://smarticle.tech/ar/category/society) |
| [`/tech`](./tech) | 💻 التقنية والحوسبة | 29 | 213 | [سمارتيكل - 💻 التقنية والحوسبة](https://smarticle.tech/ar/category/tech) |

### 📊 مواصفات البيانات

#### 1. رؤوس النسخة العربية (`data-ar.csv`)
* `المفهوم الأكاديمي`: الكيان المعرفي أو المفهوم العلمي الموثق في سمارتيكل.
* `رابط المفهوم على سمارتيكل`: رابط التحليل المعرفي للمفهوم على المنصة.
* `التخصص الفرعي`: التخصص الأكاديمي الفرعي.
* `عنوان المرجع الأكاديمي`: عنوان المرجع الأكاديمي أو الكتاب المقتبس.
* `رابط المرجع المباشر`: الرابط المباشر للمرجع الأصلي (DOI، أرشيف الإنترنت، إلخ).
* `التوثيق المنسق`: التوثيق البيبليوغرافي المنسق باللغة العربية.

#### 2. رؤوس النسخة الثنائية (`data-bilingual.csv`)
* `Academic Concept (EN)`: المفهوم الأكاديمي بالإنجليزية.
* `Academic Concept (AR)`: المفهوم الأكاديمي بالعربية.
* `Concept URL (EN)`: رابط المفهوم بالإنجليزية.
* `Concept URL (AR)`: رابط المفهوم بالعربية.
* `Subcategory`: التخصص الأكاديمي الفرعي.
* `Reference Title`: عنوان المرجع الأكاديمي.
* `Reference URL`: الرابط المباشر للمرجع.
* `Citation (EN)`: التوثيق المنسق بالإنجليزية.
* `Citation (AR)`: التوثيق المنسق بالعربية.

### 📖 الاستخدام المفتوح

هذه البيانات متوفرة كمصادر مفتوحة للجميع. إذا كنت تستخدم هذه المجموعات في أبحاثك العلمية أو مشاريعك البرمجية، نرجو الإشارة إلى موقعنا كمصدر رسمي:

> **لقراءة التحليلات المعرفية الكاملة، واستكشاف شبكات المفاهيم التفاعلية، تفضل بزيارة [منصة سمارتيكل](https://smarticle.tech/ar).**

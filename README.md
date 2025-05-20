# Bank Marketing Campaign Classification

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)   
3. [Key Components](#key-components)  
4. [Contact](#contact)  

---

## Project Overview
Model klasifikasi ini bertujuan memprediksi kolom `deposit` (yes/no) untuk kampanye marketing produk deposito berjangka di Bank Sejahtera.  
- **Business goal**: Maksimalkan *recall* calon depositor, minimalkan false negatives.  
- **Technical goal**: Membangun pipeline end-to-end dengan metrik utama F₂-score (β=2), lalu menetapkan threshold dan strategi outreach berbasis ROI.

---

## Dataset
- **Raw data**: `data/raw/data_bank_marketing_campaign.csv`  
- **Ukuran**: 7.813 baris × 11 kolom  

**Fitur utama**  
- Numerik: `age`, `balance`, `campaign`, `pdays`  
- Kategorikal: `job`, `housing`, `loan`, `contact`, `month`, `poutcome`  
- Target: `deposit` (yes/no)

---
## Key Components
F₂-score: Metrik utama, β=2 untuk menekankan recall.

Random Forest (tuned): Model terbaik dengan F₂(test)=0.815 (threshold=0.10).

Tiered ROI Analysis: Segmentasi Low/Medium/High, perhitungan calls, revenue, cost, ROI, dan alokasi budget.


---
## Contact

Hasson Josia Siregar

📧 josiasiregar@gmail.com

# Analisis Sentimen Opini Publik Terhadap Demo DPR di X
## Project Overview
##### Proyek ini menganalisis opini publik terkait demo DPR di Indonesia melalui data Twitter. Fokus utama adalah melihat persepsi masyarakat apakah cenderung positif, negatif, atau netral dengan bantuan metode Artificial Intelligence (AI).
## Dataset
[demo_dpr.csv]
## Insight & Findings
##### Mayoritas tweet bernada netral (98.3%), diikuti negatif (1.0%) dan positif (0.8%). Opini negatif banyak berisi kritik terhadap DPR, isu tunjangan, dan ketidakadilan. Opini positif cenderung berupa dukungan terhadap demo dan solidaritas publik.
## AI Support Explanation
##### LLM Agent (LangChain) → eksplorasi dataset dengan query natural language.  
##### Transformers Pipeline → klasifikasi sentimen (positif, negatif, netral).
##### Summarization (mT5) → merangkum opini publik agar lebih mudah dipahami.

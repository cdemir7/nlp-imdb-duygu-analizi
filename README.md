# 🎬 NLP ile IMDB Duygu Analizi (Sentiment Analysis)

Bu proje, Kaggle'dan alınan IMDB film yorumları veri setini kullanarak, yorumların **olumlu (positive)** mu yoksa **olumsuz (negative)** mu olduğunu tahmin eden bir Makine Öğrenmesi modeli geliştirir.

Projede sınıflandırma algoritması olarak **Random Forest Classifier** kullanılmıştır.

## 📂 Proje İçeriği

* `NLP_IMDB_Duygu_Analizi.py`: Veri ön işleme, model eğitimi ve test adımlarını içeren ana Python dosyası.
* `NLPlabeledData.tsv`: Modelin eğitilmesi ve test edilmesi için kullanılan etiketli veri seti.

## ⚙️ Kullanılan Teknolojiler ve Kütüphaneler

Proje **Python** dili ile geliştirilmiş olup, aşağıdaki temel kütüphaneleri kullanmaktadır:

* **Pandas:** Veri okuma ve manipülasyonu için.
* **Scikit-learn:** Makine öğrenmesi modeli (Random Forest) ve vektörleştirme (CountVectorizer/Tfidf) işlemleri için.
* **NLTK (Natural Language Toolkit):** Metin temizleme, stop words (etkisiz kelimeler) temizliği ve ön işleme adımları için.
* **NumPy:** Sayısal işlemler için.

## 🚀 Kurulum

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

1.  **Repoyu klonlayın:**
    ```bash
    git clone [https://github.com/cdemir7/nlp-imdb-duygu-analizi.git](https://github.com/cdemir7/nlp-imdb-duygu-analizi.git)
    cd nlp-imdb-duygu-analizi
    ```

2.  **Gerekli kütüphaneleri yükleyin:**
    Eğer yüklü değillerse, terminal veya komut satırında şu komutu çalıştırın:
    ```bash
    pip install pandas numpy scikit-learn nltk
    ```

## 💻 Kullanım

Modeli eğitmek ve sonuçları görmek için ana Python dosyasını çalıştırın:

```bash
python NLP_IMDB_Duygu_Analizi.py

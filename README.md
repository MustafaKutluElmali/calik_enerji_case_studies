Notebook dosyalarında bazı istenenler için birden fazla çözüm ekledim, 
özellikle histogram çizdirirken birden fazla şekilde çizidirdim / gösterdim, 
bu çözümlerin bazıları benim çözümlerim, bazıları da başka çözümleri incelerken / araştırıken bulduğum, beğendiğim ve eklemek istediğim çözümler.

Genel Özet 
# ⚡ İleri Veri Analitiği Case Study Çalışmaları

Bu depo (repository), İleri Veri Analitiği eğitimi kapsamında hazırladığım iki ana vaka çalışmasını (Case Study) içermektedir. Projeler; enerji perakende ve elektrik dağıtım sektörlerine ait gerçek dünya verileri üzerine kurgulanmıştır.

## 📂 Proje Yapısı

* **case_study_01_perakende/**: Amasya ilindeki 3 ilçeye ait elektrik tüketim ve tahsilat analizleri.
    * `notebook_01_veri_kesfi.ipynb`: Veri temizleme ve temel istatistikler.
    * `notebook_02_gorsellestirme.ipynb`: Zaman serisi ve ilçe bazlı görselleştirmeler.
    * `notebook_03_storytelling.ipynb`: Ödeme alışkanlıkları ve sonuç raporu.
* **case_study_02_og_olcum/**: OG (Orta Gerilim) hattı ölçüm verileri ve anomali tespiti.
    * `2_og_olcum_analizi.ipynb`: Veri ön işleme ve keşifçi analiz.
    * `03_tahmin_modeli.ipynb`: Kural tabanlı anomali tespiti ve istatistiksel tahminleme.

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
* **Dil:** Python
* **Kütüphaneler:** Pandas, NumPy, Matplotlib, Seaborn
* **Analiz Yöntemleri:** Veri Temizleme, Zaman Serisi Analizi (Resampling), İstatistiksel Anomali Tespiti.

## 🚀 Nasıl Çalıştırılır?
1. Bu repoyu bilgisayarınıza indirin (Clone).
2. Terminale `pip install -r requirements.txt` yazarak gerekli kütüphaneleri yükleyin.
3. Jupyter Notebook veya VS Code üzerinden `.ipynb` dosyalarını sırayla çalıştırın.

## 📈 Önemli Bulgularım
* Amasya verilerinde ortalama tüketimin 92.6 kWh olduğunu doğruladım.
* Tahsilat verilerinde, ödemelerin büyük çoğunluğunun vade tarihinden sonraki ilk 5 gün içinde yapıldığını gözlemledim.
* OG ölçüm verilerinde; faz dengesizliği ve tüketim-akım uyumsuzluğu üzerinden potansiyel arıza/kaçak noktalarını tespit eden kurallar geliştirdim.

---
**Hazırlayan:** [Adın Soyadın]
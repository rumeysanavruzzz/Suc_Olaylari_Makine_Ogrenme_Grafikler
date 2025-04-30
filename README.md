🤖 Makine Öğrenmesi Uygulamaları – Jupyter Notebook Projeleri
Bu projede, makine öğrenmesi (ML) konusuna yönelik temel ve orta düzey uygulamaları içeren Jupyter Notebook dosyalarını barındırmaktadır. Proje kapsamında iki ana çalışma yer almakta olup, her biri farklı algoritmalarla, veri setleriyle ve modelleme süreçleriyle ilgili adımları içermektedir.

Makine öğrenmesine ilgi duyan, öğrenmeye yeni başlayan ya da pratik yapmak isteyen herkesin faydalanabileceği bir kaynak olması amaçlanmıştır.

📂 İçerikler
🔹 Makine_Ögrenme.ipynb
Bu ilk defterde, makine öğrenmesinin temel adımları adım adım işlenmiştir. İçerikte yer alan konular:

Veri Kümesi Tanıtımı ve Yükleme: CSV formatında veri yükleme ve ön izleme işlemleri.

Veri Temizleme ve Hazırlama:

Eksik değerlerin tespiti ve giderilmesi

Gerekli kolonların seçimi

Kategorik verilerin dönüştürülmesi (Label Encoding / One-Hot Encoding)

Veri Görselleştirme: Verinin dağılımı, korelasyon analizi, grafiklerle yorumlama (Matplotlib, Seaborn).

Veri Kümesinin Ayrılması: Eğitim ve test verisinin ayrılması (train_test_split).

Modelleme:

DecisionTreeClassifier

KNeighborsClassifier

LogisticRegression gibi temel sınıflandırma algoritmaları.

Model Performans Analizi:

Doğruluk oranı, karışıklık matrisi (confusion matrix)

Sınıflandırma raporu (precision, recall, F1-score)

Sonuçların Karşılaştırılması: Farklı algoritmaların başarım metrikleriyle kıyaslanması.

🔹 Makine_Ögrenme_2.ipynb
İkinci defterde, daha gelişmiş modelleme örnekleri yer almakta ve farklı veri setleriyle algoritmaların uygulanabilirliği test edilmektedir.

Alternatif Veri Setleri ile Çalışma: UCI Machine Learning Repository gibi kaynaklardan alınan veriler.

Model Eğitimi ve Hiperparametre Ayarlamaları:

GridSearchCV ile en iyi parametrelerin bulunması

Overfitting (aşırı öğrenme) ve underfitting (eksik öğrenme) gibi problemler üzerine deneysel gözlemler

Model Karşılaştırmaları: Karar ağacı, Naive Bayes, k-NN gibi modellerin doğruluk değerleri.

Model Kaydetme ve Yükleme: joblib veya pickle ile eğitilen modelin dosyaya kaydedilmesi ve yeniden kullanımı.

🔧 Kullanılan Kütüphaneler ve Teknolojiler

Kütüphane	Kullanım Amacı
pandas	Veri okuma, işleme ve analiz
numpy	Sayısal işlemler
matplotlib	Görselleştirme
seaborn	İleri düzey görselleştirme
scikit-learn	Makine öğrenmesi modelleri ve metrikler
joblib/pickle	Model saklama ve yeniden yükleme


Hedef ve Amaç
Bu projeler, makine öğrenmesi ile ilgilenen bireylerin modelleme süreçlerini daha iyi kavrayabilmesi için hazırlanmıştır. Amaç yalnızca modelleri uygulamak değil, aynı zamanda:

Verinin yapısını anlayarak doğru ön işlemleri yapmak,

Uygun algoritmaları seçmek,

Model başarısını ölçmeyi öğrenmek,

Gerçek dünya verileri üzerinde analiz pratiği kazanmaktır.

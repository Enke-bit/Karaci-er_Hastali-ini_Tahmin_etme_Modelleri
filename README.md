## Karaçiğer Hastalığı Tahmini için Makine Öğrenimi Modellerinin Karşılaştırılması

## Bu proje, karaçiğer hastalığının tahmin edilmesi için çeşitli makine öğrenimi modellerinin performansını değerlendirmeyi ve en etkili modeli belirlemeyi amaçlamaktadır. Ayrıca, bu çalışma gelecek araştırmalar için bir temel oluşturarak, klinik uygulamalarda kullanılabilecek potansiyel modelleri ortaya koymayı hedeflemektedir.

## Kullanılan Modeller ve Sonuçlar:

- K En Yakın Komşu (KNN):

Accuracy: 0.774
Precision (0/1): 0.76 / 0.78
Recall (0/1): 0.76 / 0.79
F1-score (0/1): 0.76 / 0.78

- Yapay Sinir Ağları (ANN):

Accuracy: 0.853
Precision (0/1): 0.91 / 0.81
Recall (0/1): 0.77 / 0.93
F1-score (0/1): 0.83 / 0.87

- Destek Vektör Makineleri (SVM):

Accuracy: 0.774
Precision (0/1): 0.79 / 0.76
Recall (0/1): 0.72 / 0.83
F1-score (0/1): 0.75 / 0.79

- Karar Ağaçları:

Accuracy: 0.838
Precision (0/1): 0.86 / 0.82
Recall (0/1): 0.78 / 0.89
F1-score (0/1): 0.82 / 0.85

- Rastgele Ormanlar:

Accuracy: 0.897
Precision (0/1): 0.93 / 0.87
Recall (0/1): 0.85 / 0.94
F1-score (0/1): 0.89 / 0.91

- Logistik Regresyon:

Accuracy: 0.809
Precision (0/1): 0.83 / 0.80
Recall (0/1): 0.76 / 0.85
F1-score (0/1): 0.79 / 0.82

## Bu çalışma, karaçiğer hastalığı tahmininde Rastgele Ormanlar modelinin en yüksek doğruluğu (%89.7) sağladığını göstermiştir. Bu model, hem hassasiyet hem de geri çağırma açısından diğer modellere göre daha üstün performans sergilemiştir. Yapay Sinir Ağları da (%85.3) yüksek bir doğruluk elde etmiş olup, ikinci en iyi performans gösteren model olarak belirlenmiştir.

## Diğer modellerin performansı ise genel olarak %77 ile %84 arasında değişmektedir. Bu modellerin her birinin güçlü ve zayıf yönleri dikkate alınarak, gelecek çalışmalarda daha ileri düzeyde doğruluk ve güvenilirlik sağlayacak yeni yöntemlerin araştırılması önerilmektedir.


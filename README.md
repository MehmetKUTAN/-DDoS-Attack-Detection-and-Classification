# DDoS Saldırı Tespiti ve Sınıflandırması

## Proje Özeti

Dağıtılmış Hizmet Engelleme (DDoS) saldırıları, sistemleri kötü niyetli trafikle aşırı yükleyerek hizmet kesintilerine yol açan önemli ağ güvenlik tehditleri oluşturur. Bu proje, ağ trafiği verilerini kullanarak DDoS saldırılarını tespit etmek ve sınıflandırmak için makine öğrenimi tabanlı bir model geliştirmeyi amaçlamaktadır. Ana hedef, normal ağ trafiği ile DDoS saldırı trafiği arasında ayrım yapabilen sağlam ve doğru bir model oluşturmaktır.

## Depo İçeriği

- `ddos-attack-detection-classification.ipynb`: Veri analizi, önişleme, özellik mühendisliği, model eğitimi, değerlendirme ve optimizasyon için gerekli tüm kodları içeren Jupyter Defteri.
- `dataset_sdn.csv`: Modellerin eğitimi ve değerlendirilmesi için kullanılan veri kümesi. Normal ve saldırı trafiği için çeşitli ağ trafiği özelliklerini ve etiketleri içerir.

## Kurulum ve Gereksinimler

Defteri çalıştırmak için aşağıdaki Python kütüphanelerinin kurulması gerekmektedir:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Bu bağımlılıkları pip kullanarak yükleyin:
```
pip install pandas numpy matplotlib seaborn scikit-learn
 ```


## Kullanım
Veri Kümesini Yükleme
Veri kümesini (dataset_sdn.csv) analiz için bir pandas DataFrame'e aktarın.

 ## Veri Önişleme
Eksik verileri işlemek, özellikleri normalleştirmek ve kategorik değişkenleri kodlamak için veriyi temizleyin ve önişleyin.

## Proje İş Akışı
- ` Veri Yükleme ve İlk Keşif: Veri kümesini yükleyin ve yapısını ve içeriğini anlamak için ilk keşif analizini yapın.`
- ` Veri Önişleme: Veriyi temizleyin ve model eğitimi için uygun hale getirin.`
- ` Özellik Mühendisliği: Yeni özellikler oluşturun ve önemli olanları seçin.`
- ` Model Eğitimi: İşlenmiş veri üzerinde çeşitli makine öğrenimi modellerini eğitin.`
- ` Model Değerlendirme: Modelleri uygun değerlendirme metrikleri kullanarak değerlendirin ve sonuçları görselleştirin.`
- ` Model Optimizasyonu: Hiperparametre ayarı ile model performansını optimize edin.`
- ` Sonuçların Yorumlanması: Her modelin güçlü ve zayıf yönlerini vurgulayarak sonuçları analiz edin ve yorumlayın.`

## Sonuç
Bu proje, makine öğrenimi kullanarak DDoS saldırılarını tespit etmek ve sınıflandırmak için kapsamlı bir yaklaşımı göstermektedir. Belirtilen adımları izleyerek, ağ güvenliği uygulamaları için modellerin oluşturulması ve değerlendirilmesi sürecini baştan sona anlayabilirsiniz. Sağlanan veri kümesi ve kod, siber güvenliğin bu kritik alanında daha fazla deney ve iyileştirme için bir temel oluşturur.

Lisans
 `Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın. `

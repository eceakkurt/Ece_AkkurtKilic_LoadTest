# Ece Akkurt Kılıç - Load Test Repository

Bu repository, **JMeter** kullanarak yapılan yük testlerini içerir. **Web, mobil ve servis testleri** için performans test senaryoları geliştirilmiştir.

## 📌 İçerik

- **JMeter Test Planları**: Web, API ve mobil uygulamalar için hazırlanmış test planları.
- **Test Senaryoları**: Kullanıcı akışlarını içeren detaylı test senaryoları.
- **Raporlama**: JMeter raporlarının nasıl oluşturulacağına dair yönergeler.
- **Konfigürasyon Dosyaları**: Testlerin özelleştirilmesi için gerekli ayarlar.

## 🚀 Başlangıç

### Gereksinimler
- [Apache JMeter](https://jmeter.apache.org/) kurulumu gereklidir.
- Java 8 veya üzeri yüklü olmalıdır.

### Kurulum
1. Bu repository'yi klonlayın:
   ```sh
   git clone https://github.com/eceakkurt/Ece_AkkurtKilic_LoadTest.git
   ```
2. JMeter'i açarak **.jmx** dosyalarını yükleyin.
3. Testleri çalıştırın ve sonuçları inceleyin.

## 📊 Raporlama
JMeter, test sonuçlarını **HTML, CSV, ve XML** formatlarında raporlayabilir. Aşağıdaki komut ile test sonucunu HTML olarak alabilirsiniz:
```sh
jmeter -n -t test-plan.jmx -l results.jtl -e -o report-folder
```

## 📞 İletişim
Herhangi bir soru için benimle iletişime geçebilirsiniz!

## Sonuçlar
![image](https://github.com/user-attachments/assets/bf451509-52f5-4544-bba8-7ee6cda6eccb)

Sayıdan Mors Alfabesine Dönüştürücü (C)
Bu proje, bir metin dosyasındaki rakamları (0-9) okuyarak karşılık gelen Mors alfabesi sembollerine dönüştüren ve sonucu başka bir dosyaya kaydeden basit bir C programıdır.
Özellikler
Dosya Okuma: Hatalar.dat (veya belirtilen herhangi bir dosya) içerisindeki verileri karakter karakter analiz eder.
Hata Yönetimi: Dosyanın bulunamaması veya açılamaz olması durumunda kullanıcıyı bilgilendirir.
Genişletilmiş Yazma: Mevcut Mors.txt dosyasının üzerine yazmaz, sonuçları dosyanın sonuna ekler (append modu).
Format Koruma: Boşlukları ve satır sonlarını (\n) koruyarak okunabilirliği artırır.
Dosya Adı,Açıklama
main.c,Programın kaynak kodu.
Hatalar.dat,Okunacak kaynak verileri içeren giriş dosyası.
Mors.txt,Dönüştürülen Mors kodlarının kaydedildiği çıktı dosyası.
Önemli Notlar
Program şu an için sadece rakamları desteklemektedir. Harf veya özel karakterler (boşluk hariç) göz ardı edilir.
Mors.txt dosyası her çalıştırmada güncellenir, önceki veriler korunur.

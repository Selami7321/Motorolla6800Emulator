# Motorolla6800Emulator
Motorola 6800 Assembler & Interactive Simulator
Proje Tanımı
Bu proje, Motorola 6800 işlemci mimarisi için modern, görsel ve etkileşimli bir assembler ve simülatör ortamı sağlar. Amacımız, assembly kodunu satır-satır makine koduna çeviren ve gerçek zamanlı olarak simüle eden, eğitim odaklı ve kullanıcı dostu bir yazılım geliştirmekti. Özellikle bilgisayar mühendisliği ve sistem programlama eğitimlerinde, öğrencilerin assembly dilini ve mikroişlemci mimarisini derinlemesine anlamalarını kolaylaştırmak için tasarlanmıştır.

Kullanılan Teknolojiler
Python 3.11+: Hızlı geliştirme, platformlar arası uyumluluk ve kolay bakım için.

Tkinter: Modern ve sezgisel grafik arayüz.

Matplotlib: Simülasyon sırasında CPU performansı ve istatistiklerin görselleştirilmesi.

Özel Assembler & Simülatör Çekirdeği: Komut seti desteği, opcode/operand çözümleme ve gerçek zamanlı bellek/register simülasyonu tamamen özgün olarak Python’da geliştirildi.

Temel Özellikler
Assembly Kod Editörü: Kullanıcı, assembly kodunu doğrudan arayüzden yazabilir veya dosyadan yükleyebilir.

Satır-Satır Çeviri Tablosu: Her komutun adres ve makine kodu eşleşmesini gösterir.

Breakpoint ve Koşullu Durma: Satır bazında breakpoint, istenirse koşullu durdurma (ör. A==5 olunca dur).

Adım Adım ve Hızlı Simülasyon: Hem tek adımda, hem topluca simülasyon imkânı.

Register ve Bellek Takibi: A, B, X, PC, SP gibi tüm ana register’ların ve RAM’in canlı izlenmesi.

Stack Viewer: Stack işlemleri ve alt program (JSR/RTS) akışının görselleştirilmesi.

Simülasyon Logları: Her adımda yapılan işlemler ve olaylar kaydedilip kullanıcıya gösterilir.

Bellek ve CPU Analizi: Hex ve ASCII gösterimli bellek penceresi, komut istatistikleri ve döngü analizleri.

Modern, Türkçe GUI: Sezgisel ve kullanıcı odaklı renkli arayüz.

Sistem Mimarisi
Assembler6800: Assembly kodunu makine koduna çevirir, label ve opcode çözümlemesi yapar.

Simulator6800: Makine kodunu gerçek bir 6800 CPU gibi simüle eder, adım adım çalıştırır.

AssemblerUI: Tkinter tabanlı görsel arayüz; kod editörü, sonuç tablosu, simülasyon kontrolleri ve istatistik gösterimi içerir.

Eğitim ve Katma Değer
Bu projede, gerçek donanımda gözlemlenmesi zor olan stack, register, RAM ve breakpoint akışları, öğrencinin adım adım izleyebileceği şekilde görselleştirildi. Assembler ve simülatör çekirdeği, gerçek 6800 komut setiyle tam uyumlu olarak sıfırdan geliştirildi. Sonsuz döngü tespiti, hatalı kod uyarıları ve etiket/branch analizleriyle hata ayıklama süreçleri kolaylaştırıldı.

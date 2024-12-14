# Bilgisayar Sistem Simülatörü

Bu proje, temel bir bilgisayar sistemini simüle eden basit bir programdır. CPU, RAM ve Sabit Disk gibi temel donanım bileşenlerinin çalışmasını gösterir.

## Özellikler

- CPU simülasyonu (hız, sıcaklık ve kullanım takibi)
- RAM simülasyonu (veri yazma/okuma)
- Sabit Disk simülasyonu (dosya kaydetme/okuma)
- Temel bilgisayar işlemleri:
  - Açma/Kapama
  - Program çalıştırma
  - Dosya kaydetme
  - Sistem durumu görüntüleme

## Kullanım

Program çalıştırıldığında menüden istenen işlem seçilir:

1. Bilgisayarı Aç: Sistemi başlatır
2. Bilgisayarı Kapat: Sistemi kapatır
3. Program Çalıştır: RAM'e program yükler ve CPU'da işler
4. Dosya Kaydet: Sabit diske dosya kaydeder
5. Sistem Durumunu Göster: Tüm bileşenlerin durumunu gösterir
6. Çıkış: Programı sonlandırır

## Teknik Detaylar

- Java 8 ile geliştirilmiştir
- Maven kullanılarak derlenebilir
- Konsoldan kullanıcı girişi alır
- Simüle edilen sistem özellikleri:
  - 2000 MHz CPU
  - 1024 MB RAM
  - 500 GB Sabit Disk

## Derleme ve Çalıştırma

```bash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.computer.Main"
```

## Yazar

Yahya Efe Kuruçay

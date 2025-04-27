# Sahibinden.com URL Testi (Cucumber + Java)

Bu proje, sahibinden.com ana sayfasının açılıp açılmadığını Cucumber ve Selenium ile test eder.

## Kullanım

1. Java 11+ ve Maven yüklü olmalı.
2. Chrome ve uygun ChromeDriver sistemde bulunmalı.
3. Testi çalıştırmak için kök dizinde şu komutu kullan:

```
mvn test
```

## Yapı
- `src/test/resources/features/UrlTest.feature`: Test senaryosu.
- `src/test/java/stepdefs/UrlStepDefs.java`: Step definition dosyası.
- `src/test/java/runner/RunCucumberTest.java`: Test runner.

## Rapor
Test sonrası `target/cucumber-report.html` altında HTML raporu oluşur.

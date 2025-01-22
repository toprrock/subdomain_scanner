# Subdomain Scanner

Hedef domainler için subdomain taraması yapan Python tabanlı bir araç.

## Özellikler

- DNS taraması
- SSL sertifika kontrolü
- HTTP durum kontrolü
- Aktif/Pasif tarama modları
- Çoklu thread desteği
- JSON formatında çıktı

## Gereksinimler

- Python 3.8 veya üzeri
- pip (Python paket yöneticisi)
- Git (projeyi klonlamak için)

## Kurulum

1. Repo'yu klonlayın:
```bash
git clone https://github.com/toprrock/subdomain_scanner.git
cd subdomain_scanner

Tüm parametrelerle kullanım:
bashCopypython subdomain_scanner.py --domain example.com --mod tam --thread 10 --

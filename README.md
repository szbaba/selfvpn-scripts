SelfVPN Outline Installation Script
This repository contains a bash script used for the automated installation of the Outline VPN server on Google Cloud VMs.

Purpose
The SelfVPN app and similar automation tools can use this script to perform one-click Outline VPN installation on Google Cloud.
The script installs the Outline server using Docker and performs the necessary initial configuration automatically.
Installation Script
You can run the install_outline.sh file directly on your Google Cloud VM.
The script is based on the official Outline installation script and can be customized as needed.
Manual Installation
After connecting to your VM via SSH, run:

sh
CopyInsert
curl -sS https://raw.githubusercontent.com/szbaba/selfvpn-scripts/main/install_outline.sh | sudo bash
Once the installation is complete, the Outline admin access key and port information will be displayed.

Customization
You can modify the script to suit your needs.
You may add advanced logging, error handling, or additional security steps.
Support
If you encounter any issues or have suggestions, please open an issue on Github.

Note:
This script is designed to work on Google Cloud VMs. If you use a different cloud provider, make sure to check your network/firewall settings.

You can copy this directly into your README.md file. If you want to change the username or repo name, just let me know!




SelfVPN Outline Kurulum Scripti
Bu repoda, Google Cloud VM’ler üzerinde Outline VPN sunucusunun otomatik kurulumu için kullanılan bash scripti bulunmaktadır.

Kullanım Amacı
SelfVPN uygulaması veya benzeri otomasyon araçları, bu scripti kullanarak Google Cloud üzerinde tek tıkla Outline VPN kurulumunu gerçekleştirebilir.
Script, Docker ile Outline sunucusunu kurar ve gerekli ilk yapılandırmayı otomatik yapar.
Kurulum Scripti
install_outline.sh dosyasını doğrudan Google Cloud VM üzerinde çalıştırabilirsiniz.
Script, Outline’ın orijinal kurulum scriptine dayalıdır ve gerektiğinde özelleştirilebilir.
Manuel Kurulum
SSH ile VM’ye bağlandıktan sonra:

sh
CopyInsert
curl -sS https://raw.githubusercontent.com/szbaba/selfvpn-scripts/main/install_outline.sh | sudo bash
Kurulum tamamlandığında, Outline yönetici bağlantı anahtarı ve port bilgileri ekrana yazdırılır.

Özelleştirme
Scripti kendi ihtiyaçlarınıza göre düzenleyebilirsiniz.
Gelişmiş loglama, hata yönetimi veya ek güvenlik adımları ekleyebilirsiniz.
Destek
Herhangi bir sorunla karşılaşırsanız veya öneriniz varsa, Github Issues üzerinden bildirebilirsiniz.

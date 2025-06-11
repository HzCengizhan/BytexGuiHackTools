# BytexGuiHackTools


BytexGuiHackTool
Hakkında

BytexGuiHackTool, BytexHackTools’un grafik arayüzlü (GUI) versiyonudur. Siber güvenlik araçlarını kolayca ve görsel olarak kullanabilmen için tasarlanmıştır. Parola üretici, hash oluşturucu, Tor IP değiştirici, payload üretici ve daha fazlası tek uygulamada!
Kurulum ve Kullanım

Öncelikle repoyu bilgisayarına klonla ve dizine geç:

git clone https://github.com/HzCengizhan/BytexGuiHackTools.git

cd BytexGuiHackTools

Derlenmiş GUI uygulamayı çalıştırmak için:

Öncelikle dosyaya çalıştırma izni ver:

chmod +x BytexGuiHackTools

Ardından programı çalıştır:

./BytexGuiHackTools

Notlar:

    Python ya da ek kütüphane kurulumuna gerek yoktur. Uygulama PyInstaller ile bağımsız hale getirilmiştir.

    Root yetkisi gerektiren işlemler için (örneğin Tor IP değiştirme) yetkili kullanıcı olmalısınız.

    Nmap, msfvenom, searchsploit gibi sistem araçlarının kurulu ve erişilebilir olması gerekir.

    Linux tabanlı sistemlerde (Kali Linux önerilir) çalıştırılması tavsiye edilir.

Özellikler

    Parola Üretici: Rastgele güçlü parolalar oluşturur.

    Hash Oluşturucu: MD5, SHA1, SHA256, SHA512 algoritmaları ile hash hesaplar.

    Tor IP Değiştirici: Tor ağı üzerinden anonim IP değiştirir, otomatik IP değiştirme seçeneği vardır.

    Hash Cracker: Sözlük tabanlı hash kırma desteği sunar.

    Admin Panel Bulucu: Yaygın admin panel yollarını hedef sitede kontrol eder.

    Payload Üretici: Metasploit msfvenom kullanarak ters bağlantı payload’ları oluşturur (Windows, Android, Python).

    Nmap ile Ağ Taraması: Hızlı port taraması, servis ve versiyon tespiti, işletim sistemi belirleme.

    Exploit Arama: Searchsploit komutuyla anahtar kelime bazlı exploit arama.

    Kullanıcı Dostu GUI Arayüzü: Tüm araçlar görsel ve kolay menülerle yönetilebilir.

Güncellemeler

BytexGuiHackTool’un yeni sürümleri ve güncellemeleri bu repoya yüklenecektir. Takip etmeyi unutmayın!
Dikkat

    Root yetkisi gerektiren komutları çalıştırmak için uygun yetkiye sahip olmalısınız.

    Bazı işlemler arka planda iptables, Tor servisi gibi sistem araçlarını kullanır.

    Yazılımın etik ve yasal sınırlar içinde kullanılması önemlidir.

İletişim

Sorularınız veya önerileriniz için repoda issue açabilirsiniz.

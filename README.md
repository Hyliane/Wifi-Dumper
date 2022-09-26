# Wifi-Dumper
Bu, Windows makinesindeki bağlı erişim noktalarının wifi profillerini ve açık metin şifrelerini boşaltmak için açık kaynaklı bir araçtır. Bu araç bir Wifi testinde size yardımcı olacaktır. Ayrıca, kırmızı ekip veya dahili altyapı angajmanları gerçekleştirirken kullanışlıdır.
![image](https://user-images.githubusercontent.com/106737906/192343675-e73118f3-8c34-4c17-8a92-e68c86541998.png)

Özellikler
Seçenek 1:Sistemin kullanabileceği kablosuz ağları gösterir. Arayüz adı verilirse sadece verilen arayüzdeki ağlar listelenecektir. Aksi takdirde, sisteme görünen tüm ağlar listelenecektir.

Seçenek 2: Sistemde yapılandırılan kablosuz profillerin bir listesini gösterir.

Seçenek 3: İzin verilen ve engellenen kablosuz ağ listesini gösterir.

Seçenek 4: Sistemdeki tüm kablosuz LAN arabirimlerinin bir listesini gösterir.

Seçenek 5: Sistemdeki her kablosuz erişim noktası profili hakkında ayrıntılı bir rapor oluşturur. Grup İlkesi Profilleri salt okunurdur. Kullanıcı Profilleri okunabilir ve yazılabilirdir ve tercih sırası değiştirilebilir.

Seçenek 6: Sistemdeki her kablosuz profilin açık metin parolalarını atar. Bu seçeneği çalıştırmadan önce profil dosyasını (seçenek 2'yi seçerek) oluşturduğunuzdan emin olun. Açık metin parolasını görmek için bunu her zaman yönetici kullanıcı olarak çalıştırın. Kullanıcının profil adlarını okuyarak bireysel kablosuz adı sağlaması gerekir (seçenek 7).

Seçenek 7: Sistemdeki kablosuz profillerin listesini not defteri kullanarak açar.

Seçenek 8: WLAN profillerini XML dosyalarına kaydeder.

Seçenek 9: Zarif bir şekilde çıkın.

Genel Notlar
 [+] Araçtaki her seçenek, çıktı olarak ".txt" dosyasını oluşturur.
 [+] Aracı birden çok kez çalıştırırsanız, çıktı önceki sonuçlara eklenir.

Uygulama nasıl çalıştırılır?
 [+] cmd.exe'yi yönetici olarak çalıştırın.
 [+] Dizini Değiştir
[+] Uygulamayı C:\>python wifi_dumper.py olarak çalıştırın

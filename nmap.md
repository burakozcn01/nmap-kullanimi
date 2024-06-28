| Parametre | Açıklama | Örnek Kullanım |
|-----------|----------|----------------|
| -sS | SYN taraması yapar | nmap -sS 192.168.1.1 |
| -sT | TCP taraması yapar | nmap -sT 192.168.1.1 |
| -sU | UDP taraması yapar | nmap -sU 192.168.1.1 |
| -O | Hedef sistemin işletim sistemini tanımlamak için tarama yapar | nmap -O 192.168.1.1 |
| -p | Belirli bir bağlantı noktasını taramak için kullanılır | nmap -p 80 192.168.1.1 |
| -oN | Tarama sonucunu belirtilen dosyaya normal formatta kaydeder | nmap -oN taramasonucu.txt 192.168.1.1 |
| -oX | Tarama sonucunu XML formatında kaydeder | nmap -oX taramasonucu.xml 192.168.1.1 |
| -oG | Tarama sonucunu grep formatında kaydeder | nmap -oG taramasonucu.gnmap 192.168.1.1 |
| -oA | Tarama sonuçlarını üç formatta birden kaydeder | nmap -oA taramasonucu 192.168.1.1 |
| -iL | Belirtilen dosyada bulunan hedef listesine tarama yapar | nmap -iL hedefliste.txt |
| -sV | Hedef sistemde çalışan servislerin sürümünü tespit etmek için kullanılır | nmap -sV 192.168.1.1 |
| -sP (veya -sn) | Ping taraması yapar | nmap -sP 192.168.1.0/24 |
| -sF | TCP FIN taraması yapar | nmap -sF 192.168.1.1 |
| -sA | TCP ACK taraması yapar | nmap -sA 192.168.1.1 |
| -sW | Belirtilen port için TCP window scan taraması yapar | nmap -sW 22 192.168.1.1 |
| -sX | Belirtilen port için TCP Xmas scan taraması yapar | nmap -sX 22 192.168.1.1 |
| -T<0-5> | Tarama hızı seviyesi belirler (0-5 arası) | nmap -T4 192.168.1.1 |
| -n | DNS çözümlemesi yapmadan tarama yapar | nmap -n 192.168.1.1 |
| -v | Ayrıntılı çıktı sağlar | nmap -v 192.168.1.1 |
| -A | Agresif tarama yapar (OS tespiti, sürüm tespiti, script taraması ve traceroute içerir) | nmap -A 192.168.1.1 |
| --script | Belirli bir script ile tarama yapar | nmap --script=banner 192.168.1.1 |
| --script-args | Script argümanları ile tarama yapar | nmap --script-args=arg=değer 192.168.1.1 |
| -f | IP paketlerini fragmente ederek tarama yapar | nmap -f 192.168.1.1 |
| -D | Decoy IP adresleri ile tarama yapar | nmap -D decoy1,decoy2 192.168.1.1 |
| -g | Belirli bir kaynak portunu kullanarak tarama yapar | nmap -g 53 192.168.1.1 |
| --proxies | Proxy sunucuları üzerinden tarama yapar | nmap --proxies http://proxy1,http://proxy2 192.168.1.1 |
| --data-length | Paketlere rastgele veri ekler | nmap --data-length 200 192.168.1.1 |
| --version-intensity | Sürüm tespit taramasının yoğunluğunu belirler (0-9 arası) | nmap --version-intensity 5 192.168.1.1 |
| --open | Sadece açık portları gösterir | nmap --open 192.168.1.1 |
| --max-rate | Saniyede gönderilecek maksimum paket sayısını belirler | nmap --max-rate 1000 192.168.1.1 |
| --script-help | Belirli bir script hakkında bilgi verir | nmap --script-help=banner |
| --top-ports | En yaygın kullanılan portları tarar | nmap --top-ports=100 192.168.1.1 |
| --packet-trace | Gönderilen ve alınan tüm paketleri gösterir | nmap --packet-trace 192.168.1.1 |
| --resume | Durdurulan bir taramaya devam eder | nmap --resume taramasonucu |
| --iflist | Host arayüzlerini ve rotalarını gösterir | nmap --iflist |
| --disable-arp-ping | ARP ping kullanımını devre dışı bırakır | nmap --disable-arp-ping 192.168.1.1 |
| --reason | Bir portun durumunu belirten nedeni gösterir | nmap --reason 192.168.1.1 |

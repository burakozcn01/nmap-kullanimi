Tablo şeklinde olacak şekilde aşağıdaki gibi görselleştiriyorum:

Parametre	Açıklama	Örnek Kullanım
-sS	SYN taraması yapar	nmap -sS 192.168.1.1
-sT	TCP taraması yapar	nmap -sT 192.168.1.1
-sU	UDP taraması yapar	nmap -sU 192.168.1.1
-O	Hedef sistemin işletim sistemini tanımlamak için tarama yapar	nmap -O 192.168.1.1
-p	Belirli bir bağlantı noktasını taramak için kullanılır	nmap -p 80 192.168.1.1
-o	Tarama sonucunu belirtilen dosyaya kaydeder	nmap -oN taramasonucu.txt 192.168.1.1
-iL	Belirtilen dosyada bulunan hedef listesine tarama yapar	nmap -iL hedefliste.txt
-sV	Hedef sistemde çalışan servislerin sürümünü tespit etmek için kullanılır	nmap -sV 192.168.1.1
-sP	Ping taraması yapar	nmap -sP 192.168.1.0/24
-sF	TCP FIN taraması yapar	nmap -sF 192.168.1.1
-sA	TCP ACK taraması yapar	nmap -sA 192.168.1.1
-sR	TCP Remote taraması yapar	nmap -sR 192.168.1.1
-sZ	SCTP COOKIE-ECHO taraması yapar	nmap -sZ 192.168.1.1
-sI	IP protokol taraması yapar	nmap -sI 192.168.1.1
-sL	DoS saldırısı taraması yapar	nmap -sL 192.168.1.1
-sM	Belirtilen IP adresinden DoS saldırısı taraması yapar	nmap -sM 192.168.1.1 192.168.1.2
-sN	ICMP yanıt taraması yapar	nmap -sN 192.168.1.1
-sW	Belirtilen port için TCP window scan taraması yapar	nmap -sW 22 192.168.1.1
-sX	Belirtilen port için TCP Xmas scan taraması yapar	nmap -sX 22 192.168.1.1
-sY	Belirtilen port için TCP Yoklama taraması yapar	nmap -sY 22 192.168.1.1
-T<0-5>	Tarama hızı seviyesi belirler (1-5 arası)	nmap -T4 192.168.1.1
-n	DNS çözümlemesi yapmadan tarama yapar	

## TryHackMe Passive Reconnaissance Writeup.
> Öncelikle Herkese Selamlar. Bugün sizlere Yapmış olduğum **Passive Reconnaissance** Lab'ının Writeup'ını çıkaracağım.

## Bilgiler.
- Zorluk: *Kolay*
- Writeup Yazarı: *Rüzgar Umut Gündoğan*
- Lab adı: *Passive Reconnaissance*
- Writeup yazılma Tarihi: *30.10.2025*

## Lab'dan Öğrendiklerim.
- Pasif Keşifin **basitçe** nasıl yapıldığını öğrendim.
- Pasif Keşif ve Aktif keşifin aralarında ki farkı öğrendim.
- **nslookup** ve **dig** komutlarının basitçe nasıl kullanıldığını öğrendim.
- **Whois** komutunu basitçe nasıl kullanıldığını öğrendim.
- **DNSDumpster**'ın ne işe yaradığını öğrendim ve basitçe nasıl kullanıldığını öğrendim.
- **Shodan.io(GUI)** Basitçe nasıl kullanıldığını öğrendim.

## Lab Sırasında Yaptıklarım.
- **Shodan.io(GUI)** ile Apache sunucularının en çok kullanılan ülkesinin Amerika Birleşik Devletleri olduğunu öğrendim.
- **whois** Komutu ile tryhackme.com adresini sorguladım ve ne zaman tescil edildiğini, kayıt şirketini ve name Server'ünü öğrendim.
- **nslookup** Komutu ile thmlabs.com adresinin TXT record'larını kontrol ettim ve böylece Flag'i bulmuş oldum(Flag: THM{a5b83929888ed36acb0272971e438d78}).
- **Shodan.io(GUI)** ile Apache sunucusu için 3. olarak en çok kullanılan Port'un hangisi olduğunu öğrendim(8080 Port'u).
- **Shodan.io(GUI)** ile nginx için 3. olarak en çok kullanılan Port'un hangisi olduğunu öğrendim(888 Port'u).
- **DNSDumpster** ile tryhackme.com adresinin ilginç bi subdomain'ini öğrendim(remote).

## Referanslar.
- [Shodan.io](https://www.shodan.io/)
- [DNSDumpster](https://dnsdumpster.com/)
- [TryHackMe](https://tryhackme.com/dashboard)
- [TryHackMe | Passive Reconnaissance](https://tryhackme.com/room/passiverecon)
- Linux *whois* komutu.
- Linux *nslookup* komutu.
- Linux *dig* komutu.

## Teşekkür.
> Buraya kadar gelip Writeup'ımı okuduğunuz için çok teşekkür ederim. Farklı bir Writeup'da görüşmek üzere...

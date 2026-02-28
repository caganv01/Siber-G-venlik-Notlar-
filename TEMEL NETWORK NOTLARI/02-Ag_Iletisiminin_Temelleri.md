# IP Adresi Nedir ?

IP (Internet Protocol), bir cihazın ağ üzerindeki mantıksal adresidir.

Bir ağda birden fazla cihaz bulunur ve bu cihazların birbirleriyle veri alışverişi yapabilmesi için tanımlanabilir bir adres yapısına ihtiyaç vardır. IP adresi, bu ihtiyacı karşılar.

Basitçe ifade etmek gerekirse:
IP adresi, veri paketlerinin doğru hedefe ulaşmasını sağlayan adresleme sistemidir.

Nasıl ki gerçek hayatta bir mektubun ulaşabilmesi için adres bilgisine ihtiyaç varsa, ağ ortamında da verinin doğru cihaza ulaşabilmesi için IP adresine ihtiyaç vardır.

# IP Adresinin Temel Görevleri

- Ağ üzerindeki cihazları adreslemek.
- Veri paketlerini doğru hedefe yönlendirmek.
- Ağlar arası iletişimi mümkün kılmak.
IP olmadan routerlar ( yazı devamında bahsedeceğim ) paketi nereye göndereceğini bilemez.Bu nedenle IP internet yapısının temel taşlarından biridir.

# IPv4 ve IPv6 Nedir ?

IP protokolünün iki ana sürümü bulunmaktadır.

## IPv4
- 32 bit uzunluğundadırlar.
- 4 oktetden oluşurlar.
- Noktalara ayrılmış ondalık sayı formatında gösterilirler.

Örneğin : 192.168.1.154 gibi bir gösterimi bulunur.

IPv4 yaklaşık 4.3 milyar adres kapasitesine sahiptir.Tabi ki internet büyümesiyle bu adresler yetersiz gelmeye başladı.

### IPv4 Adresler 2'ye Ayrılır

##### Public IP
İnternet üzerinden doğrudan erişilebilen adreslerdir.
##### Private IP
Yerel ağ içerisinde kullanılan adreslerdir internet üzerinden doğrudan erişemeyiz.

Private IP aralıkları:
- 10.0.0.0/8
- 172.16.0.0-172.31.255.255
- 192.168.0.0/16

## IPv6
IPv6 , IPv4 adresler yetersiz gelmeye başladığı için geliştirilen bir IP sürümdür.
- 128 bit uzunluğundadır.
- Hexadecimal format kullanır.
- Çok daha egniş bir adresleme kapasitesine sahiptir.

Örneğin : 2001:0db8:85a3:0000:0000:8a2e:0370:7334 gibi bir gösterimi vardır.

# Peki IP Adresleri Manipule Edilebilir mi ?

IP adresi üzerinden :
- Açık port taraması yapılabilir.
- Sistem üzerinde çalışan servisler tespit edilebilir.
- Log analizlerinde kaynak ve hedef belirlenebilir.
  
Fakat unutmayalım :
- NAT
- Proxy
- VPN
- IP Spoofing 
gibi teknikler ile gizlenebilir veyahut manipule edilebilirler.

Kısaca birçok bilgi toplayabilirsin fakat bu bilgilere körü körüne güvenmemek gerek.
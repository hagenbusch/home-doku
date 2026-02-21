# Einrichtung von IPv6 Weiterleitung auf der Fritzbox
## Stand 21.02.2026

### Allgemein

siehe auch : https://nocksoft.de/tutorials/dyndns-fuer-ipv6-server-hinter-fritzbox-konfigurieren/

Angepasster Eintrag für die Fritzbox

Host: 
- nas  ::265e:beff:fe2e:5be9
- docker ::840e:357a:1a0b:90f6

```
https://dynv6.com/api/update?hostname=nas&token=<username>&ipv6=::265e:beff:fe2e:5be9&ipv6prefix=<ip6lanprefix>&trash=<ip6addr> https://dynv6.com/api/update?hostname=<docker&token=<username>&ipv6=::840e:357a:1a0b:90f6&ipv6prefix=<ip6lanprefix>&trash=<ip6addr>
``


TODO:

implement templates distribution

implement zabbix node registration

done:

- dht
  http://www.yacy-websuche.de/wiki/index.php/Seedlists
  lynx --source "http://<peer>:<port>/Network.html?page=1"|grep "Type: Principal"|cut -d '"' -f 4
  http://www.yacy-websuche.de/wiki/index.php/De:Netzdefinition
  to be stored into http://dht.ahmia.fi/dht.net

  network.unit.name = ahmia
  network.unit.description = Ahmia Tor Seach Index
  network.unit.domain = local
  network.unit.dhtredundancy.junior = 1
  network.unit.dhtredundancy.senior = 3
  network.unit.bootstrap.seedlist0 = http://dht.ahmia.fi/seedlist.txt
  network.unit.update.location0 = http://yacy.net/yacy/Download.html


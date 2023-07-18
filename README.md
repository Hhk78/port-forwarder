# port-forwarder
Herhangi bir IP adresinin herhangi bir portunu sahip olduğunuz IP adresindeki portlara yönlendirin.

# Derleme
```bash
chmod +x build.sh
./build.sh
```

# Kullanım
```bash
./tcpfwd|./udpfwd <yerel_ip:yerel_port> <hedef_ip:hedef_port> [-d] [-o]
```

# Parametreler
```bash
-d              arka planda çalıştırın
-o              IPv6 bağlantılarını yalnızca IPv6 dinleyicisi için kabul edin
-p <pidfile>    PID'i herhangi bir dosyaya yazdırın
```

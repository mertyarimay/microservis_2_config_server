# Config Server
[GitHub](https://github.com/mertyarimay/microservis_2_config_server)

config server URL:http://localhost:8888/application/default



# Config Server
- Mikroservislerin konfigurasyonlarını  merkezi bir yerde yönetmek için  kullanılan yapidir.
- Bu config-server:Merkezi bir alan içinde  config server üzerinden  yapılandırmaları dinamik olarak alabilir.

# Spring Cloud(Config Client)
- Spring Cloud serverdan konfigürasyonları almak için kullanılan istemcidir.
- Mikroservisler Genellikle Config client olarak  yapılandırılır.
- Config Client Config server'a bağlanır ve merkezi olarak yönetilen  konfigürasyon dosyalarını  alır.
- Eğer uygulamamız merkezi olarak yönetilen  konfigürasyonları almak için  spring cloud config servera bağlanacaksa biz config cliente ekliyoruz



# Spring Cloud(Config Server)
- merkezi  bir konfigürasyon yönetim sunuculugunu yapar.
- Bir veya daha fazla  mikroservislerin  konfigürasyon dosyalarını merkezi bir  yerde sunar


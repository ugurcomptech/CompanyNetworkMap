# Company Network Map

Yapmış olduğumuz network simulasyonunu 4 farklı IP aralığına atadım bunlar sırasıyla; 
  - 192.168.50.1
  - 192.168.60.1
  - 192.168.70.1
  - 192.168.80.1


Network Haritası üzerinde, toplamda 2 adet yönlendirici, 1 adet ev yönlendirici, 5 adet anahtar cihazı, 1 adet güvenlik duvarı, 1 adet Bulut PT ve 3 adet sunucu bulunmaktadır.

IP aralıklarını farklı şubeler için ayrı ayrı belirlemek isterseniz, örneğin İstanbul ofisi için 192.168.50.1-254 IP aralığını kullanabilirsiniz; Antalya ofisi için ise 192.168.60.1-254 IP aralığını tercih edebilirsiniz. Tamamen sizin tercihinize kalmış.

![image](https://github.com/ugurcomptech/CompanyNetworkMap/assets/133202238/c8b72d0b-af7c-48d5-a2b7-475cc89cdad6)

Şimdi sırasıyla ıp Yapılandırmalarına geçelim;

## Router IP Yapılandırmaları

- **Router1**'in konfigürasyonu;
  - **Serial 2/0**: 192.168.60.1
  - **Serial 3/0**: 192.168.50.1
  - **GigabitEthernet 7/0:** 192.168.70.1
  - **GigabitEthernet 8/0:** 192.168.80.1

- **Router2**'in konfigürasyonu;
  - **Serial 2/0**: 192.168.70.1
  - **GigabitEthernet 7/0:** 192.168.80.1
  - **GigabitEthernet 8/0:** 192.168.60.1
  - **GigabitEthernet 9/0:** 192.168.50.1
 

- **HomeRouter**'ın konfigürasyonu;
  - **LAN(Local Area Network):** 192.168.80.1
 

## Firewall IP yapılandırması

- **GigabitEthernet 1/1:** 192.168.80.10



## Server IP Yapılandırmaları
- **FastEthernet0:** 192.168.80.11
- **FastEthernet0:** 192.168.80.12
- **FastEthernet0:** 192.168.80.13


## Client IP Yapılandırmaları

- **Client1:** 192.168.50.11
- **Client1:** 192.168.60.11
- **Client1:** 192.168.70.11
- **Client1:** 192.168.80.11


## Printer IP Yapılandırmaları

- **Printer1:** 192.168.50.20
- **Printer2:** 192.168.60.20
- **Printer3:** 192.168.70.20

## Video



https://github.com/ugurcomptech/CompanyNetworkMap/assets/133202238/a4d34456-4c2a-486f-acd2-055fda3e6d42






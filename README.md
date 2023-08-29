# Company Network Map

Yapmış olduğumuz network simulasyonunu 4 farklı IP aralığına atadım bunlar sırasıyla; 
  - 192.168.50.1
  - 192.168.60.1
  - 192.168.70.1
  - 192.168.80.1

Bu Network Map de toplam 2 tane router, bir tane home router, 5 tane switch, 1 tane Firewall, 1 tane Cloud PT ve 3 tane de server var.

IP aralıklarını ister farklı şubeler için yapın örneğin 192.168.50.1-254 ıp aralığı İstanbul ofisiniz için olsun, Antalya ofisinizin ıp aralığı da 192.168.60.1-254 tamamen size kalmış.

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
 






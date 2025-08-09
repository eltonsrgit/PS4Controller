# Aviso
Utilize o programa SixAxisPairTool para descobrir o endereço MAC Bluetooth do controle DualShock.
1. Abra o programa e conecte o controle via USB no computador.
2. Veja qual endereço aparece no programa e cole no argumento da função PS4.begin("COLE O ENDEREÇO AQUI") no void setup.
3. "Limpe o ESP32 com o arquivo .ino "remove_paired_devices" (isso deve ser feito sempre que não houver conexão).
4. Faça o upload do seu código.

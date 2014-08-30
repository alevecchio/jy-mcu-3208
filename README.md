jy-mcu-3208
===========

Configuração de hardware para usar o display jy-mcu-3208 com a IDE do Arduino. Testado na IDE 1.5.5
É necessário um gravador externo para carregar o "Bootloader" e os softwares. Eu usei o USBASP.

1. Fechar a IDE do Arduino.
2. Copiar a pasta jy-mcu-3208 na pasta hardware. 
3. Abrir a IDE do Arduino.
4. Selecionar o menu: Ferramentas/Placa/jy-mcu-3208
5. Selecionar o menu: Ferramentas/Clock para determinar a velocidade do clock. Para clock 16 mHz externo é necessária uma adaptação de hardware.
6. Selecionar o menu: Ferramentas/Programador para determinar qual programador você está usando.
7. Selecionar o menu: Ferramentas/Gravar Bootloader para carregar as configurações corretas de fuse para a velocidade de clock selecionada.
8. Carregar seu Sketch na IDE do Arduino
9. Selecionar o menu: Arquivo/Carregar usando programador
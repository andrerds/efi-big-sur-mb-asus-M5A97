# Asus M5A97 AMD FX Hackintosh 

## MacOS BigSur
** Status Atual **: Não Estável  
** Bootloader **: OpenCore 6.4   

**Trabalhando**
- Ethernet
- Som (com VoodooHDA)
- Wifi Atheros 9285

**Não está funcionando**
- Appstore, iTunes e Safari têm problema de congelamento de morte
- Despertar
- Controle do ventilador
- USB 3.0

**Atenção OPENCORE brikando BIOS**
- Tome cuidado / Warning
- Em caso em que sua BIOS for corrompido, terá varios problemas e o mais grave e travar sem conseguir
    Inicializar com PENDRIVE ou HD/SSD plugado na placa mãe.
- Solução **Por sua conta e Risco**
- Baixar o Firmware (antigo e atulizado ) formata um pendriver em FAT e por os dois arquivos lá.
- Iniciar o PC em nada plugado / Pendriver ou HD/SSD assim o voce terá acesso a BIOS,  estando dentro da BIOS
    acesse Tools, em ASUS EZ Flash. Saia, espete o pendrive com os firwmares, e volte ao ASUS EZ Flash,
    veja se o pendrive está listando.
- Se chegou ate aqui, listou o pendrive, ira ver os dois arquivos, Clique no firmare mais antigo, fazendo um Downgrade,
    reinicie e deixe o pendrive plugado, se deu certo, irá dar uma mensagem para entrar na BIOS, caso contrário 
    vai ficar travado. Então e necessário executar o passo anterior e por o Firmware mais atual novamente e cruzar os dedos.

**Esse problema aconteceu comigo e resolvir dessa forma acima**

**Você deve alterar as linhas "TO-BE-CHANGED" em Config.plist (SystemSerialNumber, SystemUUID, ROM, MLB). Você pode usar [GenSMBIOS] (https://github.com/corpnewt/GenSMBIOS) para isso.**  
  
**Minhas especificações**  
**CPU**: AMD FX-6300  
**GPU**: GerForce GT 710
**SSD**: WD 120 GREEN  
**RAM**: 24 GB 
Para atualizar o firmware da placa ZVC-8I4P-R, é necessário um conversor RS485 conectado na porta de expansão.

Após ter em mãos o número da porta serial (COMxx onde xx é número da porta serial), coloque a placa em modo DFU mantendo pressionando os botões "PROG" e "SEL" ao ligar a placa.

Em modo DFU, os leds indicativos "System" e "Program" piscam alternadamente.

No prompt de comando, execute:

fw_upload.exe -p COMxx -f arquivo_de_firmwara.bin

Siga as instruções apresentadas na tela.

Ao término, o novo firmware inicializará automaticamente.

Importante: Caso a placa não reconheça, verifique a porta serial, as conexões e alimentação do conversor RS485 e se a placa está em modo DFU.


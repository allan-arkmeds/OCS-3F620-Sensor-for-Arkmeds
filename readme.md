--- Conclusão da lógica de leitura do sensor OCS-3F260 ---

São lidos e validados os 12 bytes de informação que o sensor envia, após isso,
é calculada a porcentagem de oxigênio somando-se os bytes 4 e 5 do vetor principal.
A vazão é calculada somando os bytes 6 e 7, e a temperatura é calculada fazendo a 
concatenação dos bytes 9 e 10. os bytes 11 e 12 não são utilizados.

# Sobre o projeto

Esse projeto é uma continuação do [udp-chat](https://github.com/gooday4u/udp-chat).</br>
Nessa continuação foi implementada criptografia entre o cliente e o servidor, com o uso da biblioteca simple-crypt.</br>
Foram realizadas análises de tráfego entre as trocas de mensagems para prova de conceito acerca da confiablidade da informação que trafega na rede com e sem criptografia.<br>

<h1>Demonstrações</h1>

1 - Esta análise de tráfego com o tcpdump foi realizada no [udp-chat](https://github.com/gooday4u/udp-chat), no qual não havia nenhuma criptografia implementada.</br>

![sem-criptografia](images/no-crypt.png)

Como pode ser observado na análise, a confidencialidade da informação é perdida.

2 - Diante disso, após a implementação da criptografia pode se observar que a confiabilidade da informação permanece ao trafegar na rede:

![com-criptografia](images/crypt.png)




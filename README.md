# Diagnóstico e expansão de infraestrutura de rede

![Status](https://img.shields.io/badge/Status-Documentado-blue)
![Área](https://img.shields.io/badge/Área-Infraestrutura%20de%20Redes-purple)
![Plataforma](https://img.shields.io/badge/Plataforma-Windows%2011-blue)

## Sobre o projeto

Este repositório documenta uma atividade prática de infraestrutura de redes realizada em um ambiente com equipamentos e dispositivos previamente instalados.

O trabalho consistiu na integração de um ponto de acesso TP-Link EX3000 à infraestrutura existente, com o objetivo de disponibilizar conectividade em uma sala que anteriormente não possuía acesso à internet.

Durante a atividade, foram analisadas as conexões entre os equipamentos, realizada a configuração do novo ponto de acesso e executados testes de conectividade para verificar a comunicação com a rede existente.

O processo também envolveu a necessidade de manter os dispositivos que já utilizavam a infraestrutura em funcionamento durante a implementação.

## Objetivos

- Analisar a topologia de uma rede existente.
- Integrar um novo equipamento à infraestrutura.
- Disponibilizar conectividade em uma área sem acesso à internet.
- Verificar a comunicação entre os dispositivos.
- Documentar as configurações, os testes realizados e os resultados observados.

## Topologia da rede

A infraestrutura utilizada na atividade era composta por equipamentos de rede distribuídos entre diferentes áreas do ambiente.

A conexão principal parte do equipamento ZTE ZXHN F670L, passa pelo roteador TP-Link Archer C60 e chega ao Intelbras AF 1200, que disponibiliza conectividade para a área onde estão instaladas as câmeras.

A partir do Intelbras AF 1200, foi integrado um TP-Link EX3000 por meio de uma conexão Ethernet, utilizando o modo Access Point para disponibilizar uma rede Wi-Fi adicional.

### Diagrama da infraestrutura

![Topologia da infraestrutura de rede](diagramas/topologia.png)

### Equipamentos envolvidos

| Equipamento | Função na infraestrutura |
|---|---|
| ZTE ZXHN F670L | Equipamento principal de acesso à rede |
| TP-Link Archer C60 | Roteador da rede local |
| Intelbras AF 1200 | Equipamento responsável pela conectividade da área das câmeras |
| TP-Link EX3000 | Ponto de acesso adicional |
| Câmeras | Dispositivos conectados à infraestrutura existente |
| Notebook | Dispositivo utilizado para configuração e testes |

O diagrama representa as conexões físicas e sem fio identificadas durante a atividade. Os detalhes de configuração e funcionamento lógico da rede são abordados nas próximas seções.

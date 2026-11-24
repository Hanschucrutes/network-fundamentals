# 02 — Modelos de rede: OSI e TCP/IP

Este arquivo é um guia inicial para estudar como a comunicação em rede pode ser organizada em camadas. O conteúdo será aprofundado ao longo dos estudos.

## Modelo OSI

O modelo OSI organiza a comunicação em sete camadas:

| Camada | Nome | Ideia principal |
|---|---|---|
| 7 | Aplicação | Serviços de rede usados por aplicações |
| 6 | Apresentação | Representação, codificação e transformação dos dados |
| 5 | Sessão | Organização das sessões de comunicação |
| 4 | Transporte | Comunicação fim a fim, portas e controle de transporte |
| 3 | Rede | Endereçamento lógico e roteamento |
| 2 | Enlace | Comunicação no enlace local e endereços MAC |
| 1 | Física | Transmissão de bits pelo meio físico |

## Modelo TCP/IP

O modelo TCP/IP é usado para descrever a arquitetura prática da internet. Uma divisão comum apresenta quatro camadas:

1. **Aplicação:** protocolos como HTTP, HTTPS, DNS e DHCP.
2. **Transporte:** protocolos TCP e UDP.
3. **Internet:** endereçamento IP e roteamento.
4. **Acesso à rede:** tecnologias e mecanismos de comunicação no enlace.

## Por que estudar camadas?

A divisão em camadas ajuda a entender onde uma função acontece e a organizar a investigação de problemas. Em segurança, esse conhecimento também ajuda a interpretar comunicações, protocolos e possíveis comportamentos suspeitos.

## Para revisar

1. Quantas camadas tem o modelo OSI?
2. Em qual camada estudamos endereçamento IP e roteamento?
3. Em qual camada aparecem TCP e UDP?
4. Cite dois protocolos da camada de aplicação no modelo TCP/IP.

**Status:** guia inicial — validar os conceitos com exercícios e exemplos práticos.

---
title: RC — Redes de Computadores
tags:
  - cadeira/RC
  - semestre/2526
aliases:
  - RC
  - Redes de Computadores
estado-cadeira: ativa
nota-final:
ects: 6
---

# RC — Redes de Computadores

> [!info] Identificação
> **ECTS:** 6 · **Tipo:** Contínua
> **Docente:** Prof. Doutor Fernando Joaquim Lopes Moreira
> **Terça:** 15:30–17:30 · TP · Sala 301
> **Quinta:** 11:00–13:00 · PL · Sala 421
> **FUC:** ![[FUC_REDES.pdf]]

---

## Avaliação

> [!success] Tipo: Avaliação Contínua

### Época Normal — Avaliação Contínua

| # | Elemento | Peso | Nota Mín. | Data | Hora | Local | Nota |
|---|----------|------|-----------|------|------|-------|------|
| 1E | Teste #1 | 30% | 7,0 val. | 24/04/2026 | 18:00h | A definir | |
| 2E | Teste #2 | 30% | 7,0 val. | 02/06/2026 | 18:00h | A definir | |
| 3E | Trabalho de grupo: entrega e apresentação | 40% | 7,0 val. | Entrega até 07/jun · Apres. última semana | — | Aula | |
| | **Total** | **100%** | | | | | |

### Época de Recurso

| Elemento | Peso | Nota Mín. | Data | Hora |
|----------|------|-----------|------|------|
| Exame Final | 60% | 7,0 val. | 30/06/2026 | 14:30h |
| Trabalho de grupo | 40% | 7,0 val. | — | — |

> [!note] Recurso: só é avaliado na componente sem aprovação (nota < 10,0).

### Época Especial

| Elemento | Peso | Nota Mín. |
|----------|------|-----------|
| Exame Final | 60% | 7,0 val. |
| Trabalho de grupo | 40% | 7,0 val. |

> [!note] Especial: só é avaliado na componente sem aprovação (nota < 10,0).

---

## Objetivos de Aprendizagem

> [!abstract] No final da UC o estudante deverá ser capaz de:
> i. **Terminologia de redes** — principais termos da área
> ii. Compreender a **estrutura em camadas** de uma arquitetura de rede
> iii. Compreender o **encaminhamento IP**
> iv. Identificar os **diferentes níveis de complexidade** numa rede
> v. Analisar as diferenças entre **nomes e endereços** numa rede; endereçamento hierárquico
> vi. Descrever a operação de **protocolos de comunicação fiáveis**
> vii. Analisar as diferenças entre **redes IP e Ethernet**
> viii. Analisar os mecanismos de **deteção e correção de erros**
> ix. Avaliar as **propriedades de segurança de redes sem fio**

---

## Conteúdos Programáticos

### 1. Introdução
- 1.1 Redes de computadores e a Internet
- 1.2 Tecnologias de comutação
- 1.3 Arquitetura em camadas
- 1.4 Protocolos e serviços

### 2. Camada de Aplicação
- 2.1 Web
- 2.2 **HTTP**
- 2.3 **FTP**
- 2.4 **SMTP**
- 2.5 **DNS**

### 3. Camada de Transporte
- 3.1 Multiplexagem e desmultiplexagem
- 3.2 **UDP**
- 3.3 Transferência fiável de dados
- 3.4 Stop-and-wait, Go-Back-N, Selective Repeat
- 3.5 **TCP**
- 3.6 Controlo de congestionamento

### 4. Camada de Rede
- 4.1 Encaminhamento por estado-da-ligação
- 4.2 Encaminhamento por vetor-distância
- 4.3 **IP**
- 4.4 **CIDR**
- 4.5 **RIP** · 4.6 **OSPF** · 4.7 **BGP**
- 4.8 **IPv6**
- 4.9 **VPNs** · 4.10 **NAT**

### 5. Camada de Ligação de Dados
- 5.1 Deteção e correção de erros
- 5.2 Acesso múltiplo
- 5.3 **ALOHA** · 5.4 **CSMA** · 5.5 Token-ring
- 5.6 **WLANs e IEEE 802.11**
- 5.7 **ARP**
- 5.8 Hubs e comutadores
- 5.9 PPP · 5.10 ATM

### 6. Camada Física

### 7. Redes Sem Fios
- 7.1 Características das redes sem fios
- 7.2 **WiFi: 802.11 Wireless LANs**
- 7.3 Acesso
- 7.4 Princípios de gestão da mobilidade
- 7.5 **IP móvel**

---

## Planificação Semanal

| Sem. | Conteúdo | Prática |
|------|----------|---------|
| 1 | Apresentação | — |
| 2 | Introdução às Redes e Internet | Wireshark |
| 3–4 | **Camada de Aplicação** | Wireshark |
| 5–6 | **Camada de Transporte** | Wireshark |
| **7** | **Teste #1** | Wireshark |
| 8 | **Férias da Páscoa** | — |
| 9–10 | **Camada de Rede** | Sockets |
| 11–12 | **Camada de Ligação de Dados** | Sockets |
| 13 | **Queima das Fitas** | — |
| 14 | Camada Física | Sockets |
| 15 | Revisões | Sockets |
| **16** | **Teste #2** | Sockets |
| 17 | **Apresentação de Trabalhos** | — |

> [!note] Teste #1 abrange Semanas 2–6 (Introdução + Aplicação + Transporte)
> Teste #2 abrange Semanas 9–15 (Rede + Ligação Dados + Física)

---

## Ferramentas Utilizadas nas Aulas

> [!example] Simuladores e analisadores
> - **Cisco Packet Tracer** — simulador de redes de computadores
> - **Wireshark** — analisador de protocolos (semanas 2–7)
> - **Programação com Sockets** (semanas 9–16)

---

## Referência Rápida — Modelo OSI

> [!note] As 7 camadas do modelo OSI
>
> | # | Camada | Protocolos |
> |---|--------|------------|
> | 7 | Aplicação | HTTP, FTP, SMTP, DNS |
> | 6 | Apresentação | SSL/TLS |
> | 5 | Sessão | NetBIOS |
> | 4 | Transporte | TCP, UDP |
> | 3 | Rede | IP, ICMP, OSPF, RIP |
> | 2 | Ligação de Dados | Ethernet, Wi-Fi, ARP |
> | 1 | Física | Cabos, sinais elétricos |

## Referência Rápida — TCP vs UDP

> [!note] Comparação
>
> | Característica | TCP | UDP |
> |----------------|-----|-----|
> | Ligação | Orientado à ligação | Sem ligação |
> | Fiabilidade | Garantida | Não garantida |
> | Ordem | Garantida | Não garantida |
> | Velocidade | Mais lento | Mais rápido |
> | Uso | Web, email, ficheiros | Streaming, DNS, jogos |

## Referência Rápida — Endereçamento IP

> [!note] Classes de IP e CIDR
>
> | Classe | Intervalo | Máscara |
> |--------|-----------|---------|
> | A | 1.0.0.0 – 126.255.255.255 | /8 |
> | B | 128.0.0.0 – 191.255.255.255 | /16 |
> | C | 192.0.0.0 – 223.255.255.255 | /24 |
>
> **Privados:** 10.x.x.x · 172.16–31.x.x · 192.168.x.x

---

## Método de Ensino

> [!tip] Estratégias utilizadas
> - **Sala de aula invertida** (flipped classroom) para a teoria
> - **Método expositivo-ativo** + discussão em sala
> - **Simuladores** (Packet Tracer + Wireshark) para prática
> - **Trabalho de grupo** aplicado

---

## IA Generativa

> [!success] IA Permitida
> - **Para:** Autoestudo
> - **Ferramentas:** Livres
> - **Declaração:** Não se aplica

---

## Carga Horária

| Tipo | Horas de Contacto | Trabalho Independente |
|------|-------------------|----------------------|
| Teórico-Prático [TP] | 30h | — |
| Prático/Laboratorial [PL] | 30h | — |
| Projeto de grupo | — | 26h |
| Provas | — | 6h |
| Investigação | — | 15h |
| Experimentação laboratorial | — | 20h |
| Estudo autónomo | — | 35h |
| **Total** | **60h** | **102h** |

---

## Bibliografia

> [!quote] Recomendada (principal)
> - **Kurose, J. F., & Ross, K. W. (2021). *Computer Networking: A Top-Down Approach*, 8th ed., Pearson.**

> [!quote]- Complementar
> - Stallings, W. (2005). *Data and Computer Communications*, 10th ed., Prentice-Hall.
> - Tanenbaum, A. S., & Wetherall, D. (2014). *Computer Networks*, 6th ed., Pearson.
> - Boavida, F., & Monteiro, E. (2011). *Engenharia de Redes Informáticas*, 10ª ed., FCA.

---

## Aulas

![[RC - Redes de Computadores/Aulas]]

---

## Trabalhos

![[RC - Redes de Computadores/Trabalhos]]

---

## Recursos

- [[RC - Redes de Computadores/Recursos]]
- FUC: [[FUC_REDES.pdf]]

---

## Notas de Estudo

> [!tip] Dicas
> - O livro base é **Kurose & Ross** — segue-o de perto, a cadeira segue a abordagem top-down.
> - Instala o **Cisco Packet Tracer** e o **Wireshark** para praticar.
> - Teste #1 (24/abr): Semanas 2–6 → Introdução + **Camadas Aplicação e Transporte**.
> - Aprende **subnetting** (CIDR) muito bem — aparece sempre nos exames.
> - Para a parte prática: pratica **programação com Sockets** em Python ou Java.

---

## Ligações

- [[Dashboard]]

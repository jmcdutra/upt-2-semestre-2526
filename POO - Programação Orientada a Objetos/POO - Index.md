---
title: POO — Programação Orientada a Objetos
tags:
  - cadeira/POO
  - semestre/2526
aliases:
  - POO
  - Programação Orientada a Objetos
estado-cadeira: ativa
nota-final:
ects: 6
---

# POO — Programação Orientada a Objetos

> [!info] Identificação
> **ECTS:** 6 · **Tipo:** Contínua · **Linguagem:** Java
> **Docente (Regente):** Prof. Doutora Maria Paula Coutinho Dias Morais
> **Docente:** Prof. Doutor Tiago Silva Oliveira Bastos
> **Segunda:** 11:00–13:00 · PL · Sala 412
> **Terça:** 13:30–15:30 · PL · Sala 416
> **Quarta:** 11:00–13:00 · TP · Sala 305
> **FUC:** ![[FUC_POO.pdf]]

---

## Avaliação

> [!success] Tipo: Avaliação Contínua
> **Assiduidade mínima: 70% das aulas**

### Época Normal — Avaliação Contínua

| # | Elemento | Peso | Nota Mín. | Data | Hora | Local | Nota |
|---|----------|------|-----------|------|------|-------|------|
| 1E | Participação/Empenho nas aulas | 25% | 10,0 val. | Ao longo do semestre | — | Aula | |
| 2E | Quiz #1 (avaliação formativa e sumativa) | 10% | — | Semana 16–20 mar | — | Aula | |
| 3E | Quiz #2 (avaliação formativa e sumativa) | 10% | — | Semana 27–30 abr | — | Aula | |
| 4E | Prova Prática individual | 25% | 9,0 val. | 13/05/2026 | 17:00h | Lab. Informática | |
| 5E | Projeto interdisciplinar de grupo (SI+POO) | 30% | 10,0 val. | 11 mai – 12 jun | — | Aula | |
| | **Total** | **100%** | | | | | |

> [!warning] Quiz #1 esta semana (16–20 março)!

> [!warning] Observações importantes
> - A **Participação (25%)** inclui empenho e atividades no MOODLE para alunos com estatuto.
> - O **Projeto é interdisciplinar com SI** — usa metodologia **SCRUM** (sprints).
> - Alunos que entregaram projeto na época normal podem **manter a nota** no recurso.
> - **IA não é permitida** em momentos de avaliação.

### Época de Recurso

| Elemento | Peso | Nota Mín. | Data | Hora |
|----------|------|-----------|------|------|
| Prova Escrita | 35% | 8,0 val. | 03/07/2026 | 14:30h |
| Prova Prática individual | 35% | 9,0 val. | — | — |
| Projeto interdisciplinar de grupo | 30% | 10,0 val. | — | — |

### Época Especial

| Elemento | Peso | Nota Mín. |
|----------|------|-----------|
| Prova Escrita | 50% | 8,0 val. |
| Prova Prática individual | 50% | 9,0 val. |

---

## Objetivos de Aprendizagem

> [!abstract] No final da UC o estudante deverá ser capaz de:
> 1. Identificar as características dos **paradigmas e linguagens de programação**
> 2. Implementar **composição** entre classes
> 3. Implementar **herança** entre classes
> 4. Implementar **aplicações orientadas a objetos usando Java**
> 5. **Otimizar** aplicações OO usando Java

> [!note] Pré-requisitos recomendados
> - Algoritmia e Programação (1º semestre)
> - Álgebra Linear e Geometria Analítica (raciocínio lógico)
> - Competências de trabalho em grupo e comunicação

---

## Conteúdos Programáticos

### 1. Linguagens e Paradigmas de Programação
- 1.1 Paradigmas: **imperativo, OO, funcional, lógico, declarativo**
- 1.2 Exemplos de linguagens de programação

### 2. Programação Orientada a Objetos
- 2.1 **Classes e objetos**
- 2.2 Construtores, métodos, parâmetros
- 2.3 **Polimorfismo por overloading**
- 2.4 **Encapsulamento** — modificadores de acesso (`public`, `private`)
- 2.5 Boas práticas na escrita de classes

### 3. Relações entre Classes — Composição
- 3.1 Relação **"tem-um"** (has-a relationship)
- 3.2 Uso de listas para representar objetos compostos

### 4. Relações entre Classes — Herança
- 4.1 Relação **"é-um"** (is-a relationship)
- 4.2 Benefícios da reutilização de código
- 4.3 Hierarquia de classes
- 4.4 **Classes abstratas e interfaces**
- 4.5 Tipos estático e dinâmico
- 4.6 **Polimorfismo por overriding**
- 4.7 Procura dinâmica de métodos

### 5. Java
- 5.1 JDK, JRE, **máquina virtual Java (JVM)**
- 5.2 Tipos primitivos e Strings
- 5.3 Arrays
- 5.4 Estruturas de controlo e repetição
- 5.5 Estrutura base de um programa Java
- 5.6 Definição de classes e criação de objetos
- 5.7 Wrapper classes
- 5.8 I/O Simples
- 5.9 **Java Collections Framework** (ArrayList, HashSet, HashMap)

### 6. IDEs e Ferramentas
- 6.1 Objetivos e vantagens de um IDE
- 6.2 **BlueJ** e **Eclipse**
- 6.3 Ferramentas de Debugging

### 7. Qualidade no Desenho de Software
- 7.1 Boas práticas na escrita de programas em Java
- 7.2 Desenho orientado a responsabilidades, **coesão**, **acoplamento**, encapsulamento

### 8. Testes e Debugging
- 8.1 Conceito e importância do debugging
- 8.2 Técnicas de Debugging
- 8.3 **Análise e tratamento de exceções**

---

## Planificação Semanal

### Aulas Teórico-Práticas (TP)

| Sem. | Conteúdo |
|------|----------|
| 1 | Linguagens e paradigmas. Intro Java. JVM. 1º programa Java vs Python |
| 2 | Java: tipos primitivos, arrays, estruturas controlo, métodos static |
| 3 | POO: classes, objetos, construtores, **polimorfismo overloading** |
| 4 | Visibilidade, packages, `public`/`private`, abstração, `toString` |
| 5 | Diagramas de classes e objetos. Qualidade: coesão, acoplamento |
| 6 | Composição vs agregação. Arquitetura de projetos |
| 7 | Exemplo prático: gestão de notas de alunos (Turmas/Alunos) |
| 8 | Eclipse. Coleções Java: ArrayList, HashSet, HashMap, iteradores |
| 9 | **Herança** (is-a). Polimorfismo overriding. Tipos estático/dinâmico |
| 10 | Herança. **Classes abstratas**, métodos abstratos |
| 11 | **Herança múltipla em Java. Interfaces** |
| 12 | Git e GitHub. Esclarecimento de dúvidas projeto |
| 13 | **Tratamento de exceções** em Java |
| 14–15 | Esclarecimento de dúvidas / acompanhamento projeto |
| 16 | Discussão do código do 2º incremento do projeto |

### Aulas Práticas Laboratoriais (PL)

| Sem. | Conteúdo |
|------|----------|
| 1 | Apresentação UC. Revisões algoritmia |
| 2 | Revisões Algoritmia |
| 3 | Python vs Java. BlueJ. Arrays e matrizes em Java |
| 4–5 | Exercícios sobre métodos e Strings em Java |
| 6 | Classes e objetos. JavaDoc |
| 7 | Composição (has-a) |
| 8 | Composição + `java.time` + Debugging |
| 9 | Eclipse, ArrayList, Wrapper classes. **User Stories (com SI)** |
| 10–11 | Herança. **User Stories (com SI)** |
| 12 | **1º Sprint Planning** — Projeto interdisciplinar |
| 13 | Arquitetura do projeto; 1º incremento |
| 14 | 1º sprint review/retrospective; 2º sprint planning |
| 15 | Acompanhamento do 2º sprint |
| 16 | **2º sprint review/retrospective** |

---

## Os 4 Pilares da POO

> [!example] Conceitos fundamentais
>
> **Encapsulamento** — esconder detalhes internos, expor só o necessário
> **Herança** — reutilizar código de classes pai (`extends`)
> **Polimorfismo** — um objeto, várias formas (overloading + overriding)
> **Abstração** — simplificar a complexidade

```java
// Exemplo de hierarquia de classes
public abstract class Animal {
    private String nome;

    public Animal(String nome) { this.nome = nome; }
    public String getNome() { return nome; }

    public abstract void fazerSom(); // método abstrato
}

public class Cao extends Animal {
    public Cao(String nome) { super(nome); }

    @Override
    public void fazerSom() { System.out.println("Au Au!"); }
}

// Polimorfismo
Animal a = new Cao("Rex");
a.fazerSom(); // "Au Au!" — procura dinâmica de métodos
```

---

## Projeto Interdisciplinar POO + SI

> [!example] Metodologia SCRUM
> - **Sprint 1:** 1º incremento (implementação inicial)
> - **Sprint 2:** 2º incremento (evolução)
> - Inclui **auto-avaliação** e **avaliação de pares**
> - Utiliza **Git/GitHub** para controlo de versões
> - Entregas e apresentações: **11 mai – 12 jun**

---

## Método de Ensino

> [!tip] Estratégias utilizadas
> - **Aulas TP:** sala de aula invertida, think-pair-share, método expositivo
> - **Aulas PL:** resolução de exercícios no computador, peer-review, SCRUM
> - Aprendizagem baseada em projeto

---

## IA Generativa

> [!warning] IA Permitida com restrições
> - **Para:** Auxiliar de estudo e tutor na escrita de programas
> - **NÃO** é permitida em momentos de avaliação (quizzes, prova prática, exame)
> - **Ferramentas:** Qualquer ferramenta de GenAI

---

## Carga Horária

| Tipo | Horas de Contacto | Trabalho Independente |
|------|-------------------|----------------------|
| Teórico-Prático [TP] | 30h | — |
| Prático/Laboratorial [PL] | 60h | — |
| Projeto de grupo | — | 32h |
| Provas | — | 8h |
| Investigação | — | 4h |
| Estudo autónomo | — | 28h |
| **Total** | **90h** | **72h** |

---

## Bibliografia

> [!quote] Recomendada
> - Schildt, H., & Coward, D. (2024). *Java: The complete reference* (13ª ed.). McGraw Hill.
> - Liang, D. (2020). *Introduction to Java programming and data structures* (12ª ed.). Pearson.
> - Barnes, D., & Kolling, M. (2017). *Objects first with Java* (6ª ed.). Prentice-Hall.
> - Martins, M. (2017). *Java 8: POO + Construções Funcionais*. FCA.

> [!quote]- Complementar (online)
> - Java Documentation: https://docs.oracle.com/en/java/index.html
> - The Java™ Tutorials: http://docs.oracle.com/javase/tutorial/index.html
> - Rubin, K. (2013). *Essential Scrum*. Addison-Wesley.

---

## Aulas

![[POO - Programação Orientada a Objetos/Aulas]]

---

## Trabalhos

![[POO - Programação Orientada a Objetos/Trabalhos]]

---

## Recursos

- [[POO - Programação Orientada a Objetos/Recursos]]
- FUC: [[FUC_POO.pdf]]

---

## Notas de Estudo

> [!tip] Dicas
> - **Quiz #1 esta semana!** — revê paradigmas, Java básico, classes e objetos.
> - Pratica código todos os dias — a POO aprende-se **fazendo**.
> - O projeto usa SCRUM — aprende Git desde já (semana 12 das PL).
> - **IA não é permitida nas avaliações** — pratica sem ajuda regularmente.
> - A **participação vale 25%** — estás presente e envolvido em todas as aulas.

---

## Ligações

- [[Dashboard]] · [[SI - Index]] (projeto interdisciplinar)

# 🎵 Minhas Músicas – Java (POO)

Este projeto simula um **sistema de músicas e podcasts**, permitindo reproduzir conteúdos, 
curtir e classificar automaticamente os favoritos com base na popularidade.

Projeto focado na prática de **Programação Orientada a Objetos (POO)** em **Java**, seguindo 
o padrão ensinado pela **Alura**.

---

## 📌 Funcionalidades

- 🎶 Reproduzir músicas
- 🎙️ Reproduzir podcasts
- ❤️ Curtir conteúdos
- ⭐ Classificar automaticamente os favoritos
- 📊 Exibir mensagens de sucesso no terminal

---

# 🎶 Música

Representa uma música com as seguintes características:

- 📌 Título
- 🎤 Cantor
- ▶️ Total de reproduções
- ❤️ Total de curtidas

Pode ser reproduzida e curtida, incrementando seus contadores.

# 🎙️ Podcast

Representa um podcast com:

- 📌 Título
- 🎧 Apresentador
- ▶️ Total de reproduções
- ❤️ Total de curtidas

Também pode ser reproduzido e curtido.

# ⭐ Minhas Preferidas

A classe MinhasPreferidas é responsável por:

Avaliar músicas e podcasts
Identificar conteúdos populares
Exibir mensagens no terminal conforme o sucesso do conteúdo

📊 Regra de Classificação

```txt
Curtidas >= 1000 → Sucesso absoluto
Curtidas < 1000 → Conteúdo popular

```
---

## ⚙️ Pprojeto Funcionando
```txt


- ProgramacaoComJava é considerado sucesso absoluto e preferido por todos!

- ImagineDragon também é um dos que todo mundo está curtindo


```
---

## 🧱 Estrutura do Projeto

```txt
br.com.alura.minhasmusicas
├── principal
│   └── Principal.java
└── modelos
    ├── Audio.java
    ├── Musica.java
    ├── Podcast.java
    └── MinhasPreferidas.java
```

---

## 🛠️ Tecnologias Utilizadas

- ☕ Java
- 🧠 Programação Orientada a Objetos (POO)
- 🔁 Laços de repetição (for)
- 🗂️ Organização em pacotes
- 🔐 Encapsulamento (getters e setters)
- 🧩 Polimorfismo

---
  
## 📚 Conceitos Aplicados

- Classes e objetos
- Encapsulamento
- Herança
- Polimorfismo
- Reutilização de código
- Simulação de regras de negócio

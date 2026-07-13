# 🏛️ Portal do Cidadão — Câmara Municipal

> Aplicação web desenvolvida como trabalho da **AEP** do curso de **Engenharia de Software** da **UniCesumar**.

Este projeto está alinhado ao **Objetivo de Desenvolvimento Sustentável (ODS) 11** da ONU — **Cidades e Comunidades Sustentáveis**, buscando aproximar a população das decisões legislativas municipais por meio da tecnologia, incentivando a participação cidadã, a transparência e a inclusão política.

---

## 💡 Sobre o Projeto

O **Portal do Cidadão** foi desenvolvido para facilitar o acompanhamento das propostas legislativas em tramitação nas Câmaras Municipais.

A plataforma permite que cidadãos acompanhem projetos de lei, expressem suas opiniões e contribuam com sugestões, promovendo uma comunicação mais direta entre a população e o poder legislativo.

### Objetivos

- Incentivar a participação popular nas decisões do município;
- Promover transparência no processo legislativo;
- Facilitar o acesso às informações públicas;
- Estimular a cidadania por meio da tecnologia.

---

## ✨ Funcionalidades

- 📋 Visualização de propostas legislativas por cidade;
- 🪟 Modal com detalhes completos de cada proposta;
- 💬 Envio de comentários e sugestões;
- ⭐ Avaliação das propostas por estrelas (1 a 5);
- ❤️ Curtidas nos comentários;
- 🔍 Filtro de comentários por projeto legislativo;
- 🔃 Ordenação por comentários mais recentes ou mais curtidos;
- ✅ Validação da idade mínima de 16 anos para participação.

---

## 🏗️ Estrutura do Projeto

```text
📁 portal-cidadao/
├── 📄 aep.html   # Estrutura da aplicação
├── 🎨 aep.css    # Estilos e layout
└── ⚙️ aep.js     # Lógica e funcionalidades
```

---

## 🧠 Conceitos Aplicados

### 🏛️ Orientação a Objetos

O projeto utiliza conceitos de Programação Orientada a Objetos por meio das seguintes classes:

### Classe `Proposta`

Representa cada projeto legislativo contendo:

- título;
- descrição;
- status;
- detalhes completos;
- quantidade de curtidas.

### Classe `Comentario`

Representa cada opinião enviada pelos cidadãos, contendo:

- nome;
- idade;
- cidade;
- projeto relacionado;
- nota atribuída;
- comentário;
- quantidade de curtidas;
- data e horário da publicação (*timestamp*).

---

## 📚 Estruturas de Dados

### 📋 Lista

A estrutura `listaComentarios[]` armazena todos os comentários enviados pelos usuários, utilizando métodos como:

- `push()`
- `filter()`
- `forEach()`

### 📚 Pilha (LIFO)

A estrutura de pilha é utilizada para exibir os comentários mais recentes, respeitando o princípio **Last In, First Out (LIFO)**, em que o último comentário enviado é o primeiro a ser apresentado ao usuário.

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

---

## 🚀 Como Executar

Você pode acessar o projeto diretamente pelo GitHub Pages:

🔗 **https://heloysaf.github.io/Portal_Cidad-o/

Ou executar localmente:

1. Clone este repositório;
2. Abra o arquivo `aep.html` em qualquer navegador moderno.

> Não é necessário instalar dependências ou realizar configurações adicionais.

---

## 🌎 Objetivo de Desenvolvimento Sustentável

Este projeto está relacionado ao:

**ODS 11 — Cidades e Comunidades Sustentáveis**

Buscando incentivar a participação cidadã, fortalecer a transparência pública e ampliar o acesso às informações legislativas municipais.

---

## 📚 Referências

- Organização das Nações Unidas (ONU). **Objetivo de Desenvolvimento Sustentável 11 — Cidades e Comunidades Sustentáveis.**
- NOVECK, Beth Simone. *Smart Citizens, Smarter State*. Harvard University Press, 2015.

---

## 👩‍💻 Autores

Desenvolvido por:

- **Ana Clara Gomes de Andrade**
- **Heloysa Fernandes**
- **Thiago Lopes**

**Curso:** Engenharia de Software  
**Instituição:** UniCesumar

---

<div align="center">

### ⭐ Obrigado por visitar este projeto!

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório.

</div>

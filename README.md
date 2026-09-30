# Plataforma Colaborativa de Trabalho Remoto

<p align="center">
  <img src="docs/gifs/tela-inicial.gif" width="300">
</p>

<p align="center">
  Aplicativo mobile desenvolvido para auxiliar na organização,
  distribuição e acompanhamento de trabalhos realizados por
  equipes em ambientes de trabalho remoto.
</p>

---

## Sobre o Projeto

A Plataforma Colaborativa de Trabalho Remoto é um aplicativo mobile desenvolvido com o objetivo de centralizar informações relacionadas às atividades de equipes que trabalham remotamente.

A aplicação permite o gerenciamento de usuários, equipes e trabalhos, proporcionando uma forma organizada de acompanhar as atividades e facilitar a colaboração entre os integrantes.

O projeto foi desenvolvido como Trabalho de Conclusão de Curso (TCC).

---

## Funcionalidades

* Cadastro de usuários
* Autenticação por e-mail e senha
* Gerenciamento de informações do usuário
* Criação e gerenciamento de equipes
* Gerenciamento de membros das equipes
* Envio e gerenciamento de convites
* Solicitações de entrada em equipes
* Cadastro e gerenciamento de trabalhos
* Acompanhamento das atividades

---

## Demonstração

### Autenticação

O usuário pode realizar seu cadastro e acessar a plataforma utilizando e-mail e senha.

<p align="center">
  <img src="docs/gifs/login.gif" width="300">
</p>


### Tela Inicial

Após a autenticação, o usuário é direcionado à tela principal da aplicação.

<p align="center">
  <img src="docs/gifs/tela-inicial.gif" width="300">
</p>

### Gerenciamento de Equipes

A aplicação permite a criação e o gerenciamento de equipes de trabalho.

<p align="center">
  <img src="docs/gifs/criar-equipe.gif" width="300">
</p>

### Convites

Os usuários podem enviar, receber e gerenciar convites relacionados às equipes.

<p align="center">
  <img src="docs/gifs/convites.gif" width="300">
</p>

### Gerenciamento de Trabalhos

Os trabalhos podem ser cadastrados e gerenciados dentro das equipes.

<p align="center">
  <img src="docs/gifs/criar-trabalho.gif" width="300">
</p>

### Perfil do Usuário

O usuário pode consultar e gerenciar suas informações pessoais cadastradas na plataforma.

<p align="center">
  <img src="docs/gifs/perfil.gif" width="300">
</p>

---

## Tecnologias Utilizadas

| Tecnologia              | Aplicação                               |
| ----------------------- | --------------------------------------- |
| Kotlin                  | Desenvolvimento da aplicação Android    |
| Android Studio          | Ambiente de desenvolvimento             |
| Firebase Authentication | Autenticação dos usuários               |
| Firebase Firestore      | Armazenamento e gerenciamento dos dados |
| Material Design         | Desenvolvimento da interface            |
| Kotlin Coroutines       | Execução de operações assíncronas       |

---

## Banco de Dados

A aplicação utiliza o Firebase Firestore como banco de dados não relacional.

As principais coleções utilizadas são:

```text
usuarios
equipes
membros_equipe
convites_equipe
trabalhos
pedidos_entrada
```

---

## Arquitetura

O projeto utiliza uma arquitetura baseada em um modelo MVC simplificado, no qual cada tela principal da aplicação é representada por uma `Activity`.

A comunicação com o Firebase é realizada diretamente por meio dos SDKs disponibilizados pela plataforma, utilizando operações assíncronas com Kotlin Coroutines.

O fluxo de autenticação utiliza o Firebase Authentication, enquanto os dados complementares dos usuários e demais informações da aplicação são armazenados no Firestore.

---

## Estrutura do Projeto

```text
CTR_App-Comunidade_de_Trabalho_Remoto_Aplicativo/
│
├── app/
│   └── ...
│
├── docs/
│   ├── gifs/
│   │   ├── login.gif
│   │   ├── cadastro.gif
│   │   ├── tela-inicial.gif
│   │   ├── criar-equipe.gif
│   │   ├── convites.gif
│   │   ├── criar-trabalho.gif
│   │   └── perfil.gif
│   │
│   └── manual/
│       └── manual-do-usuario.md
│
├── README.md
└── ...
```

---

## Manual do Usuário

O manual apresenta as principais funcionalidades da aplicação e fornece instruções para utilização do sistema.

[Manual do Usuário](docs/manual/manual-do-usuario.md)

---

## Projeto Acadêmico

**Título:** Plataforma Colaborativa de Trabalho Remoto

**Tipo:** Trabalho de Conclusão de Curso

**Plataforma:** Android

**Linguagem:** Kotlin

**Banco de dados:** Firebase Firestore

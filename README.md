# cadastroSenac

Este repositório é dedicado ao trabalho do Projeto Integrador III do SENAC, vinculado ao curso superior de graduação em Análise e Desenvolvimento de Sistemas, com a participação de sete membros:

* Andressa de Souza Cataruci
* Cristiano Ricardo Borges
* Fabíola Bernardes Boldrin
* Gesika Santiago da Silva
* Jamila Cristina Gois da Costa
* Lorenzo de Lima Pandolfo
* Rafael Sangiorgio Muniz

## Objetivo

O objetivo do projeto é a criação de um sistema de cadastro criado para a gestão escolar da universidade SENAC, com o objetivo de cadastrar:

* Pessoa física (aluno e professor)
* Pessoa jurídica (fornecedor)
* Funcionários da universidade

O sistema possui as principais funcionalidades:

* Fazer login
* Visualizar perfil do fornecedor com acesso ao seu cadastro e histórico de negociações
* Cadastrar fornecedores
* Solicitação de cadastro por alunos e professores
* Acesso ao perfil de aluno com visualização de cadastro e solicitação de atualização de dados
* Acesso ao perfil de professor com visualização de cadastro, solicitação de atualização de dados e consultar o perfil de alunos vinculados
* Validação de documentação anexa aos cadastros
* Ativação de usuário
* Inativação de usuário
* Consultar cadastro de pessoas físicas e jurídicas
* Cadastrar usuários para funcionários da universidade


## Diagrama de casos de uso

Neste tópico será apresentado a construção de um diagrama de casos de uso, uma ferramenta essencial da UML (Unified Modeling Language), destinada a capturar os requisitos e interações de um sistema de gestão escolar abrangente. O foco recai sobre a representação dos diferentes tipos de usuários e suas ações no sistema, delineando as nuances do cadastro de informações para uma variedade de entidades cruciais: desde os alunos, professores e fornecedores até as pessoas físicas e jurídicas associadas à instituição.

![Diagramacasosuso](https://github.com/crborges86/cadastroSenac/assets/143454517/e8d7b7a2-c579-4e64-ba71-14c2bb9b5b3b)

## Diagrama de classes

Neste tópico foi desenvolvido o diagrama de classes como uma ferramenta de modelagem de sistemas orientados a objetos, sendo representado no diagrama as classes, atributos, métodos e relacionamentos entre classes, enfatizando sua relevância no contexto do sistema de gestão escolar.

![Diagrama_de Classes](https://github.com/crborges86/cadastroSenac/assets/143454517/5512ed7c-21e6-483a-bf06-f090fc46949c)


## Protótipos

O desenvolvimento de protótipos de interface com base nos casos de uso é uma etapa crucial para garantir a eficácia e a usabilidade de um sistema. Esses protótipos não apenas visualizam o layout e a estrutura da interface, mas também integram os fluxos de interação delineados nos diagramas de caso de uso, proporcionando uma representação tangível das funcionalidades esperadas. Ao alinhar os protótipos com esses diagramas, o objetivo é criar uma interface que atenda precisamente às necessidades e expectativas dos usuários, promovendo uma experiência intuitiva e eficiente durante a interação com o sistema.

### Login

Protótipos relacionados ao caso de uso “UC001 - Fazer login”, demonstrando a jornada de login do usuário.

UC001 - Tela 1: início para login ou solicitar cadastro

![UC001  Fazer login-1](https://github.com/crborges86/cadastroSenac/assets/143454517/6741e4af-cf15-48a3-a75f-f4e05af276f5)

UC001 - Tela 2: login

![UC001  Fazer login](https://github.com/crborges86/cadastroSenac/assets/143454517/4aa1ee06-0736-4f55-b931-40c746ac9409)

UC001 - Tela 3: fluxo alternativo, usuário bloqueado

![UC001  Fazer login (Fluxo alternativo)](https://github.com/crborges86/cadastroSenac/assets/143454517/ce296a53-ad6f-44d9-a869-cccef7ed5edd)

UC001 - Tela 4: tela principal após login do funcionário

![UC001  Tela principal após o login do funcionário](https://github.com/crborges86/cadastroSenac/assets/143454517/d5e9327d-b845-4b18-9ceb-19c65c899108)


### Cadastrar fornecedores

Protótipos relacionados ao caso de uso “UC002 - Cadastrar fornecedores”, demonstrando a jornada de cadastro de fornecedores.

UC002 - Tela 1: cadastro de fornecedor

![UC002  Cadastrar fornecedores](https://github.com/crborges86/cadastroSenac/assets/143454517/45440fa0-6026-4750-ab68-b7e2ac1ef3f1)

UC002 - Tela 2: confirmação de cadastro de fornecedor

![UC002  Cadastrar fornecedores (Confirmação)](https://github.com/crborges86/cadastroSenac/assets/143454517/2d27617a-ec70-44c1-b6ec-b6f508e8974b)

UC002 - Tela 3: fluxo alternativo, dados incompletos

![UC002  Cadastrar fornecedores (Fluxo alternativo)](https://github.com/crborges86/cadastroSenac/assets/143454517/38d4592e-4b4a-4974-906b-a3e60a295ea2)

### Solicitar cadastro

Protótipos relacionados ao caso de uso “UC003 - Solicitar cadastro”, demonstrando a jornada de cadastro de alunos e professores.

UC003 - Tela 1: cadastro de aluno e professor

![UC003  Solicitar cadastro](https://github.com/crborges86/cadastroSenac/assets/143454517/1d19802a-9305-4d9f-a2ce-32407b6bfe96)

UC003 - Tela 2: anexar documentação de aluno

![UC003  Solicitar cadastro-1](https://github.com/crborges86/cadastroSenac/assets/143454517/d73fe4bc-50d2-47eb-91fc-369c093f816b)

UC003 - Tela 3: anexar documentação de professor

![UC003  Solicitar cadastro-2](https://github.com/crborges86/cadastroSenac/assets/143454517/a8102ef7-08a1-4ef7-b57c-e28d2246f83f)

UC003 - Tela 4: confirmação de solicitação

![UC003  Solicitar cadastro-3](https://github.com/crborges86/cadastroSenac/assets/143454517/9e52ce18-65fc-4089-9f9e-56b206f12c82)

UC003 - Tela 5: fluxo alternativo, falta de documentação

![UC003  Solicitar cadastro-4](https://github.com/crborges86/cadastroSenac/assets/143454517/1699504f-c580-476d-aa26-e248ad44bc30)


### Validar documentação

Protótipos relacionados ao caso de uso “UC004 - Validar documentação”, demonstrando a jornada de validação de documentação para cadastro de usuários.

UC004 - Tela 1: lista de documentos pendentes de validação

![UC004  Validar documentação](https://github.com/crborges86/cadastroSenac/assets/143454517/4012c98b-cb83-40b8-b237-f3c282b8baab)

UC004 - Tela 2: aprovação ou reprovação

![UC004  Validar documentação-1](https://github.com/crborges86/cadastroSenac/assets/143454517/400a96e6-2c29-41ae-a69a-66f2e837f605)

UC004 - Tela 3: documentação validada

![UC004  Validar documentação-2](https://github.com/crborges86/cadastroSenac/assets/143454517/7265e083-0551-4d8c-a3ce-1782f4a38ba8)

UC004 - Tela 4: documentação reprovada

![UC004  Validar documentação (fluxo alternativo)](https://github.com/crborges86/cadastroSenac/assets/143454517/35c47a55-53f1-42fd-bde5-853ac50c557f)

### Ativar usuários

Protótipos relacionados ao caso de uso “UC005 - Ativar usuários”, demonstrando a jornada de ativação dos usuários.

UC005 - Tela 1: validação de documentos para ativar usuários

![UC005  Ativar usuários](https://github.com/crborges86/cadastroSenac/assets/143454517/5ca8f8ea-387c-4c81-bc9c-21cb4fa1280d)

UC005 - Tela 2: revisão dos dados para ativar cadastro

![UC005  Ativar usuários-1](https://github.com/crborges86/cadastroSenac/assets/143454517/12dd17b5-cd59-4971-85a6-96ee059f442f)

UC005 - Tela 3: confirmação usuário ativado

![UC005  Ativar usuários-2](https://github.com/crborges86/cadastroSenac/assets/143454517/8d03dd70-c0b9-48bf-8fcf-7a7e1b9e6944)

### Atualizar cadastro

Protótipos relacionados ao caso de uso “UC006 - Atualizar cadastro”, demonstrando a jornada de atualização de dados cadastrais dos usuários.

UC006 - Tela 1: atualização de cadastro

![UC006  Atualizar cadastro](https://github.com/crborges86/cadastroSenac/assets/143454517/d676c41b-e490-465c-a023-e32be71ab29f)

UC006 - Tela 2: confirmação cadastro atualizado

![UC006  Atualizar cadastro-1](https://github.com/crborges86/cadastroSenac/assets/143454517/31c06835-1821-4ca0-b323-536c33977473)

UC006 - Tela 3: fluxo alternativo, alteração de nome

![UC006  Atualizar cadastro (fluxo alternativo)](https://github.com/crborges86/cadastroSenac/assets/143454517/c97a4b8b-1dbe-487a-bb9c-83ff59b00d18)

### Consultar cadastro de pessoas físicas e jurídicas

Protótipos relacionados ao caso de uso “UC007 - Consultar cadastro de pessoas físicas e jurídicas”, demonstrando a jornada de consulta dos cadastros de pessoas físicas e jurídicas ligadas à universidade.

UC007 - Tela 1: localizar pessoas físicas e jurídicas

![UC007  Consultar cadastro de pessoas físicas e jurídicas](https://github.com/crborges86/cadastroSenac/assets/143454517/deb4bdd3-d874-44c7-94d7-8ba5d8c5ccf0)

UC007 - Tela 2: consulta de cadastro pessoa física

![UC007  Consultar cadastro de pessoas físicas e jurídicas-2](https://github.com/crborges86/cadastroSenac/assets/143454517/44c30cfa-ecc5-44e8-b200-7def3b7dd359)

UC007 - Tela 3: consulta de cadastro pessoa jurídica

![UC007  Consultar cadastro de pessoas físicas e jurídicas-3](https://github.com/crborges86/cadastroSenac/assets/143454517/23c09a90-1fff-40f8-be21-ffdfdfdc8cbc)

UC007 - Tela 4: cadastro não encontrado

![UC007  Consultar cadastro de pessoas físicas e jurídicas-1](https://github.com/crborges86/cadastroSenac/assets/143454517/dfca2b2b-f6a6-458c-8986-2b34147fe5be)

### Inativar usuários

Protótipos relacionados ao caso de uso “UC008 - Inativar usuários”, demonstrando a jornada de inativação de usuários ligados à universidade.

UC008 - Tela 1: localizar usuário para inativar

![UC008  Inativar usuários](https://github.com/crborges86/cadastroSenac/assets/143454517/a9dacf44-8964-4bec-8b94-02a7e1942482)

UC008 - Tela 2: revisão dos dados para seguir com inativação

![UC008  Inativar usuários-3](https://github.com/crborges86/cadastroSenac/assets/143454517/3fc42ade-50dc-4187-b681-016a27d24654)

UC008 - Tela 3: confirmação de inativação

![UC008  Inativar usuários-2](https://github.com/crborges86/cadastroSenac/assets/143454517/87e4ef7a-5397-4dee-aad0-a451464a3d7b)

UC008 - Tela 4: fluxo alternativo, cadastro não encontrado

![UC008  Inativar usuários-1](https://github.com/crborges86/cadastroSenac/assets/143454517/01766860-9e60-4e27-9d7f-2e6828d2ee2a)


### Cadastrar usuários para funcionários

Protótipos relacionados ao caso de uso “UC009 - Cadastrar usuários para funcionários”, demonstrando a jornada de cadastro para login de funcionários.

UC009 - Tela 1: cadastro de usuários para funcionários

![UC009  Cadastrar usuário para funcionários](https://github.com/crborges86/cadastroSenac/assets/143454517/ee8433ff-462f-4d21-9ef9-011ae3dcc3ed)

UC009 - Tela 2: usuário cadastrado

![UC009  Cadastrar usuário para funcionários-1](https://github.com/crborges86/cadastroSenac/assets/143454517/b57aa68b-6ef1-4db0-a834-45e3ecf338c3)

UC009 - Tela 3: fluxo alternativo, dados incompletos

![UC009  Cadastrar usuário para funcionários-2](https://github.com/crborges86/cadastroSenac/assets/143454517/4423a0c5-9d58-476c-bfea-be7d8f3b99f2)

### Visualizar perfil com histórico de negociações

Protótipos relacionados ao caso de uso “UC010 - Visualizar perfil com histórico de negociações”, demonstrando a jornada do fornecedor consultar seu histórico de negociações com a universidade.

UC010 - Tela 1: tela após login pessoa jurídica

![UC010  Visualizar perfil com histórico de negociações](https://github.com/crborges86/cadastroSenac/assets/143454517/676c0775-c6fc-4e25-8362-646d3ec14093)

UC010 - Tela 2: dados cadastrais pessoa jurídica

![UC002  Cadastrar fornecedores3](https://github.com/crborges86/cadastroSenac/assets/143454517/2e0520c4-7b6a-4d3b-b16a-731683688484)

UC010 - Tela 3: histórico de negociações

![UC010  Visualizar perfil com histórico de negociações1](https://github.com/crborges86/cadastroSenac/assets/143454517/232ee986-26a0-4b01-8898-12cc5f0d49ba)

UC010 - Tela 4: detalhamento de negociação

![UC010  Visualizar perfil com histórico de negociações2](https://github.com/crborges86/cadastroSenac/assets/143454517/7b59973f-1a3b-4e5d-8dbe-b9c6536448f0)

UC010 - Tela 5: fluxo alternativo, sem histórico de negociações

![UC010  Visualizar perfil com histórico de negociações4](https://github.com/crborges86/cadastroSenac/assets/143454517/b3f549b8-e72c-47f2-b467-c631649a9ba7)

### Visualizar perfil

Protótipos relacionados ao caso de uso “UC011 - Visualizar perfil”, demonstrando a jornada do professor ou aluno visualizar seu perfil.

UC011 - Tela 1: perfil de aluno

UC011 - Tela 2: fluxo alternativo, acesso inativado

### Consultar perfil do aluno

Protótipos relacionados ao caso de uso “UC012 - Consultar perfil do aluno”, demonstrando a jornada do professor ao consultar o perfil do aluno.

UC012 - Tela 1: perfil professor

UC012 - Tela 2: lista de alunos vinculados

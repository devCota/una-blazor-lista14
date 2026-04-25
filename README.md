# Lista de Exercicios XIV - Curriculo Blazor

![Status](https://img.shields.io/badge/status-concluido-green)
![Tecnologia](https://img.shields.io/badge/tecnologia-Blazor%20WebAssembly-purple)
![Linguagem](https://img.shields.io/badge/linguagem-C%23%20.NET-blue)
![Disciplina](https://img.shields.io/badge/IHC%20e%20UX-UNA-orange)

---

## Sobre o Projeto

Este repositorio documenta a implementacao da **Lista de Exercicios XIV** da disciplina **Interacao Humano Computador e UX**, desenvolvida no contexto academico do **Centro Universitario UNA**, sob orientacao do **Professor Daniel Henrique Matos de Paiva**.

A atividade consiste na atualizacao de uma aplicacao de curriculo feita em **Blazor WebAssembly**, personalizando o layout e as informacoes profissionais para apresentar os dados de forma mais clara, organizada e profissional.

---

## Identificacao

**Aluno:** Lucas Cota  
**Curso:** Analise e Desenvolvimento de Sistemas  
**Instituicao:** Centro Universitario UNA  
**Disciplina:** Interacao Humano Computador e UX  
**Professor:** Daniel Henrique Matos de Paiva

---

## Objetivo da Atividade

Refazer o layout e/ou adicionar informacoes ao projeto **MeuCurriculo Blazor**, deixando a aplicacao mais profissional e alinhada aos dados pessoais e profissionais do aluno.

A proposta envolve:

- personalizacao da interface do curriculo
- organizacao das informacoes profissionais
- exibicao de experiencias em componentes reutilizaveis
- aplicacao de conceitos de Interacao Humano Computador e UX
- uso de C# e .NET no desenvolvimento da aplicacao

---

## Tecnologia Utilizada

- **C#**
- **.NET 8**
- **Blazor WebAssembly**
- **Razor Components**
- **HTML**
- **CSS**
- **Bootstrap**

---

## Funcionalidades Implementadas

### Pagina inicial do curriculo

A aplicacao apresenta uma pagina principal com informacoes do profissional, incluindo nome, area de atuacao e imagem de perfil.

### Lista de experiencias profissionais

As experiencias sao exibidas de forma visual por meio de cards, facilitando a leitura das informacoes mais importantes, como cargo, empresa, periodo e descricao das atividades.

### Componente reutilizavel

O componente `ExperienciaCard.razor` foi criado para receber os dados de cada experiencia profissional e exibi-los de forma padronizada, melhorando a organizacao do codigo e da interface.

---

## Heuristica: Ajuda e Documentacao

De acordo com a heuristica **Ajuda e documentacao**, mesmo que o sistema seja simples e intuitivo, as informacoes de apoio devem ser faceis de encontrar e focadas na tarefa do usuario.

Neste projeto, essa heuristica foi aplicada por meio de:

- interface objetiva, com separacao clara entre dados pessoais e experiencias profissionais
- titulos diretos para orientar a leitura do curriculo
- cards com informacoes organizadas por cargo, empresa, periodo e descricao
- documentacao no README com instrucoes de execucao e descricao da estrutura do projeto
- uso de componentes nomeados de forma clara, facilitando manutencao e entendimento do codigo

Assim, o usuario consegue compreender rapidamente o objetivo da aplicacao e navegar pelas informacoes sem depender de explicacoes extensas.

---

## Screenshot

Adicione ao repositorio um printscreen da aplicacao em execucao e atualize o caminho abaixo, caso necessario.

![Screenshot da aplicacao](docs/screenshot.png)

---

## Estrutura do Projeto

```text
una-blazor-lista14/
├── Components/
│   └── ExperienciaCard.razor
├── Layout/
│   ├── MainLayout.razor
│   ├── MainLayout.razor.css
│   ├── NavMenu.razor
│   └── NavMenu.razor.css
├── Models/
│   └── Experiencia.cs
├── Pages/
│   ├── Home.razor
│   ├── Counter.razor
│   └── Weather.razor
├── Properties/
│   └── launchSettings.json
├── wwwroot/
│   ├── css/
│   ├── favicon.png
│   ├── icon-192.png
│   └── index.html
├── App.razor
├── Program.cs
├── MeuCurriculo.csproj
├── MeuCurriculo.sln
├── _Imports.razor
└── README.md
```

---

## Guia de Execucao

### Pre-requisitos

Para executar o projeto, e necessario ter instalado:

- .NET SDK 8.0 ou superior
- Git
- navegador web atualizado

### Clonar o repositorio

```bash
git clone https://github.com/seu-usuario/una-blazor-lista14.git
cd una-blazor-lista14
```

### Restaurar dependencias

```bash
dotnet restore
```

### Executar a aplicacao

```bash
dotnet run
```

Depois de executar o comando, acesse no navegador o endereco exibido no terminal, geralmente:

```text
https://localhost:5001
```

ou

```text
http://localhost:5000
```

---

## Conceitos Utilizados

- componentes Razor
- classes e objetos em C#
- lista de objetos com `List<T>`
- parametros em componentes Blazor
- estrutura de projeto .NET
- organizacao visual com Bootstrap
- principios basicos de usabilidade e UX

---

## Boas Praticas Aplicadas

- separacao de responsabilidades entre pagina, componente e modelo
- uso de componente reutilizavel para experiencias profissionais
- nomes de arquivos e classes coerentes com suas funcoes
- organizacao das informacoes em secoes claras
- interface simples, objetiva e focada na leitura do curriculo
- documentacao estruturada para facilitar execucao e avaliacao do projeto

---

## Conclusao

A atividade permitiu aplicar conceitos de **Blazor WebAssembly**, **C# .NET** e **Interacao Humano Computador e UX** em uma aplicacao pratica de curriculo profissional.

O projeto atende aos requisitos propostos ao apresentar uma aplicacao personalizada, com codigo-fonte organizado, documentacao de execucao e preocupacao com clareza, usabilidade e apresentacao das informacoes.

---

## Autor

Lucas Cota  
Estudante de Analise e Desenvolvimento de Sistemas  
Foco em Backend e Engenharia de Software

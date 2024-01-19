<h2 align="center"> Plano de Testes: Forte Blog - Plataforma Interna de Colaboração </h2>

<br>

- [ Introdução ](#Introdução)
- [ Objetivo do Teste ](#Objetivo-do-Teste)
- [ Escopo do Teste ](#Escopo-do-Teste)
- [ Casos de Teste ](#Casos-de-Teste)
- [ Ambiente de Teste ](#Ambiente-de-Teste)
- [ Critérios de Aceitação ](#Critérios-de-Aceitação)
- [ Documentação de Bugs e Comunicação ](#Documentação-de-Bugs-e-Comunicação)

<br>


## Introdução

<br>

O Forte Blog é uma plataforma interna de colaboração desenvolvida para permitir que membros da equipe publiquem artigos técnicos, atualizações de projetos e ideias. Este plano de testes visa garantir que o software atenda aos requisitos especificados, proporcionando uma experiência de usuário confiável.

<br>

## Objetivo do Teste

<br>

O objetivo principal é garantir que o Forte Blog atenda aos requisitos especificados e ofereça uma experiência de usuário consistente, segura e eficaz para a equipe de desenvolvimento.

<br>

##  Escopo do Teste

#### Testes Funcionais:

1. Verificar a funcionalidade de publicação de artigos.
2. Avaliar o sistema de comentários e interação.
3. Testar a responsividade em diferentes dispositivos.

#### Testes de Desempenho:

1. Avaliar o tempo de carregamento das páginas.
2. Testar a escalabilidade da plataforma com carga simulada.

#### Testes de Segurança e Privacidade:

1. Verificar a presença de HTTPS na conexão.
2. Garantir que os dados dos usuários estejam protegidos.

#### Testes de Usabilidade:

1. Avaliar a facilidade de navegação e uso da interface.
2. Verificar se a interface atende aos padrões de design estabelecidos.

<br>


## Casos de Teste
<br>

[VS Code](https://code.visualstudio.com/)

<br>

## Ambiente de Teste

- Navegadores: Chrome, Firefox, Edge
- Dispositivos: Desktop, Tablet, Celular
- Sistemas Operacionais: Windows, MacOS, Android, iOS
<br>

## Critérios de Aceitação

1. Todos os casos de teste passam com sucesso.
2. Não há bugs críticos ou bloqueadores não resolvidos.
3. A plataforma respeita os requisitos de segurança e privacidade.
4. A interface é responsiva e apresenta bom desempenho.

<br>

## Documentação de Bugs e Comunicação

#### Documentação de Bugs:

- Utilizar o Google Docs conforme especificado.
- Incluir detalhes como:
  - Passos para reproduzir o bug.
  - Comportamento esperado e observado.
  - Navegador utilizado.
  - Qualquer informação adicional relevante.

#### Comunicação:

- Relatar regularmente o progresso à equipe de desenvolvimento.

<br>

## Automação

Objetivo: Automatizar interações de mensagens, na perspectiva do usuário, ao acessar a aplicação [Forte Blog](https://qa-24.fuerza.space/).

<br>

#### ⚙️ Tecnologias utilizadas

**IDE para implementação**: VS Code

**Linguagens**: JavaScript

**Frameworks**: Cypress (Versão 12.2.0)

<br>

 #### ⚠️ Pré-requisito

Já deve ter instalado em seu computador:
- Node.js;
- VS Code.


Se você não tiver, verifique estes links: [Node.js](https://nodejs.org/en/) | [VS Code](https://code.visualstudio.com/)

<br>


#### 🗃️ Estrutura de Arquivos

```
    |-- cypress
    |-- e2e
    |  |-- tasks.cy.js
    |-- fixtures
    |  |-- example.json
    |-- support
    |  |-- commands.js
    |  |-- e2e.js
    |  |-- locators.js
    |-- node_modulos
```
<br>

### Assistir ao video do Projeto: [Youtube](https://youtu.be/7Olo-wJS-0Q)
	
 ------
	
:speech_balloon: [Linkedin](https://www.linkedin.com/in/camilalnmoura/)

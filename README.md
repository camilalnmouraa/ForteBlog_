# Escopo de Testes - Forte Blog

- [Objetivo](#objetivo)
- [Layout e Usabilidade](#layout-e-usabilidade)
- [Funcionalidades Principais](#funcionalidades-principais)
- [Segurança e Privacidade dos Dados](#segurança-e-privacidade-dos-dados)
- [Desempenho e Escalabilidade](#desempenho-e-escalabilidade)
- [Casos de Teste Adicionais](#casos-de-teste-adicionais)
- [Ambiente de Teste](#ambiente-de-teste)
- [Automação](#automação)

## Objetivo

O objetivo deste escopo de testes é definir os limites e áreas específicas abordadas nos testes da plataforma Forte Blog, garantindo qualidade, segurança, desempenho e usabilidade para uma experiência positiva dos usuários.

## 1. Layout e Usabilidade

### 1.1 Layout e Temas
- Garantir estética agradável e adaptação aos temas claro e escuro.
- Verificar integração visual da logo da empresa no tema claro.

### 1.2 Usabilidade
- Testar interação ao clicar na foto do perfil e selecionar botões.
- Verificar presença da opção de sair ao clicar na lupa.
- Avaliar facilidade de uso na navegação entre diferentes seções.

## 2. Funcionalidades Principais

### 2.1 Publicação de Artigos
- Testar processo de publicação, incluindo validação de campos obrigatórios.
- Confirmar visibilidade correta dos artigos na página inicial após publicação.

### 2.2 Interagir com Comentários
- Validar adição, edição e exclusão de comentários.
- Assegurar que notificações relacionadas a comentários sejam geradas corretamente.

### 2.3 Pesquisar e Filtrar Conteúdo
- Testar funcionalidade de pesquisa por título de artigo.
- Avaliar precisão da filtragem por categoria.
- Verificar se pesquisa é mantida ao navegar entre as páginas.

## 3. Segurança e Privacidade dos Dados

### 3.1 Autenticação e Autorização
- Garantir autenticação necessária para ações específicas.
- Verificar acesso restrito a dados privados de acordo com permissões do usuário.

### 3.2 Proteção contra Ataques
- Testar segurança contra injeções de SQL e Cross-Site Scripting (XSS) nos campos de entrada.

## 4. Desempenho e Escalabilidade

### 4.1 Performance Geral
- Avaliar velocidade de carregamento das páginas principais.
- Testar escalabilidade ao adicionar grande número de publicações e comentários.

### 4.2 Otimização de Banco de Dados
- Avaliar eficiência das consultas ao banco de dados.
- Testar performance durante buscas e filtragens intensivas.

## 5. Casos de Teste Adicionais

### 5.1 Interação com Comentários
- Validar experiência ao adicionar, editar e excluir comentários.

### 5.2 Compartilhamento de Publicações
- Testar funcionalidade de compartilhamento de publicações.

### 5.3 Gerenciamento de Perfil
- Avaliar capacidade de editar informações de perfil e alterar senha.

### 5.4 Experiência do Novo Usuário
- Testar processo de registro de um novo usuário.
- Avaliar orientação ou tutorial para novos usuários.

### 5.5 Navegação entre Páginas
- Confirmar navegação suave e consistência de informações em diferentes páginas.

### 5.6 Testes de Performance
- Avaliar desempenho em condições de tráfego intenso.

### 5.7 Suporte a Diferentes Navegadores
- Testar compatibilidade com navegadores populares.

### 5.8 Resiliência a Falhas
- Avaliar capacidade de recuperação após falhas de rede ou erros inesperados do servidor.

### 5.9 Acessibilidade
- Testar acessibilidade usando um leitor de tela e verificando descrições adequadas para elementos visuais.

## Ambiente de Teste

- Navegador: Chrome - Versão 120.0.6099.225 (Versão oficial)
- Dispositivos: Desktop, [Mobile simulator - responsive testing tool](https://chromewebstore.google.com/detail/ckejmhbmlajgoklhgbapkiccekfoccmk) e [PageSpeed](https://pagespeed.web.dev/)
- Sistemas Operacionais: Windows



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

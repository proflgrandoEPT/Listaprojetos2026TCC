# Portfólio de Projetos 2026 - Desenvolvimento de Sistemas

Este repositório contém a landing page estática que centraliza a vitrine de projetos dos alunos do curso técnico em Desenvolvimento de Sistemas da E.E. Dr. Alfredo Cardoso.

## Link de Acesso Production
A página atualizada e publicada pode ser acessada através do endereço:
👉 https://tccds2026.vercel.app/

Para manter a organização e o padrão visual da página, cada grupo deve atualizar suas próprias informações diretamente no arquivo `index.html` seguindo as instruções abaixo.

# Portfólio de Projetos 2026 - Desenvolvimento de Sistemas

Este repositório contém a landing page estática que centraliza a vitrine de projetos dos alunos do curso técnico em Desenvolvimento de Sistemas da E.E. Dr. Alfredo Cardoso.

Para manter a organização e o padrão visual da página, cada grupo deve atualizar suas próprias informações diretamente no arquivo `index.html` seguindo as instruções abaixo.

## Instruções para Atualização

### 1. Localize o seu Grupo no Código
Abra o arquivo `index.html` no seu editor de código (como o VS Code) e utilize o comando de busca (`Ctrl + F` ou `Cmd + F`). Digite o marcador correspondente ao seu grupo para ir direto ao bloco correto:
* Grupo 1: Procure por `[CARD] GRUPO 1: SIE`
* Grupo 2: Procure por `[CARD] GRUPO 2: SCHOOL GAME`
* Grupo 3: Procure por `[CARD] GRUPO 3: CONTROLE DE OCORRÊNCIAS`
* Grupo 4: Procure por `[CARD] GRUPO 4: AGUARDANDO DEFINIÇÃO`

### 2. Substitua as Informações do Projeto
Dentro do bloco do seu grupo, altere os textos genéricos pelas informações reais do seu projeto:
* **Título e Subtítulo:** Altere as tags `<h2>` e o parágrafo de categoria se houver necessidade de ajuste no nome do sistema.
* **Descrição:** Substitua o texto do parágrafo `<p class="text-sm...">` por um resumo claro e objetivo do escopo do seu projeto. Evite textos excessivamente longos para não desalinhar o layout.

### 3. Atualize a Lista de Integrantes e Redes Sociais
* **Se o integrante possui LinkedIn:** Utilize a tag de link existente. Substitua o link do atributo `href="..."` pelo link do perfil profissional e mude o texto para o nome do aluno.
* **Se o integrante não possui LinkedIn:** Remova a tag `<a>` e utilize apenas a tag `<span>Nome do Aluno</span>`, adicionando a classe `pl-5` na tag `<li>` para manter o alinhamento visual com os demais integrantes.

### 4. Insira os Links dos Repositórios e Portfólios
No final do bloco do seu card, localize os botões de ação e substitua o caractere `#` no atributo `href` pelos links reais do grupo:
* Link do documento de portfólio (Google Docs, Canva, etc.) no botão "Ver Portfólio".
* Link do repositório do projeto no botão "Repositório". Se o repositório ainda não estiver pronto, mantenha o botão desabilitado conforme o modelo do Grupo 4.

### 5. Configuração da Imagem do Projeto
* Tire um print screen da tela principal do seu sistema ou crie uma arte digital representativa.
* Salve a imagem na pasta `img/` do projeto.
* Nomeie o arquivo de forma padronizada (ex: `grupo1.png`, `grupo2.png`).
* No código do seu card, altere o atributo `src="img/imagem-antiga.png"` para o caminho exato da sua nova imagem.

## Boas Práticas e Cuidados Técnicos

* **Não remova as classes do Tailwind CSS:** Classes como `flex`, `p-5`, `rounded-xl`, `custom-transition`, entre outras, são responsáveis pelo design e pela responsividade da página. Altere apenas os textos e os links (conteúdo entre as tags).
* **Teste Localmente:** Antes de realizar o commit ou enviar o Pull Request, abra o arquivo `index.html` diretamente no seu navegador de preferência. Alterne o zoom da tela e verifique se o card do seu grupo mantém o alinhamento com os demais e se todos os links estão funcionando corretamente.
* **Revisão Ortográfica:** Certifique-se de que o nome dos integrantes, a descrição do projeto e os títulos estejam escritos corretamente, sem erros gramaticais ou de digitação.

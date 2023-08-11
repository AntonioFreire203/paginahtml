# Guia para Criar sua Primeira Página HTML e CSS no GitHub

**Bem-vindo ao guia de criação da sua primeira página HTML e CSS usando o GitHub!** Neste guia, você encontrará passos simples para criar e hospedar sua página no GitHub . Vamos começar!

## Passo 1: Preparação

1. **Crie uma Conta no GitHub**: Se você ainda não possui uma conta no GitHub, crie uma em `[github.com](https://github.com)`.

2. **Instale o Git**: Se ainda não tiver o Git instalado no seu computador, você pode baixá-lo em `[git-scm.com]
   (https://git-scm.com/downloads)`.

4. **Editor de Código**: Escolha um editor de código, como Visual Studio Code, Sublime Text ou Atom, para escrever e editar seu código.

## Passo 2: Estrutura Básica do HTML

Crie um novo repositório no GitHub:

1. Faça login na sua conta do GitHub e clique no sinal de "+" no canto superior direito da página. Selecione "New Repository".

2. Dê um nome ao seu repositório (por exemplo, "minha-primeira-pagina") e adicione uma descrição opcional.

3. Escolha as configurações de visibilidade do repositório (público ou privado) de acordo com sua preferência.

4. Clique em "Create Repository".

## Passo 3: Clonando o Repositório Remoto e Criar um Ramo de Desenvolvimento:

No seu computador:

1. Abra o terminal ou prompt de comando.

2. Navegue para a pasta onde deseja clonar seu repositório usando o comando `cd pasta`.

3. Clone o repositório usando o comando:

**git clone https://github.com/seu-usuario/minha-primeira-pagina.git**

4.Antes de começar a fazer alterações, crie um novo ramo para o seu trabalho. Isso permite que você isole suas alterações do ramo principal até que estejam prontas para serem incorporadas:

**git checkout -b nome-do-ramo**


## Passo 4: Estrutura Básica do HTML 

Agora que você tem uma cópia local do repositório, é hora de adicionar a estrutura básica do HTML:

   1. Navegue para a pasta do seu repositório clonado usando o comando cd minha-primeira-pagina.

   2. Crie um arquivo chamado index.html e abra-o no seu editor de código.

   3.Copie e cole o código HTML do Passo 2 neste arquivo.

##  Passo 5: Estilizando com CSS

Para estilizar sua página, você criará um arquivo externo CSS:

    1.Na pasta do seu repositório, crie uma pasta chamada css.

    2.Dentro da pasta css, crie um arquivo chamado style.css e abra-o no seu editor de código.

    3.Copie e cole o código CSS do Passo 3 neste arquivo.

## Passo 6: Commits 
**Atenção:**Realize suas alterações no código e faça commits regulares e significativos. 
Lembre-se de incluir mensagens de commit descritivas que expliquem as alterações que você fez:

**git add .**  # Adicionar as alterações para o próximo commit
**git commit -m** "Mensagem descritiva do commit"


## Passo 7: Sincronizar com o Repositório Remoto:

Regularmente, enquanto trabalha em seu ramo, você deve sincronizar com o repositório remoto para evitar divergências:

**git fetch origin  # Buscar as atualizações do repositório remoto**

**git rebase origin/nome-do-ramo  # Reaplicar suas alterações sobre as do remoto**

## Passo 8:Fazer o Push para o Repositório Remoto:

Uma vez que suas alterações estejam prontas, você pode fazer o push do seu ramo para o repositório remoto:

**git push origin nome-do-ramo**

## Atenção:Caso haja Conflitos:

Se houver conflitos durante o rebase ou o pull, resolva-os manualmente, commit e continue o rebase ou pull:

**git add .  # Adicionar as alterações resolvidas**

**git rebase --continue  # Continuar o rebase após resolver conflitos**








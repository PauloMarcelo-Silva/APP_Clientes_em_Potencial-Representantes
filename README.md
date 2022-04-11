# APP_Clientes_em_Potencial-Representantes
## Aplicativo feito com PoweApp da microsoft + o DataVerse

### Foi um projeto final do curso Formação em Power Platform - Uniesp-PB.
### Aplicativo onde foi utilizado o PowerApps da microsoft,usando iteração com o dataverse para armazenar cliente e representantes numa tabela de dados,onde o projeto precisava ter os seguintes componentes:

### O TCC do projeto, consistirá em abordar o assunto aplicativo móvel do tipo tela (Canvas) para Prospecção de Clientes.

### 1 - O aplicativo deverá ter como servidor de banco de dados o Dataverse

1.1 - Tabelas necessárias
1.1.1 - Tabela Cliente Potencial (campos abaixo) 1.1.1.1 - Nome do Cliente (Texto simples)
1.1.1.2 - Apelido (Texto simples)
1.1.1.3 - Endereço (Texto simples)
1.1.1.4 - Número do Endereço (Texto simples)
1.1.1.5 - Bairro do Endereço (Texto Simples)
1.1.1.6 - Cidade do Endereço (Texto Simples)
1.1.1.7 - Estado/UF do Endereço (Pesquisa)-> tabela de estados será descrita abaixo
1.1.1.8 - Telefone do Cliente (Texto simples -> formato telefone)
1.1.1.9 - E-mail do cliente (Texto simples -> formato e-mail)
1.1.1.10 - Representante responsável (Pesquisa) -> tabela de representante comercial será descrita abaixo

1.1.2 - Tabela Estados (campos abaixo)
1.1.2.1 - Sigla (Texto simples -> tamanho de 2 caracteres)
1.1.2.2 - Nome do Estado (Texto Simples)

Nota: A carga de dados (inclusão) dos estados deverá ser executado via planilha de excel (anexar planilha ao enviar o TCC)

1.1.3 - Tabela Representantes (campos abaixo)
1.1.3.1 - Nome do Representante (Texto simples)
1.1.3.2 - Telefone do representante (Texto simples -> formato telefone)
1.1.3.3 - Email do Representante (Texto simples -> formato e-mail)


2 - Telas do aplicativo

2.1 - Tela de abertura
2.1.1 - Titulo do aplicativo (Livre)
2.1.2 - Imagem logotipo (Livre)
2.1.3 - Botão para acesso (Livre -> botão ou icone)

2.2 - Tela de opções das funcionalidades
2.2.1 - Titulo (livre)
2.2.2 - Para cada funcionalidade/tela um botão ou icone de acesso
2.2.3 - Botão para retornar a tela de abertura (icone Back)

2.3 - Tela do Cliente Potencial
2.3.1 - Titulo
2.3.2 - Galeria contendo os clientes potenciais existente (Formato Titulo e SubTitulo)
2.3.3 - Definir que ao clicar em um registro da galeria deverá navegar para a tela de alteração de dados)
2.3.4 - Botão para adicionar novo cliente potencial (ao clicar deverá navegar para a tela de inclusão)
2.3.5 - Botão para retornar a tela anterior (icone Back)

2.4 - Tela do Cliente Potencial (Inclusão / Edição / Exclusão)
2.4.1 - Titulo
2.4.2 - Tela do tipo formulário de dados (controlar do modo de edição Criar/Editar por variável)
2.4.3 - Exibir todos os campos citados no item 1.1.1 Tabela Cliente Potencial (campos)
2.4.4 - Para o campo Estado/UF utilizar Caixa de Combinação (combobox) selecionando a tabela de estados como fonte de dados
2.4.5 - Para o campo Representante utilizar Caixa de Combinação (combobox) selecionando a tabela de Representantes como fonte de dados
2.4.6 - Exibir um botão/icone de exclusão do registro quando o modo de edição for Editar
2.4.7 - Botão para retornar a tela anterior (Back)

2.5 - Tela do Representante
2.5.1 - Titulo
2.5.2 - Galeria contendo os Representantes existente (Formato Titulo e SubTitulo)
2.5.3 - Definir que ao clicar em um registro da galeria deverá navegar para a tela de alteração de dados)
2.5.4 - Botão para adicionar novo Representante (ao clicar deverá navegar para a tela de inclusão)
2.5.5 - Botão para retornar a tela anterior (icone Back)

2.6 - Tela do Representante (Inclusão / Edição / Exclusão)
2.6.1 - Titulo
2.6.2 - Tela do tipo formulário de dados (controlar do modo de edição Criar/Editar por variável)
2.6.3 - Exibir todos os campos citados no item 1.1.3 Tabela Representantes (campos)
2.6.4 - Exibir um botão/icone de exclusão do registro quando o modo de edição for Editar
2.6.5 - Botão para retornar a tela anterior (Back)


3 - Fluxo do Power Automate

3.1 - Criar um fluxo para que quando um novo registro de cliente potencial for criado enviar um e-mail
      (endereço do e-mail será o informado no cadastro do cliente potencial)
         
4 - Exportar aplicativo e postar no portal classrom juntamente com a planilha utilizada para carga dos dados do estados.


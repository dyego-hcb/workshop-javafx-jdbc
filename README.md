# Projeto JavaFX - CRUD de Departamentos e Vendedores

### Descrição

Este projeto demonstra como criar um aplicativo JavaFX para realizar operações CRUD (Create, Read, Update, Delete) em duas entidades: Departamento e Vendedor.

O aplicativo é composto por três telas principais:

* **MainView:** Tela principal do aplicativo, que contém um menu com opções para acessar as outras telas.
* **DepartmentListView:** Tela de listagem de departamentos.
* **SellerListView:** Tela de listagem de vendedores.

### Pré-requisitos

* Java 17 ou superior
* MySQL 8 ou superior

### Instalação

Para instalar o aplicativo, siga estas etapas:

1. Instale o Java 17 ou superior.
2. Baixe o arquivo JAR do aplicativo [aqui](https://github.com/bard/workshop-javafx-jdbc-app/raw/main/workshop-javafx-jdbc-app.jar).
3. Copie o arquivo JAR para uma pasta de sua preferência.
4. Copie os arquivos `DB.properties`, `mysql-connector-java-8.0.27.jar` e `javafx-sdk-17.0.1.jar` para a mesma pasta do arquivo JAR.

### Execução

Para executar o aplicativo, siga estas etapas:

1. Abra um terminal ou prompt de comando na pasta onde o arquivo JAR está localizado.
2. Execute o comando a seguir:

java --module-path %PATH_TO_FX% --add-modules javafx.controls,javafx.fxml -cp workshop-javafx-jdbc.jar application.Main

Onde:

* %PATH_TO_FX% é o caminho para a pasta do SDK do JavaFX.
* workshop-javafx-jdbc-app é o nome da pasta que contem o arquivo workshop-javafx-jdbc.jar, arquivo JAR do aplicativo.

Uso:

Após executar o aplicativo, a tela principal será exibida.

A partir da tela principal, você pode acessar as outras telas usando o menu.

Na tela de listagem de departamentos, você pode visualizar a lista de departamentos cadastrados.

Para criar um novo departamento, clique no botão Novo.

Na tela de formulário de departamento, insira os dados do departamento e clique no botão Salvar.

Para atualizar um departamento, selecione o departamento na lista e clique no botão Editar.

Na tela de formulário de departamento, altere os dados do departamento e clique no botão Salvar.

Para excluir um departamento, selecione o departamento na lista e clique no botão Excluir.

Na tela de listagem de vendedores, você pode visualizar a lista de vendedores cadastrados.

Para criar um novo vendedor, clique no botão Novo.

Na tela de formulário de vendedor, insira os dados do vendedor e clique no botão Salvar.

Para atualizar um vendedor, selecione o vendedor na lista e clique no botão Editar.

Na tela de formulário de vendedor, altere os dados do vendedor e clique no botão Salvar.

Para excluir um vendedor, selecione o vendedor na lista e clique no botão Excluir.
# Módulo estoque
Módulo pai dos outros 2 submódulos para funcionamento do teste técnico: inventory-api e inventory-app.

# 📦 Submódulos
| Nome do módulo     | Descrição                                                                                                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `inventory-app`    | Módulo responsável pela aplicação Vue que roda as telas com funcionalidades solicitadas no teste técnico.                                                                         |
| `inventory-api`    | API simples para funções de CRUD de produtos e movimentações (também solicitadas no teste técnico).<br/> Também agrega os testes unitários desses métodos, com cobertura de 100%. |

##  💻 Rodar aplicação
Para rodar a aplicação é necessário ter o `DOCKER PREVIAMENTE INSTALADO`.

- Na pasta raiz, execute:
   ```bash
   docker compose up -d
   ```
    * Este comando vai criar os 3 containeres necessários para executar a aplicação, são eles:
      * inventory-app (front)
      * inventory-api (back)
      * stock-db (database)


- Para acessar a aplicação, abra o navegador de sua preferência:
    * `http://localhost:8081`
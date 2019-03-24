# Exemplo Cucumber - BDD (Behavior-Driven Development)

Um projeto simples utilizando BDD.

### Pré-requisitos

É necessário ter instalado

```
Java 8
Maven
```

### Instalando

Após ter todos os pré-requisitos instalados no computador, clone o projeto na sua workspace.

```
git clone https://github.com/renanlJ/exemplo-cucumber.git
```

## Executando os testes

Na pasta do projeto basta executar o seguinte comando:
```
mvn clean verify -Dcucumber.options="--tags '@Tag'"
```
Exemplo com a execução de uma tag do projeto:
```
mvn clean verify -Dcucumber.options="--tags '@BancoTeste'"
```

## Autor

* **Renan Lemos**

Veja mais projetos no meu portifólio do no [github](https://github.com/renanlJ)

## Referências

* Conhecimento extraido do [artigo](https://www.devmedia.com.br/desenvolvimento-orientado-a-comportamento-bdd-com-cucumber/33547) do DEVMEDIA


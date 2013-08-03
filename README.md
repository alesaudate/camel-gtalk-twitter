Gtalk -> Twitter
=============================

Este exemplo mostra como usar o Gtalk para mandar mensagens para o Twitter.

Você precisa configurar:

* O arquivo app.properties (dentro de src/main/resources)
* Maven

Você NÃO precisa configurar:

* Um application server
* O arquivo applicationContext.xml (embora você possa, caso exista algo que você queira modificar)

Como usar: vá até a raiz do projeto e digite mvn exec:java. Cuidado: assim que estiver pronto, ele vai mandar uma mensagem para você que será automaticamente tuitada. Se quiser alterar isso, edite o arquivo applicationContext.xml (que está presente em src/main/resources).
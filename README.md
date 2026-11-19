# cidedson.github.io

Site de apoio do app **TDAH na Vida Real**.

- `.well-known/assetlinks.json`: prova para o Android de que os links `https://cidedson.github.io/t/...` pertencem ao app `com.cidedson.tdahvidareal`. Com isso, tocar no link abre o app direto.
- `t/index.html`: página de reserva, usada se o link abrir no navegador. Mostra a tarefa e tem o botão para abrir no app.

Os dados da tarefa vão no trecho do link depois do `#`, que o navegador não envia ao servidor. O site não recebe nem guarda nenhuma tarefa.

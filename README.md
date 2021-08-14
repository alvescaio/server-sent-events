# server-sent-events
Exemplo de como usar Server-Sent Eventes (SSE) com nodejs e react

## Como usar
- Execute o client: em /sse-client rode ```yarn && yarn start```
- Execute o server: em /sse-server rode ```node server.js```
- No browser, acesse ```localhost:3000```
- No terminal, adicione um registro com o comando:
```bash
curl -X POST \
 -H "Content-Type: application/json" \
 -d '{"info": "Shark teeth are embedded in the gums rather than directly affixed to the jaw, and are constantly replaced throughout life.", "source": "https://en.wikipedia.org/wiki/Shark"}'\
 -s http://localhost:3001/fact
 ```
- Note que a paǵina da aplicação recebeu e exibiu os dados em tempo real


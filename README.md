# ÓRBITA

Crie sites e apps conversando com várias IAs em um só lugar. Traga suas próprias chaves de API, escolha o modelo a cada mensagem e veja o resultado ao vivo.

Tudo roda em **um único arquivo HTML**, sem build e sem servidor.

## Recursos

- Claude, OpenAI, Grok (xAI), Gemini, DeepSeek, Mistral, Groq, OpenRouter, Together AI, Ollama (local) e qualquer API compatível com OpenAI
- Lista de modelos de cada IA, com botão para buscar os modelos disponíveis na sua conta
- Troca de IA a cada mensagem, com o histórico compartilhado
- Visualização ao vivo do site gerado, código editável e download do `.html`
- Tempo de resposta e tokens usados em cada resposta, mais um painel de uso acumulado
- Tela inicial com logo em 3D (three.js)

## Como usar

1. Clone o repositório ou baixe o ZIP (Code → Download ZIP).
2. Abra o arquivo HTML no navegador.
3. Escolha a IA, cole sua chave de API, escolha o modelo e descreva o que quer criar.

## Segurança das chaves

- As chaves ficam no `localStorage` do navegador e são enviadas direto ao provedor escolhido. O projeto não tem servidor.
- Use o app só em computadores seus.

## Contribuindo

Issues e pull requests são bem-vindos. Para adicionar um provedor, edite os objetos `P` e `M` e a função `ask()` no arquivo. Mantenha o projeto em um único arquivo e sem dependências novas.

## Licença

Veja o arquivo [LICENSE](LICENSE).

## Aviso

Projeto independente, sem vínculo com Anthropic, OpenAI, xAI, Google ou outros provedores. O código gerado pelas IAs pode conter erros: revise antes de usar em produção.

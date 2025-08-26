# Dantas EX Nine – IA Futurista

Chat inteligente com interface moderna e integração à API OpenAI.

## Estrutura de Pastas

```
public/
  └── index.html        # Página principal do site
pages/
  └── api/
      └── chat.js       # API backend para o chat IA
.env                    # Chave da OpenAI (NÃO subir no GitHub)
package.json            # Configuração de dependências Node.js/Next.js/Tailwind
README.md               # Documentação do projeto
.gitignore              # Protege arquivos sensíveis
```

## Como rodar localmente

1. **Instale as dependências**  
   ```
   npm install
   ```

2. **Configure sua chave OpenAI**  
   O arquivo `.env` já está configurado.

3. **Rode o servidor de desenvolvimento**  
   ```
   npm run dev
   ```

4. **Acesse**  
   Normalmente em [http://localhost:3000](http://localhost:3000)

## Tecnologias

- Next.js (API e backend)
- HTML + Tailwind CSS (frontend)
- Integração com [OpenAI API](https://platform.openai.com/docs/api-reference)

## Observações

- Não envie o arquivo `.env` para o GitHub.
- O frontend está em `public/index.html`, mas pode ser adaptado para páginas React se desejar evoluir o projeto.

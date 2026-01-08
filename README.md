# GET_PROJECT_CONTENT_TXT
Gerar arquivo .txt do completo para contextualizar um chatbot externo ao ambiente de desenvolvimento. No copilot? No problem rsrs.

Quando o chat começar a derreter so começar outro com o conteúdo completo do projeto.

Executar esse script na raiz do projeto retornará todo o conteúdo implementado em um unico arquivo TXT estruturado na arvore de arquivos. 

Sim, foi feito por IA mas resolve legal o problema para nós que não tem um puto pra assinar uma IA com grande janela de contexto rsrs... todo novo chat gratuito saberá o conteúdo completo do projeto! Gemini 3 se deu muito bem com isso!
- requires python

usage: Tem um arquivo py_blacklist_files.txt o qual funciona como um gitignore so para esse script. Escreva utilizando a mesma formatação do git ignore e evitra ler arquivos indesejados.
- Está configurado para arquivos .ts, porém basta alterar a vairável 'TARGET_EXTENSION' para fazer a leitura de outros tipos de arquivos 🤙

dependencies: 
- pip install pathspec

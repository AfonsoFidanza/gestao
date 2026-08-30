# Regras deste projeto — Gestão Financeira Pessoal

## Ficheiro principal
- A app inteira vive num único ficheiro: `index.html` (HTML + CSS + JS tudo junto).
- O nome tem de ser sempre `index.html`, sem exceção — é servido via GitHub Pages, que
  procura este nome como página principal do site.
- Se receberes uma nova versão da app com outro nome de ficheiro (ex: vindo de uma
  conversa no Claude.ai), renomeia sempre para `index.html` antes de fazeres commit.

## Antes de qualquer commit ou push
- Corre uma verificação de sintaxe ao JavaScript antes de propores o commit
  (ex: `node --check` no bloco de script principal), para nunca publicar um
  ficheiro partido.
- Mostra-me sempre um resumo claro do que mudou (diff) entre a versão atual no
  repositório e a nova versão, antes de pedires confirmação.

## Confirmação obrigatória
- NUNCA faças commit ou push sem eu confirmar explicitamente que sim.
- Isto aplica-se mesmo que eu tenha dado a entender que "está tudo bem" —
  pede sempre uma confirmação clara e direta antes de publicar.
- Depois de eu confirmar, faz commit com uma mensagem descritiva (o que mudou e
  porquê, não apenas "update"), e depois o push.

## Notas gerais
- Este é o único ficheiro de código do projeto — não crias ficheiros extra
  (ex: separar em .css/.js à parte) a menos que eu peça explicitamente.
- A app usa Firebase (autenticação + Firestore) para sincronização de dados —
  não alteres a configuração do Firebase (`firebaseConfig`) sem confirmares comigo.

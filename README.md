# Archet — Estúdio de violino

Aplicação web/PWA em português para iniciantes, com conteúdo original, sem dependências externas ou backend.

## Publicação gratuita
1. Extraia o ZIP no computador. Os arquivos `index.html`, `app.js`, `curriculum.js` e demais arquivos devem estar na raiz do repositório GitHub.
2. Crie um repositório (por exemplo, `Archet`) e envie todos os arquivos desta pasta. No Netlify, escolha **Add new project → Import an existing project**, selecione GitHub e o repositório. Não há comando de build; diretório de publicação `.`.
3. Abra o endereço HTTPS. No iPhone, Safari → Compartilhar → Adicionar à Tela de Início. O primeiro carregamento exige conexão; o service worker permite uso offline posterior. Microfone exige HTTPS e permissão.

Teste local: `python -m http.server 8000` dentro desta pasta, depois abra `http://localhost:8000`.

## Funcionalidades
- Currículo progressivo em 8 módulos, teoria, ilustrações, referência sonora, teste, prática e autoavaliação. Aulas bloqueadas até a conclusão anterior.
- Planejamento móvel de 15 dias, reforço por erros recorrentes, indicadores por habilidade, XP, histórico e diário.
- Leitura de notas, ouvido relativo, ritmo por toque, dedilhado, afinação e repertório em trechos.
- Mapa cromático esquemático da primeira posição; partituras simplificadas; escalas e arpejos; afinador e metrônomo; gravador.
- Biblioteca pesquisável, glossário, referências pedagógicas, contexto copiável para ChatGPT.
- Temas claro/escuro, PWA, exportação/importação de progresso.

## Limitações
O áudio é sintetizado (não gravação de violino). O microfone estima frequência em notas isoladas; não avalia postura, arco ou expressão e não faz transcrição polifônica. Não há correção automática completa de melodias. As partituras são esquemas didáticos (não um editor/visualizador MusicXML). A biblioteca não reproduz livros: contém explicações e exercícios autorais. As gravações são mantidas na sessão e devem ser baixadas para comparação futura; backup do progresso é JSON, sem áudio. O contexto para ChatGPT é manual e não implica API/integração automática. Sem login, nuvem ou sincronização entre dispositivos. Ajuste físico do instrumento e técnica devem ser supervisionados por professor/luthier. Não toque com dor.

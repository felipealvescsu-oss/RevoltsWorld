# Revolts World — Tibia 4fun

**Primeira direção visual: O chamado das ruínas.** Criada em 05/10/2026 para Felipe. Proposta revisável, com identidade aplicada às telas demonstrativas. Sem publicação e sem alteração dos componentes em compilação.

## Abrir a proposta

Extraia o ZIP inteiro e abra `preview/index.html` em Chrome, Edge ou outro navegador moderno. Todos os assets e fontes estão locais. Também pode abrir diretamente:

- `preview/login.html` — tela de acesso demonstrativa.
- `preview/launcher.html` — launcher navegável, sem conexão ou instalação.
- `preview/brandboard.html` — marca, paleta, tipografia e arte.

Não é necessário instalar nada nem iniciar servidor HTTP. Para visualizar no telefone, transfira a pasta por um meio de sua preferência ou veja os screenshots móveis fornecidos; um caminho local deste computador não é um endereço acessível pelo telefone.

## Arquivos

| Pasta | Conteúdo |
|---|---|
| `assets/` | Arte original PNG, wordmarks em SVG, símbolo, favicon e tokens CSS |
| `assets/fonts/` | Fontes oficiais com licenças OFL, usadas localmente |
| `preview/` | Quatro páginas HTML, CSS e interações locais |
| `docs/` | Direção criativa, autoria/licenças, inventário e instruções de integração |
| `qa/` | Screenshots reais, verificações e relatório visual |
| `tools/` | Script de captura/checagem com o runtime já existente neste ambiente |

## Aplicado e pendente

**Aplicado no pacote:** Revolts World em destaque central, Tibia 4fun abaixo menor; arte, navegação, títulos de página, favicon, acesso, launcher e prancha de marca. Vocações e abas de notas são interativas. Controles de login/jogo permanecem indisponíveis, de acordo com o estado real conhecido.

**Pendente no projeto canônico:** integração dos assets e nomes em `work/client`, `work/server`, `work/login-server`, AAC e documentação operacional, conforme `docs/surface-map.md`. As fontes compartilhadas não foram alteradas porque outra tarefa compila e testa o projeto. O nome do servidor é validado entre componentes: siga a integração coordenada, não substituições globais.

## Autoria e licenças

Lettering, símbolo e interface criados nesta execução. Arte bitmap criada de fato com ImageGen para este projeto; não é screenshot do jogo. Nenhum logo ou asset CipSoft/RubinOT foi usado como referência gráfica. Fontes Cormorant Garamond e Alegreya Sans são distribuídas com suas licenças SIL Open Font License. Veja `docs/brand-assets.md` e `docs/art-provenance.md`.

O nome/subtítulo é o solicitado por Felipe. Esta proposta não declara afiliação com outros jogos. A licença das fontes não é uma declaração sobre marcas ou sobre a possibilidade jurídica de proteger arte gerada.

## Limites do preview

Não autentica, não coleta dados, não baixa binários, não consulta status, não publica um site e não instala fontes ou programas. Arte conceitual não demonstra gameplay, disponibilidade pública nem implantação de Dungeons.

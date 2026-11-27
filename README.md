# Básico para concursos

Curso completo para concursos de nível médio, do zero ao nível especialista.

## Matérias (11 trilhas, 286 aulas)

| Trilha | Conteúdo |
|---|---|
| Matemática | do cálculo básico a matrizes, sistemas lineares, geometria analítica e problemas olímpicos |
| Língua Portuguesa | ortografia, gramática, interpretação de textos, discurso direto/indireto, paralelismo e correlação verbal |
| Raciocínio Lógico | lógica proposicional, argumentação, raciocínio analítico e raciocínio espacial |
| Noções de Informática | hardware, Windows, Word/Writer, Excel/Calc, PowerPoint/Impress, internet, e-mail e segurança |
| Direito Constitucional | princípios fundamentais, art. 5º, direitos sociais e políticos, nacionalidade, organização do Estado e administração pública |
| Direito Administrativo | organização, princípios, poderes, atos, agentes, responsabilidade do Estado, Lei 14.133/2021, improbidade e Lei 9.784/1999 |
| Ética e Estatuto do Servidor | ética no serviço público, Decreto 1.171/1994 e Lei 8.112/1990 |
| Legislação Especial | LAI, LGPD, Estatuto da Pessoa com Deficiência, Lei Maria da Penha e crimes contra a administração pública |
| Atualidades | método de estudo e temas que se repetem (clima, ODS, economia, tecnologia, SUS, organismos internacionais) |
| Conhecimentos Gerais e Regionais | geografia e história do Brasil e roteiro para estudar o seu estado e município |
| Arquivologia, Administração e Atendimento | arquivologia, administração geral e atendimento ao público |

Em todas as trilhas:

- **questões geradas na hora**, com resolução passo a passo;
- simulados por nível, projetos práticos, caderno de erros com revisão espaçada, glossário e banco de questões;
- página que monta o pedido para gerar **novas questões com IA** e importá-las.

> O conteúdo de legislação foi conferido até novembro de 2026 (inclui, por exemplo, a EC 138/2025, a EC 141/2026 e as alterações de 2026 na Lei Maria da Penha). Leis mudam: confira sempre a data de corte do seu edital.

Funciona como **aplicativo instalável (PWA)**: no celular ou no computador, com ícone próprio e **sem internet** depois da primeira abertura.

---

## Como publicar no GitHub Pages (grátis)

1. Crie uma conta em <https://github.com> (se ainda não tiver).
2. Clique em **New repository**, dê um nome (por exemplo, `basico-para-concursos`), deixe como **Public** e clique em **Create repository**.
3. Na página do repositório, clique em **Add file → Upload files** e arraste **todos os arquivos desta pasta**, todos na raiz (sem subpastas):
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - os 5 ícones: `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` e `favicon-32.png`
   - `README.md`

   Depois clique em **Commit changes**.
4. Vá em **Settings → Pages**. Em **Build and deployment → Source**, escolha **Deploy from a branch**. Em **Branch**, escolha **main** e a pasta **/ (root)**, e clique em **Save**.
5. Espere 1 ou 2 minutos e recarregue a página. Vai aparecer o endereço do site, no formato:
   `https://SEU-USUARIO.github.io/basico-para-concursos/`

> O site fica **público**: qualquer pessoa com o link consegue abrir. O seu progresso, porém, fica salvo só no seu aparelho.

## Como instalar como aplicativo

- **Android (Chrome):** abra o endereço, toque no menu **⋮** e escolha **Instalar app** (ou **Adicionar à tela inicial**).
- **iPhone/iPad (Safari):** abra o endereço, toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.
- **Computador (Chrome ou Edge):** clique no ícone de instalar que aparece na barra de endereço.

Depois de abrir uma vez com internet, o curso funciona **offline**.

## Seu progresso

- O progresso (aulas concluídas, estatísticas, caderno de erros, questões importadas) é salvo **no navegador do aparelho**.
- **Faça backup de vez em quando**: no menu, abra **💾 Salvar / restaurar progresso → Exportar progresso**. A página inicial lembra você quando o último backup tiver mais de 14 dias.
- Para levar o progresso de um aparelho para outro, exporte em um e cole em **Importar do texto** no outro.
- A sincronização automática com a conta e a geração de questões com IA *dentro* do curso só funcionam na versão aberta pelos artefatos do Claude. No app, a página **🤖 Novas questões com IA** monta o pedido pronto para você colar em uma IA e depois importar as questões.

## Como atualizar

Quando receber uma versão nova, faça upload de novo do `index.html` e do `sw.js` (substituindo os antigos). O app avisa que há uma versão nova; basta fechar e abrir de novo.

## (Opcional) Publicar na Play Store

O site já é um PWA completo. Para gerar um pacote Android a partir dele, você pode usar o **PWABuilder** (<https://www.pwabuilder.com>): cole o endereço do seu GitHub Pages e siga as instruções. Publicar na Google Play exige uma conta de desenvolvedor do Google (paga).

## Estrutura

```
index.html              o curso inteiro (HTML + CSS + JavaScript num arquivo só)
manifest.webmanifest    nome, cores e ícones do app
sw.js                   service worker (funcionamento offline)
icon-192.png            ícones do app (todos na raiz)
icon-512.png
icon-maskable-512.png
apple-touch-icon.png
favicon-32.png
```

---

Desenvolvido por Josué Silveira.

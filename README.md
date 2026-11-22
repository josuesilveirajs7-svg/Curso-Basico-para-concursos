# Básico para concursos

Matemática, Língua Portuguesa e Raciocínio Lógico para concursos de nível médio.

Curso completo, do zero ao nível especialista:

- **189 aulas** em três trilhas (Matemática, Língua Portuguesa e Raciocínio Lógico), em 5 níveis cada;
- **questões ilimitadas**, geradas na hora, com resolução passo a passo;
- simulados, projetos práticos, caderno de erros com revisão espaçada, glossário e banco de questões;
- links gratuitos de aulas no YouTube e de plataformas em todas as aulas.

Funciona como **aplicativo instalável (PWA)**: no celular ou no computador, com ícone próprio e **sem internet** depois da primeira abertura.

---

## Como publicar no GitHub Pages (grátis)

1. Crie uma conta em <https://github.com> (se ainda não tiver).
2. Clique em **New repository**, dê um nome (por exemplo, `basico-para-concursos`), deixe como **Public** e clique em **Create repository**.
3. Na página do repositório, clique em **Add file → Upload files** e arraste **todo o conteúdo desta pasta**:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - a pasta `icons` (com os 5 arquivos de imagem)
   - `README.md`
   - `.nojekyll` (é opcional; se o seu computador esconder esse arquivo, pode deixar de fora)

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
- Para levar o progresso de um aparelho para outro (ou do artefato do Claude para o app): no menu, abra **💾 Salvar / restaurar progresso → Exportar progresso (copiar)**; no outro aparelho, abra a mesma página e cole em **Importar do texto**.
- A sincronização automática com a conta e a geração de questões com IA *dentro* do curso só funcionam na versão aberta pelos artefatos do Claude. No app, a página **🤖 Novas questões com IA** monta o pedido pronto para você colar em uma IA e depois importar as questões.

## Como atualizar

Quando receber uma versão nova, faça upload de novo do `index.html` e do `sw.js` (substituindo os antigos). O app avisa que há uma versão nova; basta fechar e abrir de novo.

## (Opcional) Publicar na Play Store

O site já é um PWA completo. Para gerar um pacote Android a partir dele, você pode usar o **PWABuilder** (<https://www.pwabuilder.com>): cole o endereço do seu GitHub Pages e siga as instruções. Publicar na Google Play exige uma conta de desenvolvedor do Google (paga).

## Estrutura

```
index.html            o curso inteiro (HTML + CSS + JavaScript num arquivo só)
manifest.webmanifest  nome, cores e ícones do app
sw.js                 service worker (funcionamento offline)
icons/                ícones do app
```

---

Desenvolvido por Josué Silveira.

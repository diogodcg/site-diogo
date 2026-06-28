# Diogo Campos Gomes — Site de Autoridade

Site pessoal e de autoridade de **Diogo Campos Gomes** — economista, Líder Ágil na CAIXA e mentor de transição de carreira, criador do **Framework de Transição de Carreira em 6 etapas**.

> **Desestacionar** — tirar o profissional do modo automático e colocá-lo em movimento de transformação real.

## 🔗 Site no ar

Depois de publicar, o site fica disponível em:
`https://diogodcg.github.io/site-diogo`

## 📁 Estrutura

```
site-diogo/
├── index.html        Página única, pronta para publicar
├── assets/
│   └── diogo.jpg      Foto usada no site (referenciada pelo index.html)
└── README.md          Este arquivo
```

Site estático, sem dependências e sem build — é só HTML e CSS em um único arquivo, com a foto na pasta `assets`.

## 🧱 Seções da página

1. **Hero** — o conceito "Desestacionar" e a proposta em uma frase
2. **História** — trajetória na CAIXA (2004 → hoje) e a reinvenção pessoal
3. **O problema** — dados da crise silenciosa do trabalho (WEF, Gallup, CAGED)
4. **O método** — as 6 etapas do framework, com base teórica
5. **Conteúdo** — LinkedIn, DEV-nário, Lattes e credenciais
6. **CTA** — agendamento de diagnóstico ou contato pelo LinkedIn

## 🚀 Como publicar

### GitHub Pages
1. Suba os arquivos para um repositório **público** (`index.html` + a pasta `assets`).
2. Vá em **Settings → Pages**.
3. Em **Branch**, selecione `main` e a pasta `/ (root)`, depois **Save**.
4. Em um ou dois minutos o site estará no ar no endereço indicado acima.

### Alternativa: Netlify
1. Acesse [app.netlify.com](https://app.netlify.com) → **Add new site** → **Deploy manually**.
2. Arraste a pasta inteira do projeto para a área de upload.
3. O site fica no ar em um endereço `.netlify.app`.

## ✏️ O que personalizar

- **Botão de agendamento** — os botões "Agendar diagnóstico" (no Hero e no CTA) abrem um e-mail para `diogo.dcg@gmail.com`. Para usar Calendly ou outra agenda, basta trocar o `href` desses links no `index.html`.
- **Links de redes** — LinkedIn, Lattes e DEV-nário já estão preenchidos.
- **Foto** — para trocar, substitua o arquivo em `assets/diogo.jpg` mantendo o mesmo nome (ou atualize a referência no HTML).

## 🛠️ Editar localmente

Abra a pasta no VS Code e dê dois cliques no `index.html` para visualizar no navegador. Para recarregar automaticamente a cada alteração, use a extensão **Live Server**.

---

*Mentoria e desenvolvimento profissional. Não constitui avaliação psicológica ou diagnóstico clínico.*

Forte abraço a todos!
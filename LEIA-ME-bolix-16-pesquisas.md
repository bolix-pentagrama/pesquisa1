# Pesquisas Bolix — 4 pesquisas × 4 unidades = 16 links

## Estrutura

São 4 pesquisas comportamentais aplicadas em 4 unidades, totalizando 16 pastas independentes. Cada pasta é autocontida (HTML + hero.jpg + logo-bolix.png) e pronta para subir no GitHub Pages.

### Pesquisa 1 — Perfil Consumidor
Quem é o cliente e como ele se comporta.
- `bolix-perfil-interlagos/`
- `bolix-perfil-abc/`
- `bolix-perfil-guarulhos/`
- `bolix-perfil-patio/`

### Pesquisa 2 — Origem do Cliente
De onde vem a demanda e como o cliente chegou até a unidade.
- `bolix-origem-interlagos/`
- `bolix-origem-abc/`
- `bolix-origem-guarulhos/`
- `bolix-origem-patio/`

### Pesquisa 3 — Ambiente / Experiência
Satisfação, percepção de valor e pontos de melhoria.
- `bolix-ambiente-interlagos/`
- `bolix-ambiente-abc/`
- `bolix-ambiente-guarulhos/`
- `bolix-ambiente-patio/`

### Pesquisa 4 — Familiaridade
Quanto o público conhece a Bolix e quais oportunidades ainda não percebe.
- `bolix-familiaridade-interlagos/`
- `bolix-familiaridade-abc/`
- `bolix-familiaridade-guarulhos/`
- `bolix-familiaridade-patio/`

## Como funciona em cada link

Cada pasta tem o mesmo layout, mas com 3 personalizações fixas:

1. **Aba do navegador** mostra a pesquisa e a unidade (ex: "Pesquisa Bolix — Origem do Cliente — Guarulhos").
2. **Topbar** mostra o nome da pesquisa; **welcome screen** mostra a unidade.
3. **E-mail enviado** chega em `bolixpentagrama@gmail.com` com:
   - **Assunto:** `Pesquisa [Nome da Pesquisa] — [Nome Completo da Unidade]`
   - **Corpo:** campos `00_pesquisa` e `00_unidade` para identificar tudo direto.

Assim, mesmo recebendo respostas das 16 combinações, você consegue separar tudo apenas pela linha de assunto.

## Como publicar no GitHub Pages

1. No repositório `bolix-pentagrama/bolix-pentagrama.github.io`, faça upload das 16 pastas na raiz, mantendo os nomes exatos.
2. Faça upload também do arquivo `qrcodes-bolix-todas-pesquisas.html` na raiz.
3. Commit + push.
4. Em poucos segundos, todos os 16 formulários estão no ar.

## Como gerar os 16 QR Codes

1. Abra `qrcodes-bolix-todas-pesquisas.html` no navegador (pode ser localmente ou já publicado).
2. Confirme o domínio base (padrão `https://bolix-pentagrama.github.io`).
3. Os 16 QRs aparecem agrupados por pesquisa (4 cards por linha).
4. Use **Baixar PNG** em cada card individualmente, ou **Baixar todos** ao final para fazer o download dos 16 de uma vez.
5. Imprima e fixe cada QR na unidade correspondente.

## Aplicação (matriz de rodízio)

Para evitar fadiga, aplique uma pesquisa por unidade por período. Exemplo de ciclo trimestral:
- Mês 1: Perfil Consumidor (todas as 4 unidades)
- Mês 2: Origem do Cliente
- Mês 3: Ambiente / Experiência
- Mês 4: Familiaridade

Ou aplique pesquisas diferentes simultaneamente em unidades diferentes — o e-mail identifica tudo.

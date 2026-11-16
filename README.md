<div align="center">

# 🧭 SoloRota

**Sua próxima cidade começa aqui.**

App para nômades digitais no Brasil: onde trabalhar com Wi-Fi medido, gente para encontrar e a rotina da estadia num lugar só.
Gratuito para o nômade. Piloto em Santos (SP).

[![Abrir o app](https://img.shields.io/badge/Abrir_o_app-solorota.vercel.app-FF5B3A?style=for-the-badge)](https://solorota.vercel.app)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-mobile--first-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white)

</div>

---

## 😩 O problema

> Terça, 14h, chamada com o cliente em 10 minutos. O café "com Wi-Fi" não aguenta, e você não sabe para onde ir nem a quem perguntar.

Chegar numa cidade nova ainda é começar do zero. Em pesquisas com nômades digitais brasileiros:

| | |
|---|---|
| **58%** | passam a maior parte do tempo sozinhos ¹ |
| **25,5%** | apontam relacionamentos e amizades como a maior frustração ¹ |
| **10 de 10** | entrevistados destacam a qualidade da internet como essencial ² |

<sub>¹ Martins, Lima e Kanarski, Intercom 2025 (200 nômades, amostra autosselecionada) · ² Araujo, TCC USP/ECA, 2024 (10 entrevistas). Amostras pequenas: valem como sinal, não como retrato.</sub>

## 💡 A solução: uma jornada só, do primeiro dia à rotina

| Etapa | O que o nômade faz |
|---|---|
| 1️⃣ **Chegar** | Escolhe a cidade, sem cadastro |
| 2️⃣ **Explorar** | Mapa e Radar de lugares para trabalhar, com Wi-Fi medido, fonte e data |
| 3️⃣ **Conectar** | Entra em rodas pequenas (encontros com aprovação) e comunidades da cidade |
| 4️⃣ **Planejar** | Avalia a próxima cidade e guarda um plano privado |
| 5️⃣ **Viver** | Organiza agenda, gastos, tarefas e as pessoas da estadia |

✅ **Gratuito para o nômade:** nenhuma função é bloqueada por pagamento. Quem paga são os negócios locais.
🗺️ **Cobertura:** 646 cidades de SP cadastradas, com piloto em Santos.

## 🆚 Por que é diferente

| | WhatsApp e Instagram | Nomad List e Nomads.com | Comunidades e apps de encontro | **SoloRota** |
|---|---|---|---|---|
| **Wi-Fi para trabalhar** | Relato solto, sem data | Média da cidade | Velocidade média da cidade | **Medido por lugar, com fonte e data** |
| **Encontrar pessoas** | Grupos grandes e soltos | Chat e meetups globais | Eventos, atividades e chat | **Rodas pequenas, com aprovação** |
| **Rotina da estadia** | Não se aplica | Foco em escolher destino | Foco em destinos e viagens | **Agenda, gastos e checklist** |
| **Custo e idioma** | Grátis · português | Parte paga · inglês | Planos pagos em parte | **Grátis para o nômade · brasileiro** |

<sub>Comunidades e apps de encontro: Nomadtable, NomadX, The Nomadic Club. Comparação feita a partir das páginas públicas de cada serviço.</sub>

## 🛡️ Confiança e segurança

Encontrar gente nova com segurança, principalmente para quem viaja sozinho:

- **Entrada com aprovação:** quem cria a roda decide quem entra.
- **Locais públicos:** o app pede para combinar os encontros em local público.
- **Presença agregada:** nunca mostramos pessoas individuais, só contagem por bairro, a partir de 3.
- **Perfil verificado:** documento e selfie ficam em área privada e são apagados após a decisão.
- **Sem dado de saúde:** listamos serviços de saúde, mas não guardamos dado de saúde de ninguém.
- **Denúncia e moderação:** qualquer pessoa pode denunciar, e a equipe revisa.

Privacidade pela LGPD: coletar o mínimo. Check-ins, estadias, tarefas, gastos e favoritos são privados.

## 💸 Modelo de negócio

**Grátis para o nômade, pago pelo negócio local.**

| Fonte | Como funciona |
|---|---|
| 📍 **Destaque no mapa** (R$ 49/mês) | Pino maior e faixa "Patrocinado", separada do ranking |
| 🤝 **Comissão por cliente levado** (10–15%) | Sobre ofertas e benefícios de grupo resgatados no local |

O negócio ganha grupos nos seus **horários ociosos**, um painel com as sessões e as pessoas trazidas e um selo de Wi-Fi medido por clientes.

🔒 **Regra fixa:** pagar nunca muda a nota nem a ordem do Radar. A confiança nos dados é o produto.

<sub>Preços e comissão são hipóteses a validar com os primeiros parceiros. No piloto não há pagamento real.</sub>

## 🛠️ Como foi construído

Construído **do zero por uma equipe de 4 pessoas em uma madrugada**, com vibe coding usando **Claude Code** e **Codex**.

- **Front:** Next.js + TypeScript, PWA mobile-first
- **Banco e login:** Supabase (Postgres, RLS, migrações versionadas, sessão de visitante)
- **Mapa:** dados do OpenStreetMap, com importação de lugares reais por cidade
- **Testes:** Vitest (funções puras, RLS e RPC no banco) e Playwright (fluxos em celular e desktop)
- **Deploy:** Vercel, região São Paulo

## 🚀 Próximos passos

| Até 3 meses | 3 a 6 meses | 6 a 12 meses |
|---|---|---|
| **Validar em Santos:** 20 entrevistas com nômades e 10 com negócios, 5 parceiros pagando o destaque, cobrança real por Pix | **Ganhar escala em SP:** 100 nômades ativos por mês, 100 lugares com Wi-Fi medido, retenção por estadia | **Roteiro nacional:** Florianópolis e Rio de Janeiro, parcerias com coworkings e turismo |

**Sinal de que virou negócio:** parceiros renovando o destaque pago depois dos 30 dias grátis.

## 📚 Documentação

[Roteiro do pitch](docs/PITCH.md) · [Especificação atual](SPEC_V2_NOMADE.md) · [MVP](SPEC.md) · [Visual](DESIGN.md) · [Demanda](EVIDENCE.md) · [Decisões](docs/DECISIONS.md) · [Validação](docs/VALIDATION.md) · [Comparação com concorrentes](docs/COMPETITOR_PARITY.md)

---

<details>
<summary><b>👩‍💻 Para desenvolvedores: rodar, testar e publicar</b></summary>

### Rodar localmente

Requisitos: Node 20+, pnpm 9, Docker (só para o Supabase local).

```bash
pnpm install
cp .env.example .env.local # preencha as chaves do Supabase
pnpm dev # http://localhost:3000
```

Sem chaves do Supabase o mapa abre mesmo assim (cidade padrão), sem dados.

### Supabase

1. Crie um projeto (região São Paulo) e preencha `.env.local`, incluindo `SUPABASE_DB_URL` (Connect → Session pooler).
2. Em Authentication → URL Configuration: Site URL `http://localhost:3000` e Redirect URL `http://localhost:3000/**`.
3. `pnpm db:reset` aplica migrações e seed do zero (apaga os dados das tabelas do app). No banco da nuvem use `pnpm db:push` (só migrações novas, sem apagar nada); o `db:reset` recusa bancos remotos.
   Ligue também "Allow anonymous sign-ins" (Authentication → Sign In / Providers): o app usa sessão de visitante no lugar da tela de login.
4. Para tornar sua conta admin (acesso a `/admin/verificacoes`), entre uma vez em `/entrar` e rode no SQL Editor:
   `update profiles set role = 'admin', verified = true where id = (select id from auth.users where email = 'seu@email');`

### Comandos

| Comando | O que faz |
| --- | --- |
| `pnpm dev` | servidor de desenvolvimento |
| `pnpm build` / `pnpm start` | build e servidor de produção |
| `pnpm lint` | ESLint |
| `pnpm test` | funções puras e RLS/RPC no banco configurado (Vitest) |
| `pnpm test:e2e --workers=1` | fluxos em celular e desktop (Playwright; na 1ª vez: `pnpm exec playwright install chromium`) |
| `pnpm db:reset` | apaga e recria o banco **local** (recusa banco remoto) |
| `pnpm db:push` | aplica migrações pendentes no Supabase da nuvem, sem apagar dados |
| `pnpm seed:demo` | cria/atualiza as contas demo do login de demonstração |
| `pnpm admin:grant <email>` | torna uma conta admin |
| `pnpm import:osm <cidade>` | importa lugares reais do OpenStreetMap (M2) |
| `pnpm demo:refresh` | renova somente dados Demo: check-ins, estadias, tarefas, séries, grupo de quatro, horários e ofertas |

Lista de espera: `/espera?utm_source=instagram&utm_campaign=<campanha>&bloco=work|bonds|week`. Resultados e micro-pesquisa em `/admin/metricas` (admin). Registros históricos conservam seus blocos antigos.

### Fluxos disponíveis (V1–V7)

- `/radar/santos`: adequação, fonte, data, confirmações, frescor, medição e selos com validade. Patrocínio não altera nota nem ordem.
- `/estadia`: onboarding, rotina e privacidade separados; Hoje, Tarefas, Agenda (.ics), Favoritos, Gastos e Pessoas. Descoberta exige opt-in e verificação de ambos; contato nas rodas, sem DM.
- `/lugar/<id>`: marcar sessão preenchida, horário do parceiro e benefício de grupo. `/serie/<id>` cria seis datas futuras; aprovar um seguidor entra nas datas com vaga.
- `/parceiro`: mínimo de participantes, horários e totais agregados de sessões, participantes e resgates.
- `/cidade/santos`: indicadores com fonte, data, amostra e marcação Demo. `/admin/metricas`: funis por sessão, retenção de séries e pesquisa.
- `/explorar`: busca de cidades cadastradas, acesso aos dados de cada cidade e diretório inicial de ferramentas de rotina.

Limites e pesos são hipóteses em `src/config/nomad.ts`; regras SQL equivalentes ficam nas migrações. Não há pagamento real no piloto.

### Publicar

Produção: **[solorota.vercel.app](https://solorota.vercel.app)**. Migrações 0001–0020 aplicadas no Supabase da nuvem, sem reset remoto.

1. **Banco (Supabase na nuvem):** `pnpm db:push` aplica só as migrações pendentes (usa `SUPABASE_DB_URL`). `pnpm db:reset` recusa bancos remotos, porque apaga os dados.
2. **Contas e dados demo:** `pnpm seed:demo` (Ana, Bruno, Parceiro e três perfis adicionais pela Admin API, sem privilégios admin, com `DEMO_LOGIN_PASSWORD`) e, antes de cada demo, `pnpm demo:refresh`.
3. **Auth no Supabase:** Authentication → URL Configuration: Site URL = domínio da Vercel; Redirect URLs = `https://<domínio>/**` e `http://localhost:3000/**`. Login anônimo ligado e limite alto em Rate Limits. Para o magic link aguentar a avaliação, configure SMTP próprio (Authentication → Emails → SMTP); o login de demonstração (`NEXT_PUBLIC_DEMO_LOGIN=true`) cobre a falta dele.
4. **Vercel:** `npx vercel login` (uma vez), depois `npx vercel link` e `npx vercel --prod`. Variáveis: as do `.env.example`, exceto `SUPABASE_DB_URL`. Região `gru1` (São Paulo) em `vercel.json`.
5. **Admin:** entre uma vez em `/entrar` com seu e-mail e rode `pnpm admin:grant voce@email.com`.
6. **Conferir:** `PLAYWRIGHT_BASE_URL=https://<domínio> pnpm test:e2e`.

</details>

---

<div align="center">

Feito com ☕ e vibe coding em Santos 🌊 · [João Pedro Teixeira](https://github.com/joaoteixeirap)

<sub>Dados do mapa © OpenStreetMap contributors · tiles OpenFreeMap</sub>

</div>

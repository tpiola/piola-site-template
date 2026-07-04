# 🜂 Piola Site Template

> Template oficial [piola.build](https://piola.build) para novos sites premium de clientes.
> Next.js 15 + TypeScript strict + Tailwind CSS 4 + shadcn/ui + Supabase-ready.

## 🚀 Uso Rápido (Cliente Novo)

1. Clique em **"Use this template"** no GitHub → crie repo `cliente-nome`
2. `gh repo clone tpiola/cliente-nome && cd cliente-nome`
3. `pnpm install`
4. Copie `.env.example` → `.env.local` e preencha
5. `pnpm dev`
6. Deploy: `vercel --prod`

## 📦 O que já vem incluído

- **Framework** — Next.js 15 (App Router) + TypeScript strict mode
- **Styling** — Tailwind CSS 4 + shadcn/ui + Framer Motion
- **Design System** — Paletas Hermes (Confiança / Energia / Luxo)
- **Landing Structure** — Hero, Problema, Solução, Prova, Preço, FAQ, CTA
- **WhatsApp** — Botão flutuante em todas as páginas
- **SEO** — Metadata, Open Graph, Schema LocalBusiness JSON-LD
- **LGPD** — Banner de consentimento + política pronta
- **Validação** — Zod em todos os inputs
- **Analytics** — Vercel Analytics + PostHog stub
- **Errors** — Sentry stub + error boundaries
- **Payments** — Stripe + Mercado Pago (Pix) stubs
- **Backend** — Supabase client + RLS helpers

## 🎨 Escolher Paleta

Edite `src/styles/theme.css` e descomente a paleta do nicho:

```css
/* CONFIANÇA — saúde, jurídico, financeiro */
/* ENERGIA — estética, fitness, food */
/* LUXO — odonto premium, imobiliária */
```

## ✅ Checklist Antes de Publicar

- [ ] Lighthouse ≥ 95 em Performance/A11y/SEO/Best Practices
- [ ] WCAG 2.1 AA validado
- [ ] Schema LocalBusiness com dados reais
- [ ] WhatsApp com número do cliente
- [ ] Pixel Meta + GA4 configurados
- [ ] LGPD: banner + política + rota /excluir-dados
- [ ] Domínio custom no Vercel
- [ ] SSL forçado + HTTPS

## 📚 Referências

- [Hermes Polymath v2](https://github.com/tpiola/hub) — sistema operacional
- [piola.build](https://piola.build) — agência
- [Design System Hermes](https://github.com/tpiola/hub/blob/main/design-system.md)

---

*Template mantido por Hermes Agent | piola.build*

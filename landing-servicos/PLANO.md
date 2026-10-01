# Plano: vender sites para igrejas e pequenos negócios

Custo inicial: **R$ 0**. Hospedagem gratuita (Firebase ou GitHub Pages) e
prospecção por WhatsApp e Instagram. O site da Igreja Luz Para Os Povos entra
como portfólio.

## 1. Publicar a página (15 min)

1. Se precisar mudar algo, edite o bloco `CONFIG` no fim de `index.html`:
   nome da marca, WhatsApp (só dígitos, com 55 + DDD), cidade e preços.
2. Publique de graça no Firebase Hosting, num projeto **separado** do site da
   igreja (senão o deploy substitui o site da igreja):
   1. Em [console.firebase.google.com](https://console.firebase.google.com),
      crie um projeto novo (ex.: `nexus-core-sites`). Não precisa de cartão.
   2. No terminal, dentro da pasta `landing-servicos`:
      ```bash
      npm install -g firebase-tools   # se ainda não tiver
      firebase login
      firebase deploy --only hosting --project ID-DO-PROJETO
      ```
   3. O site fica em `https://ID-DO-PROJETO.web.app`.
3. Coloque o link na bio do Instagram e no status do WhatsApp.

## 2. Preços sugeridos (ajuste à sua realidade)

| Plano | Preço | Tempo seu |
|---|---|---|
| Página Única | R$ 857 | ~1 dia |
| Site Completo | R$ 1.497 | 3–5 dias (reaproveitando o código da igreja) |
| Manutenção | R$ 97/mês | ~1 h/mês por cliente |
| Consultoria de Segurança | a partir de R$ 1.297 | 1–2 dias |
| Pentest de Site | a partir de R$ 2.497 | 3–5 dias + relatório |

Referência de mercado (pesquisa de outubro/2026): landing
page a partir de ~R$ 900; site institucional com freelancer entre R$ 2.000 e
R$ 6.000; manutenção básica R$ 100–400/mês; análise de vulnerabilidades
R$ 2.000–8.000; pentest de site simples R$ 3.000–6.000 (mercado geral
R$ 3.000–60.000). Hoje os preços estão abaixo dessas faixas, como estratégia de entrada. O dinheiro recorrente
está na **manutenção**: 10 clientes = ~R$ 970/mês.

**Vantagem:** o site da igreja já tem calendário, galeria e área de líderes
prontos. Para outra igreja, é trocar cores, textos e fotos. Margem alta.

**Pentest:** só com autorização por escrito do dono do site e escopo em
contrato. Testar sistema de terceiros sem autorização é crime (Lei 12.737/2012).

## 3. Onde achar clientes

1. **Igrejas da região sem site ou com site velho**: procure "igreja" no
   Google Maps do seu bairro e veja quais não têm site na ficha.
2. **Comércios no Google Maps sem site**: salões, oficinas, clínicas,
   restaurantes. Mesmo filtro.
3. **Indicação**: peça aos líderes da Luz Para Os Povos que indiquem pastores
   conhecidos.
4. **Workana / 99Freelas**: projetos de "site institucional" e "landing page".

Meta: **10 contatos por dia**, 5 dias por semana. Com conversão típica de 2–5%,
dá 1 a 2 vendas por semana.

## 4. Mensagem de abordagem (WhatsApp)

> Olá, [nome]! Tudo bem? Sou [seu nome], faço sites aqui em [cidade].
> Vi a [igreja/empresa] no Google Maps e reparei que ainda não tem site.
> Fiz recentemente o site da Igreja Luz Para Os Povos: [link]. Tem agenda de
> eventos, galeria de fotos e os próprios líderes atualizam.
> Posso te mandar uma ideia de como ficaria o de vocês, sem compromisso?

Regras: personalize o nome, mande uma vez só e, se não responder em 3 dias,
faça **um** acompanhamento curto. Nada de mensagens em massa: o WhatsApp bane
contas por isso.

## 5. Fechamento

- Orçamento no mesmo dia, por escrito.
- 50% via Pix para começar, 50% na entrega.
- Domínio no **nome do cliente** (Registro.br). Evita problemas depois.
- Ao entregar, ofereça a manutenção mensal.

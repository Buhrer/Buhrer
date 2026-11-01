# Olá, eu sou Lucas Bührer

### Desenvolvedor Full Stack em formação | Busco vaga júnior ou estágio

Estou começando na área de desenvolvimento e já entreguei software real: um sistema de gestão desktop vendido a um cliente (uma sorveteria) e um app de controle financeiro online, com site e app Android. Trabalho com **Spec-Driven Development**: escrevo a especificação, uso IA como apoio na implementação e valido tudo com testes automatizados. Estou aprofundando minha base em JavaScript, React e Node.js e busco minha primeira oportunidade para crescer em um time.

---

## Tecnologias

**Base:**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Usadas nos meus projetos (em aprofundamento):**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Projetos

### BIG LAKE Gestão — sistema de gestão para sorveteria (vendido a um cliente)

Sistema desktop para Windows, feito sob medida para a BIG LAKE Sorveteria (paletas, picolés, sorvete de pote e açaí, no balcão e no atacado). O objetivo é mostrar ao dono **quanto ele realmente lucra**: a margem de cada produto e o lucro do mês. O usuário principal é uma pessoa idosa, então a interface tem letra grande, poucos cliques, linguagem do dia a dia e ajuda em cada tela.

**Principais funcionalidades**
- **Vendas:** balcão pelo total do dia (dinheiro, Pix, débito, crédito) e pedidos de atacado com comprovante impresso
- **Receitas e custos:** custo por receita, lucro e margem por produto, aviso quando o preço de um ingrediente sobe
- **Estoque, produção e perdas:** validade por compra, estoque mínimo, baixa automática na produção
- **Contas a pagar:** contas recorrentes e avisos de vencimento
- **Sócios:** divisão do lucro, retiradas e reembolsos
- **Relatórios:** resultado do mês, mais vendidos, lucro por produto e indicador de "hora de reajustar preços" (imprime ou salva em PDF)
- **Segurança dos dados:** backup automático (computador e pen drive), restauração, histórico de alterações e "Desfazer"

**Destaques técnicos:** funciona 100% offline (banco SQLite local), dinheiro guardado em centavos inteiros (sem ponto flutuante), migrações versionadas, **413 testes** unitários/integração (Vitest) e **80 testes ponta a ponta** (Playwright).

**Stack:** TypeScript · Electron · React · SQLite · TanStack Query · Zod · electron-vite · electron-builder (instalador `.exe`)

[Repositório da versão demo](https://github.com/Buhrer/big-lake-demo)

### Buhrer Controle Financeiro — finanças da família (site + app Android)

Aplicação de controle financeiro familiar com site e app Android ligados à mesma API, em uso real e com deploy automático. O repositório público é uma versão demo do projeto, sem dados pessoais.

**Principais funcionalidades**
- Receitas, despesas e transferências, com saldo atual e previsto por conta
- Cartões de crédito: compras parceladas, fatura mensal e pagamento da fatura
- Contas fixas, caixinhas (objetivos), orçamento 50/30/20 e dívidas
- Importação de extrato bancário com sugestão automática de categoria e regras personalizadas
- Conciliação de saldo, relatórios por categoria/tag e projeção dos próximos meses
- Vários membros no mesmo espaço, com convite e isolamento de dados
- Lixeira, registro de atividades, exportação CSV, backup criptografado diário e comprovantes anexados

**Destaques técnicos:** segurança por linha no banco (RLS), validação com Zod, testes com Vitest e Playwright (celular e desktop), **CI/CD com GitHub Actions** que verifica, aplica migrations e publica sozinho.

**Stack:** TypeScript · React 19 · Vite · Tailwind CSS · TanStack Query · Hono (Node.js) · PostgreSQL · Drizzle ORM · Better Auth · Capacitor (Android) · Vercel · Supabase

[Repositório da versão demo](https://github.com/Buhrer/buhrer-cf-demo)

---

## Como eu trabalho

Uso **Spec-Driven Development**: primeiro escrevo a especificação do que o sistema deve fazer, depois uso IA para acelerar a implementação, e então reviso, testo e ajusto o código. Os testes automatizados são parte do processo, não um extra. Meu foco agora é entender cada camada do que construo para evoluir como desenvolvedor.

---

## Formação e estudos

- **Aprender e Crescer – Programação** · Sudotec, Dois Vizinhos – PR *(concluindo em novembro de 2026)*
- **Tecnólogo em Desenvolvimento Full Stack** · Cruzeiro do Sul *(início em 2027)*
- Aprofundando por conta própria: JavaScript/TypeScript, React, Node.js e SQL

---

## Contato

- LinkedIn: [linkedin.com/in/lucasantoniobuhrer](https://www.linkedin.com/in/lucasantoniobuhrer/)
- E-mail: lucasbuhrer@live.com

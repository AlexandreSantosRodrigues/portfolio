# Portfólio — Alexandre Santos

Portfólio profissional de Dados, Business Intelligence e Engenharia de Dados, construído com HTML, CSS e JavaScript, sem dependências de build.

## Conteúdo

- Apresentação, experiência profissional, formação e contatos.
- Quatro projetos em destaque com evidências e acesso a aplicação, dashboard ou imagem pública.
- Catálogo filtrável por área, incluindo engenharia, cloud, BI, análise, IA e ciência de dados.
- Temas claro/escuro, navegação por teclado e suporte à preferência de movimento reduzido.

As duas pós-graduações na UNINTER estão concluídas: Ciência de Dados e IA (setembro/2025) e Engenharia de Computação (outubro/2025).

## Projetos em destaque

| Projeto | Evidência documentada | Explorar |
| --- | --- | --- |
| [Oil & Gas Production Lakehouse — ANP](https://github.com/AlexandreSantosRodrigues/oil-gas-production-lakehouse) | 315.356 registros de produção/injeção e 17.817 intervenções na Gold; reconciliações entre camadas. | [Imagem pública do dashboard](https://github.com/AlexandreSantosRodrigues/oil-gas-production-lakehouse/blob/main/docs/images/dashboard-anp.png) |
| [Fuel Price Intelligence RJ](https://github.com/AlexandreSantosRodrigues/fuel-price-intelligence-rj) | 83.441 registros no RJ; comparação temporal de quatro abordagens. | [Aplicação Streamlit](https://fuel-price-intelligence-rj.streamlit.app/) |
| [GA4 Multi-Touch Attribution](https://github.com/AlexandreSantosRodrigues/ga4-multi-touch-attribution) | Cinco modelos, 5.372 compras canônicas e reconciliação de métricas. | [Dashboard](https://alexandresantosrodrigues.github.io/ga4-multi-touch-attribution/) |
| [Superstore Sales](https://github.com/AlexandreSantosRodrigues/superstore-sales-dashboard) | 9.994 itens reconciliados; análise de margem e previsão com avaliação temporal. | [Dashboard](https://alexandresantosrodrigues.github.io/superstore-sales-dashboard/dashboard/) |

Os resultados são das execuções documentadas nos projetos. Fontes, premissas, simulações e limitações constam nos respectivos repositórios. O dashboard da ANP no workspace exige autenticação; por isso o portfólio oferece uma imagem pública.

## Arquivos

| Arquivo | Função |
| --- | --- |
| `index.html` | Página, estilos e scripts; listas de projetos em `P` e destaques em `F`. |
| `perfil.jpg` | Foto de perfil e ícone. |
| `scout-directions.webp` e `scout-reactions.webp` | Imagens do mascote interativo. |
| `placidplace-birds-10554_512.gif` | Asset preservado; o fundo atual usa Canvas. |

Para visualizar localmente, abra `index.html` ou execute `python3 -m http.server 8000` na raiz do repositório e acesse `http://localhost:8000`.

## Publicar e atualizar na Vercel

1. Abra o projeto existente na Vercel.
2. Em **Settings → Git**, confirme a conexão com `AlexandreSantosRodrigues/portfolio`.
3. Em **Settings → Environments → Production → Branch Tracking**, confirme que a branch de produção é `main`.
4. Commits em `main` disparam um novo deployment quando a integração automática está habilitada.
5. Em **Deployments**, confira o SHA do commit e aguarde o status **Ready**. Abra o domínio de produção na seção **Domains**.

Para importar este repositório pela primeira vez, use **Add New → Project → Import**, selecione o framework **Other**, a raiz do repositório e nenhuma etapa de build. O site é estático; não exige `npm install` nem variáveis de ambiente.

Se precisar executar novamente o mesmo código, use **Deployments → ⋯ → Redeploy** no deployment correto. Redeploy refaz o código daquele deployment; para publicar um commit novo, confirme que o novo SHA aparece em Deployments ou crie um deployment a partir da referência Git atual.

Documentação: [integração Git](https://vercel.com/docs/git) · [gerenciar deployments](https://vercel.com/docs/deployments/managing-deployments).

## Atualizar o conteúdo

- Edite experiência, formação e contato diretamente no HTML.
- Atualize o array `P` para títulos, descrições e categorias dos projetos.
- Atualize `F` para mudar os destaques e seus links de demonstração.
- Confira as evidências nos repositórios antes de publicar novas métricas.
- Mantenha o README do perfil e o site coerentes, inclusive o domínio público informado no perfil.

[GitHub](https://github.com/AlexandreSantosRodrigues) · [LinkedIn](https://www.linkedin.com/in/alexandresantosdata/)

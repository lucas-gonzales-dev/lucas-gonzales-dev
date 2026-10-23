# Olá, sou o Lucas 👋

**Desenvolvedor Python | Dados e automação para e-commerce** · Praia Grande, SP

Sou o único profissional de TI do Grupo Náutica Refrigeração. Construo e mantenho os sistemas de dados que a empresa usa todo dia para vender no Mercado Livre e na loja física.

Antes do código, passei 5 anos como técnico em eletrônica, fazendo diagnóstico em nível de placa. É de lá que vem meu método: levantar uma hipótese, medir, isolar a falha e documentar. Uso o mesmo método para depurar sistemas e dados.

### 🏭 Em produção hoje

| Sistema | O que faz | Stack |
|---|---|---|
| **Auditoria de devoluções + SAC no Slack** | Um card por caso, quadro Kanban, fechamento diário e um auditor que confere Mercado Livre × quadro × cards a cada 2 horas | Python · PostgreSQL · Slack |
| **Radar de estoque, compra e preço** | Curvas A, B e C de cerca de 900 SKUs, ruptura, sugestão de compra com previsão sazonal, margem e preço mínimo por anúncio, com uma tela por setor | Python · pandas · SQL · Streamlit · Plotly |
| **Sombra de dados** | Recalcula os números do Radar toda noite a partir do dado cru e compara com o que está na tela | Python · SQL |
| **Integrações** | APIs do Mercado Livre (OAuth e gestão de tokens), Mercado Pago e Tiny; conciliação financeira das extrações do SAP | Python · APIs REST |
| **Infraestrutura** | Servidor Linux com 35 serviços, backup diário e alertas no Slack com nova tentativa automática | Linux · Git |

*Os repositórios desses sistemas são privados, porque usam dados reais da empresa.*

### 📊 Resultados medidos

- **Previsão de demanda:** testei regras contra a venda real em 365 datas. A nova erra 7 pontos a menos (74% contra 81%) e virou a regra de compra.
- **Qualidade de dados:** achei 3,3% de pedidos cancelados que ainda contavam como venda. Corrigi a coleta, e a nova amostra deu 0 em 300.
- **Conferência independente:** a sombra de dados fechou com 0 divergências em mais de 26 mil campos.
- **Mais de 6 mil testes automatizados.** Todo número que vai para a tela diz de onde vem: medido, calculado ou estimado com o erro.

### 🔧 Stack

- **Dados e automação:** Python · pandas · SQL · PostgreSQL · ETL · Streamlit · Plotly · n8n
- **Integrações:** APIs REST · OAuth · Slack · Mercado Livre · Mercado Pago · Tiny
- **Infra e qualidade:** Linux · Git · testes automatizados · Docker · CI/CD (AWS)
- **Back-end e front-end (formação):** Node.js · TypeScript · NestJS · Express · JWT · TypeORM · Prisma · React · Next.js
- **Hardware:** eletrônica em nível de placa · firmware (PIC, ESP32, ATmega, STM) · impressoras de etiqueta Zebra

### 📌 Projetos públicos (formação e faculdade)

| Projeto | O que é | Stack |
|---|---|---|
| [Subscry](https://github.com/lucas-gonzales-dev/Subscry) | App mobile para controlar assinaturas e dividir custos, com precisão de centavos e testes | Expo · TypeScript · Jest |
| [nestjs-users-api](https://github.com/lucas-gonzales-dev/nestjs-users-api) | API REST com autenticação JWT e guards | NestJS · TypeORM · MySQL |
| [dncommerce-api](https://github.com/lucas-gonzales-dev/dncommerce-api) | API de estoque, pedidos e vendas com modelagem de dados | Node.js · Express · MongoDB |
| [biblioteca-fullstack](https://github.com/lucas-gonzales-dev/biblioteca-fullstack) | CRUD fullstack de biblioteca | Express · React · Vite |
| [poo-bankrupt-java](https://github.com/lucas-gonzales-dev/poo-bankrupt-java) | Simulação de estratégias com herança e polimorfismo | Java |

### 🎓 Formação

- Análise e Desenvolvimento de Sistemas, FATEC Praia Grande (conclusão em 2027)
- Engenheiro de Software, Escola DNC (246h, todos os projetos avaliados, concluído em fev/2026)
- Microsoft Azure AI Essentials (Microsoft e LinkedIn)
- Inglês B2

### 📫 Contato

Aberto a vagas de dados, automação, integrações e sistemas: remoto, híbrido em São Paulo ou na Baixada Santista.

[LinkedIn](https://www.linkedin.com/in/lucas-leite-gonzales-dev/) · lucas.gonzales.dev@gmail.com

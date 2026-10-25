# Entrelinhas

Biblioteca pessoal, sessões de leitura e memórias literárias. Projeto de portfólio de **Rayane Araújo Teles**.

**Estado: planejamento e conceito visual aprovado.** As funcionalidades abaixo ainda serão implementadas e verificadas.

## Experiência proposta

Registrar a leitura de livros físicos, digitais e audiolivros, acompanhar o tempo dedicado e guardar pensamentos ao longo de cada história.

## Identidade visual aprovada

Verde esmeralda, azul profundo, coral e dourado; superfícies claras, tipografia literária e ilustrações mágicas. Referência aprovada: biblioteca ilustrada, cronômetro circular e diário com cartões. A paleta roxa foi descartada. Os livros e dados das simulações são fictícios.

## Etapa 1 — Biblioteca e sessões

- [ ] Cadastro manual de livros com título, autor, capa e quantidade de páginas quando aplicável.
- [ ] Busca por título, autor ou ISBN, condicionada à escolha e aos limites de um catálogo externo.
- [ ] Estados Quero ler, Lendo e Lido; identificar formato físico, digital ou audiolivro.
- [ ] Registro de progresso apropriado ao formato e à edição, sem exigir páginas para audiolivros.
- [ ] Iniciar, pausar, retomar e encerrar uma sessão de leitura.
- [ ] Manter a sessão ao bloquear a tela ou alternar de aplicativo; calcular duração pelos horários persistidos.
- [ ] Recuperar sessão interrompida ao reabrir, com confirmação e correção do tempo. Aparelho desligado não comprova leitura durante o intervalo.
- [ ] Diário com trechos e anotações vinculados ao livro e à sessão.
- [ ] Onde eu parei?: consultar a última anotação, personagens e perguntas registrados pela própria pessoa, sem gerar spoilers.

## Etapa 2 — Memórias literárias

- [ ] Mapa de sentimentos por sessão, com participação opcional.
- [ ] Releituras com históricos separados e comparação entre anotações.
- [ ] Estantes personalizadas por nome e identidade visual.
- [ ] Carta ao terminar, com perguntas opcionais e exportação.
- [ ] Metas opcionais, sem obrigar a manter sequência diária.

## Etapa 3 — Continuidade

- [ ] Registrar sessões e anotações sem internet.
- [ ] Sincronizar depois, mostrando claramente o que está salvo e o que está pendente.
- [ ] Definir recuperação de sessão e tratamento de conflitos antes de oferecer múltiplos dispositivos.

A estrutura inicial deve considerar persistência local e evolução offline, mesmo que a sincronização seja entregue depois.

## Pesquisa futura — Kindle

Investigar importação de destaques e anotações, inclusive por arquivo exportado pelo usuário. Não prometer acesso automático a progresso, tempo ou biblioteca da Amazon. Na primeira versão, a pessoa poderá ler no Kindle e usar o cronômetro do Entrelinhas separadamente.

## Primeiras entregas

1. Definir plataforma inicial e arquitetura, registrando a decisão e suas limitações.
2. Transformar a referência visual aprovada em componentes e telas utilizáveis.
3. Construir um fluxo completo de cadastro manual → biblioteca → detalhe do livro.
4. Implementar e testar o ciclo de sessão, incluindo bloqueio de tela, reabertura, pausa e correção.
5. Conectar diário e Onde eu parei? ao livro.

## Critérios de qualidade

Navegação acessível, contraste e alvos de toque adequados; estados vazios e de erro claros; preservação dos registros; testes de duração e recuperação de sessão. Catálogos, autenticação, hospedagem e sincronização serão escolhidos e documentados antes da integração.

## Execução

Ainda não há aplicação executável. Instruções, testes, imagens da versão real e demonstração serão acrescentados conforme as entregas forem validadas.

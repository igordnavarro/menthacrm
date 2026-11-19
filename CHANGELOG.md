# Histórico de versões — Mentha CRM

Cada versão publicada fica marcada no GitHub (aba **Releases**) e pode ser restaurada a qualquer momento.
A versão em uso aparece no app em **Config → Sobre**.

## V2.7 — 2.7.0 (19/11/2026)

**Agenda sincronizada nos dois sentidos com o Google Agenda**
- O app confere sozinho com o Google, enquanto estiver aberto e conectado:
  - ao abrir;
  - ao voltar para o app;
  - a cada poucos minutos.
- Também dá para conferir na hora pelo botão **⇄ Sincronizar**.
- **CRM → Google:**
  - todo atendimento marcado no app vai para a agenda da profissional;
  - os concluídos dos últimos 7 dias que ficaram de fora também vão;
  - excluir no app remove do Google, mesmo que tenha sido excluído em outro aparelho.
- **Google → CRM:**
  - um evento novo com o nome de uma cliente cadastrada (ex.: "Bruna Thais Gallo — Manicure russa") vira um atendimento no app, com os serviços e valores;
  - mudou o horário ou o dia no Google → muda no app;
  - passou o evento para a agenda da Amanda → o atendimento passa para a Amanda;
  - excluiu no Google → o atendimento fica como cancelado no app (sem taxa), com a observação "Excluído no Google Agenda".
- Compromissos pessoais (Folga, Fechado, Limpar, Mentoria, Encontro…) não viram atendimento.
- Eventos que parecem atendimento, mas sem cliente reconhecida, aparecem num aviso **Conferir**, com as opções **Importar** e **Não é atendimento**.
- Se a mudança foi feita no app e ainda não subiu, vale a do app.
- Cada atendimento enviado leva uma marca, que impede duplicar o evento quando dois aparelhos sincronizam ao mesmo tempo.
- Aviso amarelo na Agenda quando o login do Google expira.

## V2.6 — 2.6.1 (17/11/2026)

**Agenda no celular ainda mais parecida com o Google Agenda**
- Os nomes **quebram a linha** dentro do bloco, em vez de serem cortados com "…". Depois do nome vem "— serviço".
- Atendimentos que começam com menos de 30 min de diferença ficam **lado a lado**; os que começam depois entram **deslocados e por cima**, como no Google.
- **Horas mais compactas**: cada hora ocupa menos espaço, e cabe quase o dia todo na tela.
- A grade ocupa a **largura toda** da tela.

## V2.6 — 2.6.0 (17/11/2026)

**Agenda no celular, no estilo do Google Agenda**
- Barra de cima mais enxuta: o nome do mês (toque para abrir um **minicalendário** e pular para qualquer dia), 🔍 filtro (profissional e cliente), **Hoje** e o botão de **modo de visualização**.
- Novos modos: **Programação** (lista contínua dos próximos dias, que carrega mais conforme você desce) e **3 dias**, além de Dia, Semana e Mês.
- **Deslize para o lado** para ir ao próximo ou ao anterior dia/semana/mês.
- A semana cabe inteira na tela (sem rolagem lateral). A grade de horários rola sozinha, com o cabeçalho dos dias fixo, e já abre no horário atual ou no primeiro atendimento.
- No modo Dia, uma faixa com a semana mostra pontinhos nos dias com atendimento.
- Botão **+** flutuante para um novo atendimento.
- Rolagem mais leve: o app só "segura" o toque quando você está de fato arrastando um atendimento.
- O computador e o tablet continuam com o layout anterior, e ganharam o modo **3 dias**.

## V2.5 — 2.5.0 (14/11/2026)

**Relatórios → Retorno das clientes** (nova aba)
- Atualiza sozinho: as clientes que vieram no **mês passado** precisam ter horário no **mês atual e no próximo**. Hoje é outubro → novembro e dezembro; em dezembro passa a ser novembro → dezembro e janeiro. Dá para escolher outro mês base.
- Intervalo ideal de **20 a 30 dias**, editável na própria tela.
- Números de resumo (vieram, em dia, precisam de horário, atrasadas) e uma barra com a situação de cada grupo.
- Lista ordenada por urgência, com filtros (atrasadas, sem horário, falta mês atual, falta próximo mês, intervalo longo), busca e visão **Cartões ou Tabela** com ordenação por coluna.
- Em cada cliente:
  - **Convidar** (WhatsApp com mensagem pronta e janela de datas);
  - **Agendar** (formulário já com a cliente, o último serviço e a data sugerida);
  - **Ignorar** (para alunas e clientes esporádicas; também na ficha da cliente).
- **Copiar lista** e **Exportar Excel**.
- O Painel ganhou o cartão **Retorno das clientes**, com as mais urgentes, no lugar do antigo "Precisa agendar".
- Relatórios foi dividido em abas: **Financeiro**, **Retorno das clientes** e **Indicações**.

## V2.4 — 2.4.0 (06/11/2026)

**Horário de término no atendimento**
- Novo campo **Término**, ao lado do Início, no formulário de novo atendimento e de edição.
- Calculado sozinho pela duração dos serviços escolhidos (Config → Serviços), e atualizado ao trocar os serviços ou o início.
- Pode ser alterado à mão. A duração ajustada fica salva, aparece no calendário e no Google Agenda, e acompanha o início se ele mudar. O link "calcular pelos serviços" volta ao automático.
- Eventos importados do Google já trazem a duração do evento.
- O botão **🗑 Excluir atendimento** ficou mais visível dentro do formulário.

## V2.3 — 2.3.0 (06/11/2026)

**Agenda mais fácil**
- **Filtro por cliente:** digite o nome da cliente para ver só os horários dela e a lista dos próximos atendimentos.
  - **📲 Enviar horários pelo WhatsApp:** manda todos os próximos horários numa mensagem só.
  - **📋 Copiar mensagem** e **+ Agendar para ela**.
  - Na ficha da cliente há o botão **📅 Horários**.
- **Arrastar e soltar:** mude o dia ou a hora arrastando o atendimento nas visões Dia, Semana e Mês. No celular e no tablet, segure o horário um instante e arraste.
  - Para passar para outra semana ou mês, arraste até **Próxima semana ›** ou **‹ Semana anterior**.
  - O horário encaixa de 15 em 15 minutos e há aviso se bater com outro horário da mesma profissional.
  - Depois de mover, aparece **Desfazer**.
  - No Google Agenda, só a data e a hora do evento mudam.
- **Excluir horários:** arraste até **🗑 Excluir** ou use o botão 🗑 nos cartões. Sempre pede confirmação e também remove o evento do Google Agenda.

## V2.2 — 2.2.0 (01/11/2026)

**Ranking de indicações** (Relatórios)
- Mostra quem mais indicou clientes, com 🥇🥈🥉, número de indicações, quantas indicadas já vieram, a receita gerada pelas indicadas e a data da última indicação. Dá para ver no período escolhido ou em todo o histórico.
- Botão **🎁 Parabenizar** para as 3 primeiras, com mensagem pronta no WhatsApp.
- Reconhece a cliente indicadora mesmo com apelido, erro de digitação ou emoji (ex.: "Manicure Camila Fasto" → Camila Fausto).
- **Indicações para confirmar:** quando o nome bate com mais de uma cliente (ex.: "Gabriela"), basta tocar na cliente certa.
- **Vieram por indicação sem dizer quem:** lista para preencher quem indicou, para entrar no ranking.
- A ficha da cliente mostra quem ela indicou com a mesma regra.

## V2.1 — 2.1.0 (01/11/2026)

**Taxa de cancelamento e falta**
- Novo botão **✕ Cancelou/Faltou** nos agendamentos. Ele já sugere a taxa de **50% do valor dos procedimentos**, que pode ser ajustada ou zerada ("Sem taxa"), com a forma de pagamento.
- Mudar o status para Cancelado ou Faltou no formulário também mostra o campo da taxa.
- A taxa **entra na receita**: total faturado, Receitas, Relatórios, formas de pagamento e total gasto pela cliente.
- A taxa **não conta como atendimento nem como visita**. Linhas de "Taxa de cancelamento" vindas da planilha também deixam de contar como atendimento.
- No Painel e nos Relatórios aparece quanto da receita veio de taxas. A ficha da cliente mostra quantas vezes ela cancelou ou faltou.
- No Google Agenda, o evento não é apagado: fica marcado com ❌ "cancelou/faltou" e com o horário livre.
- O percentual da taxa pode ser alterado em **Config → Taxas e parâmetros**.

## V2 — 2.0.0 (22/10/2026)

**Correções**
- **Total faturado sem desconto da maquininha.** Os valores lançados já são líquidos, como na planilha. O desconto agora é opcional em Config e vem desligado.
- **Contagem de atendimentos igual à da planilha.** Cada serviço conta como um atendimento (uma linha na planilha). O app mostra também o número de **visitas** (cliente + dia).
- **Importar da planilha não duplica mais.** Se a planilha ganhou um serviço novo numa visita que já existe, o app atualiza essa visita em vez de criar outra.
- Ao importar clientes, a cliente é reconhecida também pelo telefone/CPF e pelo nome parcial, sem recriar duplicadas.

**Novidades**
- **Conferir com a planilha** (aba Receitas): compara o mês do app com a aba do mês da planilha e lista o que falta, o que tem valor diferente e o que só existe no app, com botão para importar.
- **Relatórios: gráficos por data** (dia, semana ou mês, no período escolhido):
  - Atendimentos por data (por profissional)
  - Serviços por data
  - Atendimentos por forma de pagamento por data
  - Visitas por cliente por data (mapa de calor, Top 10/15/30/todas)
  - Cada gráfico tem "Ver dados em tabela".
- Ticket médio passa a ser **por visita**.
- Versão do app visível em Config → Sobre.

## V1 — 1.0.0 (21–22/10/2026)

Primeira versão em uso:
- Painel no modelo da aba do mês (meta, faturado, gastos, líquido), agenda, receitas, despesas, clientes, serviços e relatórios.
- Base importada da planilha (clientes, atendimentos, despesas, metas, histórico desde set/24).
- Google Agenda com as agendas Thais e Amanda; profissionais Thais/Amanda com filtro.
- Agenda em dia / semana / mês / lista.
- Sincronização entre aparelhos pela planilha (aba oculta `CRM_dados`).
- Layout para celular e tablet; app instalável (PWA).
- Visão de cartões ou tabela com ordenação por coluna em Receitas, Despesas e Clientes.

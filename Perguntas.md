# Perguntas da Elisa + criticas minhas

# Questões Estagiários

## Habilidades Técnicas

- **Pergunta 1**: Quantas tarefas planeou concluir hoje?  
  Tipo: Campo numérico  
  Variável: tarefas_planeadas

- **Pergunta 2**: Quantas tarefas conseguiu concluir hoje?  
  Tipo: Campo numérico  
  Variável: tarefas_concluidas

- **Pergunta 3**: O tempo que estimou para concluir as tarefas foi suficiente? Se não, quanto mais tempo foi necessário?  
  Tipo: Boolean, Campo numérico (horas)  
  Variável: tempo_estimado, tempo_real

- **Pergunta 4**: Qual foi o grau de complexidade das tarefas realizadas hoje?  
  Tipo: Escala de Likert (1 = Muito fácil, 5 = Muito difícil)  
  Variável: complexidade_tarefas
---
<span style="color:red">Pergunta redundante, retirar (CRITICA)
- ~~**Pergunta 5**: Atingiu todas as metas estabelecidas para o dia?~~  
  Tipo: Boolean (Sim/Não)  
  Variável: metas_atingidas
---


- **Pergunta 6**: Quais habilidades técnicas utilizou hoje?  
  Tipo: Checklist (C#, Python, JavaScript, SQL, React, Angular, Django, PowerBI, Tableau, Docker, Git, Jira, Outro)  
  Variável: habilidades_tec_uso

- **Pergunta 7**: Quais habilidades técnicas considera que desenvolveu mais hoje?  
  Tipo: Checklist (C#, Python, JavaScript, SQL, React, Angular, Django, PowerBI, Tableau, Docker, Git, Jira, Outro)  
  Variável: habilidades_tec_desenvolvidas

- **Pergunta 8**: Quais habilidades técnicas considera que precisa melhorar?  
  Tipo: Checklist (C#, Python, JavaScript, SQL, React, Angular, Django, PowerBI, Tableau, Docker, Git, Jira, Outro)  
  Variável: habilidades_tec_melhorar


## Habilidades Comportamentais
- <span style="color:yellow">**Pergunta 9**: Quais habilidades comportamentais aplicou mais hoje? (CRITICA David, Pouca prioridade)

  Tipo: Checklist (Comunicação, Resolução de problemas, Trabalho em equipa, Adaptabilidade, Gestão de Tempo)  
  Variável: habilidades_comportamentais_uso

- <span style="color:yellow">**Pergunta 10**: Qual habilidade comportamental considera que mais desenvolveu hoje?(CRITICA David, Pouca prioridade)

  Tipo: Checklist (Comunicação, Resolução de problemas, Trabalho em equipa, Adaptabilidade, Gestão de Tempo)  
  Variável: habilidades_comportamentais_desenvolvidas

- **Pergunta 11**: Quais habilidades comportamentais considera que precisa melhorar? 

  Tipo: Checklist (Comunicação, Resolução de problemas, Trabalho em equipa, Adaptabilidade, Gestão de Tempo)  
  Variável: habilidades_comportamentais_melhorar

### Comunicação

<span style="color:yellow">#### **Incluir primeira pergunda: "Trabalha em equipa?" Se sim, abrir próximas 2 perguntas -->** (CRITICA)

- **Pergunta 12**: ~~Comunicou-se com a equipa durante o dia?~~Quanto tempo gastou em comunicacao?

  Tipo: Boolean (Sim/Não)  (CRITICA David, Estimativa em horas)
  Variável: comunicacao_equipa

- **Pergunta 13**: Se sim, qual foi a frequência das suas interações?  
  Tipo: Checklist (Nenhuma interação, Poucas interações, Interações moderadas, Muitas interações)  
  Variável: frequencia_comunicacao
---
<span style="color:yellow">Dividir em duas perguntas (CRITICA)
- **Pergunta 14**: A comunicação com a equipa/tutor foi clara e eficiente?
  (CRITICA David, devia de ser junto para anonymato do estudante)
  Tipo: Boolean (Sim/Não)  
  Variável: qualidade_comunicacao
  
Variantes:
- ~~**Pergunta 14 A**: A comunicação com a equipa foi clara e eficiente?~~
- ~~**Pergunta 14 B**: A comunicação com a tutor foi clara e eficiente?~~
---
- **Pergunta 15**: O que motivou a comunicação?  
  Tipo: Checklist (Tirar dúvidas, Reportar bug, Solicitar feedback, Ajudar a equipa, Outros)  
  Variável: motivo_comunicacao

### <span style="color:red">Autonomia (CRITICA David, por so na parte do tutor por agora)

- ~~**Pergunta 16**: Fez alguma pesquisa autónoma para resolver algum problema ou tarefa?~~ 
  Tipo: Boolean (Sim/Não)  
  Variável: pesquisa_autonoma

- ~~**Pergunta 17**: Se sim, qual foi o tema da pesquisa?~~  
  Tipo: Campo de texto  
  Variável: tema_pesquisa_autonoma
---
<span style="color:red">Pergunta redundante, retirar (CRITICA)

- ~~**Pergunta 18**: Tirou dúvidas com o tutor ou com alguém da equipa hoje?~~ 

  Tipo: Boolean (Sim/Não)  
  Variável: tirar_duvidas
  
---
- ~~**Pergunta 19**: Se sim, sobre qual tema ou tarefa tirou dúvidas?~~
  
   Tipo: Campo de texto  
  Variável: tema_tirou_duvidas

#### <span style="color:yellow">Incluir pergunta para perceber se pergunta foi esclarecida (CRITICA)
---

- ~~**Pergunta 20**: Quantas decisões importantes tomou sem precisar consultar o tutor ou equipa?~~ 
  Tipo: Campo numérico  
  Variável: decisoes_autonomas

## Autoavaliação e Satisfação 
- <span style="color:green">**Pergunta 21**: Como se sentiu em relação ao seu desempenho hoje?  (CRITICA David, gostou bastante desta pergunta)

  Tipo: Escala de Likert (1 = Muito insatisfeito, 5 = Muito satisfeito)  
  Variável: autoavaliacao_desempenho

- <span style="color:green">**Pergunta 22**: Como se sentiu em relação ao seu desempenho hoje?  (CRITICA David, gostou bastante desta pergunta)

CERTIFICAR SOBRE ESTAS PERGUNTAS
- **Pergunta 22**: Sentiu-se motivado para concluir as atividades de hoje?  
  Tipo: Escala de Likert (1 = Muito desmotivado, 5 = Muito motivado)  
  Variável: motivacao

- **Pergunta 23**: Se a motivação foi baixa (1-2), o que influenciou isso?  
  Tipo: Campo de texto obrigatório para motivação baixa.  
  Variável: motivo_baixa_motivacao

- **Pergunta 24**: Encontrou dificuldades para concluir suas atividades?  
  Tipo: Boolean (Sim/Não)  
  Variável: dificuldades_encontradas

- **Pergunta 25**: Se sim, em quais áreas encontrou dificuldades?  
  Tipo: Checklist (Técnica, Comunicação, Gestão de Tempo)  
  Variável: dificuldades_areas

# Questões Tutor

#### <span style="color:yellow">**Incluir primeira pergunda: "Comunicou-se com o estagiário hoje?"** (CRITICA)
Se sim, abrir próximas perguntas 

---
- **Pergunta 1**: O estagiário cumpriu as metas e expectativas estabelecidas para o dia?  
  Tipo: Boolean (Sim/Não)  
  Variável: cumprimento_de_expectativas

- **Pergunta 2**: O estagiário utilizou as habilidades necessárias para realizar as tarefas do dia?  
  Tipo: Boolean (Sim/Não)  
  Variável: habilidades_adequadas_tutor

- **Pergunta 3**: O estagiário demonstrou evolução no uso das habilidades técnicas?  
  Tipo: Escala de Likert (1 = Sem evolução, 5 = Evolução excepcional)  
  Variável: evolucao_habilidades_tec_tutor

- **Pergunta 4**: O estagiário demonstrou evolução na comunicação?  
  Tipo: Escala de Likert (1 = Sem evolução, 5 = Evolução excepcional)    
  Variável: evolucao_habilidades_comunic_tutor

- **Pergunta 5**: O estagiário demonstrou evolução de autonomia?  
  Tipo: Escala de Likert (1 = Sem evolução, 5 = Evolução excepcional) #nao foi possivel availiar  
  Variável: evolucao_habilidades_autonomia_tutor

- **Pergunta 6**: O estagiário demonstrou proatividade e interesse em aprender?  
  Tipo: Boolean (Sim/Não)  
  Variável: proatividade_interesse_tutor

---
#### **Peridiocidade semanal**
- **Pergunta 7**: O estagiário demonstrou evolução no desempenho em comparação com dias anteriores?  
  Tipo: Boolean (Sim/Não)  
  Variável: evolucao_desempenho_tutor
---

# <span style="color:green">Perguntas adcionais minhas

### Para Estagiários
## Habilidades Técnicas

<span style="color:green">CRIAR PAGINA SO PARA FEEDBACK E INCLUIR ESTAS PERGUNTAS

- **Pergunta:** As ferramentas e recursos disponíveis foram suficientes para realizar as tarefas?
  - Tipo: Boolean (Sim/Não) + Campo de texto para detalhes (se "Não").
  - Variável: recursos_suficientes

## Autonomia
- **Pergunta:** Em algum momento, sentiu que precisava de mais orientações para concluir suas tarefas?
  - Tipo: Boolean (Sim/Não)
  - Variável: necessidade_orientacao

### Gestão de Tempo
- **Pergunta:** Houve interrupções externas que comprometeram o andamento das tarefas?
  - Tipo: Boolean (Sim/Não) + Campo de texto para especificar.
  - Variável: interrupcoes_externas

## Motivação e Bem-estar
- **Pergunta:** Sentiu-se à vontade para pedir ajuda ou tirar dúvidas?
  - Tipo: Escala de Likert (1 = Muito desconfortável, 5 = Muito confortável)
  - Variável: conforto_ao_pedir_ajuda

### Para Tutores

## Acompanhamento e Feedback
- **Pergunta:** O estagiário demonstrou iniciativa para procurar feedback ~~sobre o seu desempenho~~?
  - Tipo: Boolean (Sim/Não)
  - Variável: procura_feedback

- **Pergunta:** Foi possível identificar melhorias no estagiário em relação a um objetivo específico discutido previamente?
  - Tipo: Boolean (Sim/Não) + Campo de texto para especificar o objetivo.
  - Variável: melhorias_em_objetivos

## Relação com a Equipa 
- ~~**Pergunta:** O estagiário conseguiu interagir de forma construtiva com outros membros da equipa?~~
  - Tipo: Escala de Likert (1 = Não interagiu, 5 = Interação excepcional)
  - Variável: interacao_equipa

## Desempenho Geral
- **Pergunta:** O estagiário apresentou dificuldades recorrentes em alguma área?
  - Tipo: Checklist (Técnica, Comunicação, Gestão de Tempo, Outro)
  - Variável: dificuldades_recorrentes
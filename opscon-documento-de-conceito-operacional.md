# Documento de Conceito Operacional (OpsCon): Programa Sukatech

## Prefácio
Este Documento de Conceito Operacional (OpsCon) apresenta conceitos e aspectos fundamentais sobre o Programa Sukatech para membros da comunidade acadêmica, da administração pública, e do terceiro setor sob a perspectiva da grande área de Sistemas de Informação. Ele consolida observações do grupo de residentes técnicos denominado Squad 2 da turma de 2025-1 da Residência Técnica em Sistemas de Informação (RTSI) do Instituto de Informática (INF) da Universidade Federal de Goiás (UFG).

Os trabalhos do Squad 2 foram desenvolvidos pelos residentes técnicos Brenda Andreia Lima Pinheiro, Fabio Tiago Vieira Soares Marques, Giovanna Waleska Theodoro Barbosa, e Yatherson Lucas Theodoro Souza. Sob orientação de Juliano Lopes de Oliveira e responsável pela demanda "Inovação em gestão para a economia circular", o Squad 2 realizou diversos estudos, visitas técnicas, e entrevistas com funcionários da organização de sociedade civil Programando o Futuro e da Secretaria de Estado de Ciência, Tecnologia e Inovação (SECTI) para modelar e analisar problemáticas enfrentadas pelo programa Sukatech.

Este OpsCon introduz os leitores aos quatro eixos de atuação do Programa Sukatech, construindo um retrato de suas atividades e desafios no decorrer do primeiro semestre de 2025. Documentamos motivações, modos de operação, objetivos gerais, objetivos específicos, indicadores e fontes de dados para cada eixo através da descrição do sistema _as is_. Por conseguinte, descrevemos pontos problemáticos nas operações atuais, e propomos um sistema _to be_ através modelo de processo de medição baseado no método GQM+Strategies. Este documento, portanto, é um marco fundamental para o apoio ao desenvolvimento do planejamento e gestão estratégicos do Programa Sukatech.

Esperamos que este documento seja atualizado, complementado, ou substituído à medida em que o entendimento sobre o Programa Sukatech evolui. Acreditamos, no entanto, que este documento ainda será capaz de oferecer informações valiosas sobre a gestão de um programa de economia circular no âmbito da administração pública ainda que o seu retrato se torne ultrapassado.

## Escopo

O Programa de Recondicionamento de Equipamentos Eletroeletrônicos - Sukatech foi instituído pelo Decreto Estadual nº 9.718, de 24 de setembro de 2020 e é administrado Secretaria de Estado de Ciência, Tecnologia e Inovação (SECTI). Sobre as suas designações, podemos afirmar que:

> O SukaTech tem a finalidade de apoiar o descarte correto e sustentável de equipamentos, materiais e bens de informática da administração pública estadual e do setor privado. Atuando na construção da logística reversa e economia circular do setor eletroeletrônico, ao passo em que recicla e recondiciona estes resíduos. Além de animar a cadeia produtiva do segmento, o programa ainda capacita a população em tecnologia, promovendo conscientização social a respeito do descarte correto destes materiais, bem como a habilitação dos mesmos para atuarem neste setor (Plano de Trabalho Programa Sukatech, 2023, p. 2).

Provocados a analisar o programa Sukatech a partir de uma perspectiva de dados, indicadores e métricas, identificamos dois principais campos de problemáticas no que denominamos as "duas pontas" do programa:

1. Campo de coleta, guarda, e gerência de dados do programa Sukatech — o "nascimento" dos dados a um nível operacional;
2. Campo de consolidação, trânsito, e análise de dados do programa Sukatech — o destino final dos dados a um nível gerencial e estratégico.

Descrevemos, então, o programa Sukatech em termos mais processuais do que diminutivamente em termos de sistemas de software que o englobam.

### Visão geral
Para fins de especificação da solução, descrevemos o sistema de informação que permeia e espelha a operacionalização do programa Sukatech a partir de duas perspectivas: _as is_ (representando o retrato atual do programa Sukatech, consolidando definições formais e observações práticas) e _to be_ (representando um projeto idealizado do programa Sukatech — aquilo que o programa almeja ser).

A perspectiva _as is_ captura descrições dos quatro eixos de operação e gerência do programa:
- Eixo 1 - Cadeia Produtiva;
- Eixo 2 - Capacitação e Empreendedorismo;
- Eixo 3 - Educação Ambiental;
- Eixo Transversal - Avaliação.

A perspectiva _to be_ se concentra em construir uma especificação para o aprimoramento do Eixo Tranversal - Avaliação a partir de uma perspectiva sistêmica, apoiada pela compreensão contextual de todos os pilares do programa Sukatech explorados pela perspectiva _as is_.

## Sistema atual—*as is*
### Eixo 1 - Cadeia Produtiva

#### Contexto, objetivos, e escopo

O **Eixo 1 do programa Sukatech – Cadeia Produtiva** visa estruturar a **logística reversa de resíduos eletroeletrônicos (REEE)** no Estado de Goiás, com foco prioritário na administração pública, mas incluindo também a sociedade civil e o setor privado. A operação é viabilizada por meio de uma rede de **Centros de Recondicionamento de Computadores (CRCs)** e **polos descentralizados**, denominados **SukaTech Labs**, que recebem resíduos provenientes de **desfazimentos institucionais, doações da sociedade civil, campanhas de arrecadação e Pontos de Entrega Voluntária (PEVs)**.

O principal objetivo deste eixo é **estruturar e operacionalizar a logística reversa de equipamentos eletroeletrônicos**, priorizando a **triagem, recondicionamento, redistribuição para inclusão digital** e o **descarte ambientalmente adequado** dos materiais não aproveitáveis. A proposta também busca fomentar a **capacitação profissional**, a **inclusão socioeconômica** e o **desenvolvimento de soluções tecnológicas inovadoras** no contexto da economia circular — **tendo como principais metas estabelecidas**:

- O **recebimento e processamento mínimo de 250 toneladas de REEE por ano**;
- O **recondicionamento e redistribuição de pelo menos 2000 computadores funcionais**;
- A **correta destinação de 100% dos resíduos não aproveitáveis a recicladoras certificadas**;
- A **ampliação da rede de CRCs e SukaTech Labs para ao menos cinco unidades**;
- E a **geração de receita por meio da comercialização de resíduos recicláveis**, contribuindo com a sustentabilidade financeira do programa.

### Escopo do Eixo 1
- Recebimento de equipamentos via doações, campanhas, desfazimentos e PEVs;
- Triagem e classificação dos resíduos conforme estado e viabilidade de reuso;
- Recondicionamento e redistribuição dos equipamentos a instituições públicas e projetos de inclusão digital;
- Encaminhamento de rejeitos para empresas recicladoras parceiras licenciadas;
- Registro e rastreamento de lotes e componentes reutilizáveis por meio de planilhas e sistemas de monitoramento;
- Monetização de materiais recicláveis como plástico e metais para garantir a sustentabilidade do programa.

#### Políticas operacionais e restrições

- **Legislação vigente:** A operação segue os princípios da Política Nacional de Resíduos Sólidos (Lei nº 12.305/2010) e normativas locais sobre economia circular e logística reversa.
- **Critérios de descarte:** Somente equipamentos com potencial de recondicionamento são mantidos em estoque. Itens inservíveis são destinados à cadeia de reciclagem.
- **Controle por lote:** Cada item ou subconjunto é rastreado por lote.
- **Infraestrutura disponível:** As atividades estão limitadas à capacidade física dos CRCs e dos polos descentralizados.
- **Limitação de pessoal:** A operação depende da disponibilidade de técnicos e pessoal capacitado.

#### Descrição

O processo inicia com o **recebimento de resíduos eletroeletrônicos** no CRC ou em polos descentralizados. Os materiais podem ter quatro origens distintas: desfazimentos de órgãos públicos, campanhas públicas de arrecadação, doações diretas e entregas em PEVs.

Após o recebimento, os itens são **triados manualmente** para separação entre:
- Equipamentos com potencial de recondicionamento
- Equipamentos danificados, mas com peças reutilizáveis
- Resíduos não reaproveitáveis (destinados à cadeia de reciclagem)

Os equipamentos selecionados seguem para **diagnóstico técnico e reparo**, com rastreabilidade mantida via planilhas e sistema de gestão de residuos. Após validação de funcionamento, os dispositivos são **redistribuídos** para escolas, organizações sociais e outras entidades cadastradas.
Os resíduos não aproveitáveis são **destinados a empresas ou cooperativas de reciclagem**, com acompanhamento e registro da massa e tipo de material.

#### Modos de operação

A operação do Eixo 1 pode ocorrer sob diferentes condições, que impactam diretamente os fluxos operacionais e a gestão logística dos resíduos eletroeletrônicos. Os modos são:

- **Operação Regular**: Funcionamento padrão, com entrada contínua de materiais provenientes de desfazimentos, doações, e PEVs. Inclui atividades rotineiras de triagem, manutenção, recondicionamento e redistribuição.

- **Operação de Campanha**: Ocasiões pontuais (como campanhas de arrecadação), exigindo adaptação temporária de fluxos, reforço de equipe, espaço e transporte.

A seguir, são apresentados os **principais fluxos operacionais** que ocorrem nos diferentes modos de operação, destacando variações de entrada, decisões críticas e saídas conforme o tipo de resíduo e sua condição:

- **Fluxo de Recebimento por Desfazimento Institucional**
![Fluxo de Desfazimento](https://github.com/contraexemplo/RTSI-2025/blob/feature/eixo1-especificacoes/processos/BPMN_-_Eixo_1_-_Desfazimento_Coleta.svg)
- **Fluxo de Triagem e Classificação**
![Fluxo de Triagem](https://github.com/contraexemplo/RTSI-2025/blob/feature/eixo1-especificacoes/processos/BPMN_-_Eixo_1_-_Triagem_Recondicionamento_Desmanufatura.svg)


#### Classes de usuário

- **Operador de CRC** 
- **Gestor de Polo**
- **Operador de Sistema**
- **Motorista** 
- **Técnico de Manutenção** 
- **Técnico de Logística** 
- **Doador Institucional** 
- **Doador Pessoa Física ou Jurídica** 
- **Beneficiário** 
- **Servidor SECTI**
- **Coordenação Técnica**

##### Estrutura organizacional

- SECTI 
- OSC Programando o Futuro
- CRC  
- Prefeituras
- Polos["SukaTech Labs"]  

##### Perfis de classes de usuário

- **Operador de CRC:** executa atividades práticas de triagem, recondicionamento e separação de materiais recicláveis. Exige conhecimento técnico-médio.
- **Gestor de Polo:** supervisiona as operações nos SukaTech Labs, organiza logística de coleta e promove ações de capacitação. Perfil administrativo e de liderança.
- **Motorista:** realiza o transporte físico de materiais entre pontos de coleta e CRCs. Exige agilidade, atenção e responsabilidade no manuseio dos resíduos.
- **Técnico de manutenção:** executa triagem e análise técnica, manutenção e montagem de computadores. . Nível técnico-intermediário.
- **Técnico de Logística:** responsável pelo recebimento, descarregamento, organização de estoque e envio de materiais.
- **Operador de sistema:** atua no sistema de gestão de resíduos, registra recebimentos, agenda coletas e organiza documentos no drive. Nível técnico-operacional.
- **Doador Institucional:** órgão público que realiza desfazimentos formais de bens, com envio de documentação e processo via SEI.
- **Doador Pessoa Física ou Jurídica:** realiza doações espontâneas em campanhas, PEVs ou entregas diretas. Atua como contribuinte do ecossistema.
- **Beneficiário:** entidade receptora dos equipamentos recondicionados. Atua apenas como solicitante.
- **Servidor SECTI:** avalia a conformidade dos processos de desfazimento e autoriza o envio de bens para o programa. Atua em interface direta com doadores institucionais.
- **Coordenação Técnica:** vinculada à SECTI, supervisiona tecnicamente a operação da cadeia produtiva, define protocolos operacionais, padrões de qualidade e indicadores de desempenho.

##### Interações entre classes de usuário

- **Doador Institucional → Servidor SECTI:** envio de documentação para análise de desfazimento.
- **Analista SECTI → Operador de Sistema:** liberação e orientação sobre processos documentais.
- **Operador de Sistema → Técnico de Logística:** registro de recebimentos e agendamento de coleta.
- **Doador Pessoa Física ou Jurídica → Técnico de Logística:** entrega direta de equipamentos.
- **Operador de CRC → Técnico de Manutenção:** transferência de itens triados para manutenção.
- **Técnico de Manutenção → Gestor:** envio de status e relatórios técnicos dos equipamentos.
- **Gestor → Coordenação Técnica:** consolidação e repasse de metas e indicadores.
- **Gestor → Beneficiário:** organização da redistribuição de equipamentos.

##### Outros atores envolvidos

- **Empresas de Reciclagem:** recebem resíduos inservíveis para tratamento.
- **Cooperativas de Catadores:** possíveis parceiras no descarte.
- **Prefeituras e Órgãos Públicos:** colaboram com campanhas e doações.

##### Ambiente de apoio

- **Google Drive:** utilizados para registro de processos de desfazimento, controle de recebimentos e compartilhamento de informações com a SECTI.
- **Sistemas de planilhas:** utilizados para análise e organização de dados operacionais, controle de lotes e rastreabilidade. Também utilizada para elaboração de relatórios técnicos e criação de dashboards para acompanhamento de metas e indicadores do programa.
- **Infraestrutura física:** CRCs e SukaTech Labs com espaço para triagem, manutenção e armazenamento.
- **Meios de transporte:** veículos para coleta e redistribuição de equipamentos.
- **Documentos de apoio:** termo de doação, termo de renúncia e termo de responsabilidade.

### Objetivos específicos, indicadores e fontes

## Meta 1 - Adequação e estruturação do Centro de Recondicionamento de Computadores (CRC)

### Objetivo Geral

Reestruturação física da Unidade CRC - polo de economia circular com os requisitos mínimos indispensáveis para o beneficiamento de 750 toneladas (250 t/ano) de resíduos eletroeletrônicos durante o período de execução do projeto.

### Objetivos específicos

M1OE1: Adequação de mobiliário
M1OE2: Manutenção

### Indicadores

* Reforma realizada
* Equipamentos adquiridos
* Expansão da capacidade de processamento de resíduos

### Fonte

Programando o Futuro

## Meta 2 – Estruturação dos polos descentralizados de economia circular (SukaTech Labs)

### Objetivo Geral

Estruturação física de 5 polos descentralizados de economia circular para o beneficiamento de resíduos eletroeletrônicos durante o período de execução do projeto.

### Objetivos específicos

M2OE1: Identificar possíveis cidades parceiras com base em critérios como desejo do município, existência de coleta seletiva, contingente populacional e localização na Região Metropolitana de Goiânia ou entorno do DF
M2OE2: Criar "enxoval" para os municípios (minuta de Lei, Convênio, Plano de trabalho, artes de divulgação)
M2OE3: Assinar Termo de Cooperação com responsabilidades entre Prefeitura, Programando o Futuro e Gestão SukaTech

### Indicadores

* Número de parcerias realizadas
* Número de SukaTech Labs implantados
* Alunos formados
* Resíduos coletados no interior

### Fonte

SECTI e Programando o Futuro

## Meta 3 – Coleta, Recondicionamento e Redistribuição de Computadores

### Objetivo Geral

Expandir a coleta, recondicionamento e redistribuição de equipamentos eletroeletrônicos oriundos da administração pública, sociedade civil e setor privado.

### Objetivos específicos

M3OE1: Criação de cadeia logística eficiente:

* M3OE1.1: Distribuição de PEVs em órgãos públicos
* M3OE1.2: Recolhimento e logística dos bens
* M3OE1.3: Entrega à estação de metarreciclagem

M3OE2: Criação de Software Centralizado de Gestão
M3OE3: Criação de Plataforma Digital de Descarte

* M3OE3.1: Construção de plano de economia para parcerias

M3OE4: Desenhar e publicar política de doação com link e formulário no site

### Indicadores

* Toneladas de material coletado
* Número de PEVs instalados
* Número de computadores recondicionados
* Número de entidades beneficiadas
* Número de alunos e beneficiários

### Fonte

SECTI e Programando o Futuro

## Meta 4 - Tratamento dos Polímeros Plásticos

### Objetivo Geral

Coletar, processar e redirecionar o termoplástico, promovendo o reaproveitamento e a valorização dos resíduos plásticos.

### Objetivos específicos

M4OE1: Implantação da linha de processamento dos resíduos plásticos
M4OE2: Processamento e triagem dos plásticos
M4OE3: Destinação adequada dos termoplásticos

### Indicadores

* Toneladas de plástico coletado
* Toneladas de plástico processado
* Toneladas de plástico redirecionado

### Fonte

Programando o Futuro


## Meta 5 - Monetização dos resíduos recicláveis

### Objetivo Geral

Reverter ao programa os recursos financeiros obtidos com a venda dos materiais não passíveis de recondicionamento.

### Objetivos específicos

M5OE1: Criar política de retorno financeiro até 2024
M5OE2: Criar modelo de prestação de contas
M5OE3: Criar plano de investimento a partir do valor arrecadado

### Indicadores

* Política criada
* Toneladas de material vendido
* Valor arrecadado e retornado ao programa

### Fonte

Programando o Futuro


### Eixo 2 - Capacitação e Empreendedorismo
### Contexto, objetivos, e escopo

###  Contexto

O **Eixo 2**, desenvolvido no **Programa Sukatech**, surge como resposta a dois problemas fundamentais identificados na sociedade goiana:  

- A **carência de oportunidades de capacitação** da população de baixa renda em um setor produtivo (tecnologia) com alta demanda por profissionais qualificados. 
- A **dificuldade de acesso a linhas de financiamento ao microempreendedorismo** e a falta de formação profissional continuada para a população de baixa renda.  

O sistema atual opera através de um **polo de economia circular e logística reversa**, integrando: 
- Educação tecnológica 
- Suporte ao empreendedorismo 
- Responsabilidade ambiental

Para endereçar estes desafios, o programa estrutura-se em três metas principais:

- **Meta 6 - Capacitação da População**: Emissão de 2.100 certificados em cursos de tecnologia desenvolvidos no polo, com objetivos específicos de ofertar anualmente no mínimo 540 vagas em Informática Básica, 540 vagas em Montagem e Manutenção de Computadores e Celulares, e 405 vagas em Eletrônica e Robótica Livre, todos com componente de Empreendedorismo.

- **Meta 7 - Projeto Idoso Tech**: Formação de 360 idosos em inclusão digital através de três módulos (Alfabetização Digital, Serviços Online e Aplicações Práticas), totalizando 60 horas de capacitação por participante, com foco em populações vulneráveis.

- **Meta 8 - Trilha Empreendedora**: Certificação de pessoas na trilha de formação do programa via PRONATEC, com objetivos específicos de montar plano de ensino em parceria com o PRONATEC, criar modelo de avaliação dos alunos e desenvolver estratégia de acompanhamento dos beneficiários do Crédito Social.

### Objetivos

O **Eixo 2 do Programa Sukatech** tem como objetivos principais:  

- **Capacitação da população** em áreas tecnológicas estratégicas, com meta de emissão de **2.100 certificados** nos cursos do polo de economia circular e logística reversa, atendendo a população a partir de 12 anos, com critérios para equidade de gênero (60% para mulheres), inclusão de pessoas afrodescendentes e com deficiência, e priorização de pessoas em vulnerabilidade social.

- **Implementação de uma trilha empreendedora**, culminando na certificação via **PRONATEC**, promovendo:
  - Conhecimento técnico em tecnologias específicas
  - Competências empreendedoras para geração de renda
  - Monitoramento e avaliação sistemática do desempenho dos alunos
  - Desenvolvimento de planos de ensino alinhados às demandas do mercado

- **Inclusão digital de idosos**, por meio do **Projeto Idoso Tech**, promovendo:
  - Capacitação de 360 idosos em situação socioeconomicamente vulnerável
  - Formação em três módulos complementares totalizando 60 horas
  - Alfabetização e Socialização Digital (20h)
  - Serviços e Proteção Online (20h)
  - Aplicações Práticas das Tecnologias Digitais (20h)
  - Aulas em 6 turmas de 30 alunos distribuídas em cidades goianas
  - Cronograma estruturado com aulas às segundas, quartas e sextas, das 9h às 10h30

- **Concessão de créditos sociais** no valor de **5.000,00 reais** para até **40 participantes** em situação de vulnerabilidade social, totalizando um investimento de **200.000,00 reais** para iniciativas empreendedoras, privilegiando:
  - Concluintes integrais dos cursos
  - Pessoas a partir de 18 anos
  - Inscritos no CadÚnico
  - Concluintes ou matriculados no Ensino Médio
  - Destaque em evolução, comprometimento e notas
  - Proporção de 60% para mulheres
  - Inclusão de afrodescendentes e pessoas com deficiência


### Escopo  

#### Cursos de Capacitação  

| Curso                                                                 | Carga Horária | Vagas Anuais | Alunos por Turma | 
|-----------------------------------------------------------------------|---------------|--------------|------------------| 
| Informática Básica e Empreendedorismo                                 | 45h           | 500          | 20               | 
| Montagem e Manutenção de Computadores e de Celulares e Empreendedorismo | 70h           | 120          | 20               | 
| Eletrônica e Robótica Livre e Empreendedorismo                        | 45h           | 200          | 15               |  

#### Projeto Idoso Tech

| Módulo                                       | Carga Horária | Vagas Totais | Alunos por Turma |
|----------------------------------------------|---------------|--------------|------------------|
| Alfabetização e Socialização Digital         | 20h           | 360          | 30               |
| Serviços e Proteção Online                   | 20h           | 360          | 30               |
| Aplicações Práticas das Tecnologias Digitais | 20h           | 360          | 30               |

#### Locais de Operação  

- **Sede da Sukatech** – Bairro Floresta, Goiânia 
- **Sukatech Lab** – Senador Canedo
- **Locais estratégicos** em municípios participantes (para o Projeto Idoso Tech)  

#### Turnos  

- **Matutino** (9h às 10h30 para Idoso Tech), **Vespertino** e **Noturno** (sob demanda)
- **Dias da semana**: segunda, quarta e sexta (para Idoso Tech)

#### Público-Alvo  

- População a partir de **12 anos** para cursos regulares de tecnologia
- **Idosos** em situação de vulnerabilidade social para o Projeto Idoso Tech
- Grupos prioritários:   
   - **Mulheres** (60% das vagas)   
   - **Afrodescendentes**   
   - **Pessoas com deficiência**   
   - **Pessoas em situação de vulnerabilidade social**
   - **População rural, indígenas, ribeirinhos, quilombolas e trabalhadores rurais**

#### Processos Operacionais  

- Sistema de inscrição **presencial e online** 
- Processo seletivo com **critérios de inclusão social** 
- Para o Idoso Tech: **identificação e convocação** de beneficiários do CadÚnico e Programa Goiás Social
- **Monitoramento pedagógico** com:   
   - Diários de classe   
   - Relatórios de atividade   
   - Formulários de avaliação 
- Avaliação **individual e coletiva** 
- **Certificação** ao final dos cursos
- **Pesquisa de satisfação** ao final de cada turma do Projeto Idoso Tech

#### Cronograma

- **Cursos regulares**: Operação contínua ao longo de 36 meses
- **Idoso Tech**:
  - 1ª turma: abril a julho de 2024
  - 2ª turma: agosto a novembro de 2024
  - Recesso: novembro a dezembro

#### Indicadores e Metas

- **Cursos regulares**: 2.100 certificados emitidos
- **Idoso Tech**:
  - 300 matrículas realizadas
  - 75% de frequência dos estudantes
  - 75% de certificação (270 certificados)
  - 100% de aplicação de pesquisa de satisfação

#### Trilha Empreendedora  

- Integração de **conteúdos de empreendedorismo** em todos os cursos 
- Possibilidade de **crédito social** para alunos destacados 
- Incentivo à **formalização como Microempreendedor Individual (MEI)** 
- **Acompanhamento e monitoramento** dos alunos beneficiados pelo crédito social   

#### Parceria Público-Privada  

O sistema atual opera por meio de uma parceria entre:
- **SECTI** (Secretaria de Estado de Ciência, Tecnologia e Inovação)
- **OSC Programando o Futuro**
- **Secretaria de Desenvolvimento Social** (para o Projeto Idoso Tech)

Os **fluxogramas de processos operacionais** abrangem desde a matrícula até: 
- A conclusão do curso 
- A possível concessão de **crédito social**
- A certificação e obtenção de feedback via pesquisa de satisfação
- 
### Políticas operacionais e restrições

### Políticas Operacionais

As políticas operacionais representam decisões gerenciais predeterminadas que orientam as operações do Programa Sukatech, estabelecendo diretrizes que, embora limitem certas liberdades decisórias, permitem algum grau de discricionariedade em sua aplicação.

#### Políticas de Inclusão Social
- **Equidade de Gênero**: Manutenção da disparidade positiva de 60% das vagas destinadas ao público feminino e 40% ao masculino
- **Ações Afirmativas**: Reserva de vagas para afrodescendentes declarados e pessoas com deficiência, em conformidade com a legislação municipal/estadual
- **Priorização Socioeconômica**: Preferência para candidatos inscritos no Cadastro Único para Programas Sociais (CadÚnico)

#### Políticas de Certificação
- **Padrão PRONATEC**: Certificados emitidos conforme os padrões estabelecidos pelo Programa Nacional de Acesso ao Ensino Técnico e Emprego
- **Assinatura Conjunta**: Documentos certificados pela equipe técnica do SukaTech e pela Secretaria de Ciência, Tecnologia e Inovação

#### Políticas de Concessão de Crédito Social
- **Transparência Avaliativa**: Os critérios de avaliação para concessão do crédito social são públicos e pré-estabelecidos
- **Distribuição Inclusiva**: Manutenção da disparidade de 60% do crédito social para mulheres
- **Retorno ao Estado**: Incentivo à formalização como MEI com expectativa de retorno dos recursos financeiros investidos

#### Políticas de Gestão Pedagógica
- **Avaliação Contínua**: Monitoramento constante do progresso dos alunos através de avaliações individuais e coletivas
- **Documentação Sistematizada**: Manutenção de diários de classe e relatórios de atividades pedagógicas e avaliativas
- **Flexibilidade de Turnos**: Oferta de cursos nos períodos matutino, vespertino e, sob demanda, no turno noturno

#### Políticas para o Projeto Idoso Tech
- **Priorização de Grupos Vulneráveis**: Foco em idosos socioeconomicamente vulneráveis, incluindo população rural, pessoas com deficiência, indígenas, ribeirinhos, quilombolas e trabalhadores rurais
- **Parceria Intersetorial**: Articulação entre Superintendência de Transformação Digital e Superintendência de Desenvolvimento Sustentável
- **Avaliação de Satisfação**: Aplicação de pesquisa de satisfação com 100% dos participantes
  
### Restrições Operacionais

As restrições operacionais constituem limitações impostas ao funcionamento do sistema, definindo os parâmetros dentro dos quais o Programa Sukatech deve operar.

#### Restrições de Capacidade
- Limite de **20 alunos** por turma nos cursos de Informática Básica e Montagem/Manutenção
- Limite de **15 alunos** por turma no curso de Eletrônica e Robótica
- Teto de **2.100 certificações** ao longo do projeto
- Máximo de **40 créditos sociais** disponíveis (R$5.000,00 cada)

#### Restrições de Infraestrutura
- Operação restrita às instalações da **Sede SukaTech** (Bairro Floresta, Goiânia) e **SukaTech Lab** (Senador Canedo)
- Disponibilidade limitada de equipamentos especializados:
  - Laboratório de Informática: 20 computadores em rede por sala
  - Laboratório de Eletrônica: osciloscópio, multímetros, ferros de solda, drones, impressoras 3D
  - Laboratório de Manutenção: estações de teste, ferramentas específicas para smartphones

#### Restrições de Cronograma
- Duração fixa de **36 meses** para a oferta completa dos cursos
- Carga horária predefinida:
  - 45 horas para Informática Básica e Empreendedorismo
  - 70 horas para Montagem e Manutenção de Computadores e Celulares
  - 45 horas para Eletrônica e Robótica

#### Restrições de Elegibilidade
- **Idade mínima** de 12 anos para cursos regulares
- **Idade mínima** de 18 anos para recebimento do crédito social
- Necessidade de **alfabetização** dos participantes
- Para o crédito social: conclusão integral dos cursos, cadastro no CadÚnico e conclusão/matrícula no Ensino Médio

#### Restrições de Recursos Humanos
- Dependência de instrutores contratados sob regime jurídico específico
- Necessidade de equipe técnica especializada para avaliação dos candidatos ao crédito social

#### Restrições Financeiras
- Orçamento fixo de **200.000,00 reais** para o programa de crédito social
- Obrigatoriedade de seguir as diretrizes do Fundo Protege para concessão de benefícios
- Manutenção das turmas de capacitação até o final da vigência contratual, independentemente do atingimento da meta de certificações

#### Restrições Específicas para o Projeto Idoso Tech
- **Cronograma Fixo**: Execução em dois semestres específicos durante 2024
- **Capacidade de Turmas**: Máximo de 30 alunos por turma
- **Metas de Desempenho**: Compromisso com 75% de frequência e 75% de certificação
- **Limitação Horária**: Aulas exclusivamente no período matutino (9h às 10h30)
  
#### Descrição
#### Modos de operação
#### Classes de usuário 
As classes de usuário identificadas são:

- **Educador Social**
- **Coordenador Geral**
- **Coordenador Psicopedgógico**
- **Supervisor Ténico**
- **Educando**
- **Supervisor Administrativo**
- **Auxiliar Técnico e Logístico**

### Ambiente Operacional

O Eixo 2 opera em um ambiente educacional tecnológico caracterizado por:

- **Localização física**: Sede da Sukatech no Bairro Floresta (Goiânia) e Sukatech Lab (Senador Canedo)
- **Contexto socioeconômico**: Foco em populações de baixa renda com acesso ao CadÚnico
- **Modelo de operação**: Parceria público-privada entre SECTI e OSC Programando o Futuro
- **Estrutura organizacional**: Hierarquia definida entre coordenadores, educadores sociais e monitores

### Elementos Principais do Sistema

#### Componentes Estruturais
- **Cursos de Capacitação Tecnológica**:
  - Informática Básica e Empreendedorismo
  - Montagem e Manutenção de Computadores e Celulares
  - Eletrônica e Robótica Livre
- **Trilha Empreendedora**
- **Programa de Crédito Social**
- **Projeto Idoso Tech**

#### Interconexões entre Elementos
- Integração dos conteúdos de empreendedorismo em todos os cursos
- Articulação entre conclusão dos cursos e elegibilidade para crédito social
- Compartilhamento de infraestrutura e recursos entre as diferentes linhas de capacitação

#### Componentes Estruturais do Idoso Tech
- **Estrutura Modular**: Três módulos complementares de 20h cada:
  - Alfabetização e Socialização Digital
  - Serviços e Proteção Online
  - Aplicações Práticas das Tecnologias Digitais
- **Conteúdo Especializado**: 15 tópicos distribuídos entre os três módulos, com foco progressivo em habilidades digitais

##### Capacidades e Funções Específicas
- **Combate ao Isolamento Social**: Foco específico no módulo I com atividades de conexão familiar e apoio psicológico
- **Autonomia Digital**: Desenvolvimento progressivo desde habilidades básicas até aplicações práticas
- **Acesso a Serviços Essenciais**: Capacitação para uso de serviços bancários, governamentais e de saúde
- **Proteção Digital**: Formação em segurança online e identificação de fraudes digitais
- 
### Interfaces com Sistemas Externos

- **PRONATEC**: Parceria para certificação e metodologias de qualificação profissional
- **CadÚnico**: Interface para verificação de elegibilidade socioeconômica dos candidatos
- **Secretaria de Desenvolvimento Social**: Suporte para o Projeto Idoso Tech
- **Fundo Protege**: Normativas para concessão do crédito social

### Capacidades e Funções

#### Capacidades Atuais
- Capacitação de 1.980 alunos por ano nos três cursos oferecidos
- Certificação de 2.100 alunos ao longo do projeto
- Concessão de até 40 créditos sociais de R$5.000,00
- Capacitação de 360 idosos em inclusão digital

#### Funções Principais
- **Educacional**: Formação técnica em tecnologia
- **Social**: Inclusão socioeconômica e digital
- **Empreendedora**: Fomento ao microempreendedorismo
- **Ambiental**: Integração com economia circular e logística reversa

### Fluxos do Sistema

#### Fluxo de Inscrição e Matrícula
1. Divulgação das vagas conforme plano de comunicação
2. Recebimento de inscrições presenciais ou online
3. Seleção de candidatos conforme critérios predefinidos
4. Matrícula e início das atividades
5. Gestão de lista de espera para substituição em caso de evasão

#### Fluxo de Capacitação
1. Participação nos módulos teóricos e práticos
2. Avaliação contínua através de instrumentos específicos
3. Verificação de frequência mínima (75%)
4. Certificação dos concluintes
5. Monitoramento pós-curso para alunos beneficiados pelo crédito social
   
#### Fluxo do Projeto Idoso Tech
1. Identificação e convocação de beneficiários do CadÚnico e Programa Goiás Social
2. Seleção e capacitação do coordenador, educadores e monitores
3. Evento de abertura do curso
4. Realização das capacitações em três módulos sequenciais
5. Acompanhamento contínuo e suporte aos participantes
6. Evento de encerramento com certificação
7. Avaliação e feedback do programa

### Custos Operacionais

- Investimento total no programa de crédito social: R$200.000,00
- Custos de manutenção das instalações físicas
- Remuneração de instrutores e equipe técnica
- Aquisição e manutenção de equipamentos para laboratórios

### Fatores de Risco Operacional

- Evasão escolar acima do limite previsto
- Dificuldade de atendimento às proporções definidas para inclusão social
- Não formalização dos negócios após concessão do crédito social
- Obsolescência tecnológica de equipamentos e conteúdos

### Características de Desempenho

- **Capacidade**: 1.980 vagas anuais nos cursos regulares
- **Volume**: 820 vagas anuais para Informática, 405 para Eletrônica, 540 para Montagem e Manutenção
- **Frequência**: Turmas regulares nos períodos matutino e vespertino, com opção noturna mediante demanda
- **Carga de trabalho**: Cursos de 45h e 70h, distribuídos ao longo de 36 meses

### Atributos de Qualidade

- **Disponibilidade**: Oferta contínua de vagas em diferentes turnos
- **Flexibilidade**: Adaptação a diferentes públicos e necessidades
- **Interoperabilidade**: Integração com sistemas municipais/estaduais de educação e assistência
- **Manutenibilidade**: Atualização regular de conteúdos e metodologias
- **Usabilidade**: Laboratórios equipados e adaptados às necessidades de aprendizagem prática

### Provisões para Segurança e Continuidade

- Procedimentos para segurança física dos alunos e equipamentos
- Backup de dados de frequência e avaliação
- Plano de contingência para substituição de equipamentos com defeito
- Protocolos para manuseio seguro de ferramentas e componentes eletrônicos

### Requisitos Logísticos

- Fornecimento de material didático para os cursos
- Manutenção preventiva de equipamentos de laboratório
- Armazenamento seguro de componentes eletrônicos
- Gestão de estoque de peças para aulas práticas
- Suporte técnico para os laboratórios de informática e eletrônica

### Modos de Operação

#### Modo de Operação Normal

O Programa Sukatech opera em seu modo normal durante o período letivo regular, com as seguintes características:

- **Horários**: Turnos matutino e vespertino, com noturno sob demanda
- **Capacidade**: Todos os laboratórios e recursos tecnológicos operando em plena capacidade
- **Pessoal**: Equipe completa disponível (instrutores, coordenadores, monitores)
- **Processos**: Todos os fluxos de matrícula, avaliação e certificação em funcionamento normal

#### Modo de Operação em Período de Férias

Durante os períodos de recesso escolar:

- **Funcionamento reduzido**: Apenas atividades administrativas e manutenção preventiva
- **Equipe mínima**: Pessoal administrativo e técnico de manutenção
- **Sem aulas**: Interrupção temporária das atividades pedagógicas
- **Preparação**: Planejamento para o próximo período letivo

#### Modo de Operação Emergencial

Em situações críticas que impossibilitam o funcionamento normal:

- **Ativação**: Protocolos específicos de contingência
- **Comunicação**: Notificação imediata aos alunos e responsáveis
- **Alternativas**: Possibilidade de migração para atividades online
- **Prioridades**: Preservação da segurança dos envolvidos e dos equipamentos

#### Modo de Manutenção

Período destinado à manutenção dos equipamentos e instalações:

- **Suspensão temporária**: Interrupção programada das aulas
- **Equipe técnica**: Especialistas em manutenção de equipamentos eletrônicos
- **Atividades**:
  - Manutenção preventiva e corretiva dos computadores
  - Atualização de software e sistemas
  - Reparo ou substituição de componentes danificados

#### Modo de Avaliação Intensiva

Durante períodos de avaliação final ou certificação:

- **Cronograma especial**: Ajuste nos horários para aplicação das avaliações
- **Recursos adicionais**: Disponibilização extra de monitores e avaliadores
- **Procedimentos**: Ativação de protocolos de avaliação formal
- **Documentação**: Centralização do registro de resultados

#### Modo de Capacitação de Instrutores

Destinado ao treinamento e atualização da equipe pedagógica:

- **Suspensão parcial**: Algumas turmas podem ser afetadas temporariamente
- **Foco em desenvolvimento**: Aprimoramento de metodologias e técnicas
- **Recursos**: Utilização dos laboratórios para práticas pedagógicas

#### Modo Específico para o Projeto Idoso Tech
- **Horários**: Aulas às segundas, quartas e sextas, das 9h às 10h30
- **Cronograma**: Duas turmas anuais (abril-julho e agosto-novembro)
- **Capacidade**: 6 turmas de 30 alunos em diferentes municípios goianos
- **Processos Avaliativos**: Verificação de frequência e certificação com metas de 75%
- **Feedback**: Aplicação de pesquisa de satisfação com todos os participantes

#### Matriz de Referência Cruzada

| Modo | Instalações | Equipamentos | Pessoal | Alunos | Processos |
|------|------------|--------------|---------|--------|-----------|
| Normal | 100% disponível | Operacionais | Completo | Acesso total | Todos ativos |
| Férias | 50% disponível | Mínimo | Reduzido | Sem acesso | Administrativo |
| Emergencial | Variável | Parcial | Mínimo | Acesso restrito | Contingência |
| Manutenção | Bloqueado | Inoperante | Técnico | Sem acesso | Manutenção |
| Avaliação | 75% disponível | Selecionados | Ampliado | Regulado | Avaliação |
| Capacitação | 50% disponível | Compartilhados | Treinamento | Reduzido | Formação |
| Idoso Tech | Múltiplas localidades | Adaptados | Especializado | 30 por turma | Inclusão Digital |

### Transição entre Modos

#### Protocolo de Mudança
1. Notificação prévia aos stakeholders
2. Comunicação aos alunos e responsáveis
3. Ajuste do calendário e cronogramas
4. Adaptação dos recursos e processos
5. Monitoramento da transição

#### Responsabilidades
- **Coordenação**: Autoriza e gerencia as transições de modo
- **Equipe Técnica**: Implementa as mudanças necessárias
- **Equipe Pedagógica**: Adapta as atividades educacionais
- **Suporte Administrativo**: Atualiza registros e documentação

### Impactos por Modo

#### Geográficos
- Operação concentrada na Sede SukaTech (Goiânia) e SukaTech Lab (Senador Canedo)
- Em modo emergencial, pode haver redistribuição para locais alternativos

#### Tecnológicos
- Modo Normal: Plena utilização dos recursos tecnológicos
- Modo Manutenção: Atualização e melhoria da infraestrutura
- Modo Emergencial: Acesso remoto prioritário

#### Pedagógicos
- Continuidade do processo de aprendizagem em todos os modos
- Adaptações metodológicas conforme necessidade
- Manutenção dos objetivos de certificação mesmo em situações adversas

#### Classes de usuário
##### Estrutura organizacional
```text
Coordenação Geral
├── Coordenador Psicopedagógico
│   └── Educadores Sociais
│        └── Educandos (Alunos)
├── Supervisor Técnico
│   └── Auxiliar Técnico e Logístico
└── Supervisor Administrativo
```
##### Perfis de classes de usuário
- **Coordenador Geral:** Acompanha e monitora a gestão do projeto, seleção de pessoal, acompanha doações e prepara relatórios.

- **Coordenador Psicopedagógico:** Elabora o plano de coordenação pedagógica, coordena a formação dos educadores sociais, cria ações socioeducativas e avalia o processo pedagógico.

- **Supervisor Técnico:** Monitora laboratórios e o recebimento de equipamentos, coordena o trabalho técnico e logístico, controla o estoque e operacionaliza a entrega e recebimento de equipamentos.

- **Supervisor Administrativo:** Gerencia o RH, conduz processos de compras e pagamentos e organiza rotinas administrativas do projeto.

- **Educador Social:** Ministra e registra aulas, controla frequência e aplica avaliações.

- **Auxiliar Técnico e Logístico:** Coordena equipes técnicas, organiza materiais e contribui com dados para relatórios.

- **Educando (Aluno):** Participa das aulas, realiza atividades avaliativas e fornece feedback.

##### Interações entre classes de usuário

- **Coordenador Geral:** Supervisiona todos os outros papéis
- **Coordenador Psicopedagógico, Supervisor Técnico e Educador Social:** Acompanhamento pedagógico.
- **Educador Social → Educando:** Ministra as aulas.
- **Educador Social → Educando:** Aplicação de exercícios e avaliações.

##### Outros atores envolvidos

- **SECTI**
- **Responsáveis pelos educandos**

##### Ambiente de apoio
- **Google Drive** utilizado para o armazenamento e a administração de todos os dados que envolvem esse eixo.
- **Planilhas:** utilizados para a análise dos dados da turmas e dos feedbacks dos alunos.
- **Google Forms:** utilizado para o preenchimento online dos dados do educando para a matrícula.
- **Ambiente Físico:** CRC, onde se encontram os laboratórios nos quais as turmas são ministradas.

### Eixo 3 - Educação Ambiental
#### Contexto, objetivos, e escopo
Todas as atividades de formação cidadã e ambiental do programa Sukatech são gerenciadas sob a alçada do Eixo 3 - Educação Ambiental. O Eixo 3 abriga duas grandes metas do programa Sukatech: Campanhas Educacionais (Meta 8) e Capacitação Institucional (Meta 9). As ações de Campanhas Educacionais têm como objetivo educar a população geral sobre a importância do descarte correto e responsável de resíduos eletroeletrônicos em uma série de ações de abordagem direta e sensibilização. Para o cumprimento da Meta 8, o programa organiza três grandes modalidades de campanhas de educação ambiental: (a) caravanas de descarte; (b) gincanas nas escolas; (c) exibições ou mostras. Dos três tipos de campanha, apenas (a) e (b) são formalmente documentados pelo Plano de Trabalho. O tipo (c) foi relatado informalmente em uma das reuniões que tivemos com funcionários da Programando o Futuro.

A Meta 9 visa aumentar o volume de coleta e processamento de lixo eletrônico oriundo da administração pública capacitando gestores de patrimônios de órgãos públicos do Estado de Goiás. Através de um Workshop de Movimentação de Bens, o programa Sukatech busca educar gestores de patrimônio sobre os caminhos processuais para que o patrimônio estatal que chegou ao fim de sua vida útil, explicando como esses equipamentos podem ser processados pelo programa Sukatech através de ações de desfazimento ou redirecionamento (regidas pelo Eixo 1 - Cadeia Produtiva) de forma continuada através de parcerias com órgãos públicos. O Eixo 3 se estabelece, portanto, como uma das portas de entrada para o início do fluxo de desfazimento do Eixo 1.

#### Políticas operacionais e restrições
O Plano de Trabalho 2024-2026 estabelece a realização de, no mínino, 6 campanhas de educação ambiental durante a sua regência. Há uma sugestão de priorização de municípios de acordo com a sua expressividade populacional no estado: Goiânia, Aparecida de Goiânia, Anápolis, Rio Verde, Águas Lindas de Goiás, Luziânia, Valparaíso e Senador Canedo. No entanto, municípios que não foram citados podem requisitar a visita de campanhas do programa Sukatech através de uma solicitação de parceria pelas suas prefeituras. Uma equipe itinerante cria um Ponto de Entrega Voluntária (PEV) temporário em uma região da cidade onde a população pode direcionar todos o seu lixo eletrônico. Essa ação, portanto, também é uma das portas de entrada para o início do fluxo de campanha do Eixo 1.

As gincanas nas escolas deverão acontecer em até 30 escolas do estado. Os critérios de seleção de escolas são: (a) escolas públicas próximas aos polos Sukatech criados ao longo da implementação do programa; (b) escolas públicas que possuam formação em tecnologia e informática em sua grade ou currículo; (c) escolas das cidades onde forem realizadas as Caravanas do Descarte; (d) escolas que tenham interesse em conhecer o programa. O roteiro de atividades pedagógicas é construído pela Secretaria de Estado de Ciência, Tecnologia e Inovação (SECTI) em parceria com a Secretaria de Estado de Educação (SEDUC).

As gincanas englobam a realização de palestras sobre a importância do lixo eletrônico e a aplicação de atividades lúdicas e interdisciplinares, adaptadas a cada faixa etária. Essa ação também é uma das portas de entrada para o início do fluxo de campanha do Eixo 1, uma vez que é realizada a coleta de lixo eletrônico entre turmas das escolas. Há um incentivo de premiação para turmas ou escolas que recolherem a maior quantidade de resíduos, atribuindo-se pontuação específica para cada tipo de lixo eletrônico recolhido. Embora o Plano de Trabalho 2024-2026 sugira uma premiação em computadores ou outros aparelhos recondicionados, encontramos relatos de premiação com pizza ou passeios.

Para a Meta 9, o Plano de Trabalho 2024-2026 estabelece uma frequência de um workshop de capacitação por ano. Esse workshop pode ser oferecido em duas modalidades: (a) presencial (b) online. O workshop envolve a apresentação do Decreto Estadual Nº 9.718 que regulamenta o programa Sukatech, destacando o programa como parceiro logístico para a destinação de lixo eletrônico da administração pública do estado. Os critérios de priorização de órgãos públicos do estado são: (a) órgãos de maior estrutura administrativa; (b) órgãos com maior volume de produção de material eletroeletrônico residual.

#### Partes envolvidas
##### Instituições
- Secretaria de Estado de Ciência, Tecnologia e Inovação (SECTI);
- Secretaria de Estado de Educação (SEDUC);
- Programando o Futuro (na figura operacional do programa Sukatech);
- Prefeituras de municípios goianos;
- Escolas de municípios goianos.

##### Personas
- **Coordenador da Secretaria de Estado de Ciência, Tecnologia e Inovação (SECTI):** Estrutura e coordena ações institucionais. Ponte entre o Programa Sukatech e a SEDUC.
- **Coordenador da Secretaria de Estado de Educação (SEDUC):** Estrutura ações pedagógicas interdisciplinares e adaptáveis para diversas faixas de idade.
- **Coordenador de Eventos do Programa Sukatech:** Coordena e gerencia todas as campanhas realizadas pelo Programa Sukatech. Organiza a Agenda de Eventos. Preenche a planilha de prestação de contas.
- **Representante da Prefeitura:** Solicita e facilita parcerias com o Programa Sukatech em nível municipal.
- **Representante da Escola:** Solicita e facilita parcerias com o Programa Sukatech em nível de escola.
- **Educador:** Atua em campanhas como a ponte entre educação ambiental e educandos. Coordena atividades educativas, faz ou facilita palestras e rodas de discussão.
- **Educando:** Participa de atividades educativas. Subcategorias:
  - **Estudante:** Participante de gincanas nas escolas.
  - **Gestor de patrimônio:** Participante de Workshop de Movimentação de Bens e/ou outras ações educativas.
  - **População geral:** Participante de caravanas de descarte e/ou outras ações educativas.

#### Modos de operação
##### Gincanas nas Escolas
![Diagrama BPMN descrevendo o caminho de realização de Gincanas nas Escolas.](/BPMNs/BPMN_-_Eixo_3_-_Gincana_nas_Escolas.png)

##### Caravanas de Descarte
![Diagrama BPMN descrevendo o caminho de realização de Caravanas de Descarte.](/BPMNs/BPMN_-_Eixo_3_-_Caravanas_de_Descarte.png)

##### Capacitação Institucional
![Diagrama BPMN descrevendo o caminho de realização de Capacitação Institucional.](/BPMNs/BPMN_-_Eixo_3_-_Capacitação_Institucional.png)

#### Objetivos específicos, indicadores e fontes
##### Meta 8 - Campanhas Educacionais
###### Objetivos específicos
- **M08OE1:** Realização de no mínimo 6 ações de conscientização ambiental;
- **M08OE2:** Realização de gincanas educacionais em pelo menos 30 escolas;
- **M08OE3:** Realização das caravanas do descarte.

###### Indicadores
- Número de eventos realizados;
- Número de instituições beneficiadas;
- Número de pessoas atendidas;
- Número de cidades atendidas.

###### Fontes
- Agenda de Eventos.

##### Meta 9 - Capacitação Institucional
###### Objetivos específicos
- **M09OE1:** Capacitação dos gestores de patrimônio de órgãos públicos em relação à destinação de resíduos eletrônicos.

###### Indicadores
- Número de workshops realizados;
- Número de órgãos participantes;
- Número de parcerias firmadas.

###### Fontes
- Agenda de Eventos.

### Eixo Transversal - Avaliação
#### Contexto, objetivos, e escopo
O Eixo Transversal - Avaliação nasce da necessidade de um processo contínuo de avaliação do programa Sukatech. O Plano de Trabalho 2024-2026 cita os seguintes problemas como os mais latentes da falta de monitoramento de programas públicos:
1. Erros cíclicos, ou seja, erros que se perpetuam sem detecção nas iterações de atividades do programa;
2. Dispêndio ineficiente de recursos;
3. Resultados abaixo do esperado.

Para atacar essa problemática, o programa Sukatech criou a Meta 10 - Aperfeiçoamento do Processo de Avaliação do Programa com o objetivo geral de elaborar ferramentas intuitivas de avaliação. Conforme estabelecido no acordo de responsabilidade pela operação do programa Sukatech, a organização Programando o Futuro deve enviar, mensalmente, dados estruturados relacionados a indicadores de execução dos três eixos de trabalho do programa: Cadeia Produtiva (Eixo 1), Capacitação e Empreendedorismo (Eixo 2), e Educação Ambiental (Eixo 3). O compartilhamento desses dados semi estruturados para a SECTI é realizado através do preenchimento manual mensal de uma planilha única hospedada na plataforma Google Drive. Essa planilha armazena todas as métricas históricas do programa desde 2021 divididas em 13 abas.

Os dados que alimentam a planilha em questão são coletados nos diversos processos executados dos supracitados três eixos de trabalho, e representam um conjunto de interações com o sistema de gestão da Programando o Futuro e/ou artefatos de facilitação de atividades relacionadas. Esses dados semi estruturados são, então, utilizados pela Programando o Futuro e pela SECTI para monitorar o programa Sukatech e elaborar relatórios de prestação de contas, desempenho e diagnóstico.

#### Políticas operacionais e restrições

O trânsito de dados semi estruturados entre a sede da Sukatech, gerenciada pela organização Programando o Futuro, e a SECTI é realizada através de uma planilha com várias abas na plataforma Google Drive. A inserção dos dados relacionados a métricas do programa Sukatech é feita de forma manual, uma vez ao mês. Essa planilha é uma o resultado da consolidação de planilhas separadas de monitoramento de cada eixo fornecidas pelo seu coordenador responsável.

Mensalmente, um servidor da SECTI realiza uma visita ao CRC sem aviso prévio para monitorar as atividades do programa Sukatech. A visita resulta na escrita de um relatório de visita técnica.

Trimestralmente, a Programando o Futuro entrega um relatório à SECTI contendo:

1. Relatório de impacto ambiental dos resíduos coletados e encaminhados para reciclagem/recondicionamento
2. Relatório de todas as atividades educacionais desenvolvidas no CRC;
3. Relatório dos equipamentos eletroeletrônicos inservíveis que entraram no CRC;
4. Relatório dos equipamentos eletroeletrônicos que foram recondicionados e qual o local de doação;
5. Relatório descritivo com detalhamento das ações dos polos descentralizados;
6. Relatório fotográfico com detalhamento das adequação do espaço físico dos polos descentralizados;
7. Relatório Fotográfico dos cursos em andamento e das aulas práticas;
8. Cópia do material pedagógico utilizado nos cursos oferecidos no CRC;
9. Cópia dos certificados entregues aos alunos concluintes dos cursos de capacitação com a devida comprovação de carga horária cumprida pelos alunos;
10. Relatório descritivo das campanhas com detalhamento dos quantitativos arrecadados, número de pessoas envolvidas, impactos gerados;
11. Relatório descritivo das atividades envolvendo as gincanas, com detalhamento do material pedagógico utilizado, detalhamento das ações desenvolvidas, detalhamento dos membros da comunidade escolar envolvidos na ação.

A SECTI também é provocada a fornecer relatórios respondendo a perguntas com recortes específicos (e.g. "Como o programa Sukatech impacta mulheres goianas?") em um curto prazo. Essas análises são realizadas empregando técnicas de filtros de campos específicos (e.g. sexo de discentes) e conhecimento organizacional.

#### Partes envolvidas
##### Instituições
- Secretaria de Estado de Ciência, Tecnologia e Inovação (SECTI);
- Programando o Futuro (na figura operacional do programa Sukatech).

##### Personas
- **Coordenador de eixo:** Consolida dados mensais do eixo.
- **Consolidador de dados:** Realiza a checagem, limpeza e consolidação dos dados fornecidos pelo coordenador de eixo. Analisa dados consolidados para criar relatórios.
- **Coordenador da SECTI:** Monitora da planilha compartilhada. Analisa dados consolidados para criar relatórios.

#### Modos de operação
##### Consolidação, trânsito e processamento de dados
![Diagrama BPMN descrevendo o caminho da consolidação, trânsito, e processamento de dados.](/BPMNs/BPMN_-_Eixo_Transversal_-_Consolidação_e_Trânsito_de_Dados.png)

#### Objetivos específicos, indicadores e fontes
##### Meta 10 - Aperfeiçoamento do processo de Avaliação do Programa
###### Objetivos específicos
- **M10OE1:** Aperfeiçoamento da ferramenta de gestão utilizada pela Programando o Futuro, implementando:
  - **M10OE1.1:** Acesso em tempo real aos dados de entrada, desmanufatura e recondicionamento;
  - **M10OE1.2:** Preenchimento de processos SEI de desfazimento por servidores da SECTI;
  - **M10OE1.2:** Área de autopreenchimento de solicitações de entidades do terceiro setor para aquisição de material recondicionado.
- **M10OE2:** Criação de planilha de gestão centralizada de Gestão Educacional, monitorando:
  - Inscrição de alunos;
  - Alunos matriculados (e os respectivos documentos pessoais);
  - Alunos desistentes;
  - Alunos aprovados;
  - Diário de classe;
  - Plano de curso;
  - Documentos pessoais de professores.
- **M10OE3:** Criação do formulário online de avaliação socioeconômica a ser aplicado no primeiro dia de aula em sala, desenvolvido de acordo com critérios do Goiás Fomento.
- **M10OE4:** Criação da planilha centralizada de Educação Ambiental.
- **M10OE5:** Desenvolvimento de metodologia de avaliação de impacto socioambiental.
  - **M10OE5.1:** Avaliação de indicadores de coleta, tratamento e redesignação de resíduos e materiais eletroeletrônicos e plástico (avaliação de impactos ambientais);
  - **M10OE5.2:** Avaliação de indicadores educacionais (avaliação de impactos sociais diretos e indiretos);
  - **M10OE5.3:** Avaliação de indicadores de atividades (avaliação operacional - avaliação de impacto social direto e indireto).
- **M10OE6:** Desenvolvimento de um Dashboard (BI) para acompanhamentos de dados quantitativos.

###### Indicadores

Não encontramos indicadores de avaliação da implementação da Meta 10 definidos pelo Plano de Trabalho 2024-2026.

###### Fontes

Não encontramos fontes para os indicadores de avaliação da implementação da Meta 10, uma vez que não encontramos indicadores definidos pelo Plano de Trabalho 2024-2026.

## Justificativa para mudanças
### Mudanças desejadas
### Prioridades
### Mudanças consideradas, mas não incluídas
### Suposições e limitações
## Conceitos do sistema proposto—*to be*
Elegemos o Eixo Transversal - Avaliação como o nosso eixo de interesse para a proposta de um sistema *to be*, uma vez que ele foi instituído como eixo monitor de todos os eixos de operação do programa.

[Pontos-chave:
- Breve descrição da história de GQM e Estratégias GQM+.
- Listagem de objetivos do emprego de Estratégias GQM+.
- Listagem de exemplos de outros trabalhos com o emprego de Estratégias GQM+.
- Argumentação sobre por que consideramos Estratégias GQM+ um método adequado para o programa Sukatech.]
- Exposição do escopo da Prova de Conceito desenvolvida por nós residentes.
- Descrição da aplicação de Estratégias GQM+ em metas do Eixo 2 monitoradas pelo Eixo Transversal.]

## Cenários operacionais
[Pontos-chave:
- Recomendações para momentos de aplicação das Estratégias GQM+.
- Recomendações para ordens de aplicação das Estratégias GQM+.
- Descrição de elementos dos modelos das Estratégias GQM+.
- Descrição de aplicação das Estratégias GQM+ através da Prova de Conceito.
- Instruções de aplicação dos artefatos das Estratégias GQM+.]

## Impactos
[Pontos-chave:
- Descoberta de dados ainda não monitorados pela gestão.
- Descoberta de dados sub-utilizados ou não utilizados pela gestão.
- Estabelecimento de processos de medição e monitoramento.
- Estabelecimento de processos de tomada de decisão.]

## Análise do sistema proposto
### Benefícios
[Pontos-chave:
- Costura entre Estratégias GQM+ e inovação frugal.
- Expansão de argumentação de gestão enxuta com Estratégias GQM+.]
### Desvantagens e limitações
[Pontos-chave:
- Aplicação de Estratégias GQM+ precisa ser apoiada por processos de medição e tomada de decisão.
- Mudanças operacionais são necessárias para a efetividade da medição e tomada de decisão.
- Estratégias GQM+ são um _primeiro passo_ de um grande processo de amadurecimento do programa.]
## Apêndices
### Apêndice A - Referências-chave
### Políticas operacionais e restrições
### Descrição
### Modos de operação
### Classes de usuário
#### Estrutura organizacional
#### Perfis de classes de usuário
#### Interações entre classes de usuário
#### Outros atores envolvidos
#### Ambiente de apoio
## Cenários operacionais
## Impactos
### Impactos operacionais
### Impactos organizacionais
### Impactos durante o desenvolvimento
## Análise do sistema proposto
### Benefícios
### Desvantagens e limitações
### Alternativas consideradas
## Apêndices
### Apêndice A - Referências-chave
1. Plano de Disciplina 2025-1 para a Residência em Sistemas de Informação, código 10000184, associado à Matriz Curricular SIINF-BN-2 - 2017.1;
2. Relatório da visita técnica do Squad 2 à sede do programa Sukatech no Bairro Floresta, realizada no dia 27 de março de 2025;
3. Edital de Chamamento Público nº 01/2020-SEDI, publicado em 27 de novembro de 2020;
4. Plano de Trabalho 2024-2026 do Programa Sukatech, fornecido por Thiago Angelino em 28 de março de 2025;
5. Planilha de consolidação de dados históricos do programa Sukatech, fornecida por Thiago Angelino em 28 de março de 2025;
6. Relatórios de discussões do Squad 2 com partes interessadas do programa Sukatech, realizada nos dias 07 e 08 de abril de 2025;
### Apêndice B - Conceitos-chave e suas definições
### Apêndice C - Acrônimos e abreviações
- INF/UFG: Instituto de Informática da Universidade Federal de Goiás
- SECTI: Secretaria de Estado de Ciência, Tecnologia e Inovação
- SEDUC: Secretaria de Estado da Educação
- UFG: Universidade Federal de Goiás

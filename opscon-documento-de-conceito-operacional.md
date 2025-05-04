# Documento de Conceito Operacional (OpsCon): Sukatech

## Prefácio

## Escopo

### Identificação

### Visão geral do documento

### Visão geral do sistema

## Referência documental

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
![Fluxo de Desfazimento](https://raw.githubusercontent.com/contraexemplo/RTSI-2025/feature/eixo1-especificacoes/processos/BPMN_-_Eixo_3_-_Desfazimento_Coleta.svg)
- **Fluxo de Triagem e Classificação**
![Fluxo de Triagem](https://raw.githubusercontent.com/contraexemplo/RTSI-2025/feature/eixo1-especificacoes/processos/BPMN_-_Eixo_3_-_Triagem_Recondicionamento_Desmanufatura.svg)


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

### Eixo 2 - Capacitação e Empreendedorismo
#### Contexto, objetivos, e escopo
#### Políticas operacionais e restrições
#### Descrição
#### Modos de operação
#### Classes de usuário
##### Estrutura organizacional
##### Perfis de classes de usuário
##### Interações entre classes de usuário
##### Outros atores envolvidos
##### Ambiente de apoio

### Eixo 3 - Campanha Ambiental
#### Contexto, objetivos, e escopo
#### Políticas operacionais e restrições
#### Descrição
#### Modos de operação
#### Classes de usuário
##### Estrutura organizacional
##### Perfis de classes de usuário
##### Interações entre classes de usuário
##### Outros atores envolvidos
##### Ambiente de apoio

### Eixo Transversal - Avaliação
#### Contexto, objetivos, e escopo
#### Políticas operacionais e restrições
#### Descrição
#### Modos de operação
#### Classes de usuário
##### Estrutura organizacional
##### Perfis de classes de usuário
##### Interações entre classes de usuário
##### Outros atores envolvidos
##### Ambiente de apoio

## Justificativa para mudanças
### Mudanças desejadas
### Prioridades
### Mudanças consideradas, mas não incluídas
### Suposições e limitações
## Conceitos do sistema proposto—*to be*
### Contexto, objetivos, e escopo
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
## Glossário

## Versões

|    Versão |  Publicação           | Comentários |
|-----------|-----------------------|-------------|
|     1.1   | 28 de abril de 2025   | Expansão de seções. Separação explícita entre sistema *as is* e sistema *to be*. |
|           |                       |             |
|           |                       |             |

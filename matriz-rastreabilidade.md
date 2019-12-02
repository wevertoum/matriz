## Matriz de rastreabilidade de Requisitos do sistema

### 1 - Problema

| ID    | Nome | O Problema é | Afeta | Cujo Impacto é |
|-------|------|--------------|-------|----------------|
| PB 01 | Gerar Relatórios | Dificuldade de organizar os relatórios e acompanhamentos efetuados no CAPS | Agilidade na geração dos relatórios | Atraso nas Entregas dos resultados |
| PB 02 | Controlar pacientes | Dificuldade em controlar fluxo de pacientes no CAPS | Organização interna | Disponibilidade das vagas |

## 2 - Necessidades

| ID | Nome | Necessidade | Solução atual |
|----|------|-------------|---------------|
| NE 01 | Diagnosticar distúrbios | Diagnosticar distúrbios psicológicos | Entrevistas registradas manualmente |
| NE 02 | Aplicar Métodos | Aplicar métodos de reabilitação | Seleção manual dos métodos técnicos |
| NE 03 | Fazer encaminhamentos | Fazer encaminhamentos dos necessitados | Triagem manual dos pacientes |
| NE 04 | Acompanhar a evolução | Acompanhar a evolução do tratamento dos pacientes | Acompanhamento registrado em planilhas do excel |

## 3 - Características

| ID       | Nome | Característica |
|----------|------|----------------|
|   CA 01  | Encaminhamento do SUS | O paciente é encaminhado pelo SUS |
|   CA 02  | Análise do grau de disturbio | Feito uma analise do grau do distúrbio psicológico |
|   CA 03  | Encaminhamento para especialistas | Feito o encaminhamento para especialistas que irão cuidar do paciente |

## 4 - Requisitos Funcionais

| ID    | Requisito Funcional |Observação|
|-------|---------------------|----------|
| RF 01 | O usuário deve ser capaz de lorem ipsum |          |
| RF 02 | O usuário deve ser capaz de lorem ipsum |          |
| RF 03 | O usuário deve ser capaz de lorem ipsum |          |
| RF 04 | O usuário deve ser capaz de lorem ipsum |          |
| RF 05 | O usuário deve ser capaz de lorem ipsum |          |
| RF 06 | O usuário deve ser capaz de lorem ipsum |          |
| RF 07 | O usuário deve ser capaz de lorem ipsum |          |
| RF 08 | O usuário deve ser capaz de lorem ipsum |          |
| RF 09 | O usuário deve ser capaz de lorem ipsum |          |
| RF 10 | O usuário deve ser capaz de lorem ipsum |          |
| RF 11 | O usuário deve ser capaz de lorem ipsum |          |
| RF 12 | O usuário deve ser capaz de lorem ipsum |          |

## 4.1 - Requisitos Não-Funcionais
| ID    | Requisito Não-Funcional |
|-------|-------------------------|
| RNF 01 | O sistema deve lorem ipsum lorem ipsum |
| RNF 02 | O sistema deve lorem ipsum lorem ipsum |
| RNF 03 | O sistema deve lorem ipsum lorem ipsum |
| RNF 04 | O sistema deve lorem ipsum lorem ipsum |
| RNF 05 | O sistema deve lorem ipsum lorem ipsum |


## 5 - Casos de Uso

|Identificador|Nome|Descrição|
|-------------|----|---------|
|     UC01    | Cadastrar paciente | Um funcionario cadastra pacientes do CAPS esperança com os dados da ficha técnica padrão já existente em papel. |
|     UC02    | Cadastrar Psicólogo | Um funcionario cadastra psicólogos do CAPS Esperança com os dados da ficha técnica padrão já existente em papel. |
|     UC03    | Cadastrar Assistente social | Um funcionario cadastra assistentes sociais do CAPS Esperança com os dados da ficha técnica padrão já existente em papel. |
|     UC04    | Cadastrar relatório de uma sessão | Um psicólogo cadastra das informações levantadas durante uma sessão com um paciente por um psicólogo. |
|     UC05    | Listar histórico de consultas | Gera um relatório das consultas de um paciente |
|     UC06    | Apresentar relatório de indicadores da evolução do paciente | Gera um relatório da evolução do paciente dentre um período de tratamento. |
|     UC07    | Listar histórico de medicamentos | Gera um relatório dos medicamentos utilizados pelo paciente em um período de tratamento. |
|     UC08    | Autenticar acesso de psicólogo | Realiza a autenticação de um psicólogo por meio de seu CRP e senha |
|     UC09    | Autenticar acesso de assistente social | Realiza a autenticação de um assistente social por meio de seu email e senha  |

## 6 - Matriz de rastreabilidade

### 6.1 - Problema X Necessidade 

| | PB01 |  PB02 |
|-|------|-------|
|**NE01**| X |   |
|**NE02**| X |   |
|**NE03**|   | X |
|**NE04**| X |   |



### 6.2 - Necessidade X Característica

|        | NE01 | NE02 | NE03 | NE04 | NE05 |
|--------|------|------|------|------|------|
|**CA01**|  X   |      |      |      |      |
|**CA02**|  X   |      |      |      |      |
|**CA03**|      |   X  |      |      |      |
|**CA04**|      |      |   X  |      |      |
|**CA05**|      |      |   X  |      |      |
|**CA06**|      |      |   X  |      |      |
|**CA07**|      |      |   X  |      |      |
|**CA08**|      |      |      |   X  |      |
|**CA09**|      |      |      |   X  |      |
|**CA10**|      |      |      |   X  |      |
|**CA11**|      |      |      |      |   X  |

### 6.3 - Característica X Requisitos Funcionais

|        | CA01 | CA02 | CA03 | CA04 | CA05 | CA06 | CA07 | CA08 | CA09 | CA10 | CA11 |
|--------|------|------|------|------|------|------|------|------|------|------|------|
|**RF01**|  X   |      |      |      |      |      |      |      |      |      |      |
|**RF02**|      |  X   |      |      |      |      |      |      |      |      |      |
|**RF03**|      |      |      |      |  X   |      |      |      |      |      |      |
|**RF04**|      |      |      |      |  X   |      |  X   |      |      |      |      |
|**RF05**|      |      |      |      |  X   |      |  X   |      |      |      |      |
|**RF06**|      |      |      |      |      |  X   |      |      |      |      |      |
|**RF07**|      |      |      |      |      |  X   |      |      |      |      |      |
|**RF08**|      |      |  X   |      |      |  X   |      |      |      |      |      |
|**RF09**|      |      |      |  X   |      |      |      |      |      |      |      |
|**RF10**|      |      |      |      |      |      |      |  X   |  X   |  X   |      |
|**RF11**|      |      |  X   |      |      |      |      |      |      |      |      |
|**RF12**|      |      |      |      |      |      |      |      |      |      |  X   |

### 6.4 - RF X Caso de uso

|   ID   |RF01|RF02|RF03|RF04|RF05|RF06|RF07|RF08|RF09|RF10|RF11|RF12|
|--------|----|----|----|----|----|----|----|----|----|----|----|----|
|**UC01**|    |    |    |    |    |    |    |    |    |    |    | X  |
|**UC02**|    |    |    |    |    |    |    |    |    |    |    | X  |
|**UC03**| X  |    |    |    |    |    |    |    |    |    |    |    |
|**UC04**|    |    |    |    |    |    |    |    |    | X  |    |    |
|**UC05**| X  |    |    |    |    |    |    |    |    |    |    |    |
|**UC06**| X  | X  |    |    |    |    |    |    |    |    |    |    |
|**UC07**| X  | X  |    |    |    | X  |    |    |    |    |    | X  |
|**UC08**|    | X  |    |    |    |    |    |    |    |    | X  |    |
|**UC09**|    |    |    |    |    |    |    |    |    | X  |    |    |
|**UC10**|    |    |    |    |    |    |    |    | X  |    |    |    |
|**UC11**|    |    | X  | X  | X  |    |    |    |    |    |    |    |
|**UC12**|    |    | X  | X  | X  |    |    |    |    | X  |    |    |
|**UC13**|    |    |    | X  |    |    |    |    |    |    |    |    |
|**UC14**|    |    |    |    | X  |    |    |    |    |    |    |    |
|**UC15**|    |    | X  |    |    |    |    |    |    |    |    |    |
|**UC16**|    |    |    |    |    | X  |    |    |    |    |    |    |
|**UC17**|    |    |    |    |    |    |    | X  |    |    |    |    |
|**UC18**|    |    |    |    |    |    | X  |    |    |    |    |    |
|**UC19**|    | X  |    |    |    |    |    |    |    |    |    |    |
|**UC20**|    |    | X  |    |    |    |    |    |    |    |    |    |
|**UC21**|    |    |    | X  |    |    |    |    |    |    |    |    |

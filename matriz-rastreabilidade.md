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
| RF 01 | O sistema deve permitir o cadastro de pacientes do CAPS esperança com os dados da ficha técnica padrão já existente em papel. |          |
| RF 02 | O sistema deverá permitir o cadastro de psicólogos do CAPS Esperança com os dados da ficha técnica padrão já existente em papel. |          |
| RF 03 | O sistema deverá permitir o cadastro de assistentes sociais do CAPS Esperança com os dados da ficha técnica padrão já existente em papel. |          |
| RF 04 | O sistema deverá permitir o cadastro das informações levantadas durante uma sessão com um paciente por um psicólogo. |          |
| RF 05 | O sistema deverá gerar um relatório das consultas de um paciente, podendo ser filtradas por data ou geral. |          |
| RF 06 | O sistema deverá gerar um relatório da evolução do paciente dentre um período de tratamento. |          |
| RF 07 | O sistema deverá gerar um relatório dos medicamentos utilizados pelo paciente em um período de tratamento. |          |
| RF 08 | O sistema deverá realizar a autenticação de um psicólogo por meio de seu CRP e senha |          |
| RF 09 | O sistema deverá realizar a autenticação de um assistente social por meio de seu email e senha |          |

## 4.1 - Requisitos Não-Funcionais
| ID    | Requisito Não-Funcional |
|-------|-------------------------|
| RNF 01 | O sistema deverá estar disponível apenas dentro da instalação do CAPS Esperança |
| RNF 02 | O sistema deve oferecer acesso por meio da rede interna do CAPS Esperança |
| RNF 03 | O sistema deve poder ser utilizado em dispositivos móveis e em desktop |
| RNF 04 | O sistema deve disponibilizado sem a necessidade de instalar o mesmo. 


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

|        | NE01 | NE02 | NE03 | NE04 |
|--------|------|------|------|------|
|**CA01**|  X   |      |  X   |      |
|**CA02**|  X   |      |      |   X  |      
|**CA03**|      |   X  |      |      | 

### 6.3 - Característica X Requisitos Funcionais

|        | CA01 | CA02 | CA03 |
|--------|------|------|------|
|**RF01**|  X   |      |      |
|**RF02**|      |  X   |      |
|**RF03**|      |   X  |      |
|**RF04**|   X  |      |      |
|**RF05**|      |      | X    |
|**RF06**|   X  |      |      | 
|**RF07**|      |      |  X   | 
|**RF08**|      |      |  X   | 
|**RF09**|   X  |      |      |

### 6.4 - RF X Caso de uso

|   ID   |RF01|RF02|RF03|RF04|RF05|RF06|RF07|RF08|RF09|
|--------|----|----|----|----|----|----|----|----|----|
|**UC01**|    |    |    |    |  X |    |    |    |    | 
|**UC02**|    |    |  X |    |    |    |    |    |    | 
|**UC03**| X  |    |    |    |    |    |    |    |    |  
|**UC04**|    |    |  X |    |  X |    |    |    |    | 
|**UC05**| X  |    |    |    |    |    |    |    |    |  
|**UC06**| X  | X  |    |    |    |    |    |    |    |  
|**UC07**| X  | X  |    |    |    | X  |    |    |    |  
|**UC08**|    | X  |    |    |    |    |    |    |    |  
|**UC09**|    |    |  X |    |  X |    |    |    |    | 

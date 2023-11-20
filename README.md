# **Projeto Integrador Grupo 07**

Esse repósitorio faz parte do Projeto Integrador: Desenvolvimento de Sistemas Orientado a Objetos

# **Diagrama de Classe**

![Diagrama de Classe](https://github.com/rodrigoo-soouza/Projeto_Integrador_Grupo07/blob/main/Diagrama%20de%20Classe.png)

# **Diagrama de Caso**

![Diagrama de Caso](https://github.com/rodrigoo-soouza/Projeto_Integrador_Grupo07/blob/main/Diagrama%20de%20Caso.png)

# **Visão Geral da Proposta**

## **Levantamento de Requisitos**

- Analisar e entender os requisitos funcionais e não funcionais de cada caso de uso.

- A fase de Levantamento de Requisitos é crucial para entender as necessidades dos atores principais, como administradores, usuários e alunos.

- O caso de uso requer uma compreensão clara dos requisitos para diferentes tipos de cadastros (Pessoa Física, Pessoa Jurídica, Professor, Fornecedor).

##	**Projeto e Arquitetura**

- Desenhar a estrutura do sistema para suportar os casos de uso.

- Projetar a interface do usuário para facilitar a interação.

- O "Lançar Notas" por exemplo destaca a importância de projetar uma área de lançamento de notas eficiente.

## **Implementação**

- Desenvolver os módulos específicos para cada caso de uso.

- Implementar a lógica de negócios para gerenciar cadastros, autenticação, matrículas, e lançamento de notas.

- Realizar testes unitários para garantir a funcionalidade correta de cada componente.

## **Testes**

- Realizar testes de sistema para garantir a integração adequada entre os diferentes casos de uso.

- Executar testes de aceitação com os usuários finais para validar a usabilidade.

- No Caso de Uso "Consultar Notas", é vital testar alternativas, como notas não liberadas ou inacessíveis devido a problemas técnicos.

## **Implementação de Alterações e Correções**

- Incorporar feedback dos testes para fazer melhorias.

- Corrigir bugs ou problemas identificados durante os testes.

- Manter uma abordagem iterativa para aprimorar continuamente o sistema.

## **Documentação**

- Confecção de documentação abrangente para os usuários finais e desenvolvedores.

- Documentar os procedimentos de uso, requisitos e a arquitetura do sistema.

## **Implantação**

- Realizar a implantação do sistema em um ambiente de produção.

- Garantir uma transição suave do ambiente de desenvolvimento para produção.

- Monitorar o desempenho e corrigir quaisquer problemas que possam surgir.

## **Manutenção e Suporte**

- Fornece suporte contínuo para resolver problemas pós-implantação.

- Realizar atualizações conforme necessário para atender a novos requisitos.

- Monitorar o desempenho e a segurança do sistema de maneira contínua.

# **Contextualização e Motivação**

No cenário atual da educação, a tecnologia desempenha um papel crucial na facilitação do aprendizado e na gestão acadêmica. Diante desse contexto, propomos o desenvolvimento de um site para uma universidade, visando otimizar a interação entre professores e alunos, além de proporcionar uma experiência educacional mais integrada e eficiente.

## **Cenário Educacional Brasileiro:**

O sistema educacional brasileiro está em constante evolução, e as instituições de ensino superior enfrentam desafios significativos para se adaptarem às demandas modernas. A transformação digital é essencial para superar esses desafios, tornando a aprendizagem mais acessível, dinâmica e envolvente.

## **Necessidade de Uma Plataforma Integrada:**

A complexidade da administração acadêmica e a diversidade de cursos e disciplinas exigem uma plataforma que centralize informações e promova uma comunicação eficiente entre docentes e discentes. Nosso site visa preencher essa lacuna, proporcionando uma solução abrangente e intuitiva para a comunidade acadêmica.

## **Benefícios Esperados:**

Ao criar essa plataforma, buscamos promover a eficiência operacional, melhorar a comunicação, e aprimorar a experiência de aprendizado. A digitalização de processos burocráticos e a criação de espaços virtuais colaborativos são aspectos fundamentais para otimizar o ambiente acadêmico.

# **Objetivos**

## **Objetivos Gerais:**

- Desenvolver um site intuitivo e de fácil navegação.

- Integrar funcionalidades que atendam às necessidades de professores, alunos e administradores.

- Proporcionar um ambiente virtual que promova a interação e colaboração entre os membros da comunidade acadêmica.

## **Objetivos Específicos:**

- Implementar um sistema de gestão acadêmica abrangente, incluindo controle de notas, frequência e horários.
   
- Criar perfis personalizados para professores e alunos, com acesso a informações relevantes de forma segura.

- Integrar um sistema de comunicação eficiente, incluindo fóruns, mensagens diretas e notificações.

- Disponibilizar recursos para o envio e acesso a materiais didáticos, como apresentações, artigos e vídeos.

- Facilitar o processo de inscrição em disciplinas e eventos acadêmicos.

- Implementar medidas de segurança robustas para proteger dados sensíveis.

## **Metas a serem Alcançadas:**

- Redução do tempo dedicado a tarefas administrativas manuais.

- Aumento da participação e interação dos alunos nas atividades virtuais.

- Melhoria na comunicação entre professores e alunos.

- Elevação da eficiência no gerenciamento de informações acadêmicas.


Ao alcançar esses objetivos, aspiramos criar um ambiente virtual que não apenas atenda às demandas atuais da comunidade acadêmica, mas que também sirva como modelo para futuros avanços na educação digital no Brasil.

# **Planejamento para Desenvolvimento da Dolução Proposta:** 
## **Ciclo de vida**
## **Premissas**

### Escopo do Projeto:

- O projeto abrange a gestão de dados de um centro universitário, com foco na utilização da Linguagem de Modelagem Unificada (UML) para desenvolver um sistema eficiente.

- O escopo principal é o cadastro e gestão de diferentes tipos de pessoas, incluindo alunos, professores, e fornecedores, em um ambiente universitário.

### Linguagem de Modelagem Unificada (UML):

- A UML será a principal ferramenta de modelagem utilizada para representar os diferentes aspectos do sistema, incluindo casos de uso, diagramas de classe, e outros artefatos conforme necessário.

### Acesso ao Sistema:

- Os usuários do sistema incluem alunos, professores, pessoas jurídicas e fornecedores. O acesso é controlado por um sistema de login, garantindo a segurança e a privacidade das informações.

### Tipos de Usuário:

- **Alunos:**

Podem visualizar seus perfis, alterar dados pessoais, realizar matrículas em cursos, resolver tarefas, fazer perguntas no fórum, salvar desempenho acadêmico e consultar notas.

- **Pessoa Jurídica (Usuários Administradores):**

Podem visualizar perfis de alunos, alterar dados institucionais e administrativos.

- **Professores (Usuários Administradores):**

Podem visualizar perfis de alunos, alterar dados pessoais, lançar notas, gerenciar tarefas, acessar o fórum e responder a perguntas.

- **Fornecedores (Usuários Administradores):**

Podem alterar dados de fornecedor.

### Segurança e Privacidade:

- O sistema implementa medidas robustas de segurança para proteger dados sensíveis dos alunos, professores, pessoas jurídicas e fornecedores, garantindo conformidade com regulamentações de privacidade.

### Integração com Sistemas Existentes:

- O projeto considera a integração com sistemas existentes na universidade, como sistemas de gerenciamento acadêmico e sistemas administrativos, para garantir consistência e interoperabilidade.

### Atualização de Dados:

- O sistema permite a atualização regular de dados, como informações pessoais dos alunos e informações de cursos, refletindo as mudanças na realidade acadêmica.

### Treinamento de Usuários:

- Um programa de treinamento será desenvolvido para capacitar professores e administradores na utilização eficaz do sistema, visando a redução de erros e a maximização da produtividade.

### Fluxo de Eventos para Alunos:

- O fluxo de eventos para alunos é estruturado, permitindo que eles acessem informações relevantes sobre os cursos, notas e seu progresso acadêmico.

### Caso de Uso: Acessar Notas:

- O caso de uso "Acessar Notas" é direcionado aos alunos, garantindo que apenas alunos autenticados possam visualizar suas notas no sistema.

### Cenário Principal para Acessar Notas:

- O aluno, após autenticação, tem a capacidade de visualizar as suas notas para os cursos matriculados, seguindo um fluxo de eventos estruturado.

### Cenário Alternativo 1 - Notas Não Liberadas pelo Professor:

- Em casos em que as notas não foram liberadas, o sistema orienta o aluno a entrar em contato com o professor para obter informações adicionais.

### Cenário Alternativo 2 - Problemas Técnicos no Acesso às Notas:

- Em situações de problemas técnicos, o sistema fornece uma mensagem de erro clara e instrui o aluno a tentar novamente posteriormente.

### Caso de Uso: Lançar Notas:

- O caso de uso "Lançar Notas" é direcionado aos professores, garantindo que apenas professores autenticados e autorizados possam inserir notas no sistema.

### Cenário Principal para Lançar Notas:

- O professor, após autenticação, tem a capacidade de lançar notas para os alunos em um curso específico, seguindo um fluxo de eventos estruturado.

### Cenário Alternativo 1 - Cancelamento do Lançamento de Notas:

- Caso o professor decida cancelar o lançamento das notas, o sistema confirma a ação e retorna ao estado anterior ao lançamento.

### Cenário Alternativo 2 - Notas Inválidas:

- Em situações de inserção de notas inválidas, o sistema informa o professor sobre o erro, solicitando a correção antes do registro das notas.

## **Requisitos**
## **Planejamento**

# **Prototipação Low Fidelity**

## **Geral com Ligações**

![Geral](https://github.com/rodrigoo-soouza/Projeto_Integrador_Grupo07/blob/main/Diagrama%20de%20Classe.png)


## **Pessoa**



## **Pessoa Jurídica**



## **Aluno**



## **Funcionário**



## **Professor**



## **Fornecedor**

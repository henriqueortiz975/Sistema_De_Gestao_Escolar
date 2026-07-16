# 📚 Sistema de Gestão Escolar


## 2. Descrição do Problema

Muitas escolas enfrentam dificuldades para organizar informações de alunos, professores, turmas, disciplinas, notas e frequência. O uso de processos manuais ou de sistemas separados pode causar atrasos, erros e dificuldade no acesso às informações.

---

## 3. Objetivo do Sistema

Modelar um sistema de gestão escolar capaz de atender às necessidades administrativas e acadêmicas de uma instituição de ensino, servindo como projeto de análise de sistemas.

---

## 4. Público-Alvo

- Direção escolar
- Secretaria
- Professores
- Coordenadores
- Alunos

---

## 5. Tipo de Sistema de Informação

**SIG (Sistema de Informação Gerencial)**

---

## 6. Técnicas de Levantamento de Requisitos

- Entrevistas com direção e secretaria;
- Questionários para professores;
- Observação da rotina escolar;
- Análise de documentos como boletins, históricos e fichas de matrícula.

---

## 7. Requisitos Funcionais

- RF-01 – Cadastrar alunos.
- RF-02 – Cadastrar professores.
- RF-03 – Cadastrar turmas.
- RF-04 – Realizar matrículas.
- RF-05 – Registrar notas.
- RF-06 – Registrar frequência.
- RF-07 – Emitir boletins.
- RF-08 – Gerar relatórios.

---

## 8. Requisitos Não Funcionais

- RNF-01 – O sistema deve possuir controle de acesso por usuário.
- RNF-02 – Deve garantir a integridade dos dados.
- RNF-03 – Deve apresentar interface simples e intuitiva.
- RNF-04 – Deve manter bom desempenho durante as operações.

---

## 9. Regras de Negócio

- Apenas professores podem lançar notas.
- Apenas alunos matriculados podem receber notas e frequência.
- Um aluno não pode estar matriculado duas vezes na mesma turma.
- Apenas administradores podem cadastrar usuários.

---

## 10. Escopo, Premissas e Restrições

### Escopo

O projeto contempla a modelagem das funcionalidades relacionadas ao gerenciamento escolar.

### Premissas

- A escola possui uma estrutura administrativa definida.
- Os requisitos foram levantados junto aos usuários.

### Restrições

- O projeto contempla apenas a documentação e a modelagem do sistema.
- Não haverá desenvolvimento ou implementação do software nesta etapa.

---

## 11. Matriz de Rastreabilidade

| Requisito | Origem |
|-----------|--------|
| RF-01 | Entrevista |
| RF-02 | Entrevista |
| RF-03 | Questionário |
| RF-04 | Observação |
| RF-05 | Entrevista |
| RF-06 | Observação |
| RF-07 | Análise de documentos |
| RF-08 | Entrevista |

---

## 12. Diagrama de Casos de Uso

O diagrama de casos de uso representa as funcionalidades disponíveis no Sistema de Gestão Escolar e os atores que interagem com elas.

O sistema possui três atores principais: Aluno, Professor e Coordenador. O aluno pode realizar login e consultar seu histórico escolar. O professor é responsável por executar as atividades acadêmicas, como lançar notas, registrar frequência, agendar provas, enviar comunicados e visualizar as turmas. Já o coordenador pode visualizar as turmas e gerar relatórios para acompanhamento das atividades da escola.

O diagrama demonstra quais funcionalidades estão disponíveis para cada perfil de usuário e como ocorre a interação entre os usuários e o sistema.

## 13. Diagrama de Classes

O diagrama de classes apresenta a estrutura do Sistema de Gestão Escolar, mostrando suas principais classes, atributos, métodos e relacionamentos.

A classe Usuário serve como classe base, contendo informações comuns, como identificação, nome, e-mail e senha, além das operações de login e logout. Dela derivam as classes Aluno, Professor e Coordenador, cada uma com suas características e responsabilidades específicas.

O sistema também é composto pelas classes Turma, Nota, Frequência, Prova e Relatório, responsáveis por armazenar e gerenciar as informações acadêmicas. Os relacionamentos entre essas classes representam a ligação entre alunos, turmas, professores e os registros de notas, frequência, provas e relatórios, organizando de forma estruturada os dados necessários para o funcionamento do sistema.

## 14. Diagrama de Sequência

O diagrama de sequência apresenta a ordem cronológica das interações entre os atores, o sistema e o banco de dados durante a execução das funcionalidades do projeto. Ele demonstra como as mensagens são enviadas e recebidas entre os componentes, evidenciando o fluxo de comunicação necessário para atender às solicitações dos usuários.

Por meio desses diagramas, é possível compreender o comportamento dinâmico do sistema, identificando a sequência de operações, as validações realizadas, as consultas ao banco de dados e os retornos enviados aos usuários. Essa representação auxilia na visualização do funcionamento interno do sistema, garantindo maior clareza sobre a lógica de execução e a integração entre seus componentes.

## Autor

**Arthur da Silva Veeck**

**Henrique Ibarra Ortiz Urbano**

**Rafael Paffrath Pires**

Disciplina: Análise de Sistemas

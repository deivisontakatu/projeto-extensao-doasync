# Organização das Equipes — Projeto de Extensão DoaSync

## 1. Objetivo

Organizar os alunos participantes do projeto de extensão **DoaSync** em equipes multidisciplinares, distribuindo responsabilidades de acordo com os interesses, conhecimentos e experiências informados pelos participantes.

A organização busca aproximar o funcionamento do projeto de uma equipe real de desenvolvimento de software, permitindo que os alunos atuem em diferentes etapas do ciclo de desenvolvimento.

---

## 2. Estrutura geral

O projeto será organizado em **5 grupos de trabalho**, cada um responsável por uma parte específica da solução.

A divisão proposta é:

| Grupo      | Área                          | Principal responsabilidade                   |
| ---------- | ----------------------------- | -------------------------------------------- |
| 🟦 Grupo 1 | Produto, Usuários e Entidades | Requisitos, UX e definição do produto        |
| 🟩 Grupo 2 | Campanhas                     | Desenvolvimento do módulo de campanhas       |
| 🟨 Grupo 3 | Doações                       | Desenvolvimento do fluxo de doações          |
| 🟧 Grupo 4 | Gestão e Dashboard            | Gestão, indicadores e relatórios             |
| 🟥 Grupo 5 | Plataforma e Qualidade        | Banco, APIs, testes, infraestrutura e deploy |

A divisão por módulos permite que cada equipe tenha uma **entrega concreta**, evitando que os alunos sejam separados apenas por tecnologia.

---

# 3. Grupo 1 — Produto, Usuários e Entidades

## Objetivo

Responsável por compreender as necessidades dos usuários e das entidades atendidas pelo DoaSync e transformar essas necessidades em funcionalidades do sistema.

## Principais atividades

* Levantamento de requisitos;
* Identificação das necessidades das entidades;
* Histórias de usuário;
* Critérios de aceite;
* Organização do backlog;
* Priorização de funcionalidades;
* Protótipos;
* UX/UI;
* Documentação;
* Validação das funcionalidades com os usuários.

## Funcionalidades relacionadas

* Cadastro de usuários;
* Login;
* Perfil;
* Cadastro de entidades;
* Informações da APAE;
* Informações da Associação Amor Inclusivo;
* Permissões e tipos de usuário.

## Perfis recomendados

* Product Owner;
* Requisitos;
* UX/UI;
* Front-end;
* Back-end.

---

# 4. Grupo 2 — Campanhas

## Objetivo

Desenvolver o módulo responsável pela criação, divulgação e gerenciamento das campanhas de arrecadação.

## Principais atividades

* Criar campanhas;
* Editar campanhas;
* Publicar campanhas;
* Encerrar campanhas;
* Exibir campanhas disponíveis;
* Página de detalhes;
* Busca e filtros;
* Imagens e informações da campanha;
* Integração com APIs;
* Persistência dos dados.

## Funcionalidades relacionadas

```text
Campanhas
├── Criar campanha
├── Editar campanha
├── Publicar campanha
├── Encerrar campanha
├── Visualizar campanha
├── Buscar campanha
└── Compartilhar campanha
```

## Perfis recomendados

* Front-end;
* Back-end;
* Banco de Dados;
* APIs;
* QA.

---

# 5. Grupo 3 — Doações

## Objetivo

Desenvolver o principal fluxo de interação entre o doador e as entidades assistenciais.

## Principais atividades

* Seleção da campanha;
* Processo de doação;
* Registro da doação;
* Histórico;
* Status da doação;
* Comprovantes;
* Integrações;
* Validação do processo;
* Testes.

## Fluxo esperado

```text
Doador
   ↓
Escolhe campanha
   ↓
Visualiza informações
   ↓
Inicia doação
   ↓
Realiza contribuição
   ↓
Doação registrada
   ↓
Confirmação
   ↓
Histórico
```

## Perfis recomendados

* Front-end;
* Back-end;
* APIs/Integrações;
* Banco de Dados;
* QA.

---

# 6. Grupo 4 — Gestão e Dashboard

## Objetivo

Desenvolver as funcionalidades utilizadas pelas entidades e administradores para acompanhar os resultados da plataforma.

## Principais atividades

* Dashboard;
* Indicadores;
* Relatórios;
* Gestão de campanhas;
* Gestão de doações;
* Gestão de entidades;
* Visualização de dados;
* Estatísticas;
* Exportação de informações.

## Indicadores possíveis

| Indicador              | Objetivo                   |
| ---------------------- | -------------------------- |
| Número de entidades    | Medir expansão             |
| Número de doadores     | Avaliar alcance            |
| Número de doações      | Medir utilização           |
| Valor arrecadado       | Avaliar impacto financeiro |
| Número de campanhas    | Acompanhar arrecadações    |
| Usuários ativos        | Avaliar utilização         |
| Entidades beneficiadas | Medir impacto social       |
| Taxa de conclusão      | Avaliar eficiência         |

## Perfis recomendados

* Front-end;
* Banco de Dados;
* Back-end;
* UX/UI;
* Análise de dados.

---

# 7. Grupo 5 — Plataforma e Qualidade

## Objetivo

Garantir que os módulos desenvolvidos pelas demais equipes estejam integrados, testados e disponíveis para utilização.

## Principais atividades

### Banco de Dados

* Modelagem;
* Tabelas;
* Relacionamentos;
* Consultas;
* Integridade dos dados.

### APIs

* APIs REST;
* Integrações;
* Comunicação entre sistemas;
* Padronização de respostas;
* Documentação.

### DevOps

* Git/GitHub;
* Branches;
* Pull Requests;
* CI/CD;
* Deploy;
* Ambientes.

### Qualidade

* Testes funcionais;
* Testes de API;
* Testes de integração;
* Testes de usabilidade;
* Identificação de bugs;
* Validação das entregas.

---

# 8. Estrutura de cada grupo

Cada equipe deverá possuir diferentes perfis sempre que possível.

```text
                 GRUPO
                   │
        ┌──────────┴──────────┐
        │                     │
   Responsável            Responsável
     Técnico                Produto
        │                     │
        └──────────┬──────────┘
                   │
          ┌────────┼────────┐
          ↓        ↓        ↓
       Front     Back      QA/Dados
```

A ideia é evitar equipes formadas exclusivamente por alunos da mesma área.

---

# 9. Responsabilidades compartilhadas

Apesar da divisão em grupos, algumas responsabilidades serão **transversais a todo o projeto**.

## GitHub

Todos os grupos deverão utilizar o repositório e seguir um padrão de trabalho com:

* Branches;
* Commits;
* Pull Requests;
* Code Review;
* Issues;
* Organização das tarefas.

## Documentação

Cada grupo deverá documentar suas atividades e decisões.

## Scrum / Kanban

As equipes deverão organizar suas atividades utilizando práticas ágeis.

Exemplos:

* Backlog;
* Sprint;
* Kanban;
* Daily;
* Review;
* Retrospectiva.

## Comunicação

As equipes deverão manter comunicação constante para evitar que uma decisão de um grupo prejudique outro módulo.

---

# 10. Integração entre os grupos

Os grupos não trabalharão de forma independente.

O fluxo principal será:

```text
             PRODUTO
                │
                ↓
        Requisitos e UX
                │
       ┌────────┼────────┐
       ↓        ↓        ↓
   CAMPANHAS  DOAÇÕES  GESTÃO
       │        │        │
       └────────┼────────┘
                ↓
        APIs / BANCO
                │
                ↓
          TESTES / QA
                │
                ↓
             DEVOPS
                │
                ↓
             DEPLOY
```

---

# 11. Modelo de liderança

Cada grupo poderá possuir:

### Líder do grupo

Responsável por:

* Organizar as atividades;
* Acompanhar o andamento;
* Distribuir tarefas;
* Participar das reuniões;
* Comunicar impedimentos;
* Acompanhar as entregas.

### Vice-líder

Responsável por:

* Apoiar o líder;
* Acompanhar as atividades;
* Substituir o líder quando necessário;
* Auxiliar na comunicação.

### Membros

Responsáveis pela execução das atividades técnicas e funcionais.

---

# 12. Critério para distribuição dos alunos

A composição das equipes deverá considerar:

1. Área de interesse indicada pelo aluno;
2. Experiência prévia;
3. Conhecimentos técnicos;
4. Equilíbrio entre alunos experientes e iniciantes;
5. Distribuição entre Front-end e Back-end;
6. Presença de conhecimentos de banco e APIs;
7. Presença de conhecimentos de Git/GitHub;
8. Interesse em gestão e documentação;
9. Necessidades específicas de cada módulo.

O objetivo não é criar grupos com alunos de mesmo nível, mas **misturar conhecimentos para favorecer a aprendizagem e a colaboração**.

---

# 13. Filosofia do projeto

O DoaSync será tratado como um projeto real de desenvolvimento de software.

Os alunos não serão responsáveis apenas por "fazer código".

Cada participante deverá ter a oportunidade de:

* Entender um problema real;
* Trabalhar em equipe;
* Planejar;
* Desenvolver;
* Testar;
* Documentar;
* Apresentar resultados;
* Receber feedback;
* Corrigir problemas;
* Entregar uma solução funcional.

Dessa forma, o projeto conecta **formação acadêmica, desenvolvimento profissional e impacto social**.

---

# 14. Resultado esperado

Ao final do projeto, espera-se que os grupos tenham contribuído para uma plataforma capaz de:

* Conectar doadores e entidades;
* Apresentar campanhas;
* Facilitar doações;
* Registrar contribuições;
* Permitir acompanhamento;
* Disponibilizar informações para as entidades;
* Gerar indicadores;
* Apoiar a gestão das arrecadações.

O projeto terá como foco inicial a **APAE** e a **Associação Amor Inclusivo**, podendo posteriormente ser adaptado para outras entidades assistenciais da região.

---

# 15. Próxima etapa

Após a definição desta estrutura, deverá ser realizada a **distribuição individual dos alunos nos cinco grupos**.

A distribuição deverá buscar equilíbrio entre:

```text
Experiência
    +
Interesse
    +
Tecnologia
    +
Perfil de liderança
    +
Necessidade do módulo
```

O resultado final deverá apresentar:

| Grupo                | Líder     | Vice      | Front-end | Back-end | Dados/API | QA/DevOps |
| -------------------- | --------- | --------- | --------- | -------- | --------- | --------- |
| Produto/Entidades    | A definir | A definir | ✓         | ✓        | —         | ✓         |
| Campanhas            | A definir | A definir | ✓         | ✓        | ✓         | ✓         |
| Doações              | A definir | A definir | ✓         | ✓        | ✓         | ✓         |
| Gestão/Dashboard     | A definir | A definir | ✓         | ✓        | ✓         | ✓         |
| Plataforma/Qualidade | A definir | A definir | ✓         | ✓        | ✓         | ✓         |

---

## Resumo

A proposta de organização do DoaSync é baseada em **cinco equipes multidisciplinares orientadas a entregas**, e não apenas em tecnologias.

Isso permite que cada aluno compreenda melhor o ciclo completo de desenvolvimento e, ao mesmo tempo, evita que o projeto fique dependente de uma única equipe para determinada etapa.

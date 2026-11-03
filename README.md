# AcheiCampus — Sistema de Achados e Perdidos

**Disciplina:** Engenharia de Software II — Senac  
**Aluno:** Benafle Soares da Hora  
**Professor:** Rafael  
**Modalidade:** Projeto individual

## 1. Descrição do produto

O AcheiCampus é um sistema de achados e perdidos para a comunidade acadêmica. Seu objetivo é facilitar o registro, a localização e a devolução de objetos perdidos no campus, oferecendo um ambiente centralizado e organizado para estudantes e funcionários.

## 2. Problema identificado

A perda de objetos pessoais em instituições de ensino é frequente. Muitas vezes, as pessoas recorrem a grupos de mensagens ou à comunicação informal, dificultando a recuperação dos pertences. O AcheiCampus propõe organizar esse processo por meio de uma plataforma digital.

## 3. Público-alvo

- Estudantes que perderam objetos.
- Estudantes que encontraram objetos.
- Professores e funcionários da instituição.
- Pessoas que desejam solicitar a devolução de um objeto.

## 4. Proposta de valor

Centralizar os registros de objetos perdidos e encontrados, facilitar pesquisas e permitir solicitações privadas de devolução, promovendo colaboração e organização na comunidade acadêmica.

### Elevator pitch

Para estudantes e funcionários que precisam localizar objetos perdidos, o AcheiCampus é uma plataforma web que reúne anúncios e solicitações de devolução. Diferentemente de recados e mensagens dispersas, o sistema organiza os registros em um único ambiente, tornando a busca mais simples.

## 5. Funcionalidades essenciais (Must Have)

1. **Cadastro de objetos:** publicar anúncios de objetos perdidos ou encontrados, com descrição, categoria, data e local aproximado.
2. **Consulta de anúncios:** visualizar itens registrados e suas informações.
3. **Solicitação de devolução:** permitir que um interessado entre em contato de maneira privada com o responsável pelo anúncio.

### Funcionalidades adicionais

- Busca por palavras-chave.
- Filtros por categoria e tipo de anúncio.
- Marcação de objetos como resolvidos.
- Edição de anúncios pelo responsável.

### Fora do escopo

- Reconhecimento de imagens por inteligência artificial.
- Rastreamento de objetos por GPS.
- Aplicativo nativo para dispositivos móveis.
- Integração com sistemas internos do Senac.
- Pagamentos e serviços de transporte.

## 6. Indicadores de sucesso

- Em testes futuros com 10 usuários, pelo menos 8 deverão conseguir cadastrar ou localizar um objeto sem auxílio.
- As solicitações privadas deverão impedir o acesso de usuários não autorizados em todos os testes de permissão.

Esses indicadores representam metas de avaliação futura, não resultados já alcançados.

## 7. Metodologia Scrum

O planejamento do AcheiCampus utiliza conceitos do Scrum, incluindo Product Backlog, histórias de usuário, priorização MoSCoW, critérios de aceitação e estimativas relativas em story points.

### Equipe

**Benafle Soares da Hora — único integrante.**

Por ser um projeto individual, o aluno acumula as responsabilidades de Product Owner, Scrum Master e Developer.

- **Product Owner:** define a visão do produto e prioriza o backlog.
- **Scrum Master:** organiza o processo e acompanha as atividades.
- **Developer:** especifica, estima, implementa e testa as funcionalidades.

## 8. Matriz RACI

R = Responsável pela execução  
A = Aprovador do resultado  
C = Consultado  
I = Informado

| Atividade | Benafle (PO) | Benafle (SM) | Benafle (Dev) | Professor |
|---|:---:|:---:|:---:|:---:|
| Definir visão do produto | A/R | C | C | I |
| Elaborar e ordenar backlog | A/R | C | C | I |
| Definir critérios de aceitação | A | I | R | I |
| Facilitar e estimar histórias | C | R | A/R | I |
| Definir escopo da sprint | C | C | A/R | I |
| Implementar e testar | I | I | A/R | I |
| Revisar alterações | I | I | A/R | C |
| Aceitar incremento | A | I | R | C |
| Avaliar entrega acadêmica | I | I | I | A/R |

A divisão representa responsabilidades distintas exercidas pelo mesmo estudante. As estimativas são individuais e não representam uma votação coletiva.

## 9. Product Backlog

As histórias estão priorizadas pelo método MoSCoW. Cada uma deverá ser criada como uma Issue no GitHub.

| ID | História de usuário resumida | Prioridade | Story Points |
|---|---|---|---|
| US01 | Publicar objeto encontrado | Must | 3 |
| US02 | Publicar objeto perdido | Must | 3 |
| US03 | Consultar anúncios e detalhes | Must | 2 |
| US04 | Solicitar devolução privada | Must | 5 |
| US05 | Visualizar solicitações recebidas | Must | A estimar |
| US06 | Responder a solicitações | Must | A estimar |
| US07 | Pesquisar por palavras-chave | Should | A estimar |
| US08 | Filtrar por tipo e categoria | Should | A estimar |
| US09 | Marcar casos como resolvidos | Should | A estimar |
| US10 | Editar anúncio próprio | Could | A estimar |

As quatro primeiras histórias deverão conter critérios de aceitação em checklist, cenários no formato Dado/Quando/Então e estimativas de esforço.

As estimativas de 2, 3 e 5 pontos representam complexidade, esforço e incerteza relativos, e não duração em horas.

### Priorização MoSCoW

- **Must:** indispensável para o funcionamento do produto.
- **Should:** importante, mas pode ser entregue posteriormente.
- **Could:** desejável caso haja disponibilidade.
- **Won't:** não será desenvolvido nesta versão.

## 10. Definition of Done

Uma história implementada será considerada concluída quando:

- [ ] Todos os seus critérios de aceitação forem atendidos.
- [ ] Os cenários de sucesso e erro forem testados.
- [ ] As regras de privacidade aplicáveis forem verificadas.
- [ ] O código estiver versionado e sem defeitos críticos conhecidos.
- [ ] As alterações forem revisadas e registradas.

O projeto está atualmente na fase de planejamento. Nenhuma funcionalidade foi declarada como implementada ou testada.

## 11. GitHub Projects

O quadro de acompanhamento será denominado **AcheiCampus — Backlog**, com as seguintes colunas:

1. Backlog
2. Pronto para sprint
3. Em andamento
4. Em revisão
5. Concluído

Todas as dez histórias iniciarão na coluna Backlog, conforme a ordem de prioridade apresentada.

## 12. Entrega

O repositório deverá conter:

- README com visão, escopo, equipe e matriz RACI.
- Dez Issues no formato de histórias de usuário.
- Etiquetas de prioridade e tipo nas Issues.
- Critérios de aceitação e cenários das quatro histórias prioritárias.
- Estimativas das quatro histórias prioritárias.
- Quadro GitHub Projects com as cinco colunas e dez histórias.

## 13. Referência

Material da aula de 21/10 — Do produto ao backlog: papéis, histórias e estimativas. Engenharia de Software II, professor Rafael, Senac.

---
**Projeto acadêmico de Benafle Soares da Hora.**

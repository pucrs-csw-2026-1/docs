# Avaliação

## Rubrica de Avaliação

| Critério | Peso | Insuficiente (0–49%) | Regular (50–69%) | Bom (70–89%) | Excelente (90–100%) |
|----------|------|----------------------|------------------|--------------|----------------------|
| **Funcionalidade** | 40% | Cliente não funciona ou apresenta falhas críticas que impedem o uso. | Funciona parcialmente; há falhas em fluxos principais ou comportamentos inconsistentes. | Funcionalidade principal concluída; poucos bugs menores; requisitos atendidos. | Robusto e confiável; todos os fluxos funcionam corretamente e tratam edge cases. |
| **Integração com APIs (T1/T2)** | 25% | Não integra com as APIs de T1/T2 ou ignora autenticação/autorização. | Integração parcial; consumo de endpoints incompleto ou tratamento de erros frágil. | Integração funcional com as APIs; autenticação, autorização e dados exibidos corretamente. | Integração sólida, com tratamento consistente de erros, sessão expirada e estados de carregamento. |
| **Documentação** | 20% | Ausente ou extremamente superficial; sem README, guia de instalação ou board de gestão de tarefas. | Documentação básica; faltam detalhes técnicos, exemplos ou board de gestão de tarefas desorganizado/incompleto. | Documentação clara e organizada; board de gestão de tarefas bem estruturado com histórico de atividades. | Documentação exemplar; diagrama arquitetural, fluxos de uso documentados, board de gestão de tarefas detalhado com histórico de iterações e decisões. |
| **Apresentação** | 10% | Apresentação desorganizada; não demonstra funcionalidades ou é confusa. | Apresentação adequada, mas sem fluidez; falta clareza em partes importantes. | Apresentação bem estruturada; comunica ideias com efetividade. | Apresentação fluida, com domínio do tema. |
| **Uso Crítico de IA** | 5% | Sem registro de uso de IA ou evidente uso acrítico com código deficiente/"alucinações". | IA utilizada, mas pouca evidência de análise crítica; aceita código sem validação. | IA integrada ao processo; logs mostram revisão e ajustes; decisões questionadas e validadas. | IA como ferramenta estratégica; logs detalhados rastreando iterações; crítica explícita e refinamento contínuo. |

---

## Rubrica Detalhada por Critério

### Funcionalidade (40%)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Erros críticos impedem execução<br>• Funcionalidades principais não implementadas<br>• Comportamento imprevisível ou inconsistente |
| **Regular (50–69%)** | • Funciona, mas com bugs moderados<br>• Parte dos requisitos principais atendida<br>• Falhas em cenários específicos ou edge cases |
| **Bom (70–89%)** | • Todos os requisitos principais funcionam<br>• Poucos bugs menores<br>• Trata a maioria dos edge cases |
| **Excelente (90–100%)** | • Funcionamento consistente em todos os cenários relevantes<br>• 100% dos requisitos + extras implementados<br>• Tratamento robusto de exceções e edge cases |

---

### Integração com APIs (T1/T2) (25%)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Não há integração com as APIs de autenticação ou do microsserviço<br>• Telas protegidas acessíveis sem login<br>• Tokens não são armazenados ou validados |
| **Regular (50–69%)** | • Integração parcial com as APIs<br>• Proteção de rotas/telas incompleta<br>• Tratamento de falhas de autenticação/requisição limitado |
| **Bom (70–89%)** | • Integração funcional com as APIs de T1 e T2<br>• Rotas/telas protegidas corretamente<br>• Estados de carregamento e erro tratados adequadamente |
| **Excelente (90–100%)** | • Integração sólida e bem desenhada<br>• Falhas de autenticação, autorização e requisição tratadas de forma consistente<br>• Experiência de uso fluida mesmo em cenários de erro |

---

### Documentação (20%)

| Nível | Documentação de Código/Projeto | Board de Gestão de Tarefas |
|-------|------------------------------|-----------------------------|
| **Insuficiente (0–49%)** | • README inexistente ou vago<br>• Sem guia de instalação ou uso<br>• Código sem comentários explicativos | • Board ausente ou não utilizado<br>• Nenhum registro de atividades ou planejamento<br>• Impossível acompanhar o progresso |
| **Regular (50–69%)** | • README básico com overview<br>• Instruções de setup parciais<br>• Faltam detalhes técnicos ou exemplos | • Board criado, mas desorganizado ou incompleto<br>• Tarefas sem estrutura clara (sem colunas, datas ou responsáveis)<br>• Falta regularidade no acompanhamento |
| **Bom (70–89%)** | • README completo e bem organizado<br>• Guia de instalação e setup claro<br>• Principais fluxos de uso documentados | • Board bem estruturado (To Do, In Progress, Done)<br>• Tarefas claras com priorização definida<br>• Histórico de atividades visível<br>• Atualizado regularmente |
| **Excelente (90–100%)** | • Documentação profissional e completa<br>• Diagrama arquitetural e fluxos<br>• Exemplos de uso<br>• Troubleshooting e FAQ | • Board profissionalmente organizado (Trello, Asana, GitHub Projects, etc.)<br>• Estrutura clara com labels, responsáveis e datas de entrega<br>• Histórico completo de iterações e mudanças de escopo<br>• Documentação de decisões arquiteturais vinculadas às tarefas<br>• Rastreamento de bloqueadores e dependências<br>• Evidência clara de planejamento iterativo |

---

### Apresentação (10%)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Ausente ou parcial<br>• Difícil entender o que foi desenvolvido no projeto |
| **Regular (50–69%)** | • Sem fluidez<br>• Alguns trechos pouco claros<br>• Erros de execução |
| **Bom (70–89%)** | • Apresentação clara e bem estruturada<br>• Fala com segurança<br>• Responde perguntas de forma coerente<br>• Domínio aparente do tema |
| **Excelente (90–100%)** | • Apresentação impecável<br>• Fala naturalmente<br>• Responde perguntas com confiança e profundidade<br>• Destaca inovações e decisões técnicas importantes |

---

### Uso Crítico de IA (5%)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Sem registro ou rastreamento de uso de IA<br>• Código contém erros óbvios não revisados<br>• Evidente aceitação acrítica do output<br>• "Alucinações" ou inconsistências não identificadas |
| **Regular (50–69%)** | • IA usada (mencionado em logs/README)<br>• Pouca evidência de validação crítica<br>• Código funciona, mas poderia ser otimizado<br>• Falta reflexão sobre limitações de IA |
| **Bom (70–89%)** | • Log de uso de IA documentado<br>• Evidência de revisão e ajustes ao código gerado<br>• Decisões questionadas vs. aceitas automaticamente<br>• Iterações entre humano e IA rastreadas |
| **Excelente (90–100%)** | • Logs detalhados de cada prompt/iteração<br>• Rastreamento de decisões arquiteturais com evidências<br>• Demonstra compreensão clara de quando IA ajuda e quando prejudica<br>• Reforço de escolhas de design com explicações técnicas |

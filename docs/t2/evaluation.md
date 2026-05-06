# Avaliação

## Rubrica de Avaliação

| Critério | Peso | Insuficiente (0–49%) | Regular (50–69%) | Bom (70–89%) | Excelente (90–100%) |
|----------|------|----------------------|------------------|--------------|----------------------|
| **Funcionalidade** | 40% | Microsserviço não funciona ou apresenta falhas críticas que impedem o uso. | Funciona parcialmente; há falhas em fluxos principais ou comportamentos inconsistentes. | Funcionalidade principal concluída; poucos bugs menores; requisitos atendidos. | Robusto e confiável; todos os fluxos funcionam corretamente e tratam edge cases. |
| **Integração com Auth** | 25% | Não integra com o serviço de autenticação ou ignora controle de acesso. | Integração parcial; validação de token ou permissões incompleta. | Integração funcional com autenticação; endpoints protegidos adequadamente. | Integração sólida, com tratamento consistente de tokens, permissões e falhas de acesso. |
| **Documentação** | 20% | Ausente ou extremamente superficial; sem README, guia de instalação ou documentação da API. | Documentação básica; faltam detalhes técnicos, exemplos ou organização. | Documentação clara e organizada; API bem descrita e setup compreensível. | Documentação exemplar; API detalhada, diagrama arquitetural, exemplos completos e troubleshooting. |
| **Apresentação** | 10% | Vídeo ou apresentação desorganizados; não demonstram o microsserviço. | Demonstração adequada, mas sem fluidez ou clareza em partes importantes. | Vídeo e apresentação bem estruturados; comunicam bem o funcionamento do serviço. | Apresentação profissional; domínio completo do tema e demonstração fluida do fluxo. |
| **Uso Crítico de IA** | 5% | Sem registro de uso de IA ou uso acrítico evidente. | IA utilizada, mas com pouca evidência de revisão e validação. | IA integrada ao processo com revisão e ajustes claros. | IA usada estrategicamente, com logs detalhados e refinamento contínuo. |

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

### Integração com Auth (25%)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Não há integração com o serviço de autenticação<br>• Endpoints sensíveis sem proteção<br>• Tokens/permissões não são validados |
| **Regular (50–69%)** | • Integração parcial com autenticação<br>• Proteção de rotas incompleta<br>• Tratamento de falhas de autorização limitado |
| **Bom (70–89%)** | • Integração funcional com o serviço de auth<br>• Endpoints protegidos corretamente<br>• Tokens e permissões validados de forma adequada |
| **Excelente (90–100%)** | • Integração sólida e bem desenhada<br>• Falhas de autenticação/autorização tratadas de forma consistente<br>• Segurança aplicada de ponta a ponta |

---

### Documentação (20%)

| Nível | Documentação de Código/Projeto | API e Setup |
|-------|------------------------------|-------------|
| **Insuficiente (0–49%)** | • README inexistente ou vago<br>• Sem guia de instalação ou uso<br>• Código sem organização adequada | • API não documentada<br>• Sem exemplos de uso<br>• Execução local pouco ou nada explicada |
| **Regular (50–69%)** | • README básico com overview<br>• Instruções parciais de setup<br>• Faltam detalhes técnicos ou exemplos | • API documentada parcialmente<br>• Exemplos limitados<br>• Setup compreensível apenas em parte |
| **Bom (70–89%)** | • README completo e organizado<br>• Guia de instalação e execução claro<br>• Estrutura de projeto compreensível | • Swagger/OpenAPI disponível<br>• Exemplos de uso dos principais endpoints<br>• Execução local documentada |
| **Excelente (90–100%)** | • Documentação profissional e completa<br>• Diagrama arquitetural e fluxos<br>• Explicação de decisões técnicas | • API detalhada e atualizada<br>• Exemplos completos<br>• Troubleshooting e orientações de operação local |

---

### Apresentação (10%)

#### Vídeo de Demo (5% da nota final)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Vídeo ausente, muito curto ou ilegível<br>• Não demonstra funcionalidades principais<br>• Áudio/vídeo de péssima qualidade |
| **Regular (50–69%)** | • Vídeo presente, mas sem fluidez<br>• Demonstra funcionalidades, mas sem contexto suficiente |
| **Bom (70–89%)** | • Vídeo claro demonstrando features principais<br>• Qualidade de áudio/vídeo boa<br>• Narração ou explicações durante a demo |
| **Excelente (90–100%)** | • Vídeo profissional e bem editado<br>• Demo fluida mostrando fluxo completo<br>• Narração clara explicando cada etapa |

#### Apresentação em Sala (5% da nota final)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Ausente ou parcial<br>• Difícil entender o que foi desenvolvido |
| **Regular (50–69%)** | • Sem fluidez<br>• Alguns trechos pouco claros<br>• Erros de execução |
| **Bom (70–89%)** | • Apresentação clara e bem estruturada<br>• Fala com segurança<br>• Responde perguntas de forma coerente |
| **Excelente (90–100%)** | • Apresentação impecável<br>• Fala naturalmente<br>• Responde perguntas com confiança e profundidade |

---

### Uso Crítico de IA (5%)

| Nível | Descrição |
|-------|-----------|
| **Insuficiente (0–49%)** | • Sem registro ou rastreamento de uso de IA<br>• Código contém erros óbvios não revisados<br>• Aceitação acrítica do output |
| **Regular (50–69%)** | • IA usada, mas com pouca evidência de validação crítica<br>• Código funciona, mas faltam ajustes ou revisão |
| **Bom (70–89%)** | • Log de uso de IA documentado<br>• Evidência de revisão e ajustes ao código gerado<br>• Iterações entre humano e IA rastreadas |
| **Excelente (90–100%)** | • Logs detalhados de cada prompt/iteração<br>• Reflexão clara sobre limites e contribuições da IA<br>• Reforço de escolhas técnicas com explicações objetivas |
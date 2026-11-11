# Auditoria de Injeção · código da página

Página **Auditoria de Injeção** da [Plataforma](https://danielamotaxp-code.github.io/central-atendimento/#auditoria). Ela abre dentro do portal, com o login, as permissões e as cores de lá.

| | |
|---|---|
| Endereço | [https://danielamotaxp-code.github.io/central-atendimento/#auditoria](https://danielamotaxp-code.github.io/central-atendimento/#auditoria) (o endereço antigo deste repositório redireciona para lá) |
| Página | `app.html` (código público, sem dados de clientes) |
| Dados | repositório privado `auditoria-dados` |
| Ligação com o portal | `<script src="/central-atendimento/kit/modulo.js" data-modulo="auditoria">` no início do `app.html` |
| Cores | `embutido.css` (WeGen verde, SmartBen azul, WattWise rosa) |

<!-- detalhes -->
## Detalhes da versão anterior

Plataforma da auditoria de injeção de energia (WeGen · SmartBen).

- Endereço: https://danielamotaxp-code.github.io/auditoria-injecao/
- Use no **Chrome ou Edge**, com a VPN ligada, e conecte a pasta do Z: (a que tem 2024, 2025, 2026 e Faturamento).
- **Lista de auditorias**: vem das abas AUD - CANCELAMENTO OP 1, AUD - VERIFICAÇÃO e AUD - INADIMPLENTES da planilha CANCELAMENTOS E AUDITORIAS.
- **Arquivo**: as planilhas ficam guardadas no repositório privado `auditoria-dados`, em pastas por tipo de auditoria e empresa.
- **Acessos**: configurados em `configurar.html` (a chave do GitHub fica trancada pela senha de cada pessoa, como na Central de Distratos).
- Os relatórios do Z: são lidos no navegador de quem usa e não saem do computador.

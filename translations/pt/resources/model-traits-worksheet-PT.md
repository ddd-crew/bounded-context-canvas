# Ficha de Características do Modelo

É provável que um modelo seja descrito por várias características diferentes. Revise a lista abaixo e escolha qual se aplica ao contexto em que você está trabalhando ou pense em suas próprias características.

| Característica | Heurística |
|---|---|
| Especificação/Esboço de Modelo | Produz um documento descrevendo um trabalho/solicitação que precisa ser executado. Exemplo: Gerador de Campanhas Publicitárias. |
| Modelo de Execução | Executa ou acompanha um trabalho. Exemplo: Motor de Campanha Publicitária. |
| Modelo de Análise/Auditoria | Monitora a execução. Exemplo: Analisador de Campanha Publicitária. |
| Aprovador | Recebe solicitações e determina se elas devem avançar para a próxima etapa do processo. Exemplo: Detecção de Fraude. |
| Executor | Garante que outros contextos realizem determinadas operações. Exemplo: Contexto LGPD (garante que outros contextos excluam todos os dados de um usuário). |
| Múltiplo Executor | Garante que vários/todos os contextos no sistema estejam em conformidade com uma regra padrão. Exemplo: Contexto LGPD (como o acima). |
| Intercâmbio | Traduz entre várias linguagens ubíquas. |
| Gateway | Situa-se na borda de um sistema e gerencia a comunicação de entrada e/ou saída. Exemplo: Gateway de Mensagem IoT .|
| Gateway de Intercâmbio | A combinação de um gateway e um intercâmbio. |
| Contexto _Dogfood_ | Simula a experiência do cliente em usar o Contexto. Exemplo: Loja de Música _Whitelabel_. |
| Contexto Bolha | Situa-se na frente dos Contextos legados, fornecendo um modelo novo e mais limpo enquanto os Contextos legados estão sendo substituídos.  |
| Bolha Autônoma | Contexto de bolha que possui seu próprio armazenamento de dados e os sincroniza de forma assíncrona com os Contextos herdados. |
| Contexto Cerebral (provavelmente um antipadrão) | Contém um grande número de regras importantes e muitos outros Contextos dependem dele. Exemplo: Motor de Regras Contendo todas as Regras de Domínio. |
| Contexto de Funil | Recebe documentos de vários Contextos acima e os passa para um único contexto abaixo em um formato padrão (depois de aplicar suas próprias regras). |
| Contexto de Engajamento | Fornece os principais recursos que atraem os usuários a continuar usando o produto. Exemplo: Contexto de Consultoria Financeira Gratuita. |
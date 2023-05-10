<h1>Integração Contínua: mais qualidade e menos risco no desenvolvimento</h1>

- Controle de versão.
	- Organização.
	- Modelos de ramificação.
- Builds e testes automatizados.
- Build pipeline.
- Continuous Delivery e Deploy.

Pequenas alterações (continuas), são mais viáveis.
<strong>Integração Continua:</strong> é uma prática de desenvolvimento que exige que os desenvolvedores integrem o código em um repositório compartilhado várias vezes ao dia.

- Ferramenta não importa.
- Comita tudo necessário para construção do projeto.
	- Código.
	- Scripts.
	- Migrações, schemas.
	- IDE Configs.
- Não comita o que pode ser construido (gem, jar, image, modules).
- Clone e começar (deve ser fácil).

<h3>Organização dos repositórios:</h3>
- <strong>Multi-repo:</strong> separa um repositório para cada projeto.
- <strong>Mono-repo:</strong> possui todos os projetos em um único repositório.

<h3>Branching:</h3>
- Commits simples e lançáveis, orientado ás tarefas.
- Branches atrasam integração, seguram o código.
- Branches de vida curta -> merges mais simples.
- Muitos branches, mais burocracia.
- Estratégias devem ser combinadas pela equipe.

<h3>Branching Models:</h3>
- Temporários (branches locais).
- Feature Branches.
- Historical Branches (Master e Develop).
- Environment Branches (Staging e Production).
- Maintenance Branches (Release e Hotfix).

<h3>Tipos Branching:</h3>
- Trunk-Based Development: tentam evitar Branchs.
- Feature Branch Workflow: criam Branchs para implementar Feature.
- Feature Branch + Pull Request.
- GitHub Flow (master + Feature Branch + Pull Request).
- Gitlab Flow (Feature Branch + Pull Request + ENV Branches).
- Git Flow (Feature Branch + Pull Request + Maintenance Branches + Historical Branches).

<h3>Evitar branchs de vida longa:</h3>
- Feature Flag.
- Branch by Abstraction. 

<h3>Como sincronizar branches:</h3>
- Merge: O comando clássico para essa situação é o merge, e então ocorre o chamado "merge commit", cria-se um novo commit que representa esse momento de sincronização.
- Rebase: Neste caso, a ideia é que se mude a base do commit, e então as modificações são aplicadas nessa nova base.

<h3>Teste automatizados:</h3>
- Teste fazem parte da construção.
- Rodar antes do commit.
- TDD pode ajudar.
- Desempenho importa.

<h3>Build automatizado:</h3>
- Build a cada commit.
- Tudo automatizado / um comando.
- Build sem depender da IDE.
- Tudo está no repositório.

<h3>Build rápido/ Feedback rápido:</h3>
- Otimize o build, métricas ajudam.
	- Verifique a fase testes e analise do código.
	- Verifique ordem dessas fases.
	- Verifique a infra do build system.
	- Use cache.
- Use staged build / pipeline (ligth build, heavy build).
- Regra: "TEN-Minute Build" (XP Programming).



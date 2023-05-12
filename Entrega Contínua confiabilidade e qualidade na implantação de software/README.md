<h1>Entrega Contínua: confiabilidade e qualidade na implantação de software</h1>


<h3>Pipeline de deploy:</h3>

- Design.
- Build.
- Teste.
- Homologação.
- Produção.

<h3>Antipattern(Fora dos padrões):</h3>

- Gerenciamento manual de ambientes.
- Deploy manual.
- Deploy apenas no fim do ciclo.

<h3>Atipattern: Como resolver:</h3>

- Gerencimaneto automatizado de ambientes.
- Deploy automatizado.
- Deploy frequente em cada ciclo de desenvolvimento.

<h3>Entrega Contínua vs Deploy Contínua:</h3>

- Na entrega contínua as modificações e atualizações não são enviadas prontamente para a produção, isto é, ficam "paradas" na homologação.
- No caso do deploy contínuo, as modificações vão de fato para o ambiente de produção. Veremos ao longo do curso que existem formas de ocultar funcionalidades que estão em produção.

<h3>Princípios de Entrega Contínua:</h3>

- Automatize.
- Versione.
- Repita.
- Garanta qualidade.
- Defina "done".
- Cria delivery team.
- Usa melhoria contínua.

<h3>Elementos da Entrega Contínua:</h3>

- Cultura DevOps.
	- feedback, colaboração e confiança.
	- melhoria e aprendizagem contínua.
- Patterns.
	- deployment pipeline.
	- deploy patterns (blue/green, canary, feature toggle, etc).
- Arquitetura.
	- Novas Propriedades: testability e deployability.
	- SOLID, Services e 12 Factor App.

<h3>Etapas/Stages do Pipeline de deploy:</h3>

- Build Unit Test.
- Teste de aceitação automatizados.
- Homologação UAT.
- Produção.

<h3>Boas práticas:</h3>

- Pipeline é a única forma de deploy.
- Mantém o pipeline o mais rápido possível.
- Build apenas uma vez.
- Build independente do ambiente.
- Ambientes iguais/semelhantes.
- Ambiente temporários.
- Deploy para ambientes de maneira igual.




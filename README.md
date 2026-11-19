# Hermes e Durkh 509

A ideia de ter uma inteligência artificial pessoal me acompanha desde o começo do meu contato com os assistentes de IA. O Hermes e o Durkh 509 se tornaram o centro do ambiente que construí para meus projetos e para o dia a dia.

[Como funciona e se conecta aos outros projetos](docs/Como-Funciona-Hermes-Durkh-509.md) · [Roteiro de implementação](docs/Tutorial-Hermes-Durkh-509.md)

## De onde veio a ideia

Comecei a experimentar IA naquela fase em que acessar o ChatGPT ainda envolvia filas e instabilidade. Já imaginava ter um assistente pessoal que pudesse acompanhar minhas coisas e agir junto comigo. Desde então, fui aperfeiçoando essa ideia.

Usei bastante ChatGPT e Claude diretamente, e continuo usando. Para os meus projetos pessoais e para as tarefas que conectei ao meu ambiente, passei a usar principalmente o Hermes. Escolhi essa base pela integração com a OpenAI e pela continuidade que ela oferecia à minha forma de trabalhar. Queria acompanhar melhor as demandas, retomar os contextos e manter histórico das execuções.

O [Hermes Agent](https://github.com/NousResearch/hermes-agent), da Nous Research, é o software que executa o agente. Durkh 509 é a identidade e o modo de operação que personalizei nessa base; o número identifica meu agente principal.

## Do terminal ao Discord

No começo eu usava o Hermes pelo terminal, tanto no VS Code quanto diretamente no computador. Depois experimentei uma interface por URL HTTPS, mas não gostei tanto da experiência. Passei para o Telegram, onde o projeto se desenvolveu bastante.

A mudança para o Discord foi a virada mais importante na forma de organizar o ambiente. Passei a ter conversas, canais e integrações no mesmo lugar. Consigo acessar meu servidor privado pelo aplicativo do celular, pelo computador ou pelo navegador de outra máquina.

Hoje o Durkh 509 é meu principal ponto de interação para organizar demandas, consultar documentos e executar rotinas configuradas. As integrações foram preparadas conforme a necessidade de cada projeto. Um exemplo público é o [Factorio — Durkh Coop](https://github.com/DURKHEIM09/factorio-durkh-coop).

Também comecei a reunir painéis de sistemas no Discord, incluindo o Hermes Control. Essa interface e suas integrações têm documentação própria, que complementa a experiência do agente.

## Experimentos com agentes especializados

Quando fui para o Discord, experimentei cinco agentes especializados: planejamento de projetos, desenvolvimento, infraestrutura, RPA e automação e revisão documental. Contando o Durkh 509, são seis agentes principais nesse conjunto.

O agente de planejamento ajuda a estruturar o começo dos projetos, os questionamentos e os requisitos. Desenvolvimento foca o código; infraestrutura, os sistemas, redes e acessos; RPA e automação, os fluxos e robôs. O agente de revisão confere a documentação e os resultados. O Durkh 509 continua sendo quem mais utilizo diretamente.

Minha intenção era que as demandas pudessem circular entre eles de forma estruturada. Desenvolvi um atendimento de chamados parecido, na experiência, com receber um card no Jira: o agente responsável recebe o contexto, as obrigações e os critérios do que precisa entregar. A implementação desse transporte e dos estados do chamado fica em um projeto separado.

Além de executar, cada agente coordenador pode criar agentes temporários para uma demanda. Nos testes que fiz, vi isso acontecer principalmente no desenvolvimento mais complexo: separar frentes como interface, backend e banco, por exemplo. Para tarefas menores, o próprio agente costuma resolver.

Para apoiar essa escolha, organizei um acervo de habilidades, skills e personas. Gosto de pensar como montar um sanduíche: escolher as peças adequadas para o trabalho. Defini a lógica e a curadoria do material que pode compor essa preparação. A seleção e a execução de agentes temporários também fazem parte de projetos conectados.

## A maior dificuldade

A maior dificuldade foi aprender a usar IA e escolher o que integrar. Existem muitas ferramentas, e elas evoluem muito rápido. Como o Hermes ficou no centro dos meus projetos, ele acabou se desenvolvendo junto comigo: conforme eu aprendia a trabalhar com IA, também mudava a forma de organizar o meu assistente.

Integrar as peças exigiu decidir o que fazia sentido para o meu dia a dia. Meu critério de arquitetura considera custo, usabilidade e utilidade real. Uma solução precisa caber na minha rotina e justificar o trabalho de construir e manter suas conexões.

Eu gosto de desenvolver coisas complexas pelo desafio e pelo aprendizado. Essa exploração tem valor para mim. Ao mesmo tempo, quero equilibrá-la com soluções que eu realmente use. Criar estruturas cada vez maiores e deixá-las sem uso acaba limitando o ganho prático.

## O que aprendi com essa estrutura

A experiência com múltiplos agentes me permitiu explorar coordenação e especialização. Como esse é um experimento pessoal, o volume de requisições é menor do que a estrutura comporta. No dia a dia, o Durkh 509 resolve muita coisa sozinho; acrescentar burocracia a toda tarefa atrapalha.

O Hermes foi meu maior ganho pessoal nesse processo porque se tornou algo que uso de verdade. Ele acompanhou minha evolução e ganhou conexões conforme minhas necessidades. Essa organização de agentes continua sendo uma possibilidade para demandas maiores, e o próximo passo depende do uso real.

**Sobre esta publicação:** experiência de uso e personalização do Hermes, organizada por Lucas em 19/11/2026. O repositório reúne o relato, a arquitetura e um roteiro de referência. A explicação técnica usa os documentos existentes; não houve nova verificação operacional dos serviços.

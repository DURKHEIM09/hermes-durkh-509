# Começar com Hermes e personalizar um agente

[Voltar à apresentação](../README.md) · [Entender as conexões](Como-Funciona-Hermes-Durkh-509.md)

Este roteiro de referência organiza a preparação do Hermes e de uma identidade personalizada a partir da experiência documentada. Os procedimentos de instalação do software são mantidos na fonte oficial. Este repositório publica a apresentação e a arquitetura; configurações do ambiente e instruções privadas do agente não são distribuídas.

## 1. Preparar uma instalação do Hermes

Use as instruções do [repositório oficial do Hermes Agent](https://github.com/NousResearch/hermes-agent) para instalar uma versão compatível com seu ambiente. No laboratório de Lucas, o runtime é mantido no servidor Linux, enquanto os dispositivos de uso acessam as interfaces de conversa.

Selecione um modelo/provedor e faça a autenticação pelo mecanismo oficial suportado na versão instalada. A integração com a OpenAI é parte da experiência descrita; outras opções dependem do suporte do Hermes e do provedor escolhido.

## 2. Definir a identidade e o modo de trabalho

Prepare suas próprias instruções de identidade, responsabilidades e limites de operação. Na instalação documentada de Lucas, isso é representado pelo `SOUL.md` do Durkh 509.

Comece com uma configuração pequena: como o agente deve colaborar, como consultar os documentos e como explicar o que fez. Os acessos e as credenciais ficam nos mecanismos próprios do ambiente, separados da documentação pública.

## 3. Começar pelo terminal e acrescentar um canal

Teste a conversa e uma tarefa simples no terminal antes de acrescentar outras interfaces. Para mensageria, siga o gateway correspondente na documentação da versão instalada. No percurso relatado, Lucas passou por uma interface HTTPS, pelo Telegram e depois pelo Discord.

No Discord, prepare seu próprio servidor privado, a aplicação/bot e os canais de interação. Configure a identidade e as permissões do agente de acordo com a necessidade. Os dados de autenticação pertencem ao mecanismo de configuração da instalação; exemplos públicos devem usar placeholders.

A topologia de Lucas possui gateways de conversa, projeções de chamados, interface de voz e Activities. Cada integração tem um projeto responsável. A migração para o Discord não exige instalar todos esses componentes de uma vez.

## 4. Conectar os documentos e as ferramentas necessários

Organize instruções e notas dos projetos em fontes claras. No ambiente relatado, agentes consultam Markdown e Lucas usa Obsidian como interface para esses mesmos arquivos. O Neuro-Link complementa a recuperação de conhecimento.

Acrescente ferramentas conforme tarefas concretas. SSH pode conectar um servidor a outras máquinas; outros adaptadores atendem relatórios e ações específicas dos projetos. Cada ferramenta exige configuração e validação próprias. O trabalho do Factorio é um exemplo publicado: [Factorio — Durkh Coop](https://github.com/DURKHEIM09/factorio-durkh-coop).

## 5. Avaliar quando vale separar agentes

Para o uso pessoal, Lucas utiliza principalmente o 509. Os experimentos acrescentam agentes de planejamento, desenvolvimento, infraestrutura, RPA e revisão documental. Comece pela demanda e pelo resultado esperado; divida a execução quando houver benefício real de coordenação ou especialização.

Chamados entre agentes, catálogo de habilidades e workers temporários têm contratos próprios. Seus materiais vão detalhar admissão, seleção de capacidades, critérios de aceite e retorno. O experimento completo tem componentes implementados e integrações ainda parciais.

## Escopo do roteiro

O roteiro apresenta a sequência de preparação. O passo a passo completo do gateway Discord e exemplos públicos de configuração não estão incluídos nesta publicação. Voz, agentes especializados e chamados têm implementação e documentação próprias.

A documentação desta etapa não consultou autenticação, memórias privadas ou serviços em execução. Os passos de instalação específicos continuam referenciados na fonte oficial, em vez de presumir os comandos e a configuração de uma versão diferente.

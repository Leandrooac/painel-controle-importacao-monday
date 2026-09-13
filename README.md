# Painel de Controle de Processos de Importação — Monday.com

## Contexto

O controle de processos e produtos de importação era feito inteiramente em planilhas de Excel, sem padronização entre os responsáveis e sem visibilidade centralizada de status (canal de parametrização, exigências, pendências documentais). Com o volume de processos crescendo, o formato em planilha isolada deixou de ser sustentável para acompanhamento em equipe.

Não houve apoio de consultoria externa nem de ferramentas especializadas do mercado (como plataformas de Trade Management) para esse projeto, a estruturação foi feita internamente.

## Abordagem

Participei da construção do painel junto a uma equipe de 3 pessoas, atuando em diferentes posições ao longo do processo (eu sendo Assistente de Importação, Analista de Planejamento e Analista de Importação). O trabalho consistiu em:

1. Mapeamento das etapas reais do processo de importação, desde a abertura até a admissão em entreposto aduaneiro.
2. Estruturação dessas etapas como um fluxo de status dentro do Monday.com (canal de parametrização, aferição de Licença de Importação, exigências, despacho).
3. Migração progressiva dos controles que antes existiam apenas em Excel para o painel, centralizando o acompanhamento da equipe.
4. Ajustes contínuos da estrutura conforme o processo real de comércio exterior evoluía (incluindo mudanças regulatórias, como a transição de múltiplas Declarações de Importação para o modelo unificado de DUIMP).

## Ferramentas

- Monday.com (estruturação de quadros, colunas de status e automações nativas da plataforma)
- Microsoft Excel (etapa anterior do processo, referência para o mapeamento)

## Resultado

- Centralização do acompanhamento de processos de importação para toda a equipe, substituindo controles individuais e dispersos em planilhas.
- Maior visibilidade de status e pendências em tempo real, sem depender de atualização manual cruzada entre arquivos.

## Sobre os dados neste repositório

Este repositório não reproduz o painel real nem dados de fornecedores, processos ou produtos da empresa, documenta a lógica de estruturação do fluxo, que é conhecimento de processo, não informação confidencial de negócio.

## Próximos passos

- Documentar o fluxo de status como um diagrama (ex.: BPMN) para consulta e apresentação em processos seletivos.
- Explorar a exportação de dados do Monday.com via API como exercício de integração de sistemas.

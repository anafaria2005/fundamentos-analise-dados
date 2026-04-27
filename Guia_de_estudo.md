De acordo com as fontes e o nosso histórico de conversa, a **limpeza de dados** é frequentemente considerada a fase mais demorada da rotina de um analista, pois os dados do mundo real costumam ser \"sujos\" ou inconsistentes.

As tarefas específicas que tornam esse processo complexo e moroso incluem:

- **Auditoria e Mesclagem de Arquivos:** Quando os dados não estão em um único local, o analista precisa entender arquivos individualmente, auditar sua qualidade e mesclá-los cuidadosamente em um \"dataframe mestre\" 1. Esse processo exige o conhecimento técnico de quais chaves conectam os diferentes arquivos e em qual ordem a junção deve ocorrer 1.

- **Tratamento de Valores Ausentes:** Envolve decidir estrategicamente se deve remover as linhas com dados faltantes ou preenchê-las por meio de fluxos de trabalho automatizados 2.

- **Correção de Entradas Inconsistentes:** Uma das tarefas mais comuns é a correção manual ou automatizada de **erros de digitação (typos)** para garantir a integridade da análise 2.

- **Padronização de Formatos (Parsing):** Ajudar as ferramentas (como o Python) a reconhecerem corretamente campos de **data e hora**, garantindo que dia, mês e ano sejam interpretados da forma certa 2.

- **Resolução de Problemas de Codificação (Encodings):** Lidar com erros de decodificação de caracteres (como o *UnicodeDecodeError*) ao carregar diferentes tipos de arquivos, como CSVs 2.

- **Escalonamento e Normalização:** Transformar variáveis numéricas para que possuam propriedades úteis para modelos matemáticos e estatísticos 2.

Em resumo, o esforço para transformar dados brutos e desorganizados em uma base confiável é o que consome a maior parte do tempo antes que qualquer análise ou previsão possa ser feita 1, 2.

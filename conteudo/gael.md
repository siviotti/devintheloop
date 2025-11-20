# Grau de Atenção à Entrada no Loop (GAEL)

O Grau e Atenção à Entrada no Loop é uma ferramenta para classificação de sistemas em relação a provável necessidade de entrada no loop por parte do desenvolvedor quando da construção de um software com assistentes de IA coding. O GAEL indica maior ou menor probabilidade de ser necessário que o desenvolvedor interfira na auação da inteligência artificial na realização de tarefas do ciclo de desenvolvimento de software. O GAEL é definido a partir de outros graus descritos a seguir:

## Grau de Impacto ao Negócio (GIN)

O Grau de Impacto ao Negócio é a combinação do Grau de Criticidade (GC) com o Grau de Longevidade (GL), gerando uma medida consolidada para o impacto de um sistema estruturante e sua devida atenção ao uso de assistentes de IA no ciclo de desenvolvimento.

### Grau de Criticidade (GC)

Indica o quão crítico é um sistema para o negócio de uma organização e, consequentemente, impacta a atenção que deve-se dar ao uso de IA no ciclo de desenvolvimento. É classificado em Baixo, Médio e Alto conforme descrito e exemplificado a seguir:

- Baixo (valor 1) - Software não ligado ao negócio ou de uso local e interno
- Médio (valor 2) - Software ligado indiretamente ao negócio nas áreas meio da organização
- Alto  (valor 3) - Software estruturante ligado fortemente à atividade fim ou de forma indispensável para o negócio

### Grau de Longevidade (GL)

Indica o quão longevo é um sistema em uma organização e, consequentemente, impacta a atenção que deve-se dar ao uso de IA no ciclo de desenvolvimento pelo tempo que permanecerá sendo mantido. É classificado em Baixo, Médio e Alto conforme descrito e exemplificado a seguir:

- Baixo (valor 1) - Protótipos, provas de conceito, aplicações temporárias ou de duração finita
- Médio (valor 2) - MVP de produto totalmente novo, versão inicial para teste de mercado ou produtos finais sem garantia de continuidade
- Alto  (valor 3) - Módulos ou partes de produtos já longevos, produtos com continuidade garantida, reboots de produtos longevos já existentes

## Grau de Dificuldade do Problema (GDP)

O Grau de Dificuldade do Problema é a combinação do Grau de Complexidade com o Grau de Particularidade, gerando uma medida consolidada do quão difícil é converter o problema em solução através da complexidade do problema apresentado associada a particularidade e a capacidade da IA conseguir obter contexto e insumos para resolver o problema.

### Grau de Complexidade (GX)

Indica o quão complexo é o problema do escopo avaliado para ser convertido em solução/software. É classificado em Baixo, Médio e Alto conforme descrito e exemplificado a seguir:

- Baixo (valor 1) - Decomposição não é necessária e o problema pode ser explicado em um único prompt. Uma rotina, um pequeno programa ou algo autocontido e simples.
- Médio (valor 2) - Decomposição já é necessária e a instrução já depende de um contexto com vários artefatos. Um módulo complexo ou um sistema inteiro com alguma integração.
- Alto  (valor 3) - Decomposião, modularização e arquitetura complexa necessárias. Um macrosistema com vários módulos e várias integrações.

### Grau de Particularidade (GP)

Indica o quão particular é o escopo do problema apresentado tanto do ponto de vista da novidade como do ponto de vista da disponibilidade de informações que podem ser usadas por ferramentas de IA. É classificado em Baixo, Médio e Alto conforme descrito e exemplificado a seguir:

- Baixo (valor 1) - Problema amplamente conhecido e disponível publicamente (jogo da velha, e-comerce, ERP, folha de pagamento etc)
- Médio (valor 2) - Problema conhecido mas com muitos detalhes específicos do negócio ou da organização ou baixa disponibilidade pública.
- Alto  (valor 3) - Problema desconhecido ou muito específico no todo ou em parte crítica do sistema (negócio sigiloso, inovador ou raro).

## Regras de Cálculo

A regra geral é a multiplicação dos valores inteiros definidos acima (baixo = 1, médio = 2 e alto = 3) a partir da seguinte fórmula:

GAEL = GIN x GDP

Como GIN = GC x GL e GDP = GX x GP, também podemos calcular GAEL a partir dos quatro graus básicoa dessa forma:

GAEL = GC x GL x GX x GP.

GIN e GDP são enquadrados como alto/médio e baixo com base na tabela de multiplicações seguir:

|       | Baixo | Médio | Alto | 
|-------|-------|-------|------| 
| Alto  |   3   |   6   |  9   |
| Médio |   2   |   4   |  6   |
| Baixo |   1   |   2   |  3   |

A faixas para enquadrar os valores numéricos novamente em baixo, médio e alto são:

- Resultado de multiplicação 1 ou 2 será baixo
- Resultado de multiplicação 3 ou 4 será médio
- Resultado de multiplicação 6 ou 9 será alto

GAEL será enquadrado como muito alto, alto, medio, baixo e muito baixo com base na tabela de multiplicações a seguir:
Dessa forma GAEL pode ter o valor numérico direto que a multiplicaçao dos quatro graus primários ou seu valor categórico que é enquadrado conforma abaixo:

- Resultado de multiplicação 1 ou 2 será muito baixo
- Resultado de multiplicação entre 3 e 8 será baixo
- Resultado de multiplicação entre 9 e 16 será médio
- Resultado de multiplicação entre 18 e 36 será alto
- Resultado de multiplicação 54 ou 81 será muito alto


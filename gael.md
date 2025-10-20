# Grau de Atenção à Entrada no Loop (GAEL)

O Grau e Atenção à Entrada no Loop é uma ferramenta para classificação de sistemas em relação a provável necessidade de entrada no loop por parte do desenvolvedor quando da construção de um software com assistentes de IA coding. O GAEL indica maior ou menor probabilidade de ser necessário que o desenvolvedor interfira na auaçao da inteligência artificial na realização de tarefas do ciclo de desenvolvimento de software.

## Grau de Impacto ao Negócio (GIN)

### Grau de Criticidade (GC)

- Baixo - Software não ligado ao negócio ou de uso local e interno
- Médio - Software ligado indiretamente ao negócio nas áreas meio da organização
- Alto - Software estruturante ligado fortemente à atividade fim ou de forma indispensável para o negócio

### Grau de Longevidade (GL)

- Baixo - Protótipos, provas de conceito, aplicações temporárias ou de duração finita
- Médio - MVP de produto totalmente novo, versão inicial para teste de mercado ou produtos finais sem garantia de continuidade
- Alto - Módulos ou partes de produtos já longevos, produtos com continuidade garantida, reboots de produtos longevos já existentes

## Grau de Dificuldade do Problema (GDP)

### Grau de Complexidade (GX)

- Baixo - Decomposição não é necessária e o problema pode ser explicado em um único prompt. Uma rotina, um pequeno programa ou algo autocontido e simples.
- Médio - Decomposição já é necessária e a instrução já depende de um contexto com vários artefatos. Um módulo complexo ou um sistema inteiro com alguma integração.
- Alto - Decomposião, modularização e arquitetura complexa necessárias. Um macrosistema com vários módulos e várias integrações.

### Grau de Particularidade (GP)

- Baixo - Problema amplamente conhecido e disponível publicamente (jogo da velha, e-comerce, ERP, folha de pagamento etc)
- Médio - Problema conhecido mas com muitos detalhes específicos do negócio ou da organização ou baixa disponibilidade pública.
- Alto - Problema desconhecido ou muito específico no todo ou em parte crítica do sistema (negócio sigiloso, inovador ou raro).

# Workshop Dev In The Loop

## Atividade de Abertura: Apresentação do conceito de "Dev In The Loop" e do GAEL (Grau de Atenção a Entrada no Loop)
1. Kahoot Dev In The Loop com perguntas sobre o GAEL (uma pergunta para cada grau: Criticidade, Longevidade, Complexidade e Particularidade)
2. Apresentação resumida Dev In The Loop
3. Super trunfo com os sistemas do Serpro - cartas com atributos do GAEL e risco de fraude

## Atividade 1 (Heurística 1 - Definição do Problema) - Percepção da Complexidade e Prática de Decomposição
1. Tarefa 1: Use uma IA para criar uma função que avalia duas opções do jogo "Pedra, Papel e Tesoura"
   - Prompt: Crie um código que avalia duas opções do jogo "Pedra, Papel e Tesoure" e indica qual é a vencedora.
   - Reflexão: O problema é simples e de comhecimento amplo (baixa complexidade e baixa particularidade)
2. Tarefa 2: Use uma IA para criar um método de validação de CNPJ (problema simples, mas provavelmente desconhecido - particular)
   - Prompt: Crie um código que valida o número de CNPJ.
   - Reflexão: O problema é simples, mas de conhecimento um pouco mais restrito (baixa complexidade e média particularidade)
3. Tarefa 3: Use uma IA para criar um sistema que encontre, recomende e altera as partes de um código onde há CNPJ numérico para CNPJ alfanumérico (problema complexo)
   - Prompt: Faça um aplicativo que carrega arquivos de código fonte de um repositório, analisa o conteúdo destes arquivos procurando lugares onde o CNPJ é representado de forma numérica e indique como possíveis pontos de adaptação (PPA) para serem adaptados para CNPJ alfanumérico, fazendo a adaptação necessária no código para que o CNPJ representado aceite números com caracteres alfanuméricos.
   - Requisitos extras:
      - O aplicativo deve ser capaz de fazer a adaptação para as linguagens Python, JavaScript, Java, C# e PHP;
      - O aplicativo deve mostrar uma tela onde o usuário escolhe quais PPAs serão efetivamente adaptadas e terão o código alterado;
      - O aplicativo deve realizar busca, identificação e adaptação transversal e em lote do código para outras necessidades além do CNPJ alfanumérico
4. Tarefa 4: Tentar usar uma IA para criar uma função que define o GAEL a partir dos quatro graus básicos: grau de criticidade, grau de longevidade, grau de complexidade e grau de particularidade
   - Prompt: Crie um método que recebe quatro graus (criticidade, longevidade, complexidade e particularidade) e retorne o GAEL (Grau de Atenção a Entrada no Loop)
   - Reflexão: A IA não faz ideia do que se trata e gera algo sem conexão com o problema
### Takeaways
1. A tarefa 1 tem um problema simples e conhecido
2. A tarefa 2 tem um problema igualmente simples a autocontido, mas um pouco desconhecido (particular porém disponível)
3. A tarefa 3 tem um problema que está bem definido na cabeça dos instrutores, mas é bem mais complexo. Cada aluno deve ter pensado uma solução diferente da dos instrutores. Precisa de interação entre os "donos do problema" e os alunos além de necessidade de alguma decomposição antes de passar a tarefa pra IA (Dev In The Loop)
- Material de exemplo: PAAT e seus módulos

## Atividade 2 (Heurística 2 - Garantia da Confiança) - Percepção da necessidade de saber sobre o que se está garantindo e validando agregando segurança, privacidade e ética (SPE)
1. Tarefa 1: Uso de IA Code para criar um jogo da velha com jogadores anônimos - todo mundo pode validar um jogo da velha
2. Tarefa 2: Uso de IA code para criar um jogo de xadrez para crianças na linguagem LUA com jogadores que precisam logar com Gov.br
- Takeaway: Reforço da atividade anterior (Simples x Complexo), mas ambos os casos são muito conhecidos. A tarefa 2 é conhecida, mas nem todos sabem todas as regras do xadrez de forma completa. A primeira qualquer pessoa pode garantir e validar. Já a segunda além de menos provável é em uma linguagem pouco comum e com elementos de SPE que devem ser responsabilidade humana

## Atividade 3 (Heurística 3 - Maximização da Eficiência) - 
1. Tarefa 1: Use uma IA para criar um teste de unidade para a função que decide a vitória no jogo "Pedra, Papel e Tesoura"
   - Prompt: Crie um teste de unidade para uma função de decide quem vence entre duas opções do jogo "Pedra, Papel e Tesoura"
   - Reflexão: uma vez definido uma função ou método, as IA são muito boas em fazer testes de unidade que é uma atividade repetivida (dependendo do caso)
2. Tafefa 2: Use uma IA para gerar massa de CNPJ para testes.
   - Prompt: Crie uma lista de CNPJs com base na nova regra de CNPJ alfanuméricos. Crie 10 CNPJ válidos e 10 CNPJ inválidos (com DV inválido).
3. Tarefa 3: Criar a função de cálculo do GAEL "na mão" e depois usando uma IA. Avalie o que foi mais eficiente.
   - Prompt : Crie um código que calcula o GAEL a partir da seguinte especificação... ESPECIFICAÇÃO
   - Reflexão: Neste caso que a IA não faz ideia que que é o GAEL, é mais eficiente escrever uma especificação extensa ou faezr o código direto?
   
## Atividade 4 (Heurística 4 - Rotina de Aprimoramento) - 

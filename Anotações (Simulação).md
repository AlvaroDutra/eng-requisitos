# Anotações (Simulação da Entrevista)

Aqui estão os pontos principais identificados durante a conversa com a Maria:

    Rapport: Iniciamos falando sobre os 15 anos dela na instituição. Ela se orgulha muito da organização, mas admite cansaço.

    Anotação sobre Pergunta 4 (Grade): Maria hesitou. Disse que "dá muito trabalho". Quando sondada (Técnica de Sondagem 1: Silêncio/Eco), ela revelou que o maior problema é o conflito de horários que as planilhas não avisam.

    Anotação sobre Pergunta 10 (Indispensáveis): Ela foi vaga: "Quero que funcione". Usei a Técnica de Sondagem 2: Especificação ("O que exatamente 'funcionar' significa para o seu relatório de fechamento?"). Ela explicou que precisa que o sistema calcule a média final sozinho, sem ela ter que conferir na calculadora.

    Comunicação não-verbal: Ela cruzou os braços ao falar de "abandonar as planilhas", indicando medo de perder o histórico.

## Lista de Requisitos Identificados

Após a simulação, filtramos o que a Maria realmente precisa:

### Requisitos Funcionais (RF)

    RF01: O sistema deve permitir a montagem da grade horária de forma visual (drag-and-drop).

    RF02: O sistema deve gerar relatórios automáticos de rendimento acadêmico por turma e por aluno.

    RF03: O sistema deve permitir a importação de dados históricos via arquivos Excel (.xlsx).

    RF04: O sistema deve calcular automaticamente a média final baseada nas fórmulas de avaliação do curso.

### Requisitos Não-Funcionais (RNF)

    RNF01: Interface intuitiva (baixa curva de aprendizado para usuários acostumados com tabelas).

    RNF02: O sistema deve processar a geração de relatórios de curso em menos de 5 segundos.

    RNF03: Segurança de dados: apenas a coordenadora e a secretaria podem editar notas após o fechamento do período.

### Regras de Negócio (RN)

    RN01: Um professor não pode ser alocado em duas disciplinas no mesmo horário.

    RN02: O sistema deve impedir o lançamento de notas após a data limite estipulada no calendário acadêmico.

    RN03: Alunos com frequência inferior a 75% devem ser sinalizados automaticamente como reprovados.

## Reflexão

    O que funcionou bem: O uso das técnicas de sondagem foram muito importantes. Quando a Maria deu respostas vagas como "é complicado", o uso do eco ("Complicado em que sentido?") ajudou a entender que o problema real era a falta de comunicação com os professores.

    O que poderia melhorar: Após reavaliar as perguntas do roteiro original, percebos que elas eram um pouco longas. Na próxima, faremos perguntas mais curtas para deixar o entrevistado falar mais tempo. Também notamos que a Maria precisa de garantias visuais (protótipos) para confiar que o sistema será útil e não desperdiçar os 15 anos de experiência dela.

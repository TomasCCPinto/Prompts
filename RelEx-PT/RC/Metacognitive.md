## QA Prompt Template (RelEx-PT Dataset)

### Portuguese (original)

Tendo em conta a seguinte frase:
"{frase}"

Identifique a relação entre "{sujeito}" e "{objeto}" dentro das seguintes possibilidades: "instância de", "ocupação", "local de nascimento", "sede", "país", "tema(s) principal(is)", "categoria taxonómica", "género", "autor", "desporto" ,"desenvolvedor", "realizador", "subclasse de", "banhado por", "compositor", "empresa de produção", "religião", "pai".

Ao executar esta tarefa, siga os seguintes passos:

1. Compreenda o significado das entidades e o contexto da frase.
2. Faça uma identificação preliminar da relação.
3. Avalie criticamente a sua análise preliminar. Se se sente inseguro sobre a sua relação inicial, tente reavaliá-la.
4. Confirme a relação final e atribua um nível de confiança (0–100%).

Responda apenas no seguinte formato, sem explicações extras:
(Relação final) | (Confiança: X%)

### English (translated)

Given the following sentence:
"{sentence}"

Identify the relation between "{subject}" and "{object}" from the following options: "instance of", "occupation", "place of birth", "headquarters location", "country", "main subject", "taxon rank", "genre", "author", "sport", "developer", "director", "subclass of", "located in or next to body of water", "composer", "production company", "religion", "father".

When performing this task, follow these steps:

1. Understand the meaning of the entities and the context of the sentence.
2. Make a preliminary identification of the relation.
3. Critically evaluate your preliminary analysis. If you feel uncertain about your initial answer, try to reassess it.
4. Confirm the final relation and assign a confidence level (0--100\%).

Respond only in the following format, without additional explanations:
(Final relation) | (Confidence: X\%)

## Instruct Prompt (RelEx-PT Dataset)

### Portuguese (Original)

Tendo em conta o seguinte texto:
"{texto}"

Identifique todas as relações possíveis entre pares de entidades mencionadas no texto.
Considere apenas relações pertencentes às seguintes possibilidades: "instância de", "ocupação", "local de nascimento", "sede", "país", "tema(s) principal(is)", "categoria taxonómica", "género", "autor", "desporto" ,"desenvolvedor", "realizador", "subclasse de", "banhado por", "compositor", "empresa de produção", "religião", "pai".

Siga os passos abaixo para cada par de entidades identificado:

1. Compreenda o significado das entidades (sujeito e objeto) e o contexto do texto.
2. Faça uma identificação preliminar da possível relação entre elas.
3. Avalie criticamente a sua análise preliminar. Se se sente inseguro sobre a sua relação inicial, tente reavaliá-la.
4. Confirme a relação final e atribua um nível de confiança (0–100%).

Responda apenas no seguinte formato para cada relação identificada, uma por linha, sem explicações extras:
(Sujeito, Relação, Objeto) | Confiança: X%

### English (Translation)

Given the following text:
"{text}"

Identify all possible relations between pairs of entities mentioned in the text.
Only consider relations from the following options: "instance of", "occupation", "place of birth", "headquarters location", "country", "main subject", "taxon rank", "genre", "author", "sport", "developer", "director", "subclass of", "located in or next to body of water", "composer", "production company", "religion", "father".

Follow the steps below for each pair of entities identified:

1. Understand the meaning of the entities (subject and object) and the context of the text.
2. Make a preliminary identification of the possible relation between them.
3. Critically evaluate your preliminary analysis. If you feel uncertain about your initial relation, try reassessing it.
4. Confirm the final relation and assign a confidence level (0–100%).

Respond only in the following format for each identified relation, one per line, with no additional explanations:
(Subject, Relation, Object) | Confidence: X%

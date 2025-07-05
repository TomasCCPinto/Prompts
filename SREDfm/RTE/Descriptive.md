## Instruct Prompt (RelEx-PT Dataset)

### Portuguese (Original)

Leia o seguinte texto:
"{texto}"

Para cada possível relação entre entidades, forneça um trio no seguinte formato:
(Sujeito, Relação, Objeto)

Explicação das relações possíveis:

- "sede": organização e a sua sede (localização).
- "autor": obra literária e o seu criador.
- "género": obra ou artista e o seu género.
- "desenvolvedor": item e organização ou pessoa que o desenvolveu.
- "instância de": item específico e a sua classe geral.
- "ocupação": pessoa e a sua ocupação/profissão.
- "local de nascimento": uma pessoa e o local onde nasceu.
- "país": item e o país a que pertence.
- "tema(s) principal(is)": obra e o seu assunto principal ou um dos.
- "categoria taxonómica": ser vivo e a sua classificação biológica.
- "desporto": pessoa/evento e o desporto associado.
- "realizador": obra audiovisual e o seu diretor/realizador.
- "subclasse de": classe e a sua superclasse.
- "banhado por": local e o mar, lago ou rio adjacente.
- "empresa de produção": filme, áudio ou trabalho artístico e a sua empresa produtora.
- "religião": pessoa, organização ou construção e a sua religião.

Responda apenas com os trios no formato indicado, um por linha, sem explicações extras.

### English (Translation)

Read the following text:
"{Text}"

For each possible relation between entities, provide a triple in the following format:
(Subject, Relation, Object)

Explanation of possible relations:

- "headquarters location": organization and its headquarters (location).
- "author": literary work and its creator.
- "genre": work or artist and its genre.
- "developer": item and organization or person who developed it.
- "instance of": specific item and its general class.
- "occupation": person and their occupation/profession.
- "place of birth": a person and the place where they were born.
- "country": item and the country it belongs to.
- "main subject(s)": work and its main subject or one of them.
- "taxon rank": living being and its biological classification.
- "sport": person/event and the associated sport.
- "director": audiovisual work and its director.
- "subclass of": class and its superclass.
- "located in or next to body of water": location and the adjacent sea, lake, or river.
- "production company": film, audio, or artistic work and its production company.
- "religion": person, organization, or structure and its religion.

Respond only with the triples in the indicated format, one per line, with no additional explanations.

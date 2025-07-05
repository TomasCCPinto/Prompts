## Instruct Prompt (RelEx-PT Dataset)

### Portuguese (Original)

Leia o seguinte texto:
"{texto}"

Passo 1: Identifique todas as entidades mencionadas no texto.
Passo 2: Para cada par de entidades encontradas, verifique se há uma relação explícita entre elas.
Passo 3: Se houver relação, escolha a melhor entre as seguintes opções: "instância de", "ocupação", "local de nascimento", "sede", "país", "tema(s) principal(is)", "categoria taxonómica", "género", "autor", "desporto" ,"desenvolvedor", "realizador", "subclasse de", "banhado por", "compositor", "empresa de produção", "religião", "pai".
Passo 4: Responda apenas com os trios identificados, um por linha, no formato:
(Sujeito, Relação, Objeto)

Não forneça explicações extras.

### English (Translation)


Read the following text:  
"{text}"  

Step 1: Identify all entities mentioned in the text.  
Step 2: For each pair of entities found, check if there is an explicit relation between them.  
Step 3: If there is a relation, choose the most appropriate one from the following options:  "instance of", "occupation", "place of birth", "headquarters location", "country", "main subject", "taxon rank", "genre", "author", "sport", "developer", "director", "subclass of", "located in or next to body of water", "composer", "production company", "religion", "father".    
Step 4: Respond only with the identified triples, one per line, in the format:  
(Subject, Relation, Object)  

Do not provide any additional explanations.

# Character Node
## Instructions for data entry
PBot Schemas are hierarchical structures with lower-ranks being dependent on higher-ranks. Therefore, each rank must be added to a Schema in order from the highest position in the hierarchy to the lowest position in the hierarchy. 
* For simplicity, “characteropsis” and “characteropses” will be used as generalized terms to refer to any rank of organizational header or character in the hierarchy. 
* “Characteropsis” ranks available in PBot include organizational header, organizational subheader, organizational subsubheader, organizational subsusbsubheader, and character. Although character is listed as the lowest-ranked “characteropsis,” it can be dependent on any rank of organizational header. 
* A lower-ranked “characteropsis” such as organizational subheader is directly dependent on a higher- ranked “characteropsis” such as organizational header. When dependencies exist, the higher-ranked “characteropsis” is known as the parent “character.” 

## REQUIRED FIELDS: 
**Schema** –  Select a schema from the dropdown menu to add a characteropsis. 

**Parent Character** – Select the higher-ranked characteropsis the new characteropsis being added is dependent on. Skip this step if you are entering an organizational header. Organizational headers are dependent on the schema (selected above). Also skip this step in cases where a character is not dependent on any rank of organizational header and is directly dependent on the schema.

**Name** – Enter any rank of organizational header name using title case. Enter character name using sentence case.

## OPTIONAL FIELDS:
**Definition** – Enter a brief definition using sentence case. Include citation(s) if appropriate. 

**Order** – This function allows schema developers to control where characteropses names appear in lists for users. Enter a number to indicate the position of each characteropsis for listing purposes. Order is specific to each rank of organizational header and each character rank group (see example below).

Header (order 1): Mammal Coloration <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Subheader (order 1): Mammal Head<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 1): Nose color<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 2): Ear color<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 3): Eye color<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Subheader (order 2): Mammal Tail<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 1): Base of tail<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 2): Shaft of tail<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 3): Tip of tail<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Subheader (order 3): Mammal Body<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 1): Primary color<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 2): Secondary color<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Character (order 3): Pattern observed<br>

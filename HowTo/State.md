# State Node
## Instructions for data entry
PBot schemas are hierarchical structures with lower-ranks being dependent on higher-ranks. Therefore, each rank must be added to a schema in order from the highest position in the hierarchy to the lowest position in the hierarchy. 
* For simplicity, “state” and “states” will be used as generalized terms to refer to any rank of state or states in the hierarchy. 
* “State” ranks available in PBot include state, substate, subsubstate, subsubsubstate, and subsubsubsubstate.
* A lower-ranked “state” such as subsubstate is directly dependent on a higher-ranked “state” such as substate. When dependencies exist, the higher-ranked “state” is known as the parent “state.” 

## REQUIRED FIELDS: 
**Schema** – Select a Schema from the dropdown menu to add an associated “state.” 

**Character** –  Select a Character from the dropdown menu to add an associated “state.”

**Parent “state”** – Select the higher-ranked “state” the new “state” being added is dependent on.  Skip this step if you are entering a state. States are dependent on the characters (selected above). 

**Quantitative** – Check this box if the “state” being entered is quantitative. If the “state” is categorical, leave this box unchecked.

**Name** – Enter “state” name using lower case (e.g., marginal). Do not include terms like “unknown” or “indeterminate” as “states”. These lead to erroneous synonymies.

## OPTIONAL FIELDS:
**Definition** – Enter a brief definition using sentence case. Include citation(s) if appropriate. 

**Order** – This function allows schema developers to control where “state” names appear in lists for users. Enter a number to indicate the position of each “state” for listing purposes. Order is specific to each character and each “state” rank group (see example below). 

Character (order 1): Primary color of the mammal body<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;state (order 1): white<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 1): solid<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 2): spotted<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 3): striped<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 4): other<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;state (order 2): black<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 1): solid<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 2): spotted<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 3): striped<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 4): other<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;state (order 3): tawny<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 1): solid<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 2): spotted<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 3): striped<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 4): other<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;state (order 4): dark brown<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 1): solid<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 2): spotted<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 3): striped<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;substate (order 4): other

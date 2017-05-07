# ft\_printf @ 42
it's just a main set to test your printf but my ft_printf is in my library in all my others projects.

#### Objectifs

• Vous devez recoder la fonction printf de la librairie C.<br/>
• Votre fonction s’appelera ft_printf et sera prototypée de la même façon que
printf.<br/>
• Vous ne ferez pas la gestion de buffer présente dans la fonction printf de la librairie
C.<br/>
• Vous devez gérer les conversions suivantes : sSpdDioOuUxXcC<br/>
• Vous devez gérer le %%<br/>
• Vous devez gérer les flags #0-+ et espace<br/>
• Vous devez gérer la taille minimum du champ<br/>
• Vous devez gérer la précision<br/>
• Vous devez gérer les flags hh h l ll j z<br/>

#### Fonctions autorisées

◦ write
◦ malloc
◦ free
◦ exit
◦ les fonctions du man 3 stdarg



Extra conversions:

| Name		| Conversion	| Example output	|
| --------- | ------------- | ----------------- |
| Binary	| b				| 00001001			|

## Compiling
Run `make` to compile the
library. Use it like you would use the `printf` function:

```c
int i;

i = 42;
ft_printf("value: %d\n", i);

// value: 42
```

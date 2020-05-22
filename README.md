# Interfaces
## Herança múltipla e o problema do diamante

**Problema do diamante:**

![ProblemaDiamante](https://github.com/glauberfernandes/interfaces4-java/blob/master/ProblemaDiamante.PNG)

A herança múltipla pode gerar o problema do diamante: uma ambiguidade causada pela existência do mesmo método em
mais de uma superclasse.

Herança múltipla não é permitida na maioria das linguagens!

Porém, uma classe pode implementar mais de uma interface

![SolucaoDiamante](https://github.com/glauberfernandes/interfaces4-java/blob/master/SolucaoDiamante.PNG)

**ATENÇÃO:**

> Isso NÃO é herança múltipla, pois NÃO HÁ REUSO na relação entre ComboDevice e as interfaces Scanner e Printer.
ComboDevide não herda, mas sim implementa as interfaces (cumpre o contrato).

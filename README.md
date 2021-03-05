# Entorns de desenvolupament
## Optimització
### Pudor al codi(code smell)
- Símptoma que indica que el codi font conté un problema més profund.
- No solen ser bugs(errors), no son tècnicament incorrectes i tampoc impedeix que el programa funcioni correctament.
- Indica deficiència al disseny que pot desenvolupar o afegir el risc d'errors o fallades a futur.
- Motiu important per realitzar la refactorització.

### Anàlisis de codi
- **Anàlisis dinàmic:** (unit tests)
- **Anàlisis estàtic:** (lint)

### Anàlisis estàtic de codi
- Mitjantçant analitzadors estàtics(**linters**)
- Mitjantçant llocs webs per inspeccionar codi(**Constinuous Inspection**)

### Linters
- Analitzadors estàtics de codi:
   - **lint:** C
   - **Sonar:** Java
   - **JSLint, ESLint:** Javascript

### Continuous Inspection o Continous Analysis
- Llocs web que ofereixen **inspecció de codi**:
   - Scrutinizer
   - SonarQube

## Refactorització
- Procés de reestructurar un codi font alterant su estructura interna sense canviar el seu comportament
- Tècniques:
  - Renombrar variables
  - Passar codi duplicat a funcions
  - Eliminar codi inalcanzables
  - Eliminar codi redundant
  - Eliminar codi mort

## Documentació
- Documentació de codi
- Documentació tècnica
- Documentació d'usuari

### Formats de documentació
- **HTML:** javadoc
- **Markdown:** Gitbook
- **reStructuredText:** Readthedocs
- **asciiDoc**
## Control de versions
- **CVS**
- **Subversion**
- **Mercurial**
- **Git**

### Git
- Característiques:
   - Modern
   - Distribuït
   - Eficient
- Conceptes:
   - Repository(local & remot)
   - Commit
   - Branch
       - Checkout
       - Merge(fast-forward, 3-way)

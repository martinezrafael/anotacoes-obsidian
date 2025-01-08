Nesta Pista Lenta nós vamos revisitar a história dos versionadores de código para entender a diferença entre o modelo `centralizado` e `distribuido`, e também pincelar como que as pessoas faziam para lidar com versionamento antes de inventarem os controladores de versão. Além disso, mostro como utilizar o **Local History**, um recurso muito interessante do VSCode, falo sobre **Merge Conflict** e onde que fica a pasta `.git`.

===Versionamento de código centralizado===

1972 - Bell Labs - SCCS Source Code Control System (Primeiro sistema digital de versionamento)
1982 - RCS Revision Control System
1986 - CVS
2000 - SVN

===Versionamento de código distribuído===

2005 - Linus Torvalds - GIT 


**Centralizado**: Em um sistema centralizado, existe uma cópia principal do repositório do código e as pessoas reservam/alugam os arquivos para dentro do seu computador e esses arquivos que foram reservados/alugados ficam indisponíveis para as outras pessoas que estão trabalhando no projeto.

**Distribuído**: Todas as pessoas que trabalham no projeto, tem uma cópia integral do projeto na sua máquina e pode modificar a vontade, sem trava alguma.

**Merge Conflict:** Quando o algorítimo não consegue resolver a junção das modificações, e isso precisa ser resolvido manualmente por um humano.

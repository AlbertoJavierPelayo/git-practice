# Laboratory 9 report

##Introduction
This lab focuses in implementing CI/CD pipeline

## Evidence

| # | Screenshot | Part |
|---|---|---|
| 1 | File staged (git status) | A.2 |
| 2 | git log with three commits | A.2 |
| 3 | Graph with the merge commit | A.3 |
| 4 | git-practice on GitHub | A.6 |
| 5 | Commit from GitHub pulled locally | A.7 |

## Reflection

**Q1. Is version control convenient for non-code documents? Use your Part B results (Markdown vs. Word).**
Sí, el control de versiones es muy conveniente para documentos que no son de código cuando se usan formatos de texto plano como Markdown. Como se vio en la Parte B, Git rastrea fácilmente los cambios línea por línea en los archivos `.md`, y el comando `git diff` resalta claramente las adiciones o eliminaciones exactas. Sin embargo, no es tan útil para formatos binarios como Microsoft Word (`.docx`). Cuando se modifica y se hace commit de un archivo de Word, Git solo detecta que el archivo binario cambió en su totalidad, pero no puede mostrar las diferencias de texto específicas en la terminal, lo que dificulta rastrear exactamente qué se editó.
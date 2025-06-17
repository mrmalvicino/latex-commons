# LaTeX Commons

&nbsp;
Paquetes, comandos y entornos para documentos LaTeX.

## Setup

&nbsp;
Agregar este repositorio como submódulo en un proyecto LaTeX:
```bash
git submodule add https://github.com/mrmalvicino/latex-commons utils/latex-commons
```

&nbsp;
Importar los archivos necesarios en `main.tex`, por ejemplo:
```tex
\input{./../utils/latex-commons/src/book_setup/book_packages.tex}
\input{./../utils/latex-commons/src/book_setup/book_commands.tex}
\input{./../utils/latex-commons/src/book_setup/book_environments.tex}
```

&nbsp;
Al clonar un proyecto que usa este submódulo, asegurarse de incluirlo:
```bash
git clone --recurse-submodules <repo>
```

&nbsp;
Si ya se clonó sin submódulos, inicializarlos con
```bash
git submodule update --init --recursive
```

&nbsp;
Para restaurar la referencia desde un proyecto consumidor, dirigirse a `utils/latex-commons` y ejecutar
```bash
git fetch origin
git checkout main
git pull origin main
```

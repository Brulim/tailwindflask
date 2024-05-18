## TAILWINDFLASK

**DOCUMENTANDO O PROJETO**

Como boa prática, é recomendável documentar cada projeto.
O arquivo README.md é um padrão de documentação que aparece na tela inicial do repositório no Github, por isso utilizo para as informações iniciais de cada projeto.
[Instruções para editar README](https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)

**OBJETIVO**

O objetivo deste projeto é criar um projeto padrão para iniciar o desenvolvimento de um projeto Flask estilizado com Tailwind.

**REQUISITOS INICIAIS - INSTALADOS NO WINDOWS**

Necessário ter instalado na máquina o Python e o Node.

**AMBIENTE VIRTUAL**

Antes de instalar os outros complementos é recomendado criar um ambiente virtual, executando o seguinte comando no terminal (será criada a pasta "venv"):

...
python -m venv venv
...

E para iniciar o ambiente virtual, utiliar o seguinte comando no terminal (note que ao lado esquerdo do caminho estará a expressão "venv"):

...
.\venv\Scripts\activate
...

**CONFIGUANDO O AMBIENTE - FLASK + TAILWIND**

Antes de seguir o tutorial será necessário instalar o flask na variável de ambiente:

...
pip3 install flask
...

[Tutorial:](https://www.codewithharry.com/blogpost/using-tailwind-with-flask/)

**INICIANDO UM NOVO PROJETO A PARTIR DE UM CLONE DESTE NO GITHUB**

Em breve!

**CONSIDERAÇÕES FINAIS**

Será necessário manter dois terminais rodando, sendo um o ambiente virtual, e outro com o node:

...
npx tailwindcss -i ./static/css/input.css -o ./static/css/output.css --watch
...
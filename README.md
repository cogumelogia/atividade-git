Seja bem vindo! Este LEIA-ME é parte da atividade do Curso Dev Full Stack do Senai São Paulo e estamos praticando comandos de versionamento utilizando GIT.
Abaixo relacionaremos comentários sobre os comandos utilizados durante a prática:

1. Criando um .gitignore para mudanças que não precisam ser observadas
comandos:
a. touch .gitignore - criando arquivo .gitignore;
b. git add .gitignore - adicionando arquivo .gitignore no repositório;
c. git commit -m "versão inicial do projeto" - aceitando a adição e comentando o início do projeto.

2. Criando nova branch para mudanças
comandos:
a. git checkout -b nova-branch - criando uma nova branch para fazer mais alterações concomintantes antes de atualizar tronco (master)

3. Merge de trabalhos em branchs simultâneas
comandos:
a. git merge [nome da branch];
b. aviso de conflitos no tronco (master);
c. git mergetool - resolvendo conflitos utilizando o programa gráfico meld.exe (https://sourceforge.net/projects/meld-installer/);
d. compare & pull request em Github.com.

4. Criando tag de versão
comandos:
a. git tag -a v1.0 -m "primeira versão";
b. git tag - para conferir versão criada no repositório local;
c. git push origin --tags - para inserir tag criada ao repositório remoto.
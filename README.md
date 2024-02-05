Este é um site básico que funciona como uma agenda de eventos, onde cada usuário pode cadastrar seus eventos e monitorar as datas, bem como edita-los.
A interface gráfica não foi desenvolvida "fica aberto a sugestões", mas a parte funcional está quase que completa.

Existem alguns problemas, mas serviu para o aprendizado de algo muito importante, a necessidade de login e a possíbilidade de editar e ver apenas os eventos que você (com seu login) cadastrou.
A parte de registro não foi elaborada, então crie seu usuário admin assim --- (python manage.py createsuperuser) digite login e senha e pronto.
Para testar:

Tenha o python instalado;
1) Crie uma pasta e clone esse repositório dentro dela (se usa o VScode, abra um terminal dentro da pasta e rode "git clone "link do repositório")
2) Abra o ambiente virtual caminhando até seu local de instalação e executando o arquivo Ativate "venv/Scripts/Activate.ps1"
3) Por fim digite no terminal "python manage.py runserver"
observações. Se o ambiente virtual der problema, crie um novo ambiente seguindo os passos abaixo:

1) pip install virtualenv
2) virtualenv venv
3) venv/Scripts/Activate.ps1
4) pip install django
5) pip install pillow
6) python manage.py makemigration (puxa os itens que ainda não estão no banco de dados)
7) python manage.py migrate (cria o banco de dados com os arquivos faltantes)
8) python manage.py runserver (executa o site em modo localhost)

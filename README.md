![logo_semfundo](https://github.com/user-attachments/assets/dd912800-1511-42cd-95ca-670641f15fda)

# Sobre
123folhas foi um projeto de finalização do 2º período das matérias de Engenharia de Requisitos, Banco de Dados, Interação Humano Computador e Programação WEB. A proposta foi fazer uma feramenta de agregação de viagens somente ecológicas, facilitando a busca e o salvamento delas. Foi usado HTML, CSS e JavaScript puro para o front. Para o back, usamos PHP e MySQL para o banco de dados. Para o planejamento, fizemos um diagrma de casos de uso e diagramas conceituais do banco de dados. Para o planejamento do design, foi feito uma prototipação no Figma: https://www.figma.com/design/IsUTm7m6Gpja4XrkSvUrj8/123folhas?m=auto&t=kuxl0m1cQbY4U3hW-1

# Instalação e execução
### 1. Aplicativos necessários
- Xampp: usamos o xampp para simular um sevidor, mas de forma local. Descompacte o projeto dentro da pasta "htdocs" do xampp. 
- MySql Workbench: recomendamos usar o workbench para a instalação do banco de dados. O arquivo de backup do banco de dados se chama "newDatabase.sql". Abra o aplicativo, vá na aba Server, clique em Data import e importe o arquivo. Talvez seja necessário a criação de uma nova instância do banco de dados para se adequar às configurações de conecção do projeto, que são: localhost:3306 (server name), root (user), PUC@1234 (password), 123folhas (bd name). Ou se preferir, altere essas configurações (connection.php) para se adequar à sua instancia.
- Navegador (projeto desenvolvido usando o Chrome).
### 2. Ative o servidor apache do Xampp
### 3. Abra o navegador e acesse http://localhost/123folhas/

# Funcionalidades
- ### Salvar viagens nas listas "Quero ir" ou "Já fui"
Acesse qualquer destino e clique em "Salvar destino" para adiciona-lo às listas.
![374386484-ea7e39f3-3aa1-4f4c-beef-020311d04da3](https://github.com/user-attachments/assets/5ed5bd34-49d7-4b20-92f8-bf33fa8db258)
![image](https://github.com/user-attachments/assets/b0a0d809-b488-4024-a3cc-fc6a23cc7398)

- ### Gerencie tudo
Gerencie todas as tabelas do banco de dados relacional, clientes, destinos, blog, brindes, blog e cupons. Essa página só pode ser acessada por usuários com privilégios de admin.
![image](https://github.com/user-attachments/assets/a910d23c-262b-485e-a81d-98037a1be182)

- ### Adicione cupons para ganhar pontos e trocar por brindes
![image](https://github.com/user-attachments/assets/45cdf4d7-0a39-478b-907d-f7ef7da808af)

- ### Pesquisa de destinos por filtros
![image](https://github.com/user-attachments/assets/0e46638c-6fd1-4d00-a9d7-bf3d6ab4e9af)

- ### Leia blogs
![image](https://github.com/user-attachments/assets/d76ceccd-76a5-4c11-9f64-93338bfcd140)


- ### Outras
Além dessas funcionalidades principais, temos as basicas, login, cadastro, edição e exclusão de usuário.

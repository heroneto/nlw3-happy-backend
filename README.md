## O que é este projeto
Este é um Backend do app Happy desenvolvido durante a semana NLW 3 da Rocketseat.
O app Happy foi criado para integrar orfanatos com voluntários para agendamento de visitas.

## Como este projeto funciona
Este é um projeto feito em Nodejs, é necessário tê-lo instalado na sua máquina. Após isso clone o repositório e execute os comandos abaixo

    Instalar dependências
    npm install

    Executar as Migrations
    npm run typeorm migrations:run

    Criar pasta uploads na raiz do projeto
    mkdir uploads

    Iniciar servidor de desenvolvidmento
    npm run dev

## Como ele foi desenvolvido
O projeto foi desenvolvido em NodeJs, utilizando Typescript como linguagem de programação. Além disso, foram utilizados algumas bibliotecas e frameworks para auxiliar no desenvolvimento:

-  Express: Servidor web
-  Yup: Tratativa de erros
-  multer: Upload de arquivos
-  typeorm: ORM de banco de dados.


## Screenshots Insomnia

Criação Orfanato
<img src="https://raw.githubusercontent.com/heroneto/nlw3-happy-backend/main/screenshots/criacao_orfanato.PNG" alt="Happy">

Listagem de orfanatos
<img src="https://raw.githubusercontent.com/heroneto/nlw3-happy-backend/main/screenshots/listagem_orfanatos.PNG" alt="Happy">

Detalhes do Orfanato
<img src="https://raw.githubusercontent.com/heroneto/nlw3-happy-backend/main/screenshots/detalhes_orfanato.PNG" alt="Happy">

Validação de erros API
<img src="https://raw.githubusercontent.com/heroneto/nlw3-happy-backend/main/screenshots/valida%C3%A7%C3%A3o_erros.PNG" alt="Happy">

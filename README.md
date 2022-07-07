![Animação-pt14](https://user-images.githubusercontent.com/86725282/177658812-4af1285b-c0fa-423c-9c14-555111e1a1c9.gif)

# Ignews - Ignite 

:pushpin: Este é um projeto construido durante o curso ignite da rocketseat. O projeto funciona basicamente como um blogue onde apenas pessoas que são assinantes podem acessar o conteudo completo, os posts do blog são criados atraves de um cms, o loguin é feito atraves do GitHub. 

:green_book: Aprendi com esse projeto a usar o next e suas "funçoes" como o next-api, getStaticProps, getServerSideRender, a usar e implementar um meio de pagamento, implementar um banco de dados, um cms entre vários outros hacks vistos durante a aula.

## Tecnologias utilizadas:
- Next.js,
- Prismic cms,
- Fauna Db, 
- Stripe, 
- Axios, 
- Sass, 
- react-icons 


#
### Como iniciar o projeto: 
Primeiro clone o repositorio na sua maquina, depois rode o comando:  `npm install` para instalar todas as dependencias. 

> Após isto execute o seguinte comando para excutar o stripe.
```bash
.\stripe listen --forward-to localhost:3000/api/webhooks
```
> Execute o comando abaixo para iniciar a aplicação.
```bash
yarn dev
```

## E pronto :fire:



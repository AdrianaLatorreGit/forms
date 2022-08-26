** Project for creating a front-end page and back-end system to store the form information in the FIREBASE database

<div align="center">
   <a href="https://mundo-invertido-adrianalatorre.netlify.app/" target="_blank">Front-end DEMO</a>
   </div>
   <br/>

![Captura de Tela 2022-08-26 às 15 34 38](https://user-images.githubusercontent.com/101880897/186973659-fb3cc43c-ecc0-42d6-a057-63fbc9559140.png)

![Captura de Tela 2022-08-26 às 15 34 48](https://user-images.githubusercontent.com/101880897/186973679-e233c03f-77bd-4d02-b028-fe5bc7c2329c.png)

![Captura de Tela 2022-08-26 às 15 15 56](https://user-images.githubusercontent.com/101880897/186973696-b84e22ec-cb9b-4530-84bb-d1a6143638fa.png)

![Captura de Tela 2022-08-26 às 15 44 00](https://user-images.githubusercontent.com/101880897/186981287-029bdfa3-d5a1-450e-9d81-1474b35d8c83.png)

\*\*Integração com banco FIREBASE

-   npx http-server

*   http-server ./ (rodar página)

    -   Adicionar as actions do formulário via JavaScript
    -   Adicionar os Ids de identificação nos Inputs
    -   Adiciona o "click" e Id no botão
    -   Inserir type="module" no script html para importação nativa do firebase (sem - isso não funciona) - indica a sintaxe de importação do JavaScript
    -   exporta app e importa ele na main
    -   Trocar a importação do service (Hellfire) para FIRESTORE

*   Função getFirestore para manipular o banco (ela vem da importação do firebase-firestore)
*   Passar pra umas const a coleção, passando o nome e (db)getFirestore
*   addDoc para adicionar documentos a coleção, passando a coleção e documento
    -   addDoc é funcão assíncrona

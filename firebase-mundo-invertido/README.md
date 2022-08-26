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

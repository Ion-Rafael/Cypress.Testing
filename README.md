# Cypress.Testing



// describe("Site Google.com",()=>{

//     it("functioneaza cu o cautare basic",()=>{

//   cy.visit("https://google.com");
//   cy.get('#L2AGLb').click();
//   cy.get(".gLFyf").type('ce faci').type('{enter}');

//   cy.get('#result-stats').should('exist');


// })

// })


describe('Examples of',() =>{

// //Teste verificare segment din URL
// it('verific daca un URL contine ceva',() =>{

//     cy.visit('https://www.digi24.ro/stiri/economie/energie/romania-in-top-3-producatori-de-petrol-in-ue-in-2021-productia-de-titei-in-scadere-2296187');

//     cy.url().should('include' ,'/stiri/')




// })
    

// //Delay Testing

// it('astepta 10 secunde', ()=>{

//     cy.visit('https://www.google.com');
//     cy.get('#L2AGLb').click();
//     cy.wait(10000);

//     cy.get('.gLFyf').type('au trecut 10 secunde')


// })


// //Testul cu selector de timp atribut

// it('selectez folosind un atribut',() =>{
//    cy.visit('https://www.google.com');
//    cy.get("#L2AGLb").click();
//    cy.get('[alt=Google]').should('be visible');    //Sector atribut + assertion cu visible //[alt=Google]
// })


// //estul screenshot pe pagina

// it('fac un screenshot la pagina',() =>{
//     cy.visit('https://www.google.com');
//     cy.screenshot();
// })



// //Testul constanta si verificare continut input

// it('verifica o valoare din input',()=>{
//     cy.visit('https://www.google.com');
//     cy.get("#L2AGLb").click();
//     const googleSearch=cy.get('.gLFyf');  //Constanta

//     googleSearch.type('12345')
//     googleSearch.should('have.value','12345')  //Asertion contine textul
// })


// //Testul verifica existenta unei clase pe un element selectat

// it('verific o valoare din input',()=>{
//     cy.visit('https://www.libris.ro')
//     cy.get('#autoCompleteButton').should('have.class','onSearchClick')

// })
// })

















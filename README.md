**CYPRESS TARGETTING ELEMENTS:-**

**visit**:-  
Visit a remote URL.
for example:- 
1) cy.visit('http://localhost:3000')
2)  cy.visit('http://example.cypress.io/commands/actions')


**get**:-
Get one or more DOM elements by selector or alias.
for example:- 
1) cy.get('input').should('be.disabled')
2) cy.get('.dropdown-menu').click()

**should** :-
Create an assertion. Assertions are automatically retried until they pass or time out.
for example:-
1) cy.get('.error').should('be.empty')
2) cy.contains('Login').should('be.visible')

**eq**:-
Get A DOM element at a specific index in an array of elements.
for example:- 
1)cy.get('tbody>tr').eq(0)
2)cy.get('ul>li').eq(4)

**click** :-
Click a DOM elementor link. 
for example :-
1)cy.get('.btn').click()
2) cy.get("#type").first().click()

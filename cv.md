# Valenin Yurchenko

### About
2+ years experience working as quality assurance engineer  
Web, Desktop, Mobile. Frontend and Backend  
Automation. JavaScript + Cypress io  

### Skills:
1. Automation: Cypress io, JavaScript, Chai Js, Mocha
2. Test Management: Testrail
3. Bug Tracking: Jira
4. Tools: Postman, Mockoon, GIT, Jenkins, GitHub Actions, DevTools
5. English: B2 

### Job experience: 
Initially, I’ve joined the project without any testing processes.
I have implemented testing processes based mostly on functional testing; added testing documentation using Testrail TMS and built a team in a QA Department in almost 2 years. 
Right now I am responsible for implementing automation testing (JS + Cypress io)

### Education
I gradutaed Peter the Great St. Petersburg Polytechnic University in 2019.  
Master's degree in politican science

### Code Example
I'm using Cypress io to automate my test cases. So there is an example of code which fill application form and send it to server
``` 
describe('Test Contact Us Page via WebdriverUni', () => {
  it('Should be able to submit a succesful submission via contact us from', () => {
    cy.visit('http://www.webdriveruniversity.com/Contact-Us/contactus.html')
    cy.document().should('have.property', 'charset').and('eq', 'UTF-8')
    cy.title().should('include', 'WebDriver | Contact Us')
    cy.url().should('include', 'Contact-Us')
    cy.get('#contact-us').click()
    cy.get('[name="first_name"]').type('Joe')
    cy.get('[name="last_name"]').type('blogs')
    cy.get('[name="email"]').type('joe_blogs123@gmail.com')
    cy.get('textarea.feedback-input').type('How can I learn Cypress?')
    cy.get('[type="submit"]').click()
    cy.get('#contact_reply h1').should('have.text', 'Thank You for your Message!')
  })
});
```
### My Social
Here is my [LinkedIn](https://www.linkedin.com/in/valentin-yurchenko-215754259/)

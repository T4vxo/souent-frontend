# SE-app frontend

## Prerequisites
nodejs & npm 

`git clone` in desired directory
`npm install`

## Structure

###  Cards
Upon creating a new enterprise it is assigned a number of BMC cards. Members may not add or delete BMC cards.
BMC 


###  Members
Any contributor (member) may add or delete a member of their enterprise. It is not possible to update an existing member so instead one should instead delete the member and add a new one with correct information. Members may delete themselves from their enterprise.

### Auth
Googles Oauth is used to handle the login functionality. No account creation is needed.

### Styling
Bulma: css styling framework
Scss: extensible css 

## TODO
- Add user in an already existing social enterprice
- only 'gmail' users can join enterprises and login
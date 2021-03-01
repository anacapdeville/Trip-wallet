# Welcome to the repository Wallet!
## Tabela de conteúdos
  * [About](#about)
  * [Requirements](#requirements)
  * [Installation](#installation)

## About
The project was developed during the Trybe course using React and Redux to manage the state.

This application is a virtual wallet to be used on trips. On it is possible to add expenses on the currency of the country that the user is. The expense is added to a list of all expenses and the application shows the sum of all expenses converted to Brazilian Real.

The project uses an API that provides the currencys and it values compared to Brazilian currency.

##### Login page
![image](https://github.com/anacapdeville/Trip-wallet/blob/master/images_to_readme/login.png?raw=true)

##### Wallet page
![image](https://github.com/anacapdeville/Trip-wallet/blob/master/images_to_readme/wallet.png?raw=true)

## Requirements
The project had a list of requirements:

1. Create a initial page that user can login and be redirect to the wallet page.

2. Create a wallet page to manage the expenses.

3. Create a header on the wallet page that shows the email of the user, the sum of the expenses in Brazilian currency and the currency that is being used.

4. Create a form to add expenses with a input to add the value, a input to add a description, a menu to select the currency, a menu to select the form of the payment, a menu to select the tag of the expense and a button to add the expense. When the button is clicked it should add the expense and its informations on a table. 

5. Develop a table of expenses.

6. Create a button to delete an expense.

## Installation

1. Acesse the terminal and clone the project:

```
git clone git@github.com:anacapdeville/trip-wallet.git
```

2. Acces the directory and install the depedencies:
```
cd trip-wallet
npm install
```

3. Initialize the project:
```
npm start
```
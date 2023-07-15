
# Credit Card Validation using Luhn algorithm

A React component for verifying the validity of a credit card number using the [Luhn algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm).

## Demo

![Demonstration](demo/demo.gif)

## Features

- Calculates potential validity of credit card number
- Indicates card issuer corresponding to issuer identification number (IIN)
- Provides colored message indicating validity

### Supported card issuers

- Visa
- Mastercard
- Discover
- American Express

## Setup

```bash
$ git clone https://github.com/rizeen/MERN.git
$ cd MERN
$ npm install
$ npm start
```

View the app at `http://localhost:3000`.


#### Credit card number formatting
Credit card numbers should follow their respective spacing as seen on their actual cards.

#### Form validation
There should be visual indication that the user has not entered a complete credit card number (only after first `focus` event) and if the user attempts to exceed `maxLength`.

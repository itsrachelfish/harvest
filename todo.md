# Schema
## Species
- ID
- Common Name
- Taxonomic Name
- Description

## Specimens
- Species ID
- Weight
- Date

## Harvest
- Species ID
- Quantity
- Weight
- Date

## Meals
- Name
- Description
- Quantity
- Date

## Ingredients
- Species ID
- Meal ID

## Pictures (polymorphic)
- Reference ID
- Reference Type
- Filename
- Date


# Interface
- Bulma
- Server-side templates
- D3.js charts

## Templates
- Home page / about
- Activity log
- Stats page
- Login
- Basic CRUD
  - Species
  - Specimens
  - Harvest
  - Meals
- File upload / gallery

## Javascript
- Dynamic ingredient picker for meals
- Stats
  - Cumulative harvest weight
  - Weight by day
  - Weight by species


# Login system
There will be no user accounts in the alpha version of the harvest app—all user authentication is performed via keypair signatures. A list of valid public keys will be stored within the app and the user will be prompted to sign some random data on the login page. Initially this process will require the user to sign a message using a program on their computer, however this could be streamlined by using a browser extension or the WebCryptoAPI.

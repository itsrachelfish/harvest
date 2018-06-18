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

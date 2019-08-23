# Be My Bartender - Back-End

### Check out the [Front-End](https://github.com/Lexscher/be-my-bartender)

Recreating my MOD 1 Terminal project, [Bartender CLI App](https://github.com/Lexscher/Bartender_CLI_App)

API: [The CocktailDB](https://www.thecocktaildb.com/)

Models:

- Users `(id: BIGSERIAL PK, firstname, lastname, username, email, password_digest)`

- Cocktails `(id: BIGSERIAL PK, name, alcoholic: boolean)`

- Favorites `(id: BIGSERIAL PK, user_id: integer FK user.id, coctail_id: integer FK cocktail.id)`

- CustomCoctails `(id: BIGSERIAL PK, name, user_id: integer FK )`

- CocktailIngredients `(id: BIGSERIAL PK, name, alcoholic: boolean)`

- CustomIngredients `(id: BIGSERIAL PK, ingredient_id: integer FK ingredient.id, custom_cocktail_id: integer FK custom_cocktail.id)`

- ingredients `(id: BIGSERIAL PK, name)`

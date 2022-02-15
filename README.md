# poke-api-tests

This is a repository for practicing automation testing for REST API. 
The test subject is ```pokeapi.co``` and Postman collection contains api tests for checking if name, ability, type and weight are correct for three most famous pokemons.

For API documentation visit: https://pokeapi.co/

For running this smoke test you use **Postman** or **Newman** if you prefer running the test in the terminal. 

Find **Postman** here: https://www.postman.com/downloads/

Find **Newman** here: https://www.npmjs.com/package/newman

## **How To Start?**

## In Postman

**Step 1:** Import ```poke_api_collection.json``` and ```poke_api_environment.json``` in Postman.

**Step 2:** Select **POKEMON ENV** in environments.

**Step 3:** Select **Runner** then drag the **POKEMON Collection** to the **RUN ORDER** and select **Start Run**.

## In Newman

Command for executing this smoke test in project root run: 

```newman run poke_api_collection.json -e poke_api_environment.json```

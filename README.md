# Wopta Flutter Exercise

Welcome to the Wopta Flutter exercise.

The task is simple: create a Flutter app that consumes the [Rick and Morty API](https://rickandmortyapi.com/).

- Your app should display a list with the characters you retrieve from the API call.
- You should display a list tile for each character, containing basic info such as the name.
- When clicking on a list tile for a given character, open a character detail page, containing the detailed info of the character.

### Bonus points if you can:
- Make the list infinite scrolling by paginating the API call and getting new data each time the user arrives at the end of the page.
- Create a search character functionality.

### Tips
- Use Clean Architecture with Bloc or Cubit for the UI layer
- You can use GoRouter for routing
- The layout is up to you, but keep in mind, simple and intuitive is better.
- Use a JSON to Dart converter to easily convert your models, you can use freezed if so you wish.

## API
DOCS: https://rickandmortyapi.com/documentation
- Use the REST api.

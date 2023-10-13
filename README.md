# Games Store App Project
 - Created a Flutter game store app powered by BLoC architecture, leveraging RAWG API for game data, and implementing dynamic category-based game filtering.
 - BLoC Architecture: Employed BLoC (Business Logic Component) design pattern to separate concerns and manage state effectively, enhancing code maintainability and testability.
 - Category Filtering: Enabled users to filter games by category, improving user experience and content discovery.
 - Repository and Service Layers: Developed structured repository and service layers for efficient API calls and data management.


### Offical documentation about Flutter Bloc

- [Flutter bloc docs](https://bloclibrary.dev/#/)

Flutter bloc pub.dev 

- [Flutter bloc pub.dev](https://pub.dev/packages/flutter_bloc) 

### .env file (API KEY)

For this project I used .env directory to store my API Key, if you want to use it, you need to create this structure on the root of your app:

````
assets:
  - .env
````

Inside this file you need to put your API KEY like that:

````
GAMES_API_KEY = 'your api key code here';
````
For more info you can check the official documentation of [flutter_dotenv](https://pub.dev/packages/flutter_dotenv) library.

--------

If you want to contribute to this code open a PR or an Issue.


Hope you enjoy it 😊


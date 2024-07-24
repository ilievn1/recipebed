# dad_project_ii

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

TODO: Name of the application
- RecipeBed

TODO: Brief description of the application
- The app is designed to provide a responsive, cross-platform recipe management experience using Flutter and Firebase.
- It allows users to view individual recipes, list recipe categories, and search for recipes by name.
- Recipes are categorized, enabling users to easily navigate and find their desired recipes.
- For authenticated users, the app includes additional features such as creating, editing, and deleting personal recipes.
- Users can mark recipes as favorites and view a list of their favorite recipes.
- The app tracks the number of times a recipe has been marked as a favorite by all users.
- A featured recipe, along with a subset of recipe categories, is displayed on the main page.
- Recipes and categories are fetched from a backend database, ensuring the content is always up-to-date.
- Pagination is implemented for both recipes and categories to enhance performance and user experience.
- Responsive design is incorporated to adapt the layout based on screen size:
- On larger screens (desktop), both categories and recipes are displayed side by side.
- On tablets, categories are expandable to show a list of recipes without navigating away.
- On mobile devices, users navigate through different pages for categories and recipes.
- Users can create new categories if the predefined ones do not meet their needs, with new categories being added to the backend database.
- The app employs a custom theme to ensure consistent styling and includes fancy fonts that scale with screen size for better readability.

TODO: 3 key challenges faced during the project
 1. Layout management can become cumbersome after introducing nested elements and this is where flutter widget inspector does wonders in allow to experiment with sizing policies
 2. Working with dialog windows was a personal choice, which introduced several problems related to navigation and lead to some long debugging sessions, but proved quite educational
 3. The most time-consuming challenge certainly was the setup of custom user object, as it was not covered in the material, but thankfully the plethora of online resources saved me

TODO: list of dependencies and their versions

dependencies:
  cupertino_icons: ^1.0.6
  flutter_riverpod: ^2.4.0
  riverpod: ^2.4.0
  firebase_core: ^2.32.0
  cloud_firestore: ^4.5.1
  firebase_auth: ^4.4.1
  go_router: ^10.1.2
  infinite_scroll_pagination: ^4.0.0
  google_fonts: ^6.2.1

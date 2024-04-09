# Restaurants List
Your task is to write a very simple restaurants list app.

1. Write a simple REST API in NodeJS that...
 - Has a complete CRUD endpoints.
 - Returns the attached "restaurants.json" payload (or a free version of it)
 - The data can all be mocked, no need for a persistence layer.

2. Create a User Model that...
 - Has username, password and a list of favourites restaurants.
 - Add authentication methods to the API.

3. Write a Next.js app that displays the restaurants from the API
- Use Context API for state management and Axios (or similar library) for fetching data from the API
- Display an initial list with all restaurants.
- When a restaurant is selected from the list, it will render a restaurant detail view displaying a few more details about that restaurant
- Enable CRUD actions.
- Display a spinner or placeholder component while the API request is ongoing.
- Make it look decent. Reproduce the figma design as accurate as possible, but it does not necessarily have to be perfect. Add images for each device.
- Retrieve user favourite restaurants and enable the ability of mark/unmark a restaurant as favourite. (That path should be protected).

4. Push the code to a public github repo with a README.md that explains how to run API & Frontend app.

## Extra information
Figma link: https://www.figma.com/file/LuwjRZZb3ms0MeAmu7gZch/Tailor-Prueba-t%C3%A9cnica-Junior?type=design&node-id=2%3A15&mode=design&t=mYbsPNUJscBcb7yN-1

## Bonus points
1. Deploy the app.
2. JWT Authentication.
3. Tailwind css implementation
4. TypeScript 😍
5. Responsive design
6. Write realistic unit/end-to-end tests.

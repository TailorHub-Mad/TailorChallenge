# Tailor

## The Challenge

Your task is to write a restaurants app. Attached below is a series of steps you can take for guidance.

## Backend

1. Write a simple _REST API_ in NodeJS that includes...

- A complete CRUD with endpoints.
- Returns the attached "restaurants.json" payload (or a free version of it)
- The data can be mocked, no need for a persistence layer.

2. Create a User model that...

- Has username, password and a list of favourites restaurants.
- Has authentication methods to the API.

## Frontend

3. Create a _Next.js_ app that displays the restaurants from your API

- Use a state management (or similar library)
- Display an initial list with all restaurants.
- When a restaurant is selected from the list, it will render a restaurant detail view displaying a few more details about that restaurant
- Enable CRUD actions for restaurants, and develop the corresponding pages.
- Enable CRUD actions for comments.
- Display a spinner or placeholder component while the API request is ongoing.
- Make it look visually appealing. Reproduce the figma design as accurate as possible, but it does not necessarily have to be perfect. Add images for each device.

4. Push the code to a public github repo with a README.md that explains how to run API & Frontend apps.

## Figma design

Figma link: https://www.figma.com/file/LuwjRZZb3ms0MeAmu7gZch/Tailor-Prueba-t%C3%A9cnica-Junior?type=design&node-id=2%3A15&mode=design&t=mYbsPNUJscBcb7yN-1

## Bonus points

1. Deploy the app.
2. JWT Authentication.
3. TailwindCSS implementation
4. TypeScript 😍
5. Responsive design
6. Write realistic unit/end-to-end tests.

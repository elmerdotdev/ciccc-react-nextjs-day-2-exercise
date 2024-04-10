# E-0923 React NextJS Exercise 2

1. Create a `dev` branch after accepting the assignment
2. Clone the repository and make sure to work on the `dev` branch
3. Create a new NextJS project by running `npx create-next-app@latest`. You can call the project 'nextjs-data-fetch'
4. Create a Users page `/users` and display a list of user first names from `https://dummyjson.com/users`. Do not use a client component to fetch the API
5. Create a dynamic route (example `/users/5` where 5 represents an id) where it displays the specific user's firstName, lastName, age, gender, and email
6. On the `/users` page, when you click on the first name, it should open a modal which displays only the user's id, firstName, and lastName. Use Parallel + Intercepting routes to create the modal
7. The modal should have a Close or Back link which redirects to the `/users/` page
8. Style your app using TailwindCSS so that it looks presentable
9. Once you are done, push your changes, create a PR from dev to master and merge

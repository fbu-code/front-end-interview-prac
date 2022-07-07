# Front-end Interview Practical

## Instructions

We have set up this new Laravel project to act as the back-end. A "products" table *migration*, and Product *model* have been added. For this work, feel free to use the Product model, or plain SQL queries.

Please refer to [https://laravel.com/docs/9.x/installation](https://laravel.com/docs/9.x/installation) for more details on setting up a Laravel project. If you're stuck, feel free to also let us know, and we'll help you out!

## Notes

- Please clone this repository, and perform the tasks below.
- You can perform the tasks in any order.
- Use VueJS v3, with a Vuex for the store - and use NPM to install packages.
- Please make the layout look respectable (you can use CDNs to bring in 3rd party CSS frameworks if you like - Tailwind is a bonus).
- Feel free to add any other niceties for the *user experience*.
- ***Please commit your changes and send us a .zip copy (including the .git directory).***

## Task

- Create a basic form for adding a new product. Include an input field &amp; submit button. A product only needs a name.
- When submitted, save the new product to the database via an API call (you can put the Laravel API code inside `routes/api.php` directly).
- List all products below the form, via an API call.
- Have a search field that filters the listed entries.

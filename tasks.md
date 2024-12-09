components :

registration/signup - db.json - user

1 admin movie booking admin - add shows timing, movies (use omdbApi)

index page

admin dashboard - view recent bookings, sales, manage, edit, add delete movies

user page - book movies, cancel booking, view seats, edit profile, create receipt, upcoming movie tiles section, currently showing movies, razor pay wallet, use wallet for paying

checkout page

wishlist page (optional)


------------------------------------------

{'/'} :
omdb api integration, create index page (movies), for upcoming movies

{'/movie-title'} :
select on tile -> description (get data from omdbapi.json)
button : >book movie<

{'/book-movies'} :
seat row x column UI, on hover green if available, booked seats marked red, otherwise white
seats represented by IDs, (array) - array indexes selected, and marked as selected, -> add to cart/book now

-> adds to cart 
{'/cart'} :
show timing, movie, theatre, how many tickets -> payment integration/ use wallet for payment -> create receipt

-> user signup/login (proper session management)

-> admin panel - admin dashboard - view recent bookings, sales, manage, edit, add delete movies
	- select movies from omdbapi data, and add show timings

-> payment integration (add wallet balance)

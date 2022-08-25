```
As a customer, so I can receive my tickets, I want to provide my contact information.
    user(username, password, role DEFAULT 'customer')
    contact(name, email, user_id)
    ticket(price, screen_id, seat, movie_id, user_id)

As a customer, so I can decide which movie I want to watch, I want to see a list of movies.
    movie(title, directors, running_time, release_date, rating, genre, cast, description)
    screen(capacity, screen_size, number)
    screening(movie_id, screen_id, screening_time)

As a customer, so I can view my order history, I want to view my previously purchased tickets.


As an admin, so I can manage the movies shown at the cinema, I want to update the list of movies.
    user.role = 'admin'
```
  
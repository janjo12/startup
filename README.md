# The "30 Seconds Game"

### Elevator pitch

This test of internal rhythm and counting has players mark exactly when an invisible timer reaches the 10, 15, 20, 25, and 30 seconds marks after being given 5 seconds of seeing the timer. Their final score at the end is comprised of the total by which they were early or late in their estimations, and these scores, the lowest being scored highest on a leaderboard associated with each user's unique username.

### Design

Here's how the basic game format will look:

![Timer going](https://github.com/janjo12/startup/assets/97489613/3de92b97-5641-4841-b711-402d7bf97da3)

![Timer hidden](https://github.com/janjo12/startup/assets/97489613/441acccd-276b-4f7d-bec6-f7364a478a75)

![Game ended](https://github.com/janjo12/startup/assets/97489613/5ed3aa2a-a14d-4adc-8dd6-c7d110789bb9)


### Key features

- Secure login over HTTPS
- Leaderboard of top 10+ scores updated with each new playthrough of the game

### Technologies

- **HTML** - Page layout, with one page for login, one for the game, and one for the leaderboard.
- **CSS** - Most of the game will rely on formatting. The design will be simple, with only the timer prominent.
- **JavaScript** - Login, timer, and time marking.
- **Service** - Login and checking the leaderboard.
- **DB** - Stores user and leaderboard information.
- **Login** - Register users, but the game will also be playable without logging in. Logging in can be done after playing to enter the leaderboard.
- **WebSocket** - The leaderboard will be accessible to all, including those who don't log in.
- **React** - The application will be ported to work for this.

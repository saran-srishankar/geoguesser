Geo Guesser replica, accessible at https://geoguessing.me.

If prompted for credit card information for Stripe, please use the fake card 4242 4242 4242 4242 for free access.

You will be shown a street-view of a random city in the world and are allowed to move around.  The goal is to guess the location of the city.  AI hints and review capability exist to help you learn what you may have missed.

Implementation:

We used the Mapillary API to generate street-views to be displayed on a single-page application.

Real-time enablement implemented to allow games to be synchronized in-time if the same user plays on multiple devices (try it!)

Implemented Stripe for payments (please play our game for free)

Google OAuth implemented for sign-in security.

AI integration done using Gemini 3.1 for user hints.

PostgreSQL database and RESTful backend

Angular-based frontend

Caddy used for HTTPS encryption and as a reverse proxy for our backend

Docker compose used to build Docker containers.  Everything deployed on a virtual machine.

<img width="1879" height="882" alt="image" src="https://github.com/user-attachments/assets/a5654a20-ad3c-4639-96cb-79177c359688" />

Created by: Saran Srishankar, Ethan Hapurne, Charles Yan Zhao

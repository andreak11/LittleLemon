API endpoints to test

Menu endpoints:
GET    /restaurant/menu/
GET    /restaurant/menu/1
POST   /restaurant/menu/
PUT    /restaurant/menu/1
DELETE /restaurant/menu/1

Booking endpoints:
GET    /restaurant/booking/tables/
GET    /restaurant/booking/tables/1/
POST   /restaurant/booking/tables/
PUT    /restaurant/booking/tables/1/
DELETE /restaurant/booking/tables/1/

User registration and authentication:
POST   /auth/users/           (register new user)
POST   /auth/token/login/     (get auth token)
POST   /auth/token/logout/    (logout)
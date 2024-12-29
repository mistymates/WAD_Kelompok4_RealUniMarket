<p align="center"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
</p>

# Laravel Simple Simple Basic Ecommerce

<p>This is a Laravel Simple Basic Ecommerce project without multiAuth</p>

## Features
#### Home page showing all products
#### Registration
#### Login
#### Showing user name when logged in
#### Session
#### Logout
#### Add to cart
#### Display all cart items of the user
#### Remove items from cart
#### Order
#### Display user's all orders
#### Bootstrap 4


## Authentication Routes
#### Register - post :: http://127.0.0.1:8000/register
#### Login - post :: http://127.0.0.1:8000/login
#### Logout - get :: http://127.0.0.1:8000/logout

## View Routes
#### Register - view :: http://127.0.0.1:8000/register
#### Login - view :: http://127.0.0.1:8000/login

## Product Routes
#### Home page - get :: http://127.0.0.1:8000/
#### Product Detail Page - get :: http://127.0.0.1:8000/detail/{id}
#### Search Page - get :: http://127.0.0.1:8000/search
#### AddToCart - post :: http://127.0.0.1:8000/add-to-cart
#### CartList Page - get :: http://127.0.0.1:8000/cart-list
#### RemoveFromCart - get :: http://127.0.0.1:8000/remove-cart/{id}
#### OrderNow Page - get :: http://127.0.0.1:8000/order-now
#### PlaceOrder Page - post :: http://127.0.0.1:8000/place-order
#### MyOrdersPage - get :: http://127.0.0.1:8000/orders

# Home Page without login (http://127.0.0.1:8000)
## Registration (http://127.0.0.1:8000/register)
## "users" Table (from database)
## Login (http://127.0.0.1:8000/login)
## Home Page After Logged in (http://127.0.0.1:8000/)
## Product Details Page (http://127.0.0.1:8000/detail/{id})
## Cart List Page (http://127.0.0.1:8000/cart-list)
## "carts" Table (from database)
## Order Now Page (http://127.0.0.1:8000/order-now)
## MyOrders Page (http://127.0.0.1:8000/orders)
## "orders" Table (from database)
## "cart" Table After Placing Order (from database)
## Search Page (http://127.0.0.1:8000/search)

If you discover a security vulnerability within Laravel, please send an e-mail to Abuhena Rony via [me@abuhenarony.com](mailto:me@abuhenarony.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).


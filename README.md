# PROJETO | Flappy-Bird

<center><img src="https://upload.wikimedia.org/wikipedia/en/0/0a/Flappy_Bird_icon.png"  width="100" height="100"></center>


> Status: Developing ⚠️
### It is a web application planned by me, game flappy-bird.

## Some fields in main Model is:

+ name 
+ description
+ repetation num
+ sequency num
+ dificult category
+ i know
+ user_id
+ image
  
Also that, has a User with this fields:

+ name
+ email
+ cpf
+ birth
+ active

## In addition to CRUD, I implement other features such as:

* See the more recently movement created, using Cookie.
* Entire verification system to validate forms with personalized messages.
* Message of success when create a movement, using Session Flash.
* Profile User editable.

## This features are in developing:

- Search for movements by name and/or dificulted category.
- Email verification.

## Technologies Used:

<table>
  <tr>
    <td>PHP</td>
    <td>Laravel</td>
    <td>Composer</td>
    <td>MySql</td>
  </tr>
  <tr>
    <td>6.*</td>
    <td>7.4</td>
    <td>2.0</td>
    <td>8.0</td>
  </tr>
</table>

## How to run the application:

1) run shell: composer install
2) run shell: php artisan key:generate
3) create new Schema MySql
4) create file .env (can copy from .env.example)
5) configure your database variables in .env
6) run shell: php artisan migrate
7) run shell: php artisan serve

## How to use mail service:

1) create free account in mailtrap
2) into of mailtrap site, go to My Inbox
3) go to SMT settigns
4) choice Laravel option in Integrations
5) copy and past in your .env

<center><img src="imagem do projeto"></center>

    © 2022 GitHub, Inc.

    Terms
    Privacy
    Security
    Status

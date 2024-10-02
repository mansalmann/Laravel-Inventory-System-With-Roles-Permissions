# Laravel School Inventory Application with Roles and Permissions

## Feature
-   CRUD all items
-   Import/export excel type for items data
-   Print items data (single/multiple)
-   CRUD BOS (Bantuan Operasional Sekolah) Data
-   CRUD Room data
-   CRUD User data
-   Profile Configuration

Created Roles and Permissions using spattie package.

## Preview

_Login page_
![Image 1](https://i.imgur.com/kD6P7BF.png)

_Dashboard_
![Image 2](https://i.imgur.com/VJ0gCEv.png)

_List items_
![Image 3](https://i.imgur.com/3AaIzxz.png)

_Print_
![Image 4](https://i.imgur.com/a7yj6Or.png)

_Print Single Data_
![Image 5](https://i.imgur.com/Spjtxpv.png)

_List of Bantuan Operasional Sekolah_
![Image 6](https://i.imgur.com/zUruox1.png)

_Room List_
![Image 7](https://i.imgur.com/CrYTczu.png)

_User List_
![Image 8](https://i.imgur.com/dF2tSet.png)

_Profile Configuration_
![Image 9](https://i.imgur.com/WbHIVPG.png)

_Roles and Permissions_
![Image 10](https://i.imgur.com/5vlJQHL.png)

### How to Install
-   Clone this repository

```bash
$ git clone https://github.com/mantokreng/Laravel-Inventory-System-With-Roles-Permissions.git
```
-   Install all packages

```bash
$ composer install
```

- Set up the database and set up the .env file according to your configuration

- Enter the school name in the .env configuration to display the school name on the item print. Put quotation marks if the school name contains spaces.

Example:

```
NAMA_SEKOLAH="SD Negeri 006 Yogyakarta"
```

-   Run migration and seed

```bash
$ php artisan migrate --seed
```

-   Run local server

```
$ php artisan serve
```

-   User for login

Administrator

```
Email       : admin@mail.com
Password    : secret
```

Staff TU (Tata Usaha)

```
Email       : stafftu@mail.com
Password    : secret
```
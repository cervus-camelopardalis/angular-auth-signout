## Authentication service for Sign out button in menu

Flow:

1. User signs up
2. User signs in
3. User signs out

*Note: menu is different when user is signed in vs. signed out*

*Changed files: `app-routing.module.ts`, `auth.service.ts`, `header.component.ts`, `header.component.html`*

---

## Setup

1. Clone the repo: `git clone https://github.com/cervus-camelopardalis/angular-auth-signout.git`
2. Create PostgreSQL database (see `database.sql` file)
3. Insert your database user and password (edit `db.js` file)
4. Install Express modules: `C:\Users\xxxxx\xxxxx\xxxxx\express-server>npm i`
5. Install Angular modules: `C:\Users\xxxxx\xxxxx\xxxxx\angular-client>npm i`
6. Start Express server: `C:\Users\xxxxx\xxxxx\xxxxx\express-server>nodemon server`
7. Run Angular app: `C:\Users\xxxxx\xxxxx\xxxxx\angular-client>ng serve -o`

---

## Screenshot

Sign in and sign out:

![Sign in and sign out](https://github.com/cervus-camelopardalis/angular-auth-signout/blob/main/01-screenshot-sign-in-sign-out.gif)
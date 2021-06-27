# **README - PaintingJoy**

## **About**

_PaintingJoy_ ( Deployed [HERE](https://paintingjoy.art/) ) is a web app that is part Art Portfolio, part E-commerce, part custom CMS.

<br>

# **Local Usage:**

<br>

### **Environmental Variables**:

This app uses the following environmental variables that you will need in order to run the app
| ENV | Value |
| --------------------- | --------------------------------------------------------- |
| `DATABASE_URI` | Postgres URI |
| `ADMIN_KEY` | Value referencing the current user for session |
| `SECRET_KEY` | Secret key |
| `PORT` | Port the server is running on |
| `NODE_ENV` | Whether the app is in production, developement, or testing |
| `BCRYPT_WORK_FACTOR` | # of rounds of encryption for Bcrypt to use |

<br>

### **Testing**:

This app uses [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/) for Smoke and Snapshot Tests, and [Jest](https://jestjs.io/) for unit testing. Tests can be run using `npm test`

<br>

### **Formatting/Linting/Pre-Commit Hooks**:

This project uses pre-commit hooks with ESLint and Prettier.

<br>

### **Features**:

_Browse Murals/General Art_: Browse through all the posts to see the artist's murals and other art.

_E-Commerce_: Uses the Stripe API to process payments for an online art store.

_Custom CMS_: On the Admin side, I've created a custom CMS for the artist to manage their posts, homepage, as well as the store.

_Integration with Personal Image CDN_: The app uses Cloudflare's CDN to serve the images for the site, decreasing load time.

<br>

### **APIs**:

1. [Stripe API](https://api.setlist.fm/docs/1.0/index.html)
    - Process payments for the web store

<br>

### **Tech Stack**:

-   JavaScript
-   [React](https://reactjs.org/)
    -   [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
-   CSS
    -   [SASS](https://sass-lang.com/) (Global Styles)
    -   [Styled Components](https://styled-components.com/) (Component Styles)
-   [Node.js](https://nodejs.org/)
-   [Express](https://expressjs.com/)
    -   [node-postgres](https://node-postgres.com/)
    -   [jest](https://jestjs.io/)
-   [PostgreSQL](https://www.postgresql.org/)
-   [Heroku](https://heroku.com/) (Express API Deployment)
-   [Cloudflare](https://www.cloudflare.com/cdn/) (Image CDN)
-   [Surge](https://surge.sh/) (Static Front-End Deployment)
-   [VSCode](https://code.visualstudio.com/)

---

## **Support**

Reach out to me at the following places:

-   Website: [jacobandes.dev](jacobandes.dev)
-   Twitter: [@booshja](https://twitter.com/booshja)
-   Email: [jacob.andes@gmail.com](mailto:jacob.andes@gmail.com)

---

Copyright &#169; [Jacob Andes](jacobandes.dev), 2021

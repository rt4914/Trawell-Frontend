<div id="top"></div>

# Trawell Frontend

Trawell App is designed to make tourism seamless by connecting users with experienced guides. Users can search for guides, review their services, and book them with ease. Guides can showcase their services and charges, and receive payments directly through the platform.

## Features

-   **Secure User and Guide Authentication**: Register and log in with email and password.
-   **Guide Discovery**: Users can search for guides by location, expertise, and rating.
-   **Service Listings**: Guides can list their services and set prices.
-   **Payment Integration**: Seamless and secure payment options for booking.
-   **Ratings and Reviews**: Users can leave reviews for guides.

## Trawell Backend API

For more information about the backend API, please refer to the [Trawell-Backend](https://github.com/rt4914/Trawell-Backend)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Before installation, please make sure you have already installed the following tools:

-   [Git](https://git-scm.com/downloads) (version 2.30.0 or higher)
-   [Node.js](https://nodejs.org/en/download/) (version 16.14.0 or higher)
-   [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) (version 7.0.0 or higher)
-   [Ruby](https://www.ruby-lang.org/en/downloads/) (version 3.0.2 or higher)
-   [Rails](https://rubyonrails.org/) (version 7.0.0 or higher)
-   [PostgreSQL](https://www.postgresql.org/download/) (version 12.0 or higher)

### Installation

**Trawell-Frontend**

1. Clone this repository:

    ```bash
    git clone https://github.com/rt4914/Trawell-Frontend.git
    ```

2. Navigate to the project directory

    ```bash
    cd Trawell-Frontend
    ```

3. Install dependencies

    ```bash
    npm install
    ```

4. Run the server in the project directory:

    ```bash
    npm run dev
    ```

5. Open the URL in your browser: `http://localhost:PORT`

6. Optional step to run a storybook

    ```bash
    npm run storybook
    ```

**Trawell-Backend**

1. Clone this repository:

    ```bash
    git clone https://github.com/rt4914/Trawell-Backend.git
    ```

2. Navigate to the project directory

    ```bash
    cd Trawell-Backend
    ```

3. Install dependencies

    ```bash
    bundle install
    ```

4. Set up the database

    ```bash
    rails db:create
    rails db:migrate
    ```

5. Run the server in the project directory:

    ```bash
    rails server
    ```

6. Open the URL in your browser: `http://localhost:PORT`

**Note**

-   Replace `PORT` with the port number where your application is running. You can typically find this information in your application's startup logs.
-   If `rails db:create` fails with a credentials error:
    1. Open the `config/database.yml` file.
    2. Update the `username` and `password` fields with your PostgreSQL credentials.
    3. Run `rails db:create` again.

## Tech Stack

<table>
  <tbody>
    <tr>
      <td align="center" width="25%">
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/tandpfun/skill-icons/65dea6c4eaca7da319e552c09f4cf5a9a8dab2c8/icons/HTML.svg" width="36" height="36" alt="HTML" /></a>
        <br>HTML
      </td>
      <td align="center" width="25%">
        <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/tandpfun/skill-icons/65dea6c4eaca7da319e552c09f4cf5a9a8dab2c8/icons/CSS.svg" width="36" height="36" alt="CSS" /></a>
        <br>CSS
      </td>
      <td align="center" width="25%">
        <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tailwindcss-colored.svg" width="36" height="36" alt="TailwindCSS" /></a>
        <br>TailwindCSS
      </td>
      <td align="center" width="25%">
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a>
        <br>JavaScript
      </td>
    </tr>
    <tr>
      <td align="center" width="25%">
        <a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" /></a>
        <br>React
      </td>
      <td align="center" width="25%">
        <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" /></a>
        <br>NodeJS
      </td>
      <td align="center" width="25%">
        <a href="https://vitejs.dev/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/profileme-dev/3fc3595593bc992e6febba6580d6c9571f5e625f/public/icons/skills/vite-colored.svg" width="36" height="36" alt="Vite" /></a>
        <br>Vite
      </td>
      <td align="center" width="25%">
        <a href="https://www.npmjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/tandpfun/skill-icons/65dea6c4eaca7da319e552c09f4cf5a9a8dab2c8/icons/Npm-Light.svg" width="36" height="36" alt="npm" /></a>
        <br>npm
      </td>
    </tr>
    <tr>
      <td align="center" width="25%">
        <a href="https://www.ruby-lang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/ruby/ruby-original.svg" width="36" height="36" alt="Ruby" /></a>
        <br>Ruby
      </td>
      <td align="center" width="25%">
        <a href="https://rubyonrails.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/rails/rails-plain.svg" width="36" height="36" alt="Rails" /></a>
        <br>Rails
      </td>
      <td align="center" width="25%">
        <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/profileme-dev/3fc3595593bc992e6febba6580d6c9571f5e625f/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" /></a>
        <br>PostgreSQL
      </td>
    </tr>
  </tbody>
</table>

## Contributing

See [CONTRIBUTING.md](https://github.com/rt4914/Trawell-Frontend/blob/main/.github/CONTRIBUTING.md)

## License

This project is available as open source under the terms of the [MIT License](https://github.com/rt4914/Trawell-Frontend/blob/main/LICENSE.txt).

## Contributors

Thanks goes to these wonderful people:

<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/Bishoy-Samwel">
          <img src="https://avatars.githubusercontent.com/u/29541335?v=4" width="100px;" alt="Bishoy Samwel Faheem"/><br />
          <sub><b>Bishoy Samwel Faheem</b></sub>
        </a><br />
        <a href="https://github.com//rt4914/Trawell-Frontend/commits?author=Bishoy-Samwel" title="Code">💻</a>
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/devFelipeAlmeida">
          <img src="https://avatars.githubusercontent.com/u/95555235?v=4" width="100px;" alt="Felipe Almeid"/><br />
          <sub><b>Felipe Almeida</b></sub>
        </a><br />
        <a href="https://github.com//rt4914/Trawell-Frontend/commits?author=devFelipeAlmeida" title="Code">💻</a>
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/">
          <img src="https://avatars.githubusercontent.com/u/98149187?v=4" width="100px;" alt="Himansh Nigam<"/><br />
          <sub><b>Himansh Nigam</b></sub>
        </a><br />
        <a href="" title="Code">💻</a>
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/">
          <img src="https://avatars.githubusercontent.com/u/98149187?v=4" width="100px;" alt="Himanshu Kumar"/><br />
          <sub><b>Himanshu Kumar</b></sub>
        </a><br />
        <a href="" title="Code">💻</a>
      </td>
    </tr>
    <tr>
          <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/rt4914">
          <img src="https://avatars.githubusercontent.com/u/9396084?v=4" width="100px;" alt="Rajat Talesra"/><br />
          <sub><b>Rajat Talesra</b></sub>
        </a><br />
        <a href="https://github.com//rt4914/Trawell-Frontend/commits?author=rt4914" title="Code">💻</a>
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/">
          <img src="https://avatars.githubusercontent.com/u/98149187?v=4" width="100px;" alt="Richie Singh"/><br />
          <sub><b>Richie Singh</b></sub>
        </a><br />
        <a href="https://github.com/" title="Code">💻</a>
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/">
          <img src="https://avatars.githubusercontent.com/u/98149187?v=4" width="100px;" alt="Ricky"/><br />
          <sub><b>Ricky</b></sub>
        </a><br />
        <a href="https://github.com" title="Code">💻</a>
      </td>
      <td align="center" valign="top" width="14.28%">
        <a href="https://github.com/zehan12">
          <img src="https://avatars.githubusercontent.com/u/73664886?s=400&u=b4640ee6fcf6bdb55f455d2b1ec8d91a330f9b04&v=4" width="100px;" alt="Zehan Khan"/><br />
          <sub><b>Zehan Khan</b></sub>
        </a><br />
        <a href="https://github.com/rt4914/Trawell-Frontend/commits?author=zehan12" title="Code">💻</a>
      </td>
    </tr>
  </tbody>
</table>

## Contact

<div>
  <a href="https://www.linkedin.com/in/rajat-talesra-59068582" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="mailto:rajattalesra4914@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>

<p>(<a href="#top">back to top</a>)</p>

<a name="readme-top"></a>

<div align="center">
  <a href="/app/assets/images/ERD.png">
    <img src="/app/assets/images/ERD.png" alt="Logo">
  </a>
  <h1 align="center">Appoint Wheels ERD - Backend</h1>
</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 Frontend Link](#frontend-link)
- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [📖 API Documentation](#api-documentation)
- [💻 Getting Started](#getting-started)
  - [Install](#install)
  - [Usage](#usage)
  - [Linters](#linters)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- FRONTEND LINK -->

# 📖 Frontend Link <a name="frontend-link"></a>

- [**Frontend Link**](https://github.com/Rebelzob/REACT-AppointWheels)

<!-- PROJECT DESCRIPTION -->

# 📖 Rails AppointWheels <a name="about-project"></a>

**Appointment Wheels** is a car rental application built with React and Ruby on Rails. The application allows users to book a car for a specific date and time. Users can create an account and log in to the application. The application is responsive and works on all devices.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **User Authentication with JWT**
- **User Authorization with CanCanCan**
- **User Roles**
- **Database Creation and Seeding**
- **API Documentation with Swagger**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- API Documentation -->

## 📖 API Documentation <a name="api-documentation"></a>

- [**API Documentation**](https://rails-appointwheels-bold-butterfly-8850.fly.dev/api-docs/index.html) in order to see the API documentation, you need to run the project locally and go to the link provided.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Install <a name="install"></a>

Install this project with:

```sh
  bundle install
  npm install
```

### Usage <a name="usage"></a>

To run the project:

First you need to setup the JWT key the database

1. Delete credentials.yml.enc and master.key(if present)

2. Generate a secret JWT key with:

```sh
  bundle exec rake secret
```
If the above command doesn't work use this:
```sh
  rails secret
```

3. Save the generated secret key on a notepad

4. Generate new credentials and master key with:

```sh
  EDITOR='code --wait' rails credentials:edit
```

5. A new tab/window will open add the value 'devise_jwt_secret_key:' with secret key

<img src="/app/assets/images/JWT-guide.png" alt="JWT key guide">

6. Close the tab/window to save the configuration

You can setup the database with:

```sh
  rails db:setup
```

To run the server:

```sh
  rails server -p 3001
```

### Linters <a name="linters"></a>

Use this command to fix **Rubocop Linter** Errors:

```sh
  rubocop -A
```

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Author1**

👤 **Soban Syeed**

- GitHub: [SnakyMZ](https://github.com/SnakyMz)
- LinkedIn: [Soban Syeed](https://www.linkedin.com/in/soban-syeed/)

👤 **Karim Barragan**

- GitHub: [Rebelzob](https://github.com/Rebelzob)
- LinkedIn: [Karim Barragan](https://www.linkedin.com/in/karim-barragan/)

👤 **Ismael Mastronardi**

- GitHub: [IsmaelMastronardi](https://github.com/IsmaelMastronardi)
- LinkedIn: [Ismael Mastronardi](https://www.linkedin.com/in/ismael-mastronardi-361873271/)

👤 **John Palacios**

- GitHub: [RysthCraft](https://github.com/Rysth)
- LinkedIn: [John Palacios](https://www.linkedin.com/in/john-palacios-rysthcraft)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- **Add a payment system**
- **Add a review system**
- **Search functionality**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank the following:

- [Microverse](https://www.microverse.org/) for assigning us this project
- Our Stand Up Teams for their feedback and suggestions
- Team members for their collaboration to the project

Attribution:

- [Murat Korkmaz](https://www.behance.net/gallery/26425031/Vespa-Responsive-Redesign) for the design idea
- [Creative Commons](https://creativecommons.org/licenses/by-nc/4.0/) for the license

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

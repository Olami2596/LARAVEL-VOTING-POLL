# Voting poll

Voting poll is a simple voting web application created using the popular PHP framework Laravel and designed with the CSS framework Tailwind and livewire was used for the interactivity of the application. It is just a simple web app where users can create polls and vote.


## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

  
## Getting Started

These instructions will help you get a copy of the project up and running on your local machine or web server.

### Prerequisites

- [PHP](https://www.php.net/) >= 7.4
- [Composer](https://getcomposer.org/)
- [Laravel](https://laravel.com/)
- [Tailwind](https://tailwindcss.com/)
- [Alpinejs](https://alpinejs.dev/)
- [Livewire](https://laravel-livewire.com/)

### Installation

Clone the repository:

   ```bash
   git clone [https://github.com/your-username/your-repo](https://github.com/Olami2596/LARAVEL-VOTING-POLL).git
   ```

Navigate to the project directory:

   ```bash
   cd your-repo
   ```

Install dependencies:

   ```bash
   composer install
   npm install
    # or
   yarn install
   ```

Set up your environment variables:

   ```bash
    cp .env.example .env
    # configure database and other necessary settings in .env
    php artisan key:generate
   ```

Run migrations and seed the database:

   ```bash
    php artisan migrate --seed
   ```

Start the development server:

   ```bash
    php artisan serve
   ```


### Usage

1. **Create polls:**

   After opening the application, you can just create new polls by filling the poll title and creating aas many options to be voted on as required.

2. **Voting:**

   After the creationof polls, you can vote any of the options available

### Features

1. **Polls Creation:**
   
   Easily create polls to be voted on.

2. **Voting:**
   
   Votes can be created and counted




### Contributing

You can contribute to the project with the following steps:


Fork the Project:

Fork the project by clicking on the 'Fork' button on the top right corner of the GitHub page. This will create a copy of the repository in your GitHub account.


Create Your Feature Branch:

Create a new branch for your feature:

   ```bash
       git checkout -b feature/YourFeature

   ```

Commit Your Changes:

Make your changes and commit them with a meaningful message:

   ```bash
    git commit -m 'Add some feature'

   ```

Push to the Branch:

Push your changes to your branch on your forked repository:

   ```bash
    git push origin feature/YourFeature

   ```

Open a Pull Request:

Open a pull request on the main repository. Provide a clear and concise description of your changes. This will initiate a discussion around your contribution.

Thank you for considering contributing to this project!




# Penguin Rails API Backend (CVWO Assignment 2025)

Backend (deployed on Render) for CVWO Assignment. 
This mainly contains the APIs and the Database Structure. 

## Prerequisites

- **Ruby** 3.2.2
- **PostgreSQL** 14+ [Guide]([www.google.com](https://www.digitalocean.com/community/tutorials/how-to-use-postgresql-with-your-ruby-on-rails-application-on-ubuntu-20-04)
- **Bundler** (`gem install bundler`)

## Setup

1. **Clone repository**
   
   ```
   git clone https://github.com/Arnav-Jhajharia/web_forum_backend.git
   cd web_forum_backend
   ```
   

3. **Install Dependencies**
   
   ```
   bundle install
   ```
   
4. **Create Database**

    ```
    rails db:create
    ```
   
4. **Run the Development Environment**
  
    ```
    bin/dev
    ```

## Important Folders / Files

1. ```app/models```: Contains all the models
2. ```app/controllers/api/v1```: Contains all the controllers
3. ```db/seeds.rb```: Optional seed to run to test the app (using ```rails db:seed```)
4. ```db/schema.rb```: Database Schema



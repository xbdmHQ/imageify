# Imageify
Your new open-source ShareX image host!

## Setup

- Download the git repo `git clone https://github.com/RealFascinated/imageify.git`

- Cd into the new directory `cd imageify`
- Rename the example env `mv .env-example .env`
- Update the env file to your needs `nano .env`
- Start the server `docker compose up -d`
- Create an admin account
- Visit the website <http://SERVERIP:3000>

## How to create an admin account (NOT DONE)

- Run `docker exec -it imageify-server npm run cli user add admin@example.com`
- You will get a password returned and you can now login to you admin account. (Please note that you should change this password)

## Todo

- Add more comments to the code
- Create the home page
- Create the dashboard (for users)
- Create the admin panel (to manage the instance)

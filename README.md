# Imageify
Your new open-source ShareX image host!

## Setup

- Download the git repo `git clone https://github.com/xbdmHQ/imageify.git share`

- Cd into the new directory `cd share`
- Update the env file to your needs `nano .env`
- Start the server `docker-compose up -d --build`
- Create an admin account `docker exec -it imageify-server npm run cli user add admin@example.com`
- Visit the website <http://SERVERIP:3000>

## Todo

- Add more comments to the code
- Create the home page
- Create the dashboard (for users)
- Create the admin panel (to manage the instance)

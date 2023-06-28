# LightBnB Project

### A simple multi-page Airbnb clone that uses a server-side Javascript to display the information from queries to web pages via SQL queries.

## Installation

1. open LightBnB_WebApp-master repo
2. [Create](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) a new repository using this repository as a template.
3. Clone your repository onto your local device.
4. Install dependencies using the `npm install` command.
5. Start the web server using the `npm run local` command. The app will be served at <http://localhost:3000/>.
6. Go to <http://localhost:3000/> in your browser.

### For Database

1. go look into .env.example file
2. create your own .env and fill out the database credentials to connet to a database
3. run command `\i seeds/seeds/02_seeds.sql`
4. run command `\i migrations/01_schema.sql`

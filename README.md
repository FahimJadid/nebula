## Getting Started

### Clone the repository

`git clone https://github.com/FahimJadid/nebula`

### Set up the database
This project uses [Supabase](https://supabase.com) as a backend. To set up the database, create a [new project](https://database.new), enter your project details, and wait for the database to launch. 

Grab the project URL and anon key from the API settings and put them in a new `.env.local` file in the root directory as shown:
```
NEXT_PUBLIC_SUPABASE_URL="<your-supabase-url>" 
NEXT_PUBLIC_SUPABASE_ANON_KEY="<your-anon-key>"
```

### Install dependencies

`npm install`

### Run the application

Run the application in the command line and it will be available at http://localhost:3000.

`npm run dev`

### Deploy

Deploy using [Vercel](https://vercel.com)

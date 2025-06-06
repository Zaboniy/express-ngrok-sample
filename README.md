This project showing how to use ngrok with github actions in order to run the app for demo purposes

1. Go to ngrok.com and copy your api key


Run locally:
    rename example.env file to .env
    place ngrok api key under NGROK_AUTH_TOKEN
    run `docker compose up`

Run via github actions:
    Go to GitHub Repo → Settings → Secrets → Actions → New Repository Secret
    Add NGROK_AUTH_TOKEN secret
    run action
    

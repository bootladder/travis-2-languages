git push --> Travis
Travis builds and tests, then hits the webhook.
The webhook URL is a travis environment variable
The webhook is behind a ngrok tunnel to the deployment machine.
Deployment machine runs webhook server.
The script redeploys.

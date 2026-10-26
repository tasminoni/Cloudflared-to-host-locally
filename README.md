# Cloudflared-to-host-locally
To install Cloudeflare in local PC run this command

winget install Cloudflare.cloudflared

Then run your project
Then run this command on another commad shell

cloudflared tunnel --url http://localhost:42002 --http-host-header localhost
(change the port if needed)

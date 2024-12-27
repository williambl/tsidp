# tsidp

I saw the [video about tsidp](https://www.youtube.com/watch?v=BdQ-Gz6bs3g),
I found it a bit sad that there was no docker container to try it out.
So I sat down to make one myself: compile it, package it, publish it.
The image is available at `ghcr.io/arunoruto/tsidp`.
You can either use `latest` for the newest version
or pin it to a specific release of Tailscale from their [repo](https://github.com/tailscale/tailscale).

## Config

Currently, no configuration is really possible.
Feel free to open an issue if you want a specific config implemented.

## Compose

There is a `compose.yml` which can be used to incorporate it in your Tailscale compose setup.
Either replace `${TS_AUTHKEY}` under environment with your key,
or create a `.env` file with `TS_AUTHKEY=paste-your-key-here`.

## Contribute

Feel free to open an issue if you have any questions or problems,
or even better, fork the repo and open a PR with a fix ;)

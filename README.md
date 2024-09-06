# kbot

This is a Telegram bot on Golang.

This bot responds to certain messages.

Now when a user types "hello", the bot responds with "Hello I'm Kbot (Kbot version)!"

Link to bot: https://t.me/dklkv_bot

Available commands:
- start the bot `./kbot go`;
- show version `./kbot version`



# how to build

`make build TARGETOS=os TARGETARCH=arch` - build application for desired operation system and architecture;
`make image TARGETARCH=arch` - build docker image;
`make push TARGETARCH=arch` - push docker image to repository;
`make clean TARGETARCH=arch`- clean up docker image and binary;

- `TARGETOS` is an optional parameter (default value linux);
- `TARGETARCH` is an optional parameter (default value amd64);

The list of available OS and architectures can be found here: https://go.dev/doc/install/source#environment ($GOOS and $GOARCH section).


![alt text](<Org charts.png>)
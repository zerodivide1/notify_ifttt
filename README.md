# notify_ifttt
Simple script to post simple values to IFTTT's Maker channel. Useful for calling at the end of a long-running job to notify you when the job is complete using a combination of Maker with a something like Telegram, Slack, Pushbullet, Pushover, etc.)

## Requirements
* curl
* [jq](https://stedolan.github.io/jq/)

## Configuration
1. Create a file at `~/.config/notify_ifttt`
2. Add a configuration variable `IFTTT_MAKER_KEY` with the value of the IFTTT Maker channel key. For example:
  ```
  IFTTT_MAKER_KEY=abcdef0123456789...
  ```

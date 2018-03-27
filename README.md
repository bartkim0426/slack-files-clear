# Slack Files Delete
> Script for bulk delete files in slack.

I love Slack, but I don’t have money enough to pay for all users in my company.

The first problem is the 10k messages history limit, it’s ok, I can deal with that. The second is the storage limit for files.

That second problem you need to delete old files to free space to still able to upload and share files. To do this, you need to open Slack, find files and delete each one, there’s no way to bulk delete. And s so, can deal with that to, with my super power.

So, I wrote this script to do that for me.

## Version
Have to use python2

## Using

You will need to clone this repo and just execute in your terminal like this:

You should enter your token with `""` (i.e. `'xoxo-18xxxxxxx-xxxxxx...'`)

```bash
$python main.py
Enter your slack token (If you dont know, check https://api.slack.com/custom-integrations/legacy-tokens):'xoxo-example-input-xxx'
Please enter days that you want to delete: 
```

# mc-automated-properties
An "automated" way to handle modded blocks/items and import information into block.properties &amp; item.properties files.

# How to use
1. clone the repo,
2. go inside the downloaded folder, in the `input-jsons` folder,
3. remove all the `.json` files for mods you are not using,
4. run `main.py` with python (pretty standard nowadays, if you don't have python, you'll have to [download it](https://www.python.org/downloads/))
5. move the generated block.properties file and item.properties to wherever you need them

Profit!

# How to help
1. clone the repo
2. go look at what I did for the `chipped.json` file, it should be pretty easy to understand. The description field doesn't matter, it is only there to help you know what to put inside.
3. copy one of the json files, (can start from whichever)
4. rename the file **to the id of the mod** for example for chipped, the items are called `chipped:xxxxitem` so the file should be named `chipped.json`
5. start working on adding custom blocks and items to your new `[mod-id].json` file. You do not need to add the mod id in the block names, just the block id.
6. when you're done, send it to me on discord (I'll credit you in the commit) or do a PR to add it directly on github

Thank you!

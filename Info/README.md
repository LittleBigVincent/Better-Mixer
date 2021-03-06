To sync your Mixer username with your Twitch username to get FFZ support, submit a pull request (PR) to the `ffzsync.json` file.

The json file will look something like this:
```json
{
  "user1": "usar1",
  "user2": "user2",
  //...
  "uuser3": "uuser3"
}
```

The first name is your Mixer username. The second name is your Twitch username. Both must be all lowercase in order for the sync to work.
If you do not comply with that style, the sync will not work and your PR will be rejected.
You must also add a comma to the end of the previous line, or the sync will not work and your PR will be rejected.

Here is an example of a correct `ffzsync.json` after your PR:
```json
{
  "user1": "usar1",
  "user2": "user2",
  //...
  "uuser3": "uuser3",
  "your_mixer": "yourtwitch"
}
```

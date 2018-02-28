This plugin adds an event where players have to try and guess a randomly generated number between two set numbers. The winner gets a prize (currently Economics or ServerRewards)

## Dependencies

### Optional

- [ServerRewards](https://oxidemod.org/plugins/serverrewards.1751/)
- [Economics](https://umod.org/plugins/economics)

## Permissions
- `guessthenumber.enter` -- players with this permission can enter in events
- `guessthenumber.admin` -- players with this permission can use the /gtn commands (administration features)

## Chat Commands
- **/gtn start** -- starts a basic event with the default numbers set in the config file
- **/gtn start \<min\> \<max\>** -- starts an event with the numbers set
- **/gtn end** -- will end the current event
- **/guess \<number\>** -- submits a guess

## Console Commands
- **gtn start** -- starts a basic event with the default numbers set in the config file
- **gtn start \<min\> \<max\>** -- starts an event with the numbers set
- **gtn end** -- will end the current event

## Rewards
- (Optional) Economics $
- (Optional) ServerRewards Points

## Configuration File
```json
{
  "Settings": {
    "Auto Event Repeat Time": 600.0,
    "Auto Events Enabled": false,
    "Economics Win Reward": 20,
    "Event Length": 30.0,
    "Max Default Number": 100,
    "Max Tries": 1,
    "Min Default Number": 1,
    "ServerRewards Win Reward": 20,
    "Use Economics": true,
    "Use ServerRewards": false
  }
}
```

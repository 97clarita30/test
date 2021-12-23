# Game Maker v0.6.9 changelog

## Game Maker Improvements

### NFT Image Self Illumination 
An option was added on the NFT Image Component that lets users select if the environment Illumination affects the NFT image or if it is Self Illuminated.
The NFTImage Component has an additional parameter now, "Ignore Lightning".
- When the parameter value is set to "True", the NFT Image seen inside the Game Maker will display the same brightness as the original NFT Image.
- When the parameter value is set to "False", the NFT Image will reflect the default lighting conditions of the experience as set by the creator.



### NFT Interact Component
Gives the creator the opportunity to let the players inspect the NFTs that have this behaviour added.
- New Component called "NFT Details Display".
- Any message can be set to trigger this feature.
- Can be used on internal assets or external NFT images.
- When triggered, a details panel is displayed with the name, creator, owner, rarity and stats of the asset, as well as a button that opens a marketplace tab with the asset in the user's browser.
- It can only be used on published assets.



### Gameplay Improvements
As part of our constant improvements to the Gameplay and Combat system we’ve added the following features:
- **Running Speed:** Running speed was increased 20%t.
- **Gameplay UI:** We’ve done a second pass on the emotes wheel, adding the random dances option.
- **NFT Interaction:** This feature was added as a complement to the NFT Interaction component.
- **Moderator Visibility:** Moderators have specific colours on the name cards and the chat.
- **Music & SFX Settings:** You’ll now be able to adjust the Music and SFX volumes from the settings panel.

## Bug fixes

- [GBT-2092](https://sandboxgame.atlassian.net/browse/GBT-2092?atlOrigin=eyJpIjoiYzgwYTQ0ZjEyNzQzNGJhN2JmNjEyZTM0NmRhZWZhNjIiLCJwIjoic2hlZXRzLWppcmEifQ) NullReferenceException when the user try to launch an experience before load the preview in "MyGames"
- [GBT-2081](https://sandboxgame.atlassian.net/browse/GBT-2081?atlOrigin=eyJpIjoiYzgwYTQ0ZjEyNzQzNGJhN2JmNjEyZTM0NmRhZWZhNjIiLCJwIjoic2hlZXRzLWppcmEifQ) NullReferenceException error after using the asset selection search bar, then clicking the Asset to Spawn input field again
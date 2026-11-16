# Eduardito01 and the Hunt for the Lost Memories

A custom, retro platform-adventure gift starring Eduardito01, guided by Commander Ken.

## Game

- Walkable overworld and four different side-scrolling worlds
- Keys, enemies, hazards, secret chambers and collectible memory shards
- Captain Glitch boss encounter and final victory cinematic
- Original synthesized 8-bit music, effects and adjustable volume
- Memory Vault with one family-photo carousel (11 pictures) and three video rewards
- Keyboard and touchscreen controls

The game entry point is [index.html](./index.html). No npm install or build is needed.

## Complete the media installation

**The HTML game is committed, but the private family media files have NOT been uploaded yet.** To enable all four reward screens, copy these files from the supplied v6 static-site ZIP into this repository:

```text
family/
  photos/
    01.jpg
    02.jpg
    ...
    11.jpg
  videos/
    video_01.mp4
    video_02.mp4
    video_03.mp4
```

**Using GitHub Desktop:**
1. Clone this repository.
2. Extract `Eduardito01_Hunt_for_the_Lost_Memories_v6_Static_Website.zip` on your computer.
3. Copy the extracted `family` folder into the cloned repository next to `index.html`.
4. Commit and push to `main`.

The deploy workflow intentionally checks for all 14 files before publishing, so visitors do not see broken memory rewards.

## Publish on GitHub Pages

Open repository **Settings → Pages** and select **GitHub Actions** as the Build and Deployment source.

After the `family` files are pushed to `main`, the site should deploy at:

https://cschrupp.github.io/eduardito01/

## Privacy

⚠️ **Public repository:** Everyone can access any photos or videos you push here, including without completing the game. The reward unlock mechanism is not access control. Only upload the media if the family is comfortable with public access.

## Technical notes

Static vanilla HTML, CSS and JavaScript with an in-browser synthesizer; no backend and no third-party runtime dependencies. Progress is saved locally in the player's browser.

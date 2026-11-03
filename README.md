# Poker Night (no accounts, no setup)

`index.html` is the whole game. Players connect directly to each other (WebRTC via PeerJS),
and the person who creates the party acts as the host. Nothing else to configure.

## Easiest hosting (2 minutes)

### Option A - Netlify Drop (no account needed to try)
1. Open https://app.netlify.com/drop
2. Drag this `index.html` file onto the page.
3. Netlify gives you a link like `https://random-name.netlify.app`. That is your game.

### Option B - GitHub Pages
1. Create a new public repository on GitHub (e.g. `poker-night`).
2. **Add file > Upload files**, drop in `index.html`, then **Commit changes**.
3. **Settings > Pages > Source: Deploy from a branch > main / (root) > Save**.
4. After about a minute: `https://YOUR-USERNAME.github.io/poker-night/`

## Playing
1. Open your link, click **Create a party** (you become the host) and keep this tab open.
2. Send friends the party code or the invite link (it ends in `#ABCDE`).
3. Friends open the link or type the code, pick a character, enter their name and sit down.
4. Add bots from the Host controls if you want to play solo.

## Good to know
- The host's browser tab holds the game. If the host closes it, the game ends for everyone.
  Reloading the host's tab on the same device restores the game.
- Works on most home and mobile networks. Some strict corporate or school networks block
  peer-to-peer connections.
- Hole cards are hidden on screen, but this is a friendly game, not a secure casino.

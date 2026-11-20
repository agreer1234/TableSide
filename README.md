# Table Side

Arcade 3D table tennis that runs in the browser. No accounts, no installs.

**Play:** https://agreer1234.github.io/TableSide/

## Modes
- **Vs CPU**: Rookie, Pro or Champion, in Quick (to 7), Standard (to 11) or best of 3.
- **Play a friend online**: host a match, then send the invite link or the 4-letter code. The two browsers connect directly (WebRTC through PeerJS's free public matchmaking server).
- **Same device**: two players on one keyboard.

## Controls
- **Swing**: move the mouse and your arm follows; swing it through the ball as the ring closes on it (green means now). Click, tap or `Space` also swing.
- **Forehand / backhand**: hold the mouse right of centre for forehand, left of centre for backhand.
- **Shape the shot**: swing up for topspin, down to chop, across to aim. A faster swing hits harder. Swing up hard at a gold ring to smash.
- **Footwork**: automatic, or press `W` `A` `S` `D` to move your own feet. The floor ring and gauge show where to stand.
- **Serve**: click or `Space` to toss, then swing as the ball drops.

## Notes
- Match records are kept in each player's own browser.
- Online play needs a direct connection between the two browsers. Very strict networks (some school or work Wi-Fi) can block it.

Everything is in `index.html`; it loads three.js and PeerJS from public CDNs.

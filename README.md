# Table Side

Arcade 3D table tennis that runs in the browser. No accounts, no installs.

**Play:** https://agreer1234.github.io/TableSide/

## Modes
- **Vs CPU**: Rookie, Pro or Champion, in Quick (to 7), Standard (to 11) or best of 3.
- **Play a friend online**: host a match, then send the invite link or the 4-letter code. The two browsers connect directly (WebRTC through PeerJS's free public matchmaking server).
- **Same device**: two players on one keyboard.

## Controls
- **Swing**: move the mouse and your arm follows; swing it through the ball as the ring closes on it (green means now). Click, tap or `Space` also swing.
- **Touch**: tap left or right of centre to aim, high on the screen to drive, low to chop. Or swipe: the angle of the swipe aims the shot.
- **Timing**: early pulls the ball cross-court and deep, late pushes it down the line and shorter.
- **Forehand / backhand**: hold the mouse right of centre for forehand, left of centre for backhand.
- **Shape the shot**: swing up for topspin, down to chop, across to aim. A faster swing hits harder. Swing up hard at a gold ring to smash.
- **Lob / drop shot**: swipe up slowly for a lob, down slowly for a drop shot (or hold `X` / `Z` as you swing). A perfectly timed full swing adds heavy spin.
- **Smash**: jump into high balls (gold ring). Smashes are nearly unreturnable (only a Perfect swing gets one back), and each extra smash in the same rally hits harder. A mistimed lob sits up to be smashed.
- **Long rallies**: past 20 shots both players are pushed back off the table and everything gets faster and riskier. Win a 15+ rally to celebrate: fist pump, spin, bow, K.O. punch or blaster (keys `1`–`5`).
- **Chop war**: every chop in a row adds more backspin until it's nearly unplayable.
- **Sound**: synthesized bat, table, net, shoe squeaks, crowd and arena ambience. Toggle with the Sound button.
- **Footwork**: automatic, or press `W` `A` `S` `D` to move your own feet. The floor ring and gauge show where to stand.
- **Serve**: click or `Space` to toss, then swing as the ball drops.
- **Trick serve**: press `T` (or tap Trick serve) before tossing, then stop the sweeping meter in the green. Nail it and it's nearly unreturnable; miss and it's a fault.

## Notes
- Match records are kept in each player's own browser.
- Online play needs a direct connection between the two browsers. Very strict networks (some school or work Wi-Fi) can block it.

Everything is in `index.html`; it loads three.js and PeerJS from public CDNs.

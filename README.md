# Split the G

A tilt-to-drink pint game. Tip your phone like a glass of stout and stop your one sip when the line lands right in the middle of the G.

Before each pint, choose which line counts:

- **Beer**: where the stout meets the head.
- **Foam**: the top of the head.

## Play it on your phone

The game is a single static page (`index.html`) and installs as a home-screen app. Tilt needs the page served over HTTPS, so host it with GitHub Pages:

1. In the repo on GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, pick the branch and `/ (root)`, and save.
3. Open the Pages URL on your phone.
   - **iPhone (Safari):** tap Share, then **Add to Home Screen**. Open it from the home screen, tap **Pour a pint**, and tap **Allow** when it asks for motion access. The game keeps itself the right way up if the screen rotates, but rotation lock avoids the flicker.
   - **Android (Chrome):** tap **Install on your home screen** under the button, or use the menu and choose **Install app**.

Once installed it works offline.

## How it plays

- Stand the phone upright like a full pint, then tip it sideways to drink. The stout stays level as the phone moves, and you can watch it pour off the low side of the rim. Tipping it back works too, but then the beer pours out behind the glass.
- The pour behaves like a real glass: nothing spills until the head reaches the rim, a gentle tip trickles, a hard tip gushes, and it stops the moment you stop tipping, with a few drips off the lip. A jolt of the phone sloshes the pint.
- You get one sip. Stand the phone back upright to stop it.
- You're scored on how many millimetres the chosen line ends up from the middle of the G, out of 100. Your best score for each mode is saved on the phone.
- On a computer with no motion sensor, you can drag the glass or use the arrow keys instead.

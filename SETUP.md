# Beatpocket: getting it onto an iPad and iPhone

Beatpocket is a web app. You put this folder on a free web host once, then add it to the Home Screen on each device. After the first visit it opens like a normal app and works with no internet connection.

## Option A: GitHub Pages (recommended, free, permanent)

1. Go to github.com and create a free account.
2. Click the + at the top right and choose New repository. Name it beatpocket, set it to Public, and click Create repository.
3. Click "uploading an existing file". Drag in every file from this folder (index.html, sw.js, manifest.webmanifest and the four icon PNGs). Click Commit changes.
4. Open the repository's Settings, then Pages. Under Build and deployment, set Source to "Deploy from a branch", choose the main branch and the / (root) folder, and click Save.
5. Wait a minute or two. The page shows your address, which looks like https://your-username.github.io/beatpocket/

GitHub Pages is free for public repositories. Nobody will find the address unless you share it.

## Option B: Netlify

Go to app.netlify.com, sign up for a free account, and drag this folder onto the deploy area. Netlify gives you an address straight away. Sign in before you drop the folder so the site is kept.

## On the iPad and iPhone

1. Open the address in Safari (not Chrome, because only Safari can add web apps to the Home Screen on iOS).
2. Tap the Share button, then Add to Home Screen, then Add.
3. Open Beatpocket from the Home Screen once while connected to the internet. That visit stores the app on the device.
4. From then on it works offline, on a plane or out of range.

Do this on each device. Each device keeps its own beats, so use Save project and Open project (via Files or AirDrop) to move a project between them. Projects made in Safari before adding to the Home Screen do not carry over to the Home Screen app.

## If there is no sound

Turn the volume up. On iOS 17 or later the app plays even with the silent switch on. On older versions, flip the silent switch off. If sound stops after switching apps, tap any pad.

## Updating later

Upload the new files over the old ones in the same place. Each device picks up the update the next time the app is opened with an internet connection. If it still shows the old version, close the app fully and open it again.

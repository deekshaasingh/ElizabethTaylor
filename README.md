# Long Live, Our Little Forever

A birthday gift for Anusha didi, from Aanya & Deeksha.

## What's in this folder

- `index.html`: the whole website (photos, chat, letter, everything is inside it)
- `anusha.mp4`: the video for chapter seven
- `music.mp3`: **you add this one.** The background song that starts when she taps "Enter our little universe".

## Add the song

1. Rename your song file to exactly `music.mp3`.
2. Put it in this folder, next to `index.html`.

If the file is missing, the site still works. The player just says "add music.mp3 to play".

To show a different song name on the player, open `index.html`, search for `bgm:` and change the `title`.

## Put it on GitHub Pages

1. Sign in at github.com and create a new repository, e.g. `anusha-birthday`. Free accounts need it to be **Public**.
2. On the repository page, click **Add file → Upload files**.
3. Drag in `index.html`, `anusha.mp4` and `music.mp3`, then click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, choose the branch **main** and the folder **/ (root)**, and click **Save**.
5. Wait a minute or two, then refresh that page. Your link appears at the top, like `https://your-username.github.io/anusha-birthday/`.

Open the link on your phone and tap through once before sending it to her.

## Good to know

- A public repository means anyone can see these files on GitHub, including the photos, the letter and the video. Anyone who has the link can also open the site.
- GitHub can take down files it receives copyright complaints about, so a commercial song in a public repository may get removed.
- Netlify Drop (app.netlify.com/drop) is another option. You drag this folder onto the page and get a link, and there's no public repository.

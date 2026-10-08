# Birthday site (encrypted)

Files
- `index.html`  lock screen + site (contains no PIN)
- `content.enc` the encrypted page body (all the text)
- `images/*.enc` encrypted photos (`images/android.png`, `iphone.png`, `desktop.png` are the lock screen wallpapers and are NOT encrypted)
- `admin.html`  tool for adding photos / editing text

Add photos
1. Open `admin.html` (locally, or on the hosted site), enter the PIN.
2. Drop photos in. Names like `date3-7.jpg` are placed automatically, otherwise pick a group.
3. Encrypt, then download the zip (or save straight into the project folder).
4. Unzip into the repo root, commit, push. They show up on the site automatically.

Edit text
- admin.html, "Site text" tab: load, edit, encrypt, replace `content.enc`.

Never commit the original (unencrypted) photos.

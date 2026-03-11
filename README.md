# iTerm2 Settings

Custom settings for iTerm2 (`com.googlecode.iterm2.plist` file).

## Import

To restore these settings on a new machine:

1. Clone this repository to `~/settings-iterm2`.
2. Open iTerm2 and go to **Settings > General > Settings**
3. Under **External settings**, check **Load preferences from a custom folder or URL**
4. Click **Browse** and select the folder with the cloned repository
5. Set **Save changes** to **Automatically**
5. Restart iTerm2

## Export

All changes to the settings are automatically saved to the local copy of the `com.googlecode.iterm2.plist` file since **Save changes** is set to **Automatically** in **External settings**.

## Backup

To back up the current version of the local `com.googlecode.iterm2.plist` file, commit and push to GitHub:

```bash
cd ~/settings-iterm2
git add com.googlecode.iterm2.plist
git commit && git push
```

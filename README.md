# MailMate Customizations

## Keybindings

| File | Description |
| :--- | :--- | :--- |
| `composer.plist` | Shortcuts for the email composition window |
| `gmail.plist` | Gmail style shortcuts in the main viewer window |
| `trackpad-gestures.plist` | Trackpad gestures as outlined in the manual |
[]

These are fairly self-explanatory if you look through the `plist` files. They should be placed in

	~/Library/Application Support/MailMate/Resources/KeyBindings

NOTE: You may need to make the KeyBindings folder if you don't already have one.

#### Some comments about gmail.plist

The keybindings in this file are, for the most part, identical to those included in MailMate. I have, however, included a couple of (IMHO) improvements:

| Shortcut | Description                                            |
| :---:    | :---                                                   |
| j/k      | will move between all messages (instead of threads)    |
| n/p      | will move between mailboxes (which I find more useful) |
| gg       | will move you to the top of the list (Vim-style)       |
| G        | will move you to the bottom (Vim-style)                |
| /        | will search all messages                               |
| u        | will go to the inbox                                   |
| #        | will delete the current message                        |
[]

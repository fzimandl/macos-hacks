# macos-hacks

## run unsigned application

1. enable full access to terminal
2. sudo chflags -R nouchg <application_path>
3. sudo xattr -rd com.apple.quarantine <application_path>
4. right-click -> open
5. in dialog click to open

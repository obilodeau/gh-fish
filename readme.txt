    Install:

gh extension install devatdawn/gh-fish

    Run the following to install the gh-fish ghcs ghce aliases automatically (existing shells will not have `ghcs` but new ones will):

gh fish alias

    Or add the following to your fish shell config:

source ~/.local/share/gh/extensions/gh-fish/gh-copilot-alias.fish

    Or (this will work instantly in the current shell)

gh fish source | source

    Local install:

clone repo -> cd gh-fish -> gh extension install . -> gh fish

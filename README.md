# Personal TextMate Bundle #

A bundle of personally useful TextMate snippets and commands.

To install:

    mkdir ~/code
    cd !$
    git clone git://github.com/btoone/brandon-tmbundle.git
    ln -s ~/code/brandon-tmbundle ~/Library/Application\ Support/TextMate/Bundles/Brandon.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Templates ##

The templates are used to create new documents that are already associated with the correct textmate langugage setting.

Each template has it's own key command but all are prefixed with "⌃ ⌥ ⌘" followed by a letter relevant to the template name

### Multimarkdown ###

⌃ ⌥ ⌘ M

The MultiMarkdown template creates a textmate document with instructional text to run the MMD snippet. It uses a snippet instead of template text because the snippet allows for use of placeholders where the template text doesn't appear to.

### Ruby ###

⌃ ⌥ ⌘ R

The Ruby template creates a new ruby script with the correct hashbang.

# configure-prompt

## Usage

1. Clone the repository:

   ```zsh
   mkdir -p ~/Projects
   git clone git@github.com:jbmorley/configure-prompt.git
   ```

2. Add the following lines to `~/.zshrc`:

   ```zsh
   FPATH="$FPATH:$HOME/Projects/configure-prompt"
   autoload configure-prompt
   configure-prompt
   ```

N.B. The above instructions assume you want to clone the project to `~/Projects/configure-prompt`, which is where I like to keep all my projects and git checkouts. Feel free to change this path if you'd like to place it somewhere else.

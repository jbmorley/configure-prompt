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

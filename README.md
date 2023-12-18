
# Shadow-Fire Vim Setup

This is my Vim setup configuration for a long time, inspired by OGs in the Vim community—primeagen and tj. The setup has been in stealth mode, evolving as needed to address challenges and enhance convenience. Feel free to help yourself if any keymaps, plugins, or schemes needed to be reused.

## Features:

- **It works :)**
   which's more than enough for self-starters.
  

## Getting Started:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/b0a04gl/shadow-fire.git
   ```

2. **Create Symbolic Links:**
   ```bash
   ln -s /path/to/shadow-fire/.vimrc ~/.vimrc
   ln -s /path/to/shadow-fire/.vim ~/.vim
   ```

3. **Include Lua File in Your Neovim Setup:**
   - Copy the Lua file (`init.lua`) from the Shadow-Fire repository to your Neovim configuration directory.
     ```bash
     cp /path/to/shadow-fire/init.lua /path/to/your-nvim-config/
     ```

4. **Update Neovim Configuration:**
   - In your `init.vim` or `init.lua` file, add the following line to source the Shadow-Fire Lua file:
     ```lua
     require('init')
     ```

5. **Stealthy Plugins:**
   Utilizes a curated set of plugins to enhance functionality while maintaining a low profile.

6. **Customization Welcome:**
   Feel free to explore and tweak the configuration to suit your preferences.
   The `.vimrc` file is your canvas.

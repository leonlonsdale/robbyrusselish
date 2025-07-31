## Available Palettes

-   **tokyonight** (by [folke](https://github.com/folke/tokyonight.nvim))
-   **gruvbox** (by [morhetz](https://github.com/morhetz/gruvbox))
-   **kanagawa** (by [rebelot](https://github.com/rebelot/kanagawa.nvim))
-   **catppuccin_mocha** (by [catppuccin](https://github.com/catppuccin/catppuccin))
-   **darkplus** (VS Code default theme)
-   **ayumirage** (by [ayu-theme](https://github.com/ayu-theme/ayu-colors))
-   **everforestdark** (by [sainnhe](https://github.com/sainnhe/everforest))

Each palette customizes the following prompt elements:

-   error
-   success
-   directory
-   branch
-   symbol
-   status
-   python
-   node
-   rust
-   go

## Usage

1. Set your preferred palette in `starship.toml`:
    ```toml
    palette = "ayumirage"
    ```
2. Copy the configuration to your Starship config file at `~/.config/starship/starship.toml`.
3. Export the `STARSHIP_CONFIG` environment variable so Starship uses this location:
    ```sh
    export STARSHIP_CONFIG="$HOME/.config/starship/starship.toml"
    ```
    Add this line to your shell profile (e.g., `.bashrc`, `.zshrc`) for persistence.
4. Restart your terminal.

## Credits

-   [Starship](https://starship.rs/)
-   Robby Russel shell theme inspiration
-   Palette authors:
    -   [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim)
    -   [morhetz/gruvbox](https://github.com/morhetz/gruvbox)
    -   [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim)
    -   [catppuccin/catppuccin](https://github.com/catppuccin/catppuccin)
    -   VS Code team (darkplus)
    -   [ayu-theme/ayu-colors](https://github.com/ayu-theme/ayu-colors)

---

Feel free to contribute

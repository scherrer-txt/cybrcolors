![Micro banner](../assets/micro.png)

# Cybrmicro
Color flavor for Micro editor inspired by the color palette popularized by **Cyberpunk 2077**.

<table>
    <tr>
    <td><img src="../assets/inspiration/insp-micro.png" width="800"/></td>
</table>

## What to do

> [!CAUTION]
> You have to have [Cybrkitty](../files/kitty.md) theme installed first!

### Create theme file:

```sh
micro ./.config/micro/colorschemes/cybrmicro.micro
```

### Insert:

```ini
# BLACK
color-link cursor-line "0"

# RED
color-link default "1"
color-link underlined "1"
color-link todo "1"

# GREEN
color-link constant.string "2"
color-link constant.string.char "2"
color-link diff-added "2"
color-link hlsearch "2,10"

# YELLOW
color-link identifier "3"
color-link constant "3"
color-link statusline-error "bold 0,3"
color-link diff-modified "3"

# BLUE

# PURPLE
color-link symbol.tag "5"
color-link trailingws "5,13"

# CYAN
color-link statement "6"
color-link line-number "9"

# WHITE
color-link symbol "7"
color-link preproc "7"
color-link type "7"
color-link special "7"
color-link comment "#4d5a80"

# ORANGE
color-link error "bold #F23D18"
color-link gutter-error "#F23D18,#330F0B"
color-link gutter-warning "#F23D18,#330F0B"
color-link diff-deleted "#F23D18"
```

### Set theme:

```sh
micro
# press CTRL+E

set colorscheme cybrmicro.micro
```

<p align="center">
  <h2 align="center">Rosé Pine for Vis</h2>
</p>

<p align="center">All natural pine, faux fur and a bit of soho vibes for the classy minimalist</p>
        
## Usage
Inside your home directory:
- Clone the repo and move the themes directly inside `~/.config/vis/themes/`
```
git clone https://github.com/matteobianchetti/rose-pine-vis-theme.git
mkdir -p ~/.config/vis/themes
cp -r ~/rose-pine-vis-theme/themes/ ~/.config/vis/themes/
```
- Set the theme inside your `visrc.lua`
add
```
vis:command('set theme rose-pine[-variant]')
```
inside
```
vis.events.subscribe(vis.events.INIT, function()

end)
```

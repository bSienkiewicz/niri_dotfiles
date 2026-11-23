### Create backup

```sh
cp -a ~/.config/niri/. ./niri/
noctalia config export > ./noctalia/config.toml
```

### Update existing config

```sh
cp -a ./niri/* ~/.config/niri/
cp -a ./noctalia/* ~/.config/noctalia/
```

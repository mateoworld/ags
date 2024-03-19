# Simple Bar

setup

```bash
mkdir -p ~/.config/ags
git clone https://github.com/Aylur/ags.git /tmp/ags
cp -r /tmp/ags/example/simple-bar/* ~/.config/ags

# optionally setup types
ags --init -c ~/.config/ags/config.js
```

running

```bash
ags -c ~/.config/ags/config.js &
```
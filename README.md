# Personal config to set up develop environment


Please add this to your bashrc:

```
CONFIG_DIR="$HOME/.config/bashrc"

for config_file in "$CONFIG_DIR"/*.sh; do
    if [ -r "$config_file" ]; then
        source "$config_file"
    fi
done
```


This will automatically add all shell scripts here to future bash sessions.

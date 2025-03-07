# plutil.yazi

Plugin for [Yazi](https://github.com/sxyazi/yazi) to preview property list ("plist") files with plutil. To install, run the below mentioned command:

```bash
ya pack -a bibugo/plutil
```

then include it in your `yazi.toml` to use:

```toml
[plugin]
append_previewers = [
  { name = "*.plist", run = "plutil" },
  { name = "*", run = "file" },
]
```
Mod from https://github.com/sxyazi/yazi/blob/main/yazi-plugin/preset/plugins/json.lua 

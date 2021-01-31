+++
date = 2021-01-30T02:00:00Z
lastmod = 2021-01-30T02:00:00Z
author = "default"
title = "You have to start somewhere"
subtitle = "Working on setting up this blog"
feature = "images/workspace2.jpg"
tags = ["hello", "post", "configuration"]
+++

{{<
    alert message="This is a test post and probably will not be published"
    type="info"
    badge="Hey there!"
>}}

Looking at various Hugo {{< link-new-window "Hugo Themes" "https://themes.gohugo.io/" >}}.
I decided to go with one named {{< link-new-window "Axiom" "https://themes.gohugo.io/axiom/" >}}.
It looks simple, it's configurable, and seems to load fast. It reminds me a bit
of Medium. Good enough. Time to configure it.

### Sometimes it's usefult to quote things.

{{< blockquote
    quote="You can trade hours for dollars or ideas for millions."
    attr="Cactus Jack on"
    cite="The Shark Tank"
    link="https://www.example.com/"
>}}

### There are also shortcodes for buttons with icons.
> Note: The `icon` parameter value must match one of the filenames at
> `/layouts/partials/svg/`. You can add more files by creating the same directory
> structure in project root. Be sure to add the same markup to the opening `<svg>`
> tag in each file.

{{< button
    text="Click me to download"
    type="info"
    icon="download"
    href="pdf/file.pdf"
>}}

### And emojis are included as well 👍
Emojis are easy to add and are fully supported.
You can even use emoji shortcodes like `:emoji_name:` to place a :beer: on the page.
Just have to make sure that `enableEmoji = true` is set in `config.toml`

### How about a little bit of code:

#### Bash:

```bash
#!/usr/bin/env bash

echo "Hello World!"
```

#### Python:

```python
#!/usr/bin/env python3

print(f"Hello World!")
```

# Embedding YouTube videos

Similar to tweets Hugo provides a shortcode for YouTube as well.
Videos can be embedded using `youtube`.

{{< youtube L_LUpnjgPso >}}


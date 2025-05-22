![Midnight](https://raw.githubusercontent.com/Serendipity-Theme/assets/main/githubHeader.png)

## Forked & inspired by [meocoder31099/Serendipity-Theme-Zed](https://github.com/meocoder31099/Serendipity-Theme-Zed)

# Serendipity Theme for Helix

A calm and pleasant theme designed for Helix. The color palette is easy on the eyes, with enough contrast to make individual elements distinguishable, but not so bright as to be jarring in a dark coding environment.

---

## Installation

### One-liner for Linux

```sh
git clone https://github.com/aqmpolyface/serendipity-theme-helix /tmp/serendipity-theme-helix && \
cp /tmp/serendipity-theme-helix/themes/* ~/.config/helix/themes
```


### Manual Installation

1. Clone this repository.
2. Locate your Helix config directory:

   * **Linux**: `~/.config/helix`
   * **Windows**: `%APPDATA%/helix`
   * **macOS**: *(Not sure, PRs welcome!)*
3. Create the `themes` directory if it doesn't exist.
4. Copy the `.toml` files from the `themes` folder in this repo into your Helix `themes` directory.
5. To use the theme:

   * Temporarily: `:theme serendipity_{variant}`
   * Permanently (in your `config.toml`):

     ```toml
     theme = "serendipity_{variant}"
     ```

---

## Available Variants

* `serendipity_morning` – Light
* `serendipity_sunset` – Dark
* `serendipity_midnight` – Darkest

### Previews

#### Midnight

![Midnight Preview](https://raw.githubusercontent.com/AQMpolyface/Serendipity-Theme-Helix/refs/heads/master/assets/previews/midnight.png)

#### Sunset

![Sunset Preview](https://github.com/AQMpolyface/Serendipity-Theme-Helix/blob/master/assets/previews/sunset.png?raw=true)

#### Morning

![Morning Preview](https://raw.githubusercontent.com/AQMpolyface/Serendipity-Theme-Helix/refs/heads/master/assets/previews/morning.png)

---

## Credits

Originally created by [Micheal Andreuzza](https://github.com/michael-andreuzza)
Follow him on [Twitter](https://twitter.com/Mike_Andreuzza).

This themes were translated from the zed themes using claude 3.7.
The themes are an absolute dumpster fire, but at least they work. 

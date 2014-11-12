# title-tab for iTerm2 + oh-my-zsh

This plugin sets the tab title to `current folder (git-branch)` if you're on a git repository or `current folder`.

![title tab working](http://i.imgur.com/9nNCNIT.png)

## Installing

1. Clone this repository to `/path/to/.oh-my-zsh/custom/plugins` (usually it is on `~/.oh-my-zsh`)

  ```bash
  $ git clone repository ~/.oh-my-zsh/custom/plugins
  ```

2. Go to `iTerm > Preferences... > Appearance` and uncheck all the checkboxes from **Window & Tab Titles** section.

![screenshot iTerm Preferences](http://i.imgur.com/IfydKIH.png)

3. Find where your zsh plugins are on the ```.zshrc``` file and add ```title-tab``` to the list.

  ```bash
  plugins=(... title-tab)
  ```

4. Run ```source .zshrc```.

  ```bash
  $ source ~/.zshrc
  ```

  Or if you use ```zsh_reload```:

  ```bash
  $ src
  ```

And that's it. :)

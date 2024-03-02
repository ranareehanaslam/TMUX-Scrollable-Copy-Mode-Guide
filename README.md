# TMUX Scrollable & Copy Mode Guide 📜

Welcome to the ultimate guide on making your TMUX session more interactive and user-friendly with scrollable panes and copy mode, along with utilizing mouse support for an enhanced experience. Whether you're a developer, system administrator, or any user who frequently works within terminal environments, mastering these features will significantly improve your workflow efficiency.

## 🌟 Features

- **Scrollable Panes:** Navigate through your terminal output with ease.
- **Copy Mode:** Select and copy text directly from your TMUX panes.
- **Mouse Support:** Seamlessly scroll and interact with TMUX using your mouse.

## 🛠️ Setup & Configuration

To unlock the full potential of TMUX, including scrollable panes, copy mode, and mouse support, follow these simple steps:

### 1. Enable Mouse Support

Add the following line to your `~/.tmux.conf` file to enable mouse support across TMUX sessions:

```tmux
set -g mouse on
```

This command allows for mouse interaction within TMUX, including scrolling through panes, resizing them, and navigating between different windows.

### 2. Accessing Scrollable Panes

Once mouse support is enabled, you can easily scroll through your terminal output using your mouse's scroll wheel. Alternatively, you can enter copy mode to scroll using keyboard commands:

- Press `Ctrl-b` then `[` to enter copy mode.
- Use arrow keys or `Page Up`/`Page Down` to navigate your history.

### 3. Utilizing Copy Mode

While in copy mode, you can select text using your arrow keys. To start text selection:

- Press `Space` to begin selecting.
- Move around with arrow keys to highlight the desired text.
- Press `Enter` to copy the highlighted text to your clipboard.

Exiting copy mode can be done by pressing `q`.

## 🖱️ Mouse Interactions

With mouse support activated, here are some additional gestures you can use:

- **Scrolling:** Use the mouse wheel to scroll up and down within a pane.
- **Pane Resizing:** Click and drag the borders between panes to resize them.
- **Window Navigation:** Click on window names in the status bar to switch between them.

## 📌 Additional Tips

- To paste the copied text from TMUX, you can use `Ctrl-b` followed by `]`.
- Remember to reload your TMUX configuration after making changes to `~/.tmux.conf` by executing `tmux source-file ~/.tmux.conf` or simply restarting TMUX.
- Explore TMUX plugins and additional settings to further customize your experience.

## 📘 Conclusion

By following this guide, you've taken a significant step towards a more efficient and user-friendly terminal experience with TMUX. Scrollable panes, copy mode, and mouse support are just the beginning of what TMUX can offer. Experiment with different configurations and plugins to tailor TMUX to your needs and preferences.

Happy TMUXing! 🚀

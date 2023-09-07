# ubuntu-environment
Reproduce local development environment

#### Kitty
* Add kitty as `x-terminal-emulator` option:

```
# run:
sudo update-alternatives --install /usr/bin/x-terminal-emulator x-terminal-emulator /home/$USER/.local/kitty.app/bin/kitty 50

# then update the default terminal by:
sudo update-alternatives --config x-terminal-emulator 

```

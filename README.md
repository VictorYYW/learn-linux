# learn-linux

## Initialization File
- *.bash_profile* is executed when you login
  - put PATH and other environment variables
- *.bashrc* is used for non login shells
  - put alias and export
- You may want to apply your setting for login shell to non-login one.
  - add the following lines to *.bash_profile*
```bash
if [ -f ~/.bashrc ]; then
  source ~/.bashrc
fi
```

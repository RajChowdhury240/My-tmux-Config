#### Theme 1 - Preview 

![](PoC.png)

Pretty Tmux config

### Install
MacOs
```bash
brew install tmux
```
Linux
```bash
sudo apt-get install tmux
```
Install using tpm 
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

If you are a tpm user, you can install the theme and keep up to date by adding the following to your .tmux.conf file:
```
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-sensible'
set -g @plugin 'kylepeeler/tmux-nightowl'
set -g @nightowl-border-contrast true
set -g @nightowl-cpu-usage true
set -g @nightowl-ram-usage true
set -g @nightowl-show-powerline true

set -g mouse on

run -b '~/.tmux/plugins/tpm/tpm'
```
- Use the tpm install command: prefix + I (default prefix is ctrl+b)
- so : Crtl + b , then I together press it will install the theme


#### Theme 2 - Preview

![](https://github-production-user-asset-6210df.s3.amazonaws.com/30806882/302259846-4017cada-dcb7-4aa6-82b1-470f53fba6da.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240205%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240205T104333Z&X-Amz-Expires=300&X-Amz-Signature=8f3bdb7d9f4a4a6c62428e74e6b23cbcec7195f53dcb534c75bcaa68e7c2c999&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=0)


#### Install
Install Tmux first
```
$ brew install tmux

$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
now onto themeing

```bash
$ git clone https://github.com/gpakosz/.tmux
$ cp .tmux/.tmux.conf ~
```
now one more step
```bash
$ git clone https://github.com/Optixal/tmux-dracula
$ cp tmux-dracula/.tmux.conf.local ~
$ sudo reboot
```

## NvChad
if you have any prev nvim config remove em , in Mac

```
$ sudo rm -r ~/.local/share/nvim/
​```
#### Install NvChad

```
$ git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
```

![](https://faizal-ctf.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F68ca7968-174f-4df4-ab04-3d91b871155c%2Fc2bfed8a-9e6f-473e-a6f4-9c7fc5880a73%2FScreenshot_2024-02-06_at_5.24.06_AM.png?table=block&id=0df38f61-9c7e-4086-b78c-d1ca226052a2&spaceId=68ca7968-174f-4df4-ab04-3d91b871155c&width=2000&userId=&cache=v2)

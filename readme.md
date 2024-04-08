# For running text gen models locally

## How to install

1) Clone `git clone https://github.com/oobabooga/text-generation-webui` or [download](https://github.com/oobabooga/text-generation-webui/archive/refs/heads/main.zip) the repository.
2) Run the `./start_linux.sh`
3) Select your GPU vendor when asked.
4) Once the installation ends, browse to `http://localhost:7860/?__theme=dark`.
5) Have fun!

https://github.com/oobabooga/text-generation-webui?tab=readme-ov-file#how-to-install

# For running image gen models locally

https://github.com/AUTOMATIC1111/stable-diffusion-webui

## Automatic Installation on Linux
1. Clone: `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`
2. Run `pyenv install 3.10.6` & `pyenv local 3.10.6`.
3. for CPU running add to COMMANDLINE_ARGS in webui-user.sh: `--use-cpu all --precision full --no-half --skip-torch-cuda-test`
3. Run `./webui.sh`.
4. Check `webui-user.sh` for options.
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
4. `sudo apt-get install libgl1`.
5. Run `./webui.sh`.
6. Check `webui-user.sh` for options.
7. download models extensions: 
Install from SD Webui: install from URL, and Paste Link https://github.com/Iyashinouta/sd-model-downloader
or https://github.com/zixaphir/Stable-Diffusion-Webui-Civitai-Helper
8. Some good models:
  * High resolution model [SDXL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
    * Not suitable for generating readable text, faces, or objects with compositional structure
  * Standard resolution photorealistic model [Photon](https://civitai.com/models/84728/photon)
    * Has some issues with rendering hands and fingers
  * Versatile model for digital art, drawings, anime and painting [GhostMix](https://civitai.com/models/36520?modelVersionId=76907)
    * Requires the use of LoRAs for perfect results
    * Not very good for photorealistic images, or even to generate images of "common" persons or scenes
  * Versatile high resolution model [JuggernautXL](https://civitai.com/models/133005/juggernaut-xl)
    * Good generalist model that makes good use of light/shadow effects
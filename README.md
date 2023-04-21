# simple_a1111_paperspace
Easy jupiter notebook to get Automatic1111 working on the paperspace environment

Instructions:

* Create a new paperspace notebook from scratch, but under advanced settings use `cyberes/gradient-base-py3.10:latest` as the base rather than the standard paperspace base install
* Run the machine
* Upload a1111.ipynb to the notebook
* Open the notebook, comment out at least one model to download in the first cell and then run both cells
* Click on the share gradio link and the a1111 UI will appear in your browser :)

Notes:

1. You will have to download the models each time you start a new machine, unless you want to pay for extra paperspace storage
2. Images are saves to /tmp/outputs so you will need to download them to your PC if you want to keep them, or change the storage location to /notebooks/stable-diffusion-webui/outputs to keep them in your paperspace - it is recommended to install the image browser extension by opening a terminal in paperspace, and then using `cd /notebooks/stable-diffusion-webui` and then `git clone https://github.com/yfszzx/stable-diffusion-webui-images-browser`, then stopping and restarting the second cell (Note this is how all extensions need to be installed)

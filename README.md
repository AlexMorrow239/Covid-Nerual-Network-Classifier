# Covid-Nerual-Network-Classifier

## Usage

### Raw Code

If you just want to look at the code, refer to `CovidClassifier.py`. This is colab's downloaded version of my ipynb.

### Visual Outputs

Getting the visual outputs will require more steps:

1. Fork and clone this repository
2. Unzip `SS24.zip` (Data) and `best_models.zip` (encoded version of already trained models).
3. Open in preferred IDE -- I used colab so this didnt hurt my CPU.
4. Modify `CovidClassifier.ipynb` so that all sections of the code that refer to relative paths reflect the desired paths on your local machine. I explicitly state when this is necessarry in the file.
5. Run every cell sequentially except for the cells where the models are trained. You can simply load the models from memory.

> **Important Remark:** If you get a bunch of these in your outputs "Could not render content for 'application/vnd.jupyter.widget-view+json'
{"version_major":2,"version_minor":0,"model_id":"6eef6f34b0b4420da99bb7d2d86d94de"}" You need to change these import statements "from tqdm.notebook import tqdm" to "from tqdm import tqdm"


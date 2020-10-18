# merishnas-generate-art-gans

Generating unique architectures using **Generative Adversarial Networks.**

1. Start by creating a virtual environment for installing the libraries.
```virtualenv venv```

2. Activate the environment
```
cd venv/Scripts
activate
```

3. Go back to the root directory and install the requirements.txt
```pip install -r requirements.txt```

4. The `GAN_generation.ipynb` file contains the code for Image generation.

Here is a sample of what the results look like.

<img src="imgs/architecture_result.gif">

Note: You can download the model checkpoints I've trained from [here](https://drive.google.com/drive/folders/1ApQPifX9OoIzjPjzuMjRZKRvs4WtU_pM?usp=sharing). Change "from_checkpoint=True" in the notebook.

### Citations

- The dataset was downloaded from [WikiArt Library](https://www.wikiart.org/en/paintings-by-genre) which contains a lot of artworks classified on the basis of genre.
- [References from Thomas Simonini's CatDCGAN](https://github.com/simoninithomas/CatDCGAN)
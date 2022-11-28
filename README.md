# Stable Diffusion 2.0 Negative Prompting

Jupyter Notebooks for experimenting with negative prompting with Stable Diffusion 2.0. All these notebooks _should_ work in Colab (even with a K80 GPU).

These notebooks include:

- [SD 2.0 Base](sd_2_0_base.ipynb) ([Colab](https://colab.research.google.com/github/minimaxir/stable-diffusion-negative-prompt/blob/main/sd_2_0_base.ipynb)): A personal notebook for easy inference with Stable Diffusion 2.0 using diffusers, including textual inversion support (the `<wrong>` token is loaded by default), grid output, and individual image output.
- [3x3 Grid](sd_2_0_grid_3x3.ipynb) ([Colab](https://colab.research.google.com/github/minimaxir/stable-diffusion-negative-prompt/blob/main/sd_2_0_grid_3x3.ipynb): A notebook to generate images using Stable Diffusion 2.0 in a 3x3 grid using a cross of positive prompt additions and negative prompts/tokens.
- [Wrong Image Generator](wrong_image_generator.ipynb): A notebook to generate synthetic "negative" images for training the `<wrong>` textual inversion token.

## Maintainer/Creator

Max Woolf ([@minimaxir](https://minimaxir.com))

_Max's open-source projects are supported by his [Patreon](https://www.patreon.com/minimaxir) and [GitHub Sponsors](https://github.com/sponsors/minimaxir). If you found this project helpful, any monetary contributions to the Patreon are appreciated and will be put to good creative use._

## License

MIT

# Estimating Coal Power Plant Operation From Satellite Images with Computer Vision
Explore how to monitor coal power plant activity by leveraging satellite imagery and computer vision models.

Original Author:
* André Ferreira, TransitionZero, andre@transitionzero.org

Updated by:
*   [2024] Isabelle Tingzon, issa@climatechange.ai
*   [2026] El Khalil Cherif, el.k.cherif@tecnico.ulisboa.pt

Originally presented at Climate Change AI Summer School 2023, revised for 2024 and 2026

## Access this tutorial

We recommend executing this notebook in a Colab environment to gain access to GPUs and to manage all necessary dependencies. <a target="_blank" href="https://colab.research.google.com/github/climatechange-ai-tutorials/coal-power-mrv/blob/main/CCAI_Summer_School_Tutorial___MRV.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

If running locally using a fork of this repository, you can install the required Python packages using the terminal command below. It is recommended to create this in a separate Python environment.
```
pip install -r requirements.txt
```

Note: The code also uses `aim` to track training progress, which is a [Python package available for Linux and MacOs](https://aimstack.readthedocs.io/en/latest/quick_start/setup.html). If you are using Windows, you may have trouble installing `aim`. If so, it is recommended to use Google Colab to execute the code instead, or remove uses of `AimLogger` in the code.

## Contribute to this tutorial

Please refer to these [GitHub instructions](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project#about-forking) to open a pull request via the "fork and pull request" workflow. 

Pull requests will be reviewed by members of the Climate Change AI Tutorials team for relevance, accuracy, and conciseness.

## Climate Change AI Tutorials
Check out the [tutorials page](https://www.climatechange.ai/tutorials?) on our website for a full list of tutorials demonstrating how AI can be used to tackle problems related to climate change.

## License
Usage of this tutorial is subject to the MIT License.

## Cite

### Plain Text
Ferreira, A, Tingzon, T., Cherif, E.K. (2026). Estimating Coal Power Plant Operation From Satellite Images with Computer Vision [Tutorial]. In Climate Change AI Summer School. Climate Change AI. https://doi.org/10.5281/zenodo.21831109

### BibTeX

```
@misc{ferreira2026estimating,
  title={Estimating Coal Power Plant Operation From Satellite Images with Computer Vision},
  author={Ferreira, Andre and Tingzon, Isabelle and Cherif, El Khalil},
  year={2026},
  organization={Climate Change AI},
  type={Tutorial},
  doi={https://doi.org/10.5281/zenodo.21831109},
  booktitle={Climate Change AI Summer School},
  howpublished={\url{https://github.com/climatechange-ai-tutorials/coal-power-mrv}}
}
```

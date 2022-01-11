# Interactive dashboard from notebook with Voilà


| Voilà |
| :---------------------: |
| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NHameleers/voila/HEAD?urlpath=voila%2Ftree%2Fnotebooks) |

This example demonstrates how to use [Voilà](https://github.com/voila-dashboards/voila) on Binder.

Original code found on [this repository](https://github.com/binder-examples/voila)

## Configuration

If you would like to use the same configuration as this repository but for another project, check out the following steps:

1. Make sure the repository is publicly available (on GitHub, Gitlab or as a [GitHub Gist](https://gist.github.com)
2. Define the dependencies in [`environment.yml`](./environment.yml). `requirements.txt` is also supported. In the dependency file, add `voila`.
3. Go to [mybinder.org](https://mybinder.org) and enter the URL of the repository.
4. In `Path to a notebook file`, select `URL` and use the Voilà endpoint: `voila/render/path/to/notebook.ipynb`
5. Click `Launch`.
6. Binder will trigger a new build if this is the first launch (or if there have been new changes since
   the last build). This might take a few minutes to complete. If an image is already available,
   the server will be able to start within a few seconds.
7. Make sure the url you get from binder contains **urlpath=** instead of **labpath=**

Here is an overview of the Binder configuration on [mybinder.org](https://mybinder.org):

![image](https://user-images.githubusercontent.com/591645/132292481-01f877c3-77f8-46ba-b265-23bd3e25f513.png)

For more details, check out the Voilà documentation on https://voila.readthedocs.io/en/latest/deploy.html#deployment-on-binder


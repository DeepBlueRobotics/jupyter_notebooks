# FRC-related Jupyter notebooks

This repository contains Jupyter notebooks math and analysis relevant to FRC.

They can be opened/edited with a Jupyter installation on your local computer, or a read-only copy can be accessed [via JupyterLite](https://deepbluerobotics.github.io/jupyter_notebooks/lab/index.html).

## Contributing

Feel free to open GitHub issues, or even better, fork this repository, modify the fork, and submit a pull-request. To make your fork accessible via JupyterLite in the GitHub Pages associated with your fork:

1. Go to your fork on GitHub.
2. Click `Settings`, click `Pages`, and then, under `Build and deployment` Source, select `GitHub Actions`.
3. Click `Actions` and enable them for the repo.
4. While on the `Actions` page, select `Build and Deploy` and then `Run workflow` to do an initial deployment of JupyterLite.

Once you've done that, everytime you push to the `master` branch, JupyterLite will be deployed to the repo's GitHub Pages site within a few minutes. Once it is deployed, you can visit it at `https://<username>.github.io/jupyter_notebooks/lab/index.html`. You won't be able to overwrite any of the files via JupyterLite, but you can change them in the notebook interface and download copies of any files with the changes (`File > Download`) and replace the files in your GitHub fork with the downloaded versions.


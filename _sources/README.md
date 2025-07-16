# PARADIM Documentation

This public repository contains a [JupyterBook](https://jupyterbook.org/) for the PARADIM Data Management platform.
It is automatically built into a Docker image using a GitHub Actions workflow. The image is pushed to a public DockerHub repository and deployed under the PARADIM portal stack as https://docs.htmdec.org. 

New commits made to the main branch will regenerate the live documentation.

To create a new compatible conda environment:
```
conda create -n paradim_docs python=3.10
conda activate paradim_docs
pip install -r requirements.txt
```

To build locally:
```
jupyter-book build --all .
```

If you then open `_build/html/index.html` in your local browser you can preview the rendered result.

To build the Docker image locally:
```
docker build -t <org>/paradim-docs .
```

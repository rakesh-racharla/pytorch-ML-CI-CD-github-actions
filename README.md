# For Local Setup

# Install requirements

Step 1: Create a new Anaconda/Miniconda environment
```shell
conda create -n <choose a name> -f conda.yaml
```

Step 2: Install packages in an existing environment using pip
```shell
pip install -r requirements.txt
```

# Step:3 Application entry point

```shell
python main.py
```

# Step:4 Tensorboard

To start Tensorboard:
```shell
tensorboard --logdir runs
```

The output will be something like:
```shell
TensorBoard 2.6.0 at http://localhost:6006/ (Press CTRL+C to quit)
```

Follow the instructions printed to the terminal to view Tensorboard in a browser.


# For Githhub Actions CICD

- Clone the repo (optional)
```shell
git clone https://github.com/rakesh-racharla/pytorch-ML-CI-CD-github-actions.git
```
 - Make changes if needed and commit.
 - Every push will trigger a new build.
 - Check your workflow under "Actions" Tab.
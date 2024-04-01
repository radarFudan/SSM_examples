This translation example is adapted from a [pytorch tutorial](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html). 
The `s4d.py` is adapted from [state-spaces/s4](https://github.com/state-spaces/s4/blob/main/example.py). 

All jupyter notebooks assume the usable of a GPU to train the model. 
Change the `load_ckpt = False` into `load_ckpt = True` (in second code cell) and then the checkpoints can be loaded from `checkpoint`. 
The comparison of training loss curve is provided in the `/assets`. 

The following snippet is the code for environment construction and data preparation. 
```
    conda create -n SSM_Examples python=3.10
    conda activate SSM_Examples
    pip install -r requirements.txt

    cd SSM_Examples
    wget https://download.pytorch.org/tutorial/data.zip
    unzip data.zip
```


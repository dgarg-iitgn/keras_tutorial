## using softmax cluster

### Login:
```bash
ssh uname@softmax.iitgn.ac.in
```


### add following lines in ~/.bashrc
```bash
export PATH=/anaconda/bin:/usr/local/cuda-9.0/bin:/snap/bin:$PATH
export LD_LIBRARY_PATH=/usr/local/cuda-9.0/lib64
source ~/.bashrc
```

### Virtual Environment with TF installed:

```bash
source activate dlsoft
```

### to check gpu usage

```bash
nvidia-smi
```

### to write code in the cluster
```bash
micro filename.extension
```

### to upload the files in cluster
```bash
scp -r filename.extension username@softmax.iitgn.ac.in:/path_of_the _desired_folder
```

### for running the code
```bash
screen -S name
python filename.py
```
# OmniSynth

```bash
docker run --name data_gen_pipeline --gpus all \
    -v /nfs/Personas:/workspace/data_gen_pipeline/tencent_personas \
    -v /home/shyam.pawar/code/data_gen_pipeline:/workspace/data_gen_pipeline \
    --network host --pid host -it python:latest /bin/bash
```

```bash
apt update && apt upgrade -y
```


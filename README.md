# images

以下均为用于推理的镜像，列表如下：

1. [Python3.7](##Python3.7)
2. [Python3.8](##Python3.8)
3. [Python3.9](##Python3.9)
4. [Python3.10](##Python3.10)

## Python3.7

## Python3.8

Python主版本3.8以下目前有1个镜像，列表如下：

## cuda11.3.1+cudnn8 + cuda12.1+cudnn9 + torch + tensorflow + mmvc+mmdet套件 + transformer

详细pip freeze如下：

```bash
absl-py==2.1.0
addict==2.4.0
aliyun-python-sdk-core==2.15.0
aliyun-python-sdk-kms==2.16.2
anyio==4.3.0
argon2-cffi==23.1.0
argon2-cffi-bindings==21.2.0
arrow==1.3.0
asttokens==2.4.1
astunparse==1.6.3
async-lru==2.0.4
attrs==23.2.0
Babel==2.14.0
backcall==0.2.0
beautifulsoup4==4.12.3
bleach==6.1.0
cachetools==5.3.3
certifi==2024.2.2
cffi==1.16.0
charset-normalizer==3.3.2
click==8.1.7
colorama==0.4.6
comm==0.2.2
contourpy==1.1.1
crcmod==1.7
cryptography==42.0.5
cycler==0.12.1
Cython==3.0.9
debugpy==1.8.1
decorator==5.1.1
defusedxml==0.7.1
exceptiongroup==1.2.1
executing==2.0.1
fastjsonschema==2.19.1
filelock==3.13.1
flatbuffers==24.3.7
fonttools==4.49.0
fqdn==1.5.1
fsspec==2024.3.1
gast==0.4.0
google-auth==2.28.1
google-auth-oauthlib==1.0.0
google-pasta==0.2.0
grpcio==1.62.0
h11==0.14.0
h5py==3.10.0
httpcore==1.0.5
httpx==0.27.0
huggingface-hub==0.21.4
idna==3.6
importlib-metadata==7.0.1
importlib_resources==6.1.2
ipykernel==6.29.4
ipython==8.12.3
ipywidgets==8.1.2
isoduration==20.11.0
jax==0.4.13
jedi==0.19.1
Jinja2==3.1.3
jiwer==3.0.3
jmespath==0.10.0
joblib==1.3.2
json5==0.9.25
jsonpointer==2.4
jsonschema==4.21.1
jsonschema-specifications==2023.12.1
jupyter==1.0.0
jupyter-console==6.6.3
jupyter-events==0.10.0
jupyter-lsp==2.2.5
jupyter_client==8.6.1
jupyter_core==5.7.2
jupyter_server==2.14.0
jupyter_server_terminals==0.5.3
jupyterlab==4.1.8
jupyterlab_pygments==0.3.0
jupyterlab_server==2.27.1
jupyterlab_widgets==3.0.10
keras==2.12.0
kiwisolver==1.4.5
Levenshtein==0.25.0
libclang==18.1.1
lightgbm==4.3.0
Markdown==3.5.2
markdown-it-py==3.0.0
MarkupSafe==2.1.5
matplotlib==3.7.5
matplotlib-inline==0.1.7
mdurl==0.1.2
mistune==3.0.2
ml-dtypes==0.2.0
mmcv==2.1.0
mmcv-full==1.7.2
mmdet==3.3.0
mmengine==0.10.3
model-index==0.1.11
mpmath==1.3.0
nbclient==0.10.0
nbconvert==7.16.3
nbformat==5.10.4
nest-asyncio==1.6.0
networkx==3.1
notebook==7.1.3
notebook_shim==0.2.4
numpy==1.23.5
nvidia-cublas-cu12==12.1.3.1
nvidia-cuda-cupti-cu12==12.1.105
nvidia-cuda-nvrtc-cu12==12.1.105
nvidia-cuda-runtime-cu12==12.1.105
nvidia-cudnn-cu12==8.9.2.26
nvidia-cufft-cu12==11.0.2.54
nvidia-curand-cu12==10.3.2.106
nvidia-cusolver-cu12==11.4.5.107
nvidia-cusparse-cu12==12.1.0.106
nvidia-nccl-cu12==2.19.3
nvidia-nvjitlink-cu12==12.4.99
nvidia-nvtx-cu12==12.1.105
oauthlib==3.2.2
opencv-python==4.9.0.80
opendatalab==0.0.10
openmim==0.3.9
openxlab==0.0.37
opt-einsum==3.3.0
ordered-set==4.1.0
oss2==2.17.0
overrides==7.7.0
packaging==23.2
pandas==2.0.3
pandocfilters==1.5.1
parso==0.8.4
patsy==0.5.6
pexpect==4.9.0
pickleshare==0.7.5
pillow==10.2.0
pkgutil_resolve_name==1.3.10
platformdirs==4.2.0
prometheus_client==0.20.0
prompt-toolkit==3.0.43
protobuf==4.25.3
psutil==5.9.8
ptyprocess==0.7.0
pure-eval==0.2.2
py-cpuinfo==9.0.0
pyasn1==0.5.1
pyasn1-modules==0.3.0
pycocotools==2.0.7
pycparser==2.21
pycryptodome==3.20.0
Pygments==2.17.2
pyparsing==3.1.1
python-dateutil==2.9.0.post0
python-json-logger==2.0.7
pytz==2023.4
PyYAML==6.0.1
pyzmq==26.0.2
qtconsole==5.5.1
QtPy==2.4.1
rapidfuzz==3.6.2
referencing==0.35.0
regex==2023.12.25
requests==2.31.0
requests-oauthlib==1.3.1
rfc3339-validator==0.1.4
rfc3986-validator==0.1.1
rich==13.4.2
rpds-py==0.18.0
rsa==4.9
safetensors==0.4.2
scikit-learn==1.3.2
scipy==1.10.1
seaborn==0.13.2
Send2Trash==1.8.3
shapely==2.0.3
six==1.16.0
sniffio==1.3.1
soupsieve==2.5
stack-data==0.6.3
statsmodels==0.14.1
sympy==1.12
tabulate==0.9.0
tensorboard==2.12.3
tensorboard-data-server==0.7.2
tensorflow==2.12.0
tensorflow-estimator==2.12.0
tensorflow-io-gcs-filesystem==0.34.0
termcolor==2.4.0
terminado==0.18.1
terminaltables==3.1.10
thop==0.1.1.post2209072238
threadpoolctl==3.3.0
tinycss2==1.3.0
tokenizers==0.15.2
tomli==2.0.1
torch==2.2.1
torchaudio==2.2.1
torchvision==0.17.1
tornado==6.4
tqdm==4.65.2
traitlets==5.14.3
transformers==4.39.0
triton==2.2.0
types-python-dateutil==2.9.0.20240316
typing_extensions==4.10.0
tzdata==2024.1
ultralytics==8.1.30
uri-template==1.3.0
urllib3==1.26.18
wcwidth==0.2.13
webcolors==1.13
webencodings==0.5.1
websocket-client==1.8.0
Werkzeug==3.0.1
widgetsnbextension==4.0.10
wrapt==1.14.1
xgboost==2.0.3
yapf==0.40.2
zhon==2.0.2
zipp==3.17.0
```

镜像中的cuda路径为：

```bash
/usr/local/cuda    -> cuda-12.1
/usr/local/cuda-11 -> cuda-11.3
/usr/local/cuda-11.3 
/usr/local/cuda-12 -> cuda-12.1
/usr/local/cuda-12.1
```

镜像拉取地址: 
registry.cn-chengdu.aliyuncs.com/mdl_base_dev/ubuntu20.04_cuda11.3.1_cudnn8_python3.8:cuda12.1_cudnn9_torch2.2_tf2.12_mmcv2.1_mmdet3.3_transformers4.39_jupyter_compressed

## Python3.9

## Python3.10

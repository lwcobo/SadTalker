<div align="center">

<img src='https://user-images.githubusercontent.com/4397546/229094115-862c747e-7397-4b54-ba4a-bd368bfe2e0f.png' width='500px'/>


<!--<h2> 😭 SadTalker： <span style="font-size:12px">Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation </span> </h2> -->

  <a href='https://arxiv.org/abs/2211.12194'><img src='https://img.shields.io/badge/ArXiv-PDF-red'></a> &nbsp; <a href='https://sadtalker.github.io'><img src='https://img.shields.io/badge/Project-Page-Green'></a> &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Winfredy/SadTalker/blob/main/quick_demo.ipynb) &nbsp; [![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/vinthony/SadTalker) &nbsp; [![sd webui-colab](https://img.shields.io/badge/Automatic1111-Colab-green)](https://colab.research.google.com/github/camenduru/stable-diffusion-webui-colab/blob/main/video/stable/stable_diffusion_1_5_video_webui_colab.ipynb) &nbsp; <br> [![Replicate](https://replicate.com/cjwbw/sadtalker/badge)](https://replicate.com/cjwbw/sadtalker) [![Discord](https://dcbadge.vercel.app/api/server/rrayYqZ4tf?style=flat)](https://discord.gg/rrayYqZ4tf) [![Add Server](https://img.shields.io/badge/MCP%20Now-Add%20Server-blue?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTcuNTc1NTQgMC4wMDE4NzY0NEgxNi40NjIzQzE3LjY2MDEgLTAuMDA3MTE1MTkgMTguODU3MiAwLjA4MTQ5NDEgMjAuMDQwNCAwLjI2NzUwMUMyMC45NDkxIDAuNDgzNzY2IDIxLjc4MTIgMC45NDM5MTkgMjIuNDQ2NiAxLjU5NzU4QzIzLjExNSAyLjI1NDg1IDIzLjU3MTkgMy4wOTU1MiAyMy43NTkxIDQuMDEyNjJDMjMuOTMxMSA1LjE5MTQ0IDI0LjAxMTEgNi4zODE5OSAyMy45OTg0IDcuNTczMTdWMTYuNDQzM0MyNC4wMDczIDE3LjY0MDYgMjMuOTE4MiAxOC44MzY2IDIzLjczMTggMjAuMDE5NUMyMy41MjU5IDIwLjkyNTcgMjMuMDY3MiAyMS43NTYzIDIyLjQwODUgMjIuNDE0QzIxLjc1MyAyMy4wODM1IDIwLjkxMzkgMjMuNTQ1NCAxOS45OTY0IDIzLjc0MzFDMTguODE0OCAyMy45MjU3IDE3LjYxOTkgMjQuMDEwOSAxNi40MjQyIDIzLjk5OEg3LjU2NDc5QzYuMzYzNTcgMjQuMDA3MSA1LjE2MzE4IDIzLjkyMDYgMy45NzU5MyAyMy43MzgyQzMuMDY5NDIgMjMuNTE3NCAyLjIzOTQzIDIzLjA1NTkgMS41NzQ1NiAyMi40MDMyQzAuOTA0MDA1IDIxLjc0NDUgMC40NDU2NjEgMjAuOTAwOCAwLjI1NzE3NiAxOS45ODE0QzAuMDk2OTExNyAxOC45NTA5IDAuMDExNTcyOCAxNy45MTA0IDAuMDAxMzE2NiAxNi44NjgxVjcuNTYyNDJDLTAuMDA3ODc3MDEgNi4zNjEzIDAuMDgxMTM5NCA1LjE2MTE1IDAuMjY3OTE4IDMuOTc0NTNDMC40Nzc2NjcgMy4wNjk4IDAuOTM1ODkyIDIuMjQxIDEuNTkxMTYgMS41ODA5OEMyLjI1MSAwLjkxNjgwOSAzLjA4ODE3IDAuNDU1MDExIDQuMDAzMjcgMC4yNTA5QzUuMTg0OSAwLjA2OTAyNjcgNi4zNzk5OCAtMC4wMTM4Mjc1IDcuNTc1NTQgMC4wMDE4NzY0NFpNMTUuMDk0MSA3LjA5ODU2QzE0LjgwOTcgNy4xMDAxOSAxNC41MjczIDcuMTQ5NTUgMTQuMjYxMSA3LjI0NDA2TDE0LjI2MDEgNy4yNDUwNEwxNC4yMjEgNy4yNTg3MUwxNC4yMjAxIDcuMjU5NjlDMTQuMTk1MiA3LjI2ODk4IDE0LjE3MDQgNy4yNzg5IDE0LjE0NTggNy4yODg5OUgxNC4xNDQ5TDE0LjExMjYgNy4zMDI2NkgxNC4xMTE3QzEzLjY0MTggNy41MDM3OCAxMy4yMjk4IDcuODUgMTIuOTU0NCA4LjMyMDI0TDEyLjAwMDMgOS45NTAxMkwxMS4wNDYyIDguMzIwMjRDMTAuNzY0NyA3LjgzOTQ1IDEwLjMzOTYgNy40ODkwMSA5Ljg1Njc5IDcuMjg5OTZIOS44NTU4MUw5LjgxNzcyIDcuMjc0MzRMOS44MTY3NSA3LjI3MzM2QzkuNzkxOTcgNy4yNjM2NSA5Ljc2NjU5IDcuMjU0OTQgOS43NDE1NSA3LjI0NjAyTDkuNzQwNTcgNy4yNDUwNEw5LjY5NzYxIDcuMjMwMzlIOS42OTY2M0M5LjQ0Mjk5IDcuMTQ1MzYgOS4xNzU5MSA3LjEwMDEzIDguOTA2NTkgNy4wOTg1Nkw4LjY3MDI2IDcuMDk3NThWNy4xMTIyM0M3Ljg5ODc3IDcuMTg0NSA3LjE2ODU0IDcuNjEwNiA2Ljc1MTMyIDguMzIzMTdMNi43NDY0MyA4LjMzMjkzTDMuMDM4NDMgMTYuMjg1MUwzLjAyNDc1IDE2LjMwOTVIMy4wMjM3OEMyLjk3NDYgMTYuMzk2OCAyLjkzMjIgMTYuNDg2NSAyLjg5NDg3IDE2LjU3NzFMMi43NjEwOCAxNi45MDAzSDUuMTE0Nkw4LjU3MDY1IDkuMzUyNDZDOC42NTM4MyA5LjIxMjg0IDguNzI1MDEgOS4xNDYzOSA4Ljc3NTczIDkuMTE3MTFDOC44MTgzOCA5LjA5MjUzIDguODU0MiA5LjA4ODggOC44OTk3NSA5LjEwMjQ2QzguOTU1MTggOS4xMTkxNiA5LjAzMTU3IDkuMTY0MDIgOS4xMjcyOSA5LjI1NTc4QzkuMjIxMyA5LjM0NTkzIDkuMzIxODIgOS40NzAwNSA5LjQzMDAzIDkuNjIzOTVDOS42NDY5OCA5LjkzMjUyIDkuODc1MTcgMTAuMzM3NSAxMC4xMTU2IDEwLjc4MjFDMTAuMTY5NCAxMC44ODE3IDEwLjIyMzcgMTAuOTgzMyAxMC4yNzg3IDExLjA4NTlDMTAuNDQ4OSAxMS40MDMyIDEwLjYyNDggMTEuNzMwNSAxMC44MDMxIDEyLjA0TDkuMjMzNzQgMTYuMjkzOUw5LjIyNDk1IDE2LjMwOTVWMTYuMzEwNUM5LjE3NTgzIDE2LjM5NzcgOS4xMzIzNiAxNi40ODY2IDkuMDk1MDcgMTYuNTc3MUw4Ljk2MTI4IDE2LjkwMDNIMTEuMzQ0MUwxMi4wMDAzIDE0LjUwODdMMTIuNjU1NiAxNi45MDAzSDE1LjAzODRMMTQuOTA0NiAxNi41NzcxQzE0Ljg2NDkgMTYuNDgwNyAxNC44MTkxIDE2LjM4NTUgMTQuNzY2IDE2LjI5MjlMMTMuMTk2NiAxMi4wNEMxMy4zNzQ4IDExLjczMDggMTMuNTUwNiAxMS40MDM1IDEzLjcyMSAxMS4wODU5QzEzLjc4MzQgMTAuOTY5NyAxMy44NDU4IDEwLjg1NDMgMTMuOTA2NiAxMC43NDIxQzE0LjE0NCAxMC4zMDM5IDE0LjM2ODMgOS45MDY2IDE0LjU4MjQgOS42MDUzOUMxNC42ODkyIDkuNDU1MTIgMTQuNzg4OCA5LjMzNTAyIDE0Ljg4MTIgOS4yNDc5N0MxNC45NzUyIDkuMTU5NDggMTUuMDQ5MiA5LjExNjg4IDE1LjEwMjkgOS4xMDE0OUMxNS4xNDY5IDkuMDg4ODkgMTUuMTgyOSA5LjA5MTkzIDE1LjIyNTkgOS4xMTcxMUMxNS4yNzY2IDkuMTQ2ODIgMTUuMzQ2NyA5LjIxNDI4IDE1LjQyOTEgOS4zNTI0NkwxOC44ODUxIDE2LjkwMDNIMjEuMjM4NkwyMS4xMDU4IDE2LjU3NzFDMjEuMDY0OCAxNi40Nzc2IDIxLjAxNjUgMTYuMzc5NSAyMC45NjEzIDE2LjI4NDFMMTcuMjUzMyA4LjMzMjkzTDE3LjI0ODQgOC4zMjMxN0MxNi44MzExIDcuNjEwNTkgMTYuMTAxIDcuMTg0NDIgMTUuMzI5NCA3LjExMjIzVjcuMDk3NThMMTUuMDk0MSA3LjA5ODU2WiIgZmlsbD0id2hpdGUiLz4KPC9zdmc+Cg==&labelColor=blue&color=green)](https://www.mcpnow.io/en/server/Vfyos2hSuh)

<div>
    <a target='_blank'>Wenxuan Zhang <sup>*,1,2</sup> </a>&emsp;
    <a href='https://vinthony.github.io/' target='_blank'>Xiaodong Cun <sup>*,2</a>&emsp;
    <a href='https://xuanwangvc.github.io/' target='_blank'>Xuan Wang <sup>3</sup></a>&emsp;
    <a href='https://yzhang2016.github.io/' target='_blank'>Yong Zhang <sup>2</sup></a>&emsp;
    <a href='https://xishen0220.github.io/' target='_blank'>Xi Shen <sup>2</sup></a>&emsp; </br>
    <a href='https://yuguo-xjtu.github.io/' target='_blank'>Yu Guo<sup>1</sup> </a>&emsp;
    <a href='https://scholar.google.com/citations?hl=zh-CN&user=4oXBp9UAAAAJ' target='_blank'>Ying Shan <sup>2</sup> </a>&emsp;
    <a target='_blank'>Fei Wang <sup>1</sup> </a>&emsp;
</div>
<br>
<div>
    <sup>1</sup> Xi'an Jiaotong University &emsp; <sup>2</sup> Tencent AI Lab &emsp; <sup>3</sup> Ant Group &emsp; 
</div>
<br>
<i><strong><a href='https://arxiv.org/abs/2211.12194' target='_blank'>CVPR 2023</a></strong></i>
<br>
<br>


![sadtalker](https://user-images.githubusercontent.com/4397546/222490039-b1f6156b-bf00-405b-9fda-0c9a9156f991.gif)

<b>TL;DR: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; single portrait image 🙎‍♂️  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; audio 🎤  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; =  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; talking head video 🎞.</b>

<br>

</div>



## Highlights

- The license has been updated to Apache 2.0, and we've removed the non-commercial restriction
- **SadTalker has now officially been integrated into Discord, where you can use it for free by sending files. You can also generate high-quailty videos from text prompts. Join: [![Discord](https://dcbadge.vercel.app/api/server/rrayYqZ4tf?style=flat)](https://discord.gg/rrayYqZ4tf)**

- We've published a [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) extension. Check out more details [here](docs/webui_extension.md). [Demo Video](https://user-images.githubusercontent.com/4397546/231495639-5d4bb925-ea64-4a36-a519-6389917dac29.mp4)

- Full image mode is now available! [More details...](https://github.com/OpenTalker/SadTalker#full-bodyimage-generation)

| still+enhancer in v0.0.1                 | still + enhancer   in v0.0.2       |   [input image @bagbag1815](https://twitter.com/bagbag1815/status/1642754319094108161) |
|:--------------------: |:--------------------: | :----: |
| <video  src="https://user-images.githubusercontent.com/48216707/229484996-5d7be64f-2553-4c9e-a452-c5cf0b8ebafe.mp4" type="video/mp4"> </video> | <video  src="https://user-images.githubusercontent.com/4397546/230717873-355b7bf3-d3de-49f9-a439-9220e623fce7.mp4" type="video/mp4"> </video>  | <img src='./examples/source_image/full_body_2.png' width='380'> 

- Several new modes (Still, reference, and resize modes) are now available!

- We're happy to see more community demos on [bilibili](https://search.bilibili.com/all?keyword=sadtalker), [YouTube](https://www.youtube.com/results?search_query=sadtalker) and [X (#sadtalker)](https://twitter.com/search?q=%23sadtalker&src).

## Changelog 

The previous changelog can be found [here](docs/changlelog.md).

- __[2023.06.12]__: Added more new features in WebUI extension, see the discussion [here](https://github.com/OpenTalker/SadTalker/discussions/386).

- __[2023.06.05]__: Released a new 512x512px (beta) face model. Fixed some bugs and improve the performance.

- __[2023.04.15]__: Added a WebUI Colab notebook by [@camenduru](https://github.com/camenduru/): [![sd webui-colab](https://img.shields.io/badge/Automatic1111-Colab-green)](https://colab.research.google.com/github/camenduru/stable-diffusion-webui-colab/blob/main/video/stable/stable_diffusion_1_5_video_webui_colab.ipynb)

- __[2023.04.12]__: Added a more detailed WebUI installation document and fixed a problem when reinstalling.

- __[2023.04.12]__: Fixed the WebUI safe issues becasue of 3rd-party packages, and optimized the output path in `sd-webui-extension`.

- __[2023.04.08]__: In v0.0.2, we added a logo watermark to the generated video to prevent abuse. _This watermark has since been removed in a later release._

- __[2023.04.08]__: In v0.0.2, we added features for full image animation and a link to download checkpoints from Baidu. We also optimized the enhancer logic.

## To-Do

We're tracking new updates in [issue #280](https://github.com/OpenTalker/SadTalker/issues/280).

## Troubleshooting

If you have any problems, please read our [FAQs](docs/FAQ.md) before opening an issue.



## 1. Installation.

Community tutorials: [中文Windows教程 (Chinese Windows tutorial)](https://www.bilibili.com/video/BV1Dc411W7V6/) | [日本語コース (Japanese tutorial)](https://br-d.fanbox.cc/posts/5685086).

### Linux/Unix

1. Install [Anaconda](https://www.anaconda.com/), Python and `git`.

2. Creating the env and install the requirements.
  ```bash
  git clone https://github.com/OpenTalker/SadTalker.git

  cd SadTalker 

  conda create -n sadtalker python=3.8

  conda activate sadtalker

  pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113

  conda install ffmpeg

  pip install -r requirements.txt

  ### Coqui TTS is optional for gradio demo. 
  ### pip install TTS

  ```  
### Windows

A video tutorial in chinese is available [here](https://www.bilibili.com/video/BV1Dc411W7V6/). You can also follow the following instructions:

1. Install [Python 3.8](https://www.python.org/downloads/windows/) and check "Add Python to PATH".
2. Install [git](https://git-scm.com/download/win) manually or using [Scoop](https://scoop.sh/): `scoop install git`.
3. Install `ffmpeg`, following [this tutorial](https://www.wikihow.com/Install-FFmpeg-on-Windows) or using [scoop](https://scoop.sh/): `scoop install ffmpeg`.
4. Download the SadTalker repository by running `git clone https://github.com/Winfredy/SadTalker.git`.
5. Download the checkpoints and gfpgan models in the [downloads section](#2-download-models).
6. Run `start.bat` from Windows Explorer as normal, non-administrator, user, and a Gradio-powered WebUI demo will be started.

### macOS

A tutorial on installing SadTalker on macOS can be found [here](docs/install.md).

### Docker, WSL, etc

Please check out additional tutorials [here](docs/install.md).

## 2. Download Models

You can run the following script on Linux/macOS to automatically download all the models:

```bash
bash scripts/download_models.sh
```

We also provide an offline patch (`gfpgan/`), so no model will be downloaded when generating.

### Pre-Trained Models

* [Google Drive](https://drive.google.com/file/d/1gwWh45pF7aelNP_P78uDJL8Sycep-K7j/view?usp=sharing)
* [GitHub Releases](https://github.com/OpenTalker/SadTalker/releases)
* [Baidu (百度云盘)](https://pan.baidu.com/s/1kb1BCPaLOWX1JJb9Czbn6w?pwd=sadt) (Password: `sadt`)

<!-- TODO add Hugging Face links -->

### GFPGAN Offline Patch

* [Google Drive](https://drive.google.com/file/d/19AIBsmfcHW6BRJmeqSFlG5fL445Xmsyi?usp=sharing)
* [GitHub Releases](https://github.com/OpenTalker/SadTalker/releases)
* [Baidu (百度云盘)](https://pan.baidu.com/s/1P4fRgk9gaSutZnn8YW034Q?pwd=sadt) (Password: `sadt`)

<!-- TODO add Hugging Face links -->


<details><summary>Model Details</summary>


Model explains:

##### New version 
| Model | Description
| :--- | :----------
|checkpoints/mapping_00229-model.pth.tar | Pre-trained MappingNet in Sadtalker.
|checkpoints/mapping_00109-model.pth.tar | Pre-trained MappingNet in Sadtalker.
|checkpoints/SadTalker_V0.0.2_256.safetensors | packaged sadtalker checkpoints of old version, 256 face render).
|checkpoints/SadTalker_V0.0.2_512.safetensors | packaged sadtalker checkpoints of old version, 512 face render).
|gfpgan/weights | Face detection and enhanced models used in `facexlib` and `gfpgan`.
  
  
##### Old version
| Model | Description
| :--- | :----------
|checkpoints/auido2exp_00300-model.pth | Pre-trained ExpNet in Sadtalker.
|checkpoints/auido2pose_00140-model.pth | Pre-trained PoseVAE in Sadtalker.
|checkpoints/mapping_00229-model.pth.tar | Pre-trained MappingNet in Sadtalker.
|checkpoints/mapping_00109-model.pth.tar | Pre-trained MappingNet in Sadtalker.
|checkpoints/facevid2vid_00189-model.pth.tar | Pre-trained face-vid2vid model from [the reappearance of face-vid2vid](https://github.com/zhanglonghao1992/One-Shot_Free-View_Neural_Talking_Head_Synthesis).
|checkpoints/epoch_20.pth | Pre-trained 3DMM extractor in [Deep3DFaceReconstruction](https://github.com/microsoft/Deep3DFaceReconstruction).
|checkpoints/wav2lip.pth | Highly accurate lip-sync model in [Wav2lip](https://github.com/Rudrabha/Wav2Lip).
|checkpoints/shape_predictor_68_face_landmarks.dat | Face landmark model used in [dilb](http://dlib.net/). 
|checkpoints/BFM | 3DMM library file.  
|checkpoints/hub | Face detection models used in [face alignment](https://github.com/1adrianb/face-alignment).
|gfpgan/weights | Face detection and enhanced models used in `facexlib` and `gfpgan`.

The final folder will be shown as:

<img width="331" alt="image" src="https://user-images.githubusercontent.com/4397546/232511411-4ca75cbf-a434-48c5-9ae0-9009e8316484.png">


</details>

## 3. Quick Start

Please read our document on [best practices and configuration tips](docs/best_practice.md)

### WebUI Demos

**Online Demo**: [HuggingFace](https://huggingface.co/spaces/vinthony/SadTalker) | [SDWebUI-Colab](https://colab.research.google.com/github/camenduru/stable-diffusion-webui-colab/blob/main/video/stable/stable_diffusion_1_5_video_webui_colab.ipynb) | [Colab](https://colab.research.google.com/github/Winfredy/SadTalker/blob/main/quick_demo.ipynb)

**Local WebUI extension**: Please refer to [WebUI docs](docs/webui_extension.md).

**Local gradio demo (recommanded)**: A Gradio instance similar to our [Hugging Face demo](https://huggingface.co/spaces/vinthony/SadTalker) can be run locally:

```bash
## you need manually install TTS(https://github.com/coqui-ai/TTS) via `pip install tts` in advanced.
python app_sadtalker.py
```

You can also start it more easily:

- windows: just double click `webui.bat`, the requirements will be installed automatically.
- Linux/Mac OS: run `bash webui.sh` to start the webui.


### CLI usage

##### Animating a portrait image from default config:
```bash
python inference.py --driven_audio <audio.wav> \
                    --source_image <video.mp4 or picture.png> \
                    --enhancer gfpgan 
```
The results will be saved in `results/$SOME_TIMESTAMP/*.mp4`.

##### Full body/image Generation:

Using `--still` to generate a natural full body video. You can add `enhancer` to improve the quality of the generated video. 

```bash
python inference.py --driven_audio <audio.wav> \
                    --source_image <video.mp4 or picture.png> \
                    --result_dir <a file to store results> \
                    --still \
                    --preprocess full \
                    --enhancer gfpgan 
```

More examples and configuration and tips can be founded in the [ >>> best practice documents <<<](docs/best_practice.md).

## Citation

If you find our work useful in your research, please consider citing:

```bibtex
@article{zhang2022sadtalker,
  title={SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation},
  author={Zhang, Wenxuan and Cun, Xiaodong and Wang, Xuan and Zhang, Yong and Shen, Xi and Guo, Yu and Shan, Ying and Wang, Fei},
  journal={arXiv preprint arXiv:2211.12194},
  year={2022}
}
```

## Acknowledgements

Facerender code borrows heavily from [zhanglonghao's reproduction of face-vid2vid](https://github.com/zhanglonghao1992/One-Shot_Free-View_Neural_Talking_Head_Synthesis) and [PIRender](https://github.com/RenYurui/PIRender). We thank the authors for sharing their wonderful code. In training process, we also used the model from [Deep3DFaceReconstruction](https://github.com/microsoft/Deep3DFaceReconstruction) and [Wav2lip](https://github.com/Rudrabha/Wav2Lip). We thank for their wonderful work.

We also use the following 3rd-party libraries:

- **Face Utils**: https://github.com/xinntao/facexlib
- **Face Enhancement**: https://github.com/TencentARC/GFPGAN
- **Image/Video Enhancement**:https://github.com/xinntao/Real-ESRGAN

## Extensions:

- [SadTalker-Video-Lip-Sync](https://github.com/Zz-ww/SadTalker-Video-Lip-Sync) from [@Zz-ww](https://github.com/Zz-ww): SadTalker for Video Lip Editing

## Related Works
- [StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pre-trained StyleGAN (ECCV 2022)](https://github.com/FeiiYin/StyleHEAT)
- [CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior (CVPR 2023)](https://github.com/Doubiiu/CodeTalker)
- [VideoReTalking: Audio-based Lip Synchronization for Talking Head Video Editing In the Wild (SIGGRAPH Asia 2022)](https://github.com/vinthony/video-retalking)
- [DPE: Disentanglement of Pose and Expression for General Video Portrait Editing (CVPR 2023)](https://github.com/Carlyx/DPE)
- [3D GAN Inversion with Facial Symmetry Prior (CVPR 2023)](https://github.com/FeiiYin/SPI/)
- [T2M-GPT: Generating Human Motion from Textual Descriptions with Discrete Representations (CVPR 2023)](https://github.com/Mael-zys/T2M-GPT)

## Disclaimer

This is not an official product of Tencent. 

```
1. Please carefully read and comply with the open-source license applicable to this code before using it. 
2. Please carefully read and comply with the intellectual property declaration applicable to this code before using it.
3. This open-source code runs completely offline and does not collect any personal information or other data. If you use this code to provide services to end-users and collect related data, please take necessary compliance measures according to applicable laws and regulations (such as publishing privacy policies, adopting necessary data security strategies, etc.). If the collected data involves personal information, user consent must be obtained (if applicable). Any legal liabilities arising from this are unrelated to Tencent.
4. Without Tencent's written permission, you are not authorized to use the names or logos legally owned by Tencent, such as "Tencent." Otherwise, you may be liable for legal responsibilities.
5. This open-source code does not have the ability to directly provide services to end-users. If you need to use this code for further model training or demos, as part of your product to provide services to end-users, or for similar use, please comply with applicable laws and regulations for your product or service. Any legal liabilities arising from this are unrelated to Tencent.
6. It is prohibited to use this open-source code for activities that harm the legitimate rights and interests of others (including but not limited to fraud, deception, infringement of others' portrait rights, reputation rights, etc.), or other behaviors that violate applicable laws and regulations or go against social ethics and good customs (including providing incorrect or false information, spreading pornographic, terrorist, and violent information, etc.). Otherwise, you may be liable for legal responsibilities.
```

LOGO: color and font suggestion: [ChatGPT](https://chat.openai.com), logo font: [Montserrat Alternates
](https://fonts.google.com/specimen/Montserrat+Alternates?preview.text=SadTalker&preview.text_type=custom&query=mont).

All the copyrights of the demo images and audio are from community users or the generation from stable diffusion. Feel free to contact us if you would like use to remove them.


<!-- Spelling fixed on Tuesday, September 12, 2023 by @fakerybakery (https://github.com/fakerybakery). These changes are licensed under the Apache 2.0 license. -->

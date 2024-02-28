# RZV2H DRP-AI Enironment

This Development Environment Uses the Docker Containers for DRP-AI Translator and DRP-AI Expansion pack. The Development environment uses the VSCode Dev Containers to create multi-container development environment. 

If the DRP-AI Dockers Images listed below are not listed `` docker images `` , follow the Installations below.

- drpai_ext_pt_img
- v2h/drp-ai

#### Install Extension Pack 

##### Requirements

Download, extract, and copy the DRP-AI Extension Pack to this environment

- drpai-extension-pack_ver*.tar.gz .

```bash
# Build docker image.
# It may take up to an hour to complete.
docker build -t drpai_ext_pt_img -f Dockerfile_DRP-AI_ExtPk .
```

### Install RZV2H DRP-AI Translator

##### Requirements

Download, extract, and copy the RZV2H DRP-AI Translator to this environment

- DRP-AI_Translator_i8-v*-Linux-x86_64-Install

```bash
# Build docker image.
cd <RZ/V2H AI IMPLEMENTATION GUIDE>/setup
docker build -f Dockerfile_DRP-AI_Translator -t v2h/drp-ai:v1.0 ../
```


3

# 샘플이미지

<img src="./comfyui_custompose/image1.jpg" width="480"/>
<img src="./comfyui_custompose/image2.jpg" width="480"/>
<img src="./comfyui_custompose/image3.jpg" width="480"/>
<img src="./comfyui_custompose/image4.jpg" width="480"/>
<img src="./comfyui_custompose/image5.jpg" width="480"/>
<img src="./comfyui_custompose/image6.jpg" width="480"/>
<img src="./comfyui_custompose/image7.jpg" width="480"/>
<img src="./comfyui_custompose/image8.jpg" width="480"/>
<img src="./comfyui_custompose/image9.jpg" width="480"/>
<img src="./comfyui_custompose/image10.jpg" width="480"/>
<img src="./comfyui_custompose/image11.jpg" width="480"/>
<img src="./comfyui_custompose/image12.jpg" width="480"/>
<img src="./comfyui_custompose/image13.jpg" width="480"/>


# 워크플로우

(마우스 오른쪽버튼을 누르고 링크 저장을 눌러주세요)

<https://raw.githubusercontent.com/ninjaneural/webui/master/memo/comfyui_custompose/workflow1.json>

<https://raw.githubusercontent.com/ninjaneural/webui/master/memo/comfyui_custompose/workflow2.json>

---

**IPAdapter Plus 2024-03-26 이후 버전 워크플로우**

<https://raw.githubusercontent.com/ninjaneural/webui/master/memo/comfyui_custompose/20240326/workflow1.json>

<https://raw.githubusercontent.com/ninjaneural/webui/master/memo/comfyui_custompose/20240326/workflow2.json>

*통합버전 (새로워진 IPAdapter Plus 방식)*

> 모든 파일명을 맞췄을경우 하나의 노드로 통합가능해요    

<https://raw.githubusercontent.com/ninjaneural/webui/master/memo/comfyui_custompose/20240326/workflow.json>

(마우스 오른쪽버튼을 누르고 링크 저장을 눌러주세요)


# IPAdapter_plus

* 커스텀노드 ComfyUI_IPAdapter_plus

<https://github.com/cubiq/ComfyUI_IPAdapter_plus>

* faceid-plus-v2 모델 다운로드

<https://huggingface.co/h94/IP-Adapter-FaceID/resolve/main/ip-adapter-faceid-plusv2_sd15.bin>

> [v1 legecy] <strike>ComfyUI 설치폴더/custom_nodes/ComfyUI_IPAdapter_plus/models 이곳에 복사</strike>  
> [2024-03-26 v2 적용] ComfyUI 설치폴더/models/ipadapter 이곳에 복사 (폴더 없으면 생성)

* faceid-plus-v2 로라 다운로드

<https://huggingface.co/h94/IP-Adapter-FaceID/resolve/main/ip-adapter-faceid-plusv2_sd15_lora.safetensors>

> [v1 legecy] <strike>ComfyUI 설치폴더/models/loras 이곳에 복사</strike>  
> [2024-03-26 v2 적용] ComfyUI 설치폴더/models/ipadapter 이곳에 복사 (폴더 없으면 생성)

* clip vision 모델 (CLIP-ViT-H-14-laion2B-s32B-b79K) 다운로드

<https://huggingface.co/h94/IP-Adapter/resolve/main/models/image_encoder/model.safetensors>

> 설치폴더/models/clip_vision 이곳에 복사  
> 파일명을 CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors 으로 변경해주세요


# 페이스ID, 페이스스왑 

<https://youtu.be/iCtyKP6sYNU>

<https://github.com/ninjaneural/webui/blob/master/memo/comfyui_faceswap.md>


# 커스텀노드

<https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes>

<https://github.com/pythongosssss/ComfyUI-WD14-Tagger>

<https://github.com/Fannovel16/comfyui_controlnet_aux>



# 프롬프트


긍정 프롬프트들
```
masterpiece, best quality,8k uhd, ultra realistic,realistic, photorealistic, RAW,
```

부정 프롬프트
```
(worst quality,low quality,normal quality:1.2),nsfw, nude
```

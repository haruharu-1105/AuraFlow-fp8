# AuraFlow-fp8
## 🚀 使い方
### ComfyUIのワークフロー
https://huggingface.co/fal/AuraFlow-v0.3/blob/main/comfy_workflow.json

### Google Colabで実行  
Googleドライブに変換後のモデルファイルを保存します。  

<a href="https://colab.research.google.com/github/haruharu-1105/AuraFlow-fp8/blob/main/to_fp8_e4m3.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>をクリックして、簡単に実行できます。  

--- 
以下からは、作業中の情報です。  
## モデルアーキテクチャ  
[auraflow_v0.3_architecture.md](https://github.com/haruharu-1105/AuraFlow-fp8/blob/main/auraflow_v0.3_architecture.md)  
- テキストエンコーダー：T5  
- FLOW
  - ダブルレイヤー：4  
  - シングルレイヤー：32  
- VAE：4ch  

## 公式資料
### パイプライン
https://github.com/huggingface/diffusers/blob/14f6464bef677e47e1ff13a12f4ddd97e7f3e973/src/diffusers/pipelines/aura_flow/pipeline_aura_flow.py#L128

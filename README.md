# AI Video Tools & Models

We build ComfyUI tools, custom AI models, and practical workflows for cinematic AI production.

---

### [MiniMax H3 Upscaler](https://github.com/SOLRICKS/comfyui-solricks)

Video upscaling and detail refinement for ComfyUI, with temporal chunking, spatial tiling, and the experimental SOLRICKS INT8 refiner.

<table>
  <thead>
    <tr><th>Before — 1376×768</th><th>After — MiniMax H3 Upscaler · 1952×1088</th></tr>
  </thead>
  <tbody>
    <tr>
      <td width="50%"><video controls playsinline preload="metadata" width="100%" src="https://github.com/user-attachments/assets/5177d194-77af-4bbd-99d4-5f116a9997e7"></video></td>
      <td width="50%"><video controls playsinline preload="metadata" width="100%" src="https://github.com/user-attachments/assets/2ddd1845-8f32-461d-9363-934b31840b66"></video></td>
    </tr>
    <tr>
      <td align="center"><a href="https://huggingface.co/SOLRICKS/MiniMax-H3-Upscaler/resolve/main/Minimax_H3_I2V.mp4">Open original video</a></td>
      <td align="center"><a href="https://huggingface.co/SOLRICKS/MiniMax-H3-Upscaler/resolve/main/Minimax-H3-Upscaler.mp4">Open upscaled video</a></td>
    </tr>
  </tbody>
</table>

*AI-generated source and upscaled output. Both clips: 243 frames, 24 FPS, 10.125 seconds. Web previews are compressed for GitHub playback. The links above open the full-quality MP4 files on Hugging Face.*

[Node and documentation](https://github.com/SOLRICKS/comfyui-solricks) · [Hugging Face models and workflows](https://huggingface.co/SOLRICKS/MiniMax-H3-Upscaler)

---

### 🚀 Custom Nodes

#### [ComfyUI Video Anti-Aliasing Pack](https://github.com/SOLRICKS/comfyui-solricks)

ComfyUI nodes for video anti-aliasing, temporal stabilization, detail refinement, and cinematic effects.

### LoRA Models

Selected LoRA models for AI video and image production.

<table>
  <tbody>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/3D-Animation-Style-MiniMax-H3/blob/main/minimax_h3_fl2v_turbo_8step_v1.0_comfyui_fp8.safetensors">MiniMax H3 Turbo 8-Step — FP8</a></td>
      <td>FP8-converted 8-step Turbo LoRA for FLF2V generation and experimental Ref2V use.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/3D-Animation-Style-MiniMax-H3">3D Animation Style — MiniMax H3</a></td>
      <td>Stylized 3D animation for T2V and I2V.</td>
    </tr>
    <tr>
      <td><a href="https://civitai.com/models/2941912/bts-movie-set">BTS Movie Set — MiniMax H3</a></td>
      <td>Film sets, production equipment, and behind-the-scenes visuals.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/ltx-2.3-product-ad-style">Product Ad Style — LTX-2.3</a></td>
      <td>Cinematic product advertising and studio visuals.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/ltx-2.3-sci-fi-cinema">Sci-Fi Cinema — LTX-2.3</a></td>
      <td>Futuristic cities, spacecraft, and cinematic sci-fi scenes.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/klein-9b-imperial-historical-style">Imperial Historical Style — FLUX.2 Klein 9B</a></td>
      <td>Historical scenes, palaces, bazaars, and imperial architecture.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/Klein-9B-SRX-Foundation">SRX Foundation — FLUX.2 Klein 9B</a></td>
      <td>Character portraits, cinematic lighting, and stylized realism.</td>
    </tr>
  </tbody>
</table>

### Workflows

<table>
  <tbody>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/3D-Animation-Style-MiniMax-H3/blob/main/MiniMax_H3_FLF_V2.json">MiniMax H3 FLF — V2</a></td>
      <td>FLF workflow for MiniMax H3.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/3D-Animation-Style-MiniMax-H3/blob/main/MiniMax_H3_R2V_ControlNet_V2.json">MiniMax H3 R2V ControlNet — V2</a></td>
      <td>R2V ControlNet workflow for MiniMax H3.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/LTX-2-5-ComfyUI-Workflows/blob/main/LTX-2.5_T2V_I2V_Audio-Dev.json">LTX-2.5 T2V / I2V + Audio — Dev</a></td>
      <td>Dev workflow for T2V and I2V generation with audio.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/LTX-2-5-ComfyUI-Workflows/blob/main/LTX-2.5-V2V-Upscaler.json">LTX-2.5 V2V Upscaler</a></td>
      <td>V2V upscaling and refinement.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/LTX-2-5-ComfyUI-Workflows/blob/main/LTX-2.5-ICLoRA-Ingredients-Two-Stage-V2.json">LTX-2.5 Ingredients — Two-Stage V2</a></td>
      <td>Two-stage Ingredients workflow.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/LTX-2-5-ComfyUI-Workflows/blob/main/LTX-2.5-ReTake-Green-Screen-Composite-V2.json">LTX-2.5 ReTake — Green Screen Composite V2</a></td>
      <td>ReTake workflow for green-screen compositing.</td>
    </tr>
  </tbody>
</table>

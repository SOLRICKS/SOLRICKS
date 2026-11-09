# AI Tools & Models

We build ComfyUI tools, custom AI models, and practical workflows for cinematic AI production.

---

### 🚀 Custom Nodes

#### [MiniMax H3 Upscaler](https://github.com/SOLRICKS/comfyui-solricks)

A ComfyUI node for video upscaling and detail refinement, with temporal chunking, spatial tiling, and the INT8 refiner.

---

#### [Video Anti-Aliasing](https://github.com/SOLRICKS/comfyui-solricks)

A ComfyUI node for video anti-aliasing, temporal stabilization, detail refinement, and cinematic effects.

---

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
      <td><a href="https://huggingface.co/SOLRICKS/3D-Animation-Style-MiniMax-H3/tree/main/SOLRICKS_MiniMaxH3_Workflows_T2V_I2V_FLF_Ref2V_V3_AllWorkflows">MiniMax H3 Workflows</a></td>
      <td>ComfyUI workflows for MiniMax H3, covering text-to-video, image-to-video, first/last-frame animation, and reference-guided video generation. Includes audio-enabled generation, ControlNet workflows for guided motion and creative control, and video upscaling for higher-resolution output and detail refinement.</td>
    </tr>
    <tr>
      <td><a href="https://huggingface.co/SOLRICKS/LTX-2-5-ComfyUI-Workflows/tree/main">LTX-2.5 Workflows</a></td>
      <td>ComfyUI workflows for LTX-2.5 text-to-video and image-to-video generation with audio support. Features a simplified main control node, two-stage generation and refinement, and flexible settings for custom audio, duration, resolution, frame rate, and prompt enhancement.</td>
    </tr>
  </tbody>
</table>

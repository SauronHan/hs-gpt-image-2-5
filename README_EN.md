# hs-gpt-image-2-5

> **English** | [中文](README.md)

**OpenAI GPT-Image-2.5 Industrial Image Generation & Surgical Inpainting Compiler (Agent Skill)**

Tailor-made for cinematic storyboarding, character concept lookdev, and photorealistic asset generation. Natively optimized for OpenAI's latest **GPT-Image-2.5** foundation model, it enforces **multi-reference feature decoupling**, **structured surgical editing (one change at a time with exhaustive retention)**, **authentic chiaroscuro lighting and physical textures**, and **standardized industrial task cards**.

---

## 🌟 Key Features

- **Native GPT-Image-2.5 Adaptation**: Harnesses the 2.5-generation capabilities in facial biometric identity preservation, physical material accuracy, and hyper-precise instruction following.
- **Three Multimodal Generation Modes**:
  - **Text-to-Image (`GENERATE`)**: Employs anamorphic optical parameters (focal length, depth of field, framing), chiaroscuro contrast, and concrete material descriptors.
  - **Multi-Reference Decoupling (`MULTI-REFERENCE GENERATE`)**: Isolates facial bone structure, wardrobe style, and environmental sketches, preventing cross-attribute contamination.
  - **Surgical Inpainting (`EDIT`)**: Strictly executes "single-variable modification" and "exhaustive preservation", performing millimeter-precision micro-adjustments without altering unselected regions.
- **Biometric Identity Lock Protocol**: Produces formal full-body lookdev master assets (neutral light-grey studio backdrop, 9:16 vertical ratio, **empty relaxed hands hanging naturally**, visible head-to-toe).
- **Zero-Dependency & Self-Contained**: Pure prompt compiler that operates out-of-the-box in any agent environment.

---

## 🛠️ Prerequisites

This skill is a pure **Prompt Engineering & Operation Card Compilation Engine**:
- **Zero Local Environment Setup**: No Python libraries, no GPUs, and no API keys required locally.
- **Plug-and-Play**: Compatible with Claude Desktop, Antigravity, Cursor, and standard LLM agent frameworks.
- **Universal Deliverables**: Formats prompts ready for ChatGPT Web, OpenAI API endpoints, or third-party image generation frontends.

---

## 🚀 Installation & Usage

### Installation
Clone or copy this directory into your AI Agent's skills directory:

```bash
git clone https://github.com/your-username/hs-gpt-image-2-5.git
```

### Prompting Examples
Instruct your Agent in plain language:
> *"Generate a cinematic sci-fi storyboard: An underground black-market cybernetic doctor in a rain-soaked neon basement, 35mm anamorphic lens, high-contrast chiaroscuro lighting, 16:9 task card."*  
> *"Using face master `face.png` and vintage leather jacket reference `jacket.png`, generate the protagonist leaning against a fighter jet at twilight."*  
> *"Surgical edit on `character.png`: Add a single fresh cut across the right eyebrow. Keep all other facial features, clothing, and background strictly identical."*

---

## 📂 Output Format & Examples

The Skill compiles a structured **Markdown Operation Card** containing input assets, parameters, and ready-to-use prompts:

```markdown
### Visual Asset Card: Character Full-Body Lookdev

- **Mode**: GENERATE (Full-Body Master)
- **Aspect Ratio**: 9:16 Vertical
- **Framing**: Full-body frontal standing pose, visible head-to-toe, empty hands.

#### 📋 Prompt:
[Photorealistic Full-Body Character Master Asset] [9:16 Vertical Aspect Ratio]
Subject: 32-year-old East Asian male risk analyst, 180cm, lean slender build, slight slouched posture.
Face & Bones: Narrow angular face, distinct jawline, subtle hollow cheeks, defined brow ridge.
Biometric Anchor: Distinct tiny dark mole directly below the right eye lower eyelid.
Skin Texture: Raw visible pores, subtle skin fatigue, zero airbrushing, strictly avoiding plastic skin.
Posture: Full-body frontal standing pose, head-to-toe visible with 10% safety margin. Arms hanging straight down naturally at sides with relaxed EMPTY hands. Absolutely no items held in hands.
Wardrobe: Faded dark charcoal grey zip-up hoodie over plain black crewneck t-shirt, dark grey straight cargo pants, worn black leather sneakers.
Optics & Studio: Seamless solid neutral light gray studio backdrop, flat diffused neutral softbox lighting, subtle ground contact shadow, 85mm prime portrait lens, 8k resolution.
```

---

## 📄 License

Private / MIT (See repository license).

<div align="center">

<img src="https://instara.s3.us-east-1.amazonaws.com/instaraw.svg" alt="INSTARAW Logo" width="240">

<br>
<br>
<br>

![Version](https://img.shields.io/badge/Version-2.0.0-gold.svg)
![Status](https://img.shields.io/badge/Status-VIP%20Access-blue.svg)

# Welcome to INSTARAW V2.0! 🎉

**Thank you for joining the INSTARAW VIP Program!**

You're now equipped with a powerful suite of custom nodes and workflows designed to create next-level AI influencer content.

Let's get you set up in minutes! ⚡

</div>

---

## ⚖️ IMPORTANT LEGAL NOTICE

**By using this software, you agree to the terms in LICENSE.txt.**

**YOU ARE RESPONSIBLE FOR:**
- ✅ Obtaining consent from anyone whose likeness you use
- ✅ Complying with all applicable laws in your jurisdiction
- ✅ Ensuring your content doesn't violate platform terms of service
- ✅ Using this software ethically and legally

**PROHIBITED USES:**
- ❌ Non-consensual deepfakes or manipulated content
- ❌ Illegal content or activities
- ❌ Content involving minors
- ❌ Deceptive, fraudulent, or harmful content
- ❌ Violations of others' rights (privacy, publicity, copyright, etc.)

**Read the full LICENSE.txt file before using this software. You indemnify the licensor for any misuse.**

---

## 🎬 Video Walkthroughs

Learn how to use INSTARAW workflows with our YouTube tutorials:

| Workflow | Video Tutorial |
|----------|---------------|
| **WAN 2.2 V2.0** | [Watch Tutorial →](https://youtu.be/gDWbd_Kc8wM) |
| **SDXL + WAN Combo V2.0** | [Watch Tutorial →](https://youtu.be/VYKFHH5xMWg) |
| **Detailing V2.0** | [Watch Tutorial →](https://youtu.be/hFhhgu41fh0) |
| **SDXL Inpainting V2.0** | [Watch Tutorial →](https://youtu.be/foriaSmbJ_I) |
| **Caption Generator V2.0** | [Watch Tutorial →](https://youtu.be/CIq3EehXWmc) |

*More tutorials coming soon!*

---

## 📋 Version History

<details>
<summary><b>Click to view changelog</b></summary>

<br>

### V2.0.0 (Current)
**Release Date:** December 2025

**Major New Features:**
- ✨ **AIL Node** - Advanced Image Loader with interactive batch management
- ✨ **RPG Node** - Reality Prompt Generator with AI integration (Gemini/Grok) and ~8K prompts
- ✨ **BIG Node** - Batch Image Generator with parallel processing and 2X mode
- ✨ **Detection Bypass System** - Spectral Engine, Texture Engine, Pixel Perturb
- ✨ **Authenticity Layer** - Camera simulation, EXIF embedding, neural grain
- ✨ **WAN 2.2 Multi-Sampler** - 4-sampler T2I/I2I for hyper-realistic skin and lighting
- ✨ **Faceswap V2.0** - Close-to-face cropping for NSFW + Nano Banana Pro expression control
- ✨ **Finalpass V2.0** - Tiling SeedVR2 for great upscaling results

**14 Production Workflows (All V2.0):**
- BIG V2.0
- Booba & Glutes V2.0
- Bypass AI Detection MAX V2.0
- Bypass AI Detection MIN V2.0
- Caption Generator V2.0
- Detailing V2.0
- Faceswap V2.0
- Finalpass V2.0
- SDXL Inpainting V2.0
- SDXL + WAN Combo NSFW V2.0
- SDXL + zImage Combo NSFW V2.0
- Teleport V2.0
- WAN 2.2 V2.0
- zImage V2.0

**Migration Notes:**
- Full replacement required from V1.x
- Must reinstall dependencies: `pip install -r requirements.txt`
- Use new V2.0 workflow files

---

### V1.0.2
**Release Date:** October 2025

**Changes:**
- 🐛 **Fixed:** Booba & Glutes workflow errors
- 🔄 **Updated:** Booba & Glutes workflow → V8

---

### V1.0.1
**Release Date:** October 2025

**Changes:**
- 🐛 **Fixed:** Gemini node dependency issues on some installations
- 🔄 **Updated:** Faceswap workflow → V12
- 🔄 **Updated:** Teleport workflow → V12
- 📄 **Added:** Comprehensive legal protections and usage guidelines

---

### V1.0
**Release Date:** October 2025

**Initial Release:**
- ✨ Complete custom nodes package for ComfyUI
- 🎨 4 production workflows: Faceswap, Teleport, Booba & Glutes, Finalpass
- 🔌 API integrations: Ideogram, fal.ai, wavespeed.ai, Google Gemini
- 🖼️ Interactive image filtering and selection nodes
- 🎭 Advanced masking with MediaPipe
- 🔧 Utility nodes for resolution control, image comparison, and more
- 📚 Complete documentation and setup guides

</details>

---

## 🔄 Update for Existing Users (V1.x → V2.0)

<details>
<summary><b>📋 Click here if you're updating from V1.x</b></summary>

<br>

### What's New in V2.0

V2.0 is a major release with significant new features:
- Three flagship interactive nodes (AIL, RPG, BIG)
- Detection bypass and authenticity system
- 14 new V2.0 workflows
- 45+ new utility nodes
- WAN 2.2 multi-sampler for hyper-realistic results
- zImage Turbo for fast local generation

### How to Update

**Full replacement required:**

1. **Backup your API keys** - Note them down from your current workflows
2. **Remove old nodes** - Delete `ComfyUI_INSTARAW` from `custom_nodes/`
3. **Install new nodes** - Copy the new `ComfyUI_INSTARAW` folder
4. **Reinstall dependencies**:
   ```bash
   cd ComfyUI/custom_nodes/ComfyUI_INSTARAW
   pip install -r requirements.txt
   ```
5. **Download new models** - Run the model downloader script (see Step 2 below)
6. **Restart ComfyUI** completely
7. **Use V2.0 workflows** - Old V1 workflows are not compatible

</details>

---

## 📦 What's in This Package?

This archive contains everything you need to start creating professional AI content:

<table>
<tr>
<td width="50%">

### 🔧 ComfyUI_INSTARAW/
The core custom nodes package:
- **AIL** - Advanced Image Loader
- **RPG** - Reality Prompt Generator (~8K prompts)
- **BIG** - Batch Image Generator (2X mode)
- 80+ utility nodes
- Detection bypass system
- API integrations

</td>
<td width="50%">

### 🎨 Workflows/ (14 Total)
Premium V2.0 workflow templates:
- **Faceswap V2.0** - Expression control
- **WAN 2.2 V2.0** - Multi-sampler T2I/I2I
- **zImage V2.0** - Fast local generation
- **Bypass AI Detection V2.0** - MAX/MIN
- **Finalpass V2.0** - SeedVR2 tiling
- And more...

</td>
</tr>
</table>

---

## 🚀 Quick Start Installation

Follow these steps to get up and running:

### Step 1️⃣ : Extract & Place Files

1. **Unzip this archive** to any location

2. **Place the folders** according to this structure:
   ```
   📁 Your ComfyUI Parent Folder/
   ├── 📁 ComfyUI/
   │   └── 📁 custom_nodes/
   │       └── 📁 ComfyUI_INSTARAW/  ← Copy here
   ├── 📁 downloader_scripts/        ← Place NEXT TO ComfyUI folder
   │   ├── 📁 linux/
   │   └── 📁 windows/
   └── 📁 Workflows/                 ← Place anywhere you like
   ```

   > ⚠️ **Important**: The `downloader_scripts/` folder must be placed **next to** (at the same level as) your `ComfyUI/` folder, NOT inside it. The scripts look for `ComfyUI/custom_nodes/` relative to where they run.

3. **Install Python dependencies**:

   Open a terminal/command prompt and navigate to your ComfyUI_INSTARAW folder:
   ```bash
   # Replace with your actual path
   cd /path/to/ComfyUI/custom_nodes/ComfyUI_INSTARAW
   pip install -r requirements.txt
   ```

   > 💡 **Tip**: Make sure you're using the same Python environment as ComfyUI

   > ⚠️ **Python Version**: INSTARAW works best with **Python 3.11**. Some Python 3.12 installations may work, but if you encounter MediaPipe installation errors on **Windows Portable**, see the [Python 3.11 Setup Guide](#-advanced-python-311-setup-for-comfyui-portable) below.

---

### Step 2️⃣ : Download Required Models

Use the automated model downloader script. **You must run this from the correct location.**

**Linux / macOS / Vast.ai:**
```bash
# Navigate to the downloader_scripts folder (next to ComfyUI folder)
cd /path/to/downloader_scripts/linux

# On Vast.ai, this is most likely:
# cd /workspace/downloader_scripts/linux

# Make executable and run
chmod +x INSTARAW_Download_Models.sh
./INSTARAW_Download_Models.sh
```

**Windows:**
```cmd
REM Navigate to the downloader_scripts folder (next to ComfyUI folder)
cd C:\path\to\downloader_scripts\windows

REM Run the script
INSTARAW_Download_Models.bat
```

> ⚠️ **Important**: Run the script from INSIDE the `downloader_scripts/linux/` or `downloader_scripts/windows/` folder. The script expects to find `ComfyUI/custom_nodes/` one level up from where it runs.

The script will:
1. Install required Python libraries (requests, tqdm)
2. Install exiftool (for metadata embedding)
3. Clone and set up comfyui_controlnet_aux
4. Install ComfyUI_INSTARAW dependencies
5. Download all required models from `INSTARAW_models_to_download.txt`
6. Extract any .zip files automatically
7. Restart ComfyUI (if supervisorctl available)

> 💡 **Tip**: You can customize `INSTARAW_models_to_download.txt` - comment out lines with `#` to skip specific models.

---

### Step 3️⃣ : Place Workflows

**You can place the `Workflows` folder anywhere you like:**
- Desktop (easy access)
- Inside your main ComfyUI folder
- A dedicated projects folder

> 📝 **Important**: The `fonts` folder inside `ComfyUI_INSTARAW` must stay where it is for preview nodes to work!

---

### Step 4️⃣ : Restart ComfyUI

**Completely shut down and restart ComfyUI** to load the new nodes.

You should now see nodes with the `INSTARAW` prefix in your node menu! 🎊

---

### Step 5️⃣ : Set Up API Keys

<table>
<tr>
<td width="30%">

#### 1. Load Workflow
Drag a `.json` file from the Workflows folder onto ComfyUI

</td>
<td width="30%">

#### 2. Find API Key nodes
Look for the green **"API Keys"** nodes in the workflow

</td>
<td width="30%">

#### 3. Add Keys
Paste your API keys into the corresponding nodes

</td>
</tr>
</table>

---

## 🔑 Getting API Keys

You'll need keys from these providers to use the workflows:

### Required Services

| Service | What It's For | Where to Get It |
|---------|---------------|-----------------|
| **fal.ai** 🎨 | Nano Banana Pro (Full mode), SeeDream, faceswaps | [Get Key →](https://fal.ai/dashboard/keys) |
| **wavespeed.ai** ⚡ | Nano Banana Pro (2X mode), image generation | [Get Key →](https://wavespeed.ai/accesskey) |
| **Google AI Studio** 🧠 | Gemini vision & prompts | [Get Key →](https://aistudio.google.com/app/apikey) |

### Optional Services

| Service | What It's For | Where to Get It |
|---------|---------------|-----------------|
| **ideogram.ai** ✍️ | Direct Ideogram access | [Get Key →](https://ideogram.ai/api/api-keys/) |
| **xAI** 🤖 | Grok API for RPG node | [Get Key →](https://console.x.ai/team/default/api-keys) |

> 💡 **Pro Tip**: Get both fal.ai and wavespeed.ai for full Nano Banana Pro support (Full + 2X modes).

---

## 💰 Understanding Costs

The workflows use a mix of premium APIs and local models:

### Approximate Costs

| Operation | Provider | Cost per Use |
|-----------|----------|--------------|
| Nano Banana Pro (Full) | fal.ai | ~$0.14 |
| Nano Banana Pro (2X Mode) | wavespeed.ai | ~$0.07 x 2 |
| Image Edit / Generation | fal.ai / wavespeed.ai | ~$0.03 |
| Face Swap | fal.ai / Ideogram | ~$0.10 |
| **SDXL** | **Local** | **Free** ⭐ |
| **WAN 2.2** | **Local** | **Free** ⭐ |
| **zImage** | **Local** | **Free** ⭐ |
| Gemini Vision/Prompts | Google | **Free tier** ⭐ |

### Cost-Saving Tips

- ✅ Use **SDXL**, **WAN 2.2**, and **zImage** workflows - they run locally for free!
- ✅ Use **Google's free tier** for prompts and vision
- ✅ Use **2X mode** in BIG for Nano Banana Pro ($0.07 x 2 instead of $0.14)
- ✅ Test workflows with lower-cost operations first

---

## ✨ The Three Flagship Nodes

### 🖼️ AIL - Advanced Image Loader

Interactive batch image management:
- **Drag-and-drop** multi-file upload
- **Thumbnail previews** with reordering
- **Per-image repeat control**
- **Batch tensor** or **sequential** mode
- **txt2img support** for text-only workflows

### 💭 RPG - Reality Prompt Generator

AI-powered prompt generation:
- **Native Gemini/Grok** API integration
- **~8K prompts database**
- **15+ expression presets** (Smiling, Sexy, Confident, etc.)
- **4 image reference slots**
- **INSTARAW Grille Mode** for hyper-realistic generation

### 🎨 BIG - Batch Image Generator

Parallel generation engine:
- **Unlimited concurrent workers**
- **Real-time progress UI**
- **Job state visualization** (Pending/Generating/Success/Failed)
- **PhotoSwipe gallery** integration
- **Multi-select export**
- **2X mode** for cost-effective Nano Banana Pro ($0.07 x 2)

---

## 🎓 Your First Workflow

Let's run your first INSTARAW workflow:

### Quick Test Run

1. **Open ComfyUI** and drag `INSTARAW BIG V2.0.json` onto the canvas
2. **Add your API keys** to the green API group (fal.ai for Nano Banana Pro)
3. **Configure your prompts** in the RPG node or add images to AIL
4. **Click "Queue Prompt"** and watch the magic happen! ✨

> 💡 **Why BIG?** The BIG workflow uses Nano Banana Pro API - it works on any hardware since generation happens in the cloud. Local workflows like WAN 2.2 require a powerful GPU (RTX 5090 recommended for WAN, RTX 4090+ for zImage/SDXL).

### What to Expect

- Workflows will pause at **Interactive Filter** nodes for your input
- Check the **console** for progress updates
- Results appear as they're generated
- BIG shows real-time progress with job states

---

## 🗂️ V2.0 Workflow Guide (14 Workflows)

### 🎨 INSTARAW BIG V2.0
**Perfect for**: Standalone batch generation with Nano Banana Pro

**Key Features**:
- Parallel processing (1-16 workers)
- 2X mode for cost savings
- Real-time progress UI

---

### 🎭 INSTARAW Faceswap V2.0
**Perfect for**: Character consistency, face replacement

**Key Features**:
- Close-to-face cropping for better NSFW support
- Expression control via Nano Banana Pro
- High-quality preservation

---

### 🖼️ INSTARAW WAN 2.2 V2.0
**Perfect for**: Hyper-realistic skin and lighting

**Key Features**:
- 4-sampler multi-pass T2I/I2I pipeline
- Local model (FREE!)
- Professional skin detail and lighting

> ⚠️ **GPU**: RTX 5090 recommended (heavy model)

---

### ⚡ INSTARAW zImage V2.0
**Perfect for**: Fast iteration and prototyping

**Key Features**:
- zImage Turbo local model (FREE!)
- Quick turnaround
- Batch processing support

> ⚠️ **GPU**: RTX 4090+ recommended

---

### 🛡️ INSTARAW Bypass AI Detection V2.0 (MAX/MIN)
**Perfect for**: Making AI images undetectable

**Key Features**:
- **MAX**: Full spectral/texture/pixel bypass
- **MIN**: Lightweight, fast processing
- EXIF metadata embedding

---

### ✨ INSTARAW Finalpass V2.0
**Perfect for**: Final polishing and quality improvements

**Key Features**:
- Tiling SeedVR2 upscaling
- Detail preservation
- Output optimization

---

### 💪 INSTARAW Booba & Glutes V2.0
**Perfect for**: Breast and butt enlargement

**Key Features**:
- Mask-based body modifications
- Natural-looking results
- Customizable intensity

---

### 🚁 INSTARAW Teleport V2.0
**Perfect for**: Background changes, setting variations

**Key Features**:
- Intelligent background replacement
- Style consistency
- Multiple generation options

---

### 🎨 INSTARAW SDXL + WAN Combo NSFW V2.0
**Perfect for**: SDXL generation with WAN face detailing

**Key Features**:
- WAN for face/character consistency
- SDXL for base generation
- Batch processing

> ⚠️ **GPU**: RTX 5090 recommended (uses WAN)

---

### ⚡ INSTARAW SDXL + zImage Combo NSFW V2.0
**Perfect for**: SDXL generation with zImage face detailing

**Key Features**:
- zImage for face/character consistency (FREE!)
- SDXL for base generation
- Quick turnaround

> ⚠️ **GPU**: RTX 4090+ recommended

---

### 🔍 INSTARAW Detailing V2.0
**Perfect for**: Face/hand/body enhancement

**Key Features**:
- YOLO-based detection
- Targeted inpainting
- Natural blending

---

### 🖌️ INSTARAW SDXL Inpainting V2.0
**Perfect for**: Intimate area inpainting (NSFW regions)

**Key Features**:
- Advanced mask tools
- SDXL quality
- Targeted region editing

---

### 📝 INSTARAW Caption Generator V2.0
**Perfect for**: AI-powered image captioning

**Key Features**:
- Gemini/Grok integration
- Detailed descriptions
- Batch processing

---

## 🔧 Advanced: Python 3.11 Setup for ComfyUI Portable

<details>
<summary><b>⚠️ Click here if you have Python 3.12+ or dependency installation issues</b></summary>

<br>

### Why Python 3.11?

INSTARAW uses **MediaPipe** for advanced masking features. While some Python 3.12 installations work, **Python 3.11 is the recommended version** for maximum compatibility, especially on **Windows Portable**. If you're encountering MediaPipe installation errors, this guide will help you set up Python 3.11.

> 💡 **This works for both new and existing ComfyUI installations**

---

### Part 1: Preparation

#### For Existing ComfyUI Users (Important):

If you have an existing ComfyUI Portable setup with models and workflows:

1. Navigate to your `ComfyUI_windows_portable` directory
2. Find the `ComfyUI` sub-folder (contains `models`, `input`, `output`)
3. **Rename `ComfyUI` to `ComfyUI_OLD`** - This preserves all your models and data

#### For All Users:

1. **Download Fresh ComfyUI Portable**:
   - Get the latest from [ComfyUI Releases](https://github.com/comfyanonymous/ComfyUI/releases)
   - Extract the ZIP file

2. **Download Python 3.11.9 Embeddable**:
   - Visit: https://www.python.org/downloads/release/python-3119/
   - Download **"Windows embeddable package (64-bit)"** (`python-3.11.9-embed-amd64.zip`)

---

### Part 2: Python 3.11 Installation

Replace the default Python in your ComfyUI:

1. **Remove Old Python**:
   - Navigate to `ComfyUI_windows_portable\`
   - **Delete** the `python_embeded` folder

2. **Install Python 3.11**:
   - Extract `python-3.11.9-embed-amd64.zip`
   - Rename the extracted folder to **`python_embeded`**
   - Move it into `ComfyUI_windows_portable\`

3. **Enable Python Features**:
   - Open `python_embeded\python311._pth` in a text editor
   - **Remove `#`** from `#import site`
   - **Add these two lines** at the top:
     ```
     ..\ComfyUI
     ..\ComfyUI\src
     ```
   - The final file should look like this:
     ```
     python311.zip
     .
     ..\ComfyUI
     ..\ComfyUI\src
     import site
     ```
   - Save and close

---

### Part 3: Restore Your Data & Install INSTARAW

1. **(Existing Users Only) Restore Models**:
   - Copy `models` and `input` folders from `ComfyUI_OLD` to the new `ComfyUI` folder
   - This restores all your checkpoints, LoRAs, and images

2. **Install INSTARAW & Manager**:
   - Copy `ComfyUI_INSTARAW` to `ComfyUI\custom_nodes\`
   - Open PowerShell in `ComfyUI_windows_portable` and run:
     ```powershell
     cd ComfyUI\custom_nodes
     git clone https://github.com/ltdrdata/ComfyUI-Manager.git
     cd ..\..
     ```

---

### Part 4: Install Dependencies

1. **Download Pip Installer**:
   - Visit: https://bootstrap.pypa.io/get-pip.py
   - Save `get-pip.py` to `ComfyUI_windows_portable\`

2. **Install Pip**:
   ```powershell
   .\python_embeded\python.exe get-pip.py
   ```

3. **Install PyTorch with GPU Support**:
   ```powershell
   .\python_embeded\python.exe -m pip uninstall torch torchvision torchaudio
   .\python_embeded\python.exe -m pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
   ```

4. **Install All Requirements** (run each command):
   ```powershell
   .\python_embeded\python.exe -m pip install -r .\ComfyUI\requirements.txt
   ```
   ```powershell
   .\python_embeded\python.exe -m pip install -r .\ComfyUI\custom_nodes\ComfyUI_INSTARAW\requirements.txt
   ```
   ```powershell
   .\python_embeded\python.exe -m pip install -r .\ComfyUI\custom_nodes\ComfyUI-Manager\requirements.txt
   ```

---

### Part 5: Final Setup

1. **Launch ComfyUI**: Run `run_nvidia_gpu.bat`
2. **Install Missing Nodes**:
   - Open ComfyUI in browser (`http://127.0.0.1:8188`)
   - Click **"Manager"** → **"Install Missing Custom Nodes"**
   - Install any listed nodes (e.g., `rgthree-comfy`, `comfyui-rmbg`)
3. **Restart**: Close and run `run_nvidia_gpu.bat` again

**Done!** Your ComfyUI now has Python 3.11 with all dependencies. You can safely delete `ComfyUI_OLD` once confirmed working.

</details>

---

## 🆘 Troubleshooting

### Common Issues & Solutions

<details>
<summary><b>❌ Nodes don't appear after installation</b></summary>

<br>

**Solution**:
1. Verify `ComfyUI_INSTARAW` is in `ComfyUI/custom_nodes/`
2. Check that `pip install -r requirements.txt` completed successfully
3. **Completely restart ComfyUI** (not just refresh)
4. Check ComfyUI console for error messages

</details>

<details>
<summary><b>❌ "API Key Invalid" or "Authentication Failed"</b></summary>

<br>

**Solution**:
1. Double-check your API key is copied correctly (no extra spaces)
2. Verify the key is active in your provider's dashboard
3. Check you have credits available
4. Make sure you're using the right key for the right provider

</details>

<details>
<summary><b>❌ "Image Too Large" or "Resolution Error"</b></summary>

<br>

**Solution**:
1. Most APIs have size limits (usually 1024x1024 max)
2. Use the `INSTARAW Ensure Image Resolution` node before API calls
3. Check the specific API's documentation for limits

</details>

<details>
<summary><b>❌ Workflow gets stuck at Interactive Filter</b></summary>

<br>

**Solution**:
1. Look for the **floating filter window** (it may be behind other windows)
2. Click **"Continue"** after making your selection
3. Use the **"Clear Node Cache"** button if needed to reset

</details>

<details>
<summary><b>❌ MediaPipe installation errors or dependency failures</b></summary>

<br>

**Symptoms**:
- `ERROR: Could not find a version that satisfies the requirement mediapipe`
- `ERROR: No matching distribution found for mediapipe`
- Nodes fail to load with import errors

**Solution**:

MediaPipe works best with **Python 3.11**. While some Python 3.12 installations work, Windows Portable users commonly encounter issues:

1. Check your Python version:
   ```bash
   python --version
   ```
2. If you see Python 3.12+ and have installation errors, follow the [Python 3.11 Setup Guide](#-advanced-python-311-setup-for-comfyui-portable) above
3. **Windows Portable users**: Python 3.11 is strongly recommended

> 💡 **Quick Fix**: The guide above walks you through setting up Python 3.11 in about 10 minutes, preserving all your existing models and data.

</details>

<details>
<summary><b>❌ PhotoSwipe gallery not loading</b></summary>

<br>

**Solution**:
1. PhotoSwipe loads from CDN - ensure internet connectivity
2. Check browser console (F12) for errors
3. Try refreshing the ComfyUI page
4. Clear browser cache if needed

</details>

<details>
<summary><b>❌ Model download issues</b></summary>

<br>

**Solution**:
1. Run the downloader script from the correct directory
2. Check internet connectivity
3. Some models require Civitai API token (already included in txt file)
4. Models resume from where they left off if interrupted

</details>

<details>
<summary><b>❌ "Rate Limit" or "Too Many Requests"</b></summary>

<br>

**Solution**:
1. Wait 30-60 seconds before trying again
2. APIs have rate limits to prevent abuse
3. Consider upgrading your API plan if this happens frequently

</details>

---

## 🌟 Pro Tips for Best Results

### Workflow Tips

- 🎯 **Start Simple**: Test each workflow with default settings first
-  **Monitor Console**: Watch the console for progress and error messages
- 🎨 **Experiment**: Try different settings to find your perfect style
- ⚡ **Use Local Models**: SDXL, WAN 2.2 and zImage are FREE and produce great results!

### API Tips

- 💰 **Budget Wisely**: Start with small tests before bulk generation
- 🔑 **Secure Keys**: Never share your API keys publicly
- 📈 **Track Usage**: Monitor your API usage in provider dashboards
- ⚡ **Use 2X Mode**: For Nano Banana Pro, 2X mode is more cost-effective

### Quality Tips

- 🖼️ **Input Quality Matters**: Better input images = better results
- 🎭 **Face Clarity**: Ensure faces are clear and well-lit for faceswaps
- 🎨 **Style Consistency**: Keep similar styles for best coherence
- ✨ **Final Polish**: Always run Finalpass V2.0 for professional results

---

## 📚 Additional Resources

### Documentation

- 📖 **Full Node Documentation**: See `ComfyUI_INSTARAW/README.md`
- 🎓 **Video Tutorials**: Available on YouTube and Discord VIP channels
- 💡 **Workflow Examples**: Included in the Workflows folder

### Getting Help

As a VIP member, you have access to:

- 💬 **Private Discord Support** - Direct help from the team
- 📧 **Priority Email Support** - For technical issues
- 🎥 **Exclusive Video Guides** - Step-by-step tutorials
- 🔄 **Early Access Updates** - Be the first to try new features

---

## 📜 License & Important Terms

### Personal Use License

✅ **You Can**:
- Use INSTARAW for your personal AI content creation
- Create content for your own projects and portfolios
- Use workflows for client work (your own business)

❌ **You Cannot**:
- Share or redistribute this software
- Use it in a commercial service (e.g., SaaS platform)
- Modify or reverse engineering the code
- Share your copy with others (even friends/team members)

> ⚠️ **Important**: Each VIP license is for single-user use only. Multiple users need separate licenses.

### Full License

See `LICENSE.txt` in this package for complete terms and conditions.

---

## 🎉 You're All Set!

You're now ready to create amazing AI influencer content with INSTARAW V2.0!

### What's Next?

1. ✅ Run the model downloader script
2. ✅ Load your first V2.0 workflow
3. ✅ Add your API keys
4. ✅ Queue your first prompt
5. ✅ Join us in Discord to share your results!

---

## 📊 Version History

| Version | Release Date | Highlights |
|---------|--------------|------------|
| **V2.0.0** | December 2025 | 14 workflows, AIL/RPG/BIG nodes, WAN 2.2 multi-sampler, zImage local, Detection bypass, ~8K prompts |
| **V1.0.2** | October 2025 | Fixed Booba & Glutes workflow errors, Updated to V8 |
| **V1.0.1** | October 2025 | Fixed Gemini node dependencies, Updated workflows to V12, Added legal protections |
| **V1.0** | October 2025 | Initial VIP release with full functionality, 4 production workflows |

---

<div align="center">

<br>

**Made with ❤️ by Instara**

*Your Digital Empire, Automated.*

<br>

---

### Need Help?

**Discord**: Join the [VIP general chat](https://discord.com/channels/1402334538092380350/1426528469700972564) | **Email**: support@instara.io

**Questions?** Reach out in [Discord](https://discord.gg/instara) | **Feedback?** We'd love to hear it!

<br>

**Happy Creating! 🚀**

</div>

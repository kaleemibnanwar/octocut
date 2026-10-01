<div align="center">

<img src="https://github.com/kaleemibnanwar/octocut/releases/download/v2.6.10/octo-logo.png" alt="Octo Cut logo" width="190">

# 🎬 Octo Cut

### The video editor that's **free**, **fast**, and built to be driven by you—or your AI agent.

No watermarks. No subscriptions. No paywalled exports. No account. Ever.

<br>

[![Download](https://img.shields.io/badge/⬇_Download-Free-brightgreen?style=for-the-badge)](../../releases/latest)
[![Price](https://img.shields.io/badge/Price-$0_forever-blue?style=for-the-badge)](#-license)
[![Watermark](https://img.shields.io/badge/Watermark-None-orange?style=for-the-badge)](#-features)
[![MCP Tools](https://img.shields.io/badge/MCP_Tools-60-blueviolet?style=for-the-badge)](#-built-for-ai-agents)
[![Source Requests](https://img.shields.io/badge/Source_Requests-0%2F50-red?style=for-the-badge)](#-unlock-the-source-code)

<br>

**Your timeline. Your files. Your machine.**

<br>

[**Download**](#-download) · [**Features**](#-features) · [**AI + MCP**](#-built-for-ai-agents) · [**Why Octo Cut?**](#-why-octo-cut) · [**Roadmap**](#-roadmap) · [**Unlock the Source**](#-unlock-the-source-code)

</div>

---

## ⚡ Why Octo Cut?

Most “free” editors hide a watermark, reserve useful tools for a paid tier, or make you upload your work before you can create. **Octo Cut doesn't.**

| | Typical “Free” Editors | **Octo Cut** |
|---|:---:|:---:|
| Watermark on exports | ❌ Often | ✅ **Never** |
| Subscription | 💰 Monthly | ✅ **None** |
| Account required | ❌ Often | ✅ **No** |
| Local editing and rendering | ⚠️ Not always | ✅ **Yes** |
| AI-agent control | ❌ No | ✅ **60 MCP tools** |
| Automated edits | ⚠️ Cloud-locked | ✅ **Local MCP workflows** |

Octo Cut is non-destructive: arrange, trim, animate, grade and mix without changing your original media.

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🎞️ Timeline Editing

- Multi-track video, image, text and audio timeline
- Drag, resize, rotate, trim, split and arrange
- Snapping, alignment guides, grids and safe areas
- Full project undo/redo
- Local autosave and saved project library

</td>
<td width="50%" valign="top">

### ✨ Motion & Effects

- Keyframe position, scale, rotation, opacity and volume
- Linear, ease-in, ease-out and ease-in-out animation
- **45 transitions**, from clean dissolves to GLSL warps
- Filters, blend modes and colour controls
- Procedural overlays, shapes, stickers and backgrounds

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔊 Audio & Voice

- Multi-layer audio mixing
- Per-clip volume and fade in/out
- Waveform-aware editing
- Built-in generated impacts, whooshes, ticks and ambience
- AI narration, transcription and caption workflows

</td>
<td width="50%" valign="top">

### 🖼️ Content Creation

- Rich titles with fonts, outline, shadow and background pills
- Brand packs and reusable templates
- Thumbnail and still-image composition
- Stock search across Wikimedia Commons and The Met
- Optional Pixabay and Pexels integrations

</td>
</tr>
</table>

### 📦 Real local export

Preview and export share the same renderer, so the exported frame matches the canvas. Export support is detected on your machine and can include:

`MP4` · `WebM` · `PNG` · mixed audio · configurable canvas size and frame rate

---

## 🤖 Built for AI agents

Octo Cut includes a local **Model Context Protocol server** with **60 editing tools**, live resources and agent playbooks. Connect an MCP-capable assistant and let it operate the same editor you see on screen.

| Tool family | What an agent can do |
|---|---|
| 👀 **Observe** | Read the project, timeline, playhead, selection, media bin and export activity |
| ✂️ **Control** | Add, trim, split, move, style, animate, reorder and delete clips |
| 🎥 **Media** | Import local/remote media, search stock libraries and place footage |
| 🎙️ **Voice** | Generate narration, transcribe takes, add captions and build voiced sequences |
| 🗂️ **Projects** | Create, save, open and manage projects, templates and brand packs |
| ⚙️ **Flows** | Assemble rough cuts, ripple-delete, create J/L cuts, cut on beats, reframe for social, build titles and lower thirds, trim silence and check picture lock |
| 🖼️ **Images** | Compose thumbnails and graphics from text, images, shapes, stickers and overlays |
| 📜 **Manifests** | Validate and apply a complete declarative edit in one operation |

The desktop endpoint stays on your machine at:

```text
http://127.0.0.1:51351/mcp
```

It binds to localhost, validates the host, and can be started or stopped from the Agent panel.

> **The pitch:** describe the edit, let an agent build it, then refine every cut yourself on the timeline.

---

## ⬇️ Download

Go to the [**latest release**](../../releases/latest), then choose your platform:

| Platform | Requirements | Download |
|:--|:--|:--|
| 🪟 **Windows** | Windows 10 / 11, 64-bit | [`Setup.exe` installer or portable `.exe`](../../releases/latest) |
| 🍎 **macOS** | Apple Silicon | [Signed and notarized `.dmg` or `.zip`](../../releases/latest) |
| 🐧 **Linux** | 64-bit Linux | [`.AppImage` or Debian `.deb`](../../releases/latest) |

Windows and macOS check for updates automatically and offer a restart when the next version is ready. Linux updates are installed manually from Releases.

<details>
<summary><b>💻 Recommended specs</b></summary>

- **CPU:** 4 or more cores
- **RAM:** 8 GB minimum; 16 GB recommended for larger edits
- **Browser engine:** Included in the desktop app
- **Disk:** Approximately 1 GB for the app, plus room for source media and exports

</details>

---

## 🚀 Quick Start

```text
1. Download and install Octo Cut
2. Open the demo project or create a new project
3. Drop clips, images or audio into the media bin
4. Build the timeline yourself—or connect an MCP agent
5. Preview → Export → Done 🎉
```

---

## 🗺️ Roadmap

- [x] Multi-track, non-destructive timeline
- [x] Keyframe animation and 45 transitions
- [x] Local MP4/WebM export with no watermark
- [x] Saved projects and local autosave
- [x] AI narration, transcription and caption workflows
- [x] 60-tool MCP server for agent-driven editing
- [x] Automatic Windows and macOS updates
- [ ] Background removal
- [ ] Community template marketplace
- [ ] Plugin ecosystem
- [ ] More platform-native export codecs

💡 **Have an idea?** [Open a feature request](../../issues/new?template=feature_request.md) — useful, well-supported ideas move up the list.

---

## 🔓 Unlock the Source Code

> ### 🎯 **Goal: 50 source-code requests → Octo Cut becomes public source.**

Octo Cut is currently closed-source, but if enough creators and developers want to build with it, the source will be opened.

**Progress**

```text
[░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 0 / 50 requests
```

### How to request the source

1. 🧾 [**Open an issue**](../../issues/new?title=Source%20Request&body=I%27d%20like%20Octo%20Cut%20to%20become%20open%20source.) titled `Source Request`
2. 👍 Add a **👍 reaction** to an existing Source Request issue
3. ⭐ Star this repository and share it with another editor or agent builder

**At 50 genuine requests, the full source goes public.** No moving goalposts.

---

## 🤝 Sponsorship & Partnership

Octo Cut is independently built. Sponsorship helps keep it free and accelerates new formats, workflows and integrations.

### 🏢 Let's build together

Open to collaborations with **creator tools, hardware makers, stock-media platforms, AI companies and brands**—including integrations, co-marketing, bundled distribution and custom workflows.

📩 **Contact:** [kaleemibnanwar@gmail.com](mailto:kaleemibnanwar@gmail.com) · [GitHub](https://github.com/kaleemibnanwar)

---

## 💬 Support & Community

- 🐛 **Found a bug?** [Open an issue](../../issues/new)
- 💡 **Ideas and requests:** [Start a discussion](../../discussions)
- 📦 **Downloads:** [Releases](../../releases)
- 📧 **Email:** [kaleemibnanwar@gmail.com](mailto:kaleemibnanwar@gmail.com)

> This public repository contains the README, release notes and binary downloads. Application source code is not published yet.

---

## 📜 License

**Octo Cut is closed-source freeware.** You may use the official app for personal or commercial video creation at no charge. You may redistribute links to the official release; you may not modify, repackage, resell or reverse-engineer the application.

The videos and images you create remain yours. The software is provided “as is,” without warranty.

## 🔒 Privacy

Editing, project storage and rendering happen locally. Your imported media is not uploaded by the editor.

Octo Cut connects to the internet only for features that need it: optional stock-media searches, update checks, and anonymous Microsoft Clarity usage analytics. Analytics can be disabled at any time under **Keys → Privacy**.

---

<div align="center">

### ⭐ If Octo Cut saves you time, **star the repo and tell a creator.**

Made with ❤️ by [Kaleem](https://github.com/kaleemibnanwar) · © 2026 Octo Cut

</div>

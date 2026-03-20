<h1 align="center">Michael D</h1>

- Cofounder of [ShareX](https://github.com/ShareX/ShareX), one of the most widely used open source capture and automation tools with tens of millions of downloads and a global user base.
- Currently building [XerahS](https://github.com/ShareX/XerahS), a cross-platform evolution designed to bring ShareX capabilities to Windows, macOS, and Linux using modern architecture.
- I develop with AI agents as first-class collaborators - agentic engineering is how I ship faster without cutting corners.

<p align="center">
  <a href="https://getsharex.com">Website</a> |
  <a href="https://github.com/ShareX/ShareX">ShareX</a> |
  <a href="https://github.com/ShareX/XerahS">XerahS</a> |
  <a href="https://github.com/McoreD/ShareX.ImageEditor">ShareX.ImageEditor</a> |
  <a href="https://github.com/McoreD/UploaderX">UploaderX</a> |
  <a href="https://x.com/mcored">X</a>
</p>

## What I work on

- Desktop software in C# and .NET
- Cross-platform UI with Avalonia
- Screen capture, annotation, upload, and automation workflows
- Building tools used daily by developers, engineers, and creators
- Agentic engineering: running AI coding agents to plan, implement, verify, and ship production features end-to-end

## Current projects

### ShareX

A mature, battle-tested Windows application for screen capture, file sharing, and advanced automation workflows. Used globally as a core productivity tool.

### XerahS

A modern, cross-platform reimagining of ShareX built with **.NET 10** and **Avalonia 11.3+**. The codebase is architected specifically to maximize AI comprehension and agentic contribution: strict nullability, exhaustive documentation, and standardized MVVM. **XerahS is developed using agentic coding workflows as a first-class engineering practice** - GitHub Copilot, Claude, and other AI agents drive feature development, refactoring, and quality improvements throughout the project.

Feature highlights:
- **Cross-platform desktop** on Windows, Linux, and macOS, plus experimental **.NET MAUI** mobile for Android and iOS
- **Region, fullscreen, and window capture** with multi-monitor support; Windows uses the Desktop Duplication API (DXGI), macOS uses ScreenCaptureKit, Linux covers X11 and Wayland
- **17 annotation types** — shapes, arrows, text, numbered steps, blur/pixelate/magnify/highlight regions, freehand pen, speech balloon, image/sticker insertion, spotlight, smart eraser, and crop — with full undo/redo and object-level selection
- **Hardware-accelerated image editor** rendering 4K+ at 60 FPS via Skia/Metal/Direct2D, with 40+ effects across Adjustments, Filters, Manipulations, and Drawings
- **Workflow system with zero inheritance** - every workflow is fully independent with its own hotkeys and tasks, eliminating configuration errors from inheritance chains

### ShareX.ImageEditor

A modular, high-performance annotation and image editing engine powering ShareX and XerahS. Built with a clean split between a UI-agnostic core (annotation model, history stack, 100+ image effects) and an Avalonia + SkiaSharp presentation layer, so host applications can embed the editor without coupling to its UI internals.

Effect categories include standard transforms and color corrections through to stylized looks like ASCII art, matrix digital rain, holographic foil shimmer, claymation texture, and watercolor/Kuwahara. The host API accepts a file path or stream, wires callbacks for copy/save/upload/pin, and plugs into a larger capture pipeline rather than running only standalone.

### UploaderX

A cross-platform implementation of the ShareX uploader ecosystem, designed for reuse across multiple apps and platforms.

## Agentic engineering

I treat AI coding agents as team members that can own bounded tasks end-to-end: reading the codebase, proposing designs, writing and verifying code, and committing clean output. This isn't autocomplete - it's a disciplined workflow where agents operate within defined skill files, follow build and architecture rules, and are held to the same quality bar as human-written code.

XerahS is the live experiment. The codebase is intentionally structured to be agent-readable: strict nullability, consistent MVVM, registry-driven dispatch, and skill files that give agents the domain context they need to work autonomously on real features.

## Earlier projects

- [TDMaker](https://github.com/McoreD/TDMaker) - Torrent Description Maker and Torrent Creator
- [iTSfv](https://github.com/McoreD/iTSfv) - iTunes Store file validator

## Notes

I build software that stays installed for years. Fast, reliable tools with clear workflows, minimal friction, and long-term maintainability — increasingly shipped with agents as active contributors rather than passive assistants.

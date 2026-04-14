🚀 Local AI Launcher (KoboldCPP Config Manager)

Lightweight launcher for KoboldCPP configs + auto app or URL execution on launch.
Create multiple AI configurations for fast switching between models and setups.


📁 AI Profiles

Create multiple AI configurations.
Each profile contains model settings, flags, context window overrides, launch actions, and optimization rules for quick switching between local AI setups.


⚙️ Features

Create AI profiles using KoboldCPP config files for fast launch.
Auto launch apps, browsers, or URLs per AI or use case.
Extend context window beyond KoboldCPP limits.
Adjust global KoboldCPP flags.
Enable Windows process kill rules on launch to free RAM.


🧪 Example Menu (BAT Interface)

1. Qwen Coder Next + Zed
2. Qwen 32B Uncensored [100000] [rope] @ firefox.exe
3. Qwen3 Omni 30B thinker
4. Qwen 3VL 8B


📥 Setup

1. Download official KoboldCPP and set up AI config profiles.
2. On first launch, set:
    KoboldCPP executable path,
    Config folder path,
    Windows auto task-kill list,
    Remove default KoboldCPP configs if needed,
    Add your KoboldCPP config files,
    Optional: auto-run app or browser + URL per profile,
    Optional: override context window per profile,
    Optional: edit global flags in JSON

**Direct JSON editing is supported for fast workflow changes.**

🚀 Launch System
Select any saved profile to launch instantly.
The launcher applies model path, flags, context size, and system rules before startup.

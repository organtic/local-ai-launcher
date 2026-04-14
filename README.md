🚀 Local AI Launcher (KoboldCPP Config Manager)

(Open source, AS IS)

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
2. Qwen 3.5 35B [100000] [rope] @ firefox.exe
3. Qwen 3.5 35B [16000] @ firefox.exe
4. Qwen 3.5 9B [256000] [rope] + Void
5. Qwen 3 Omni 30B thinker
6. Qwen 2.5 Omni 7B
7. Gemma 4 26B @ chrome.exe
8. Gemma 4 E4B @ chrome.exe
9. WizardCoder Python 7B

   **press number and enter to launch**


📥 Setup

1. Double-click **`Local AI Launcher.bat`** (same folder as `kobold_launcher_config.ps1` and the JSON config files).
2. Download official KoboldCPP and set up AI config profiles in Kobold.
3. On first launch, set:
    KoboldCPP executable path,
    Config folder path,
    Windows auto task-kill list,
    Remove default KoboldCPP configs if needed,
    Add your KoboldCPP config files,
    Optional: auto-run app or browser + URL per profile,
    Optional: override context window per profile,
    Optional: edit global flags in JSON.

**Direct JSON editing is supported for fast workflow changes.**

🚀 Launch System
Select any saved profile to launch instantly.
The launcher applies model path, flags, context size, and system rules before startup.


**Security:**
This project is a local Windows launcher for KoboldCpp. It runs your configuration with full user permissions and does not sandbox execution.

All actions (including app launches, URLs, and process kills) should occur only when you manually launch a profile.

Do not import or merge JSON files, zip bundles, or shared configs from untrusted sources. Always review before use. Build and maintain your own configuration files.

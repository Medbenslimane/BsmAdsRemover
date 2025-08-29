BsmAdsRemover v1.0.2025- Android Adware Removal Tool
Project Overview
BsmAdsRemover is a powerful Windows application designed to help users detect and remove adware, bloatware, and suspicious applications from Android devices via ADB (Android Debug Bridge). This tool provides an intuitive graphical interface to scan installed apps, identify potential ad-related packages, and safely uninstall or disable them—without requiring root access.

Key Features
✔ Device Detection – Automatically detects connected Android devices and retrieves basic info (model, manufacturer, Android version).
✔ App Scanning – Lists all installed packages and highlights potential adware based on:

Package name patterns (e.g., com.adservice, ads.sdk)

Suspicious permissions (e.g., INTERNET, SYSTEM_ALERT_WINDOW)

Ad-related services/receivers
✔ Smart Filtering – Isolate adware or system apps with color-coded labels (🔴 = adware, 🔵 = system app).
✔ Safe Removal – Uninstalls apps for the current user (pm uninstall) or disables them if uninstall fails (pm disable-user).
✔ Real-Time Logging – Detailed RichEdit log with timestamps, success/error messages, and progress tracking.
✔ User-Friendly UI – Progress bar, stop button for long operations, and exportable logs.

Technical Highlights
🔧 ADB Command Automation – Executes shell commands silently and parses outputs efficiently.
🔧 Multi-Threading Support – Prevents UI freezing during scans/removals (via TThread).
🔧 Customizable Blacklists – Predefined keywords (AD_KEYWORDS) and system app filters (SYSTEM_APPS_BLACKLIST).
🔧 Dynamic List Handling – Caches app lists for quick toggling between full/ad-only views.

Use Cases
📌 Privacy Protection – Remove hidden ad trackers and analytics SDKs.
📌 Performance Boost – Eliminate background ad services draining battery/RAM.
📌 Bloatware Removal – Disable preinstalled vendor apps (non-root).

Requirements
Windows 7+ (.NET compatible)

ADB installed and device connected in USB Debugging mode

No root needed (uses standard adb shell command

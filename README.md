# Ven



ABOUT

Ven is a Windows desktop browser built with C# (WinForms) and Microsoft WebView2. It has a  a custom window, and a simple installer that can also repair or uninstall it. Inspired by Zen.

Features
Dark by design. A near-black, gray-only interface that stays out of the way.
Tabs, address bar and downloads in a custom borderless window.
Local accounts with a profile picture and banner.
Your choice of search engine: DuckDuckGo, Google or Brave.
Simple installer that installs for your Windows user only, and can repair or uninstall Ven.
Sc
Download and install
Go to the Releases page and download the latest VenSetup.zip.
Extract the zip.
Run VenSetup.exe and click Install Ven.

Requirements: Windows 10 or 11 (64-bit) and the Microsoft WebView2 Runtime, which is already included with Windows 11 and most up-to-date Windows 10 PCs.

Windows warning? Ven isn't code-signed yet, so Windows SmartScreen may show "Windows protected your PC". Click More info, then Run anyway. If your browser blocks the download, open the downloads list (Ctrl+J) and choose Keep.

FAQ

How do I uninstall Ven? Run VenSetup.exe again and click Uninstall Ven.

Something is broken. Do I need to reinstall? No. Run VenSetup.exe and click Repair installation.

Where is Ven installed? For your user only, in C:\Users\<you>\AppData\Local\Programs\Ven.

Ven won't open. Install the WebView2 Runtime, then run Repair installation. Also check that your antivirus didn't quarantine the file.

Roadmap
 Our own Ven search engine (in progress, coming soon)
 Tab groups
 Custom wallpaper, including uploading your own
Build from source
Clone the repo: git clone https://github.com/everwow1/Ven.git
Open the solution in Visual Studio on Windows.
Restore NuGet packages (including Microsoft.Web.WebView2) and build.
Feedback

Found a bug or have an idea? Open an issue.

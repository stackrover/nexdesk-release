# NexDesk releases

NexDesk is a remote desktop for your own computers on your **local network**: control a
Windows PC or a Mac from another Mac, PC or Android phone. Nothing goes through the
internet or any cloud service; computers pair once with a code and you approve each new
device on the computer being controlled.

Download the latest version from **[Releases](../../releases)**.

| File | For |
| --- | --- |
| `NexDesk_<version>_x64-setup.exe` | Windows 10/11 (64-bit) |
| `NexDesk_<version>_aarch64.dmg` | macOS 13 or later, Apple silicon (M1 and later) |
| `NexDesk_<version>_android-arm64.apk` | Android 8 or later (64-bit ARM phones) |

Check a download with `SHA256SUMS.txt` (`shasum -a 256 <file>` on macOS,
`Get-FileHash <file>` on Windows).

## Installing

The builds aren't signed by Apple or Microsoft, so each system asks once.

**Windows:** run the setup. If "Windows protected your PC" appears, choose **More info →
Run anyway**. Set your network to **Private** (NexDesk only accepts connections on
Private networks).

**macOS:** open the DMG and drag NexDesk to Applications. The first time, macOS blocks it:
open **System Settings → Privacy & Security** and choose **Open Anyway**. To let others
control this Mac, allow **Screen Recording** and **Accessibility** when NexDesk asks, and
**Allow incoming connections** if the firewall asks.

**Android:** open the APK and allow installing from that app when asked. The phone
controls other computers (it can't be controlled).

**iOS:** not available (an iPhone app needs a paid Apple Developer account to install).

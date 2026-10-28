# Multi Control

One keyboard and mouse for all your computers. Move the pointer off the edge of one screen and onto the next computer. Copy and paste, and send files, between them.

## Download

Get the latest installer from **[Releases](../../releases/latest)**.

| Computer | File |
|---|---|
| Windows 10/11 (64-bit) | `Multi Control_x.y.z_x64-setup.exe` |
| Mac, Apple silicon (M1 and later) | `Multi Control_x.y.z_aarch64.dmg` |
| Mac, Intel | `Multi Control_x.y.z_x64.dmg` |
| Ubuntu / Debian (64-bit) | `multi-control_x.y.z_amd64.deb` |

Install it on every computer you want to connect.

## Install

- **Windows:** run the `.exe`. Windows may show "Windows protected your PC" because the app isn't code-signed yet: choose **More info**, then **Run anyway**. The installer needs administrator approval and allows Multi Control through the firewall on private networks. If your Wi-Fi is set to **Public**, set it to **Private** (Settings → Network & internet → Wi-Fi → your network), or other computers won't reach this one.
- **macOS:** open the `.dmg` and drag Multi Control to Applications. If macOS blocks the first launch, right-click the app and choose **Open**. Allow **Accessibility** when asked.
- **Ubuntu / Debian:** `sudo apt install ./multi-control_x.y.z_amd64.deb`, then log out and back in.

## Pair two computers

1. Open Multi Control on both. They find each other within a few seconds.
2. On one, go to **Computers** and choose **Pair** next to the other.
3. Type the 6-digit code the other computer shows.
4. Open **Arrange** and drag the computer to where it sits on your desk.

Everything stays on your network. There's no account and no server, and all traffic is encrypted. It uses UDP ports 47320 and 47321, plus mDNS.

Windows and macOS copies update themselves. On Linux, install the new `.deb`.

Verify a download with `SHA256SUMS.txt` on the release.

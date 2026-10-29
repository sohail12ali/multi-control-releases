# Noble Relay

One keyboard and mouse for all your computers. Move the pointer off the edge of one screen and onto the next computer. Copy and paste, send files, chat, and look at another computer's screen. A product of [Noble Wave](https://noble-wave.com).

## Download

Get the latest installer from **[Releases](../../releases/latest)**. Not every release has every platform, so check the file list on the release page.

| Computer | File |
|---|---|
| Windows 10/11 (64-bit) | `Noble.Relay_x.y.z_x64-setup.exe` |
| Mac, Apple silicon (M1 and later) | `Noble.Relay_x.y.z_aarch64.dmg` |
| Mac, Intel | `Noble.Relay_x.y.z_x64.dmg` |
| Ubuntu / Debian (64-bit) | `noble-relay_x.y.z_amd64.deb` |
| Fedora / openSUSE (64-bit) | `noble-relay-x.y.z-1.x86_64.rpm` |

Install it on every computer you want to connect. All of them must run the same version.

## Install

- **Windows:** run the `.exe`. Windows may show "Windows protected your PC" because the app isn't code-signed yet: choose **More info**, then **Run anyway**. The installer needs administrator approval and allows Noble Relay through the firewall on your local network. If your Wi-Fi is set to **Public**, set it to **Private** (Settings → Network & internet → Wi-Fi → your network), or other computers won't reach this one.
- **macOS:** open the `.dmg` and drag Noble Relay to Applications. If macOS blocks the first launch, right-click the app and choose **Open**. Allow **Accessibility** when asked.
- **Ubuntu / Debian:** `sudo apt install ./noble-relay_x.y.z_amd64.deb`, then log out and back in.
- **Fedora / openSUSE:** `sudo dnf install ./noble-relay-x.y.z-1.x86_64.rpm` (or `sudo zypper install`), then log out and back in.

### Coming from Multi Control

Noble Relay is the new name of Multi Control. Install Noble Relay, then uninstall the old app, because the two are separate programs and the old one can't turn itself into the new one. The first time Noble Relay starts it moves your old settings, so the computer keeps its identity, pairings and chat history. Old and new versions can't talk to each other, so update every computer.

## Pair two computers

1. Open Noble Relay on both. They find each other within a few seconds.
2. On one, go to **Computers** and choose **Pair** next to the other.
3. Type the 6-digit code the other computer shows.
4. Open **Arrange** and drag the computer to where it sits on your desk.

Everything stays on your network. There's no account and no server, and all traffic is encrypted. It uses UDP ports 47320 and 47321, plus mDNS.

Windows and macOS copies update themselves. On Linux, install the new package.

Verify a download with `SHA256SUMS.txt` on the release.

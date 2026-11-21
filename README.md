# ShootChute for your computer

ShootChute is an iPhone app that sends photos, scans, videos, voice memos and files straight to a folder on your own computer. This page is where you get the computer half: a small app that receives what the phone sends.

Nothing goes through a cloud service. The phone sends to your computer directly, encrypted.

## Download

| Computer | Download |
|---|---|
| Windows 10 or 11 | [ShootChute-Setup.exe](https://github.com/slowgojoe/shootchute-downloads/releases/latest/download/ShootChute-Setup.exe) |
| Mac (Apple Silicon: M1 or newer) | [ShootChute-mac.zip](https://github.com/slowgojoe/shootchute-downloads/releases/latest/download/ShootChute-mac.zip) |

The iPhone app is in testing through TestFlight, by invitation.

## Set it up

1. **Install on the computer.**
   - **Windows:** run `ShootChute-Setup.exe`. Windows will say the publisher is unknown, because the app isn't signed yet: click **More info**, then **Run anyway**. It asks for permission once, to let the phone through the firewall.
   - **Mac:** unzip and open `ShootChute`. The first time, macOS will refuse to open it: go to **System Settings > Privacy & Security**, scroll down and click **Open Anyway**.
2. **A page with a code opens.** Leave it on screen.
3. **On the iPhone,** open ShootChute, go to Settings, tap **Pair with a computer** and point the phone at the code.
4. **Done.** What you capture lands in a `ShootChute` folder in your home folder, sorted by kind. The page has a button that opens it.

ShootChute keeps running in the background and starts when you sign in. To see the code again, open ShootChute on the computer.

## Where it works

- **At home:** the phone and the computer need to be on the same Wi-Fi.
- **Away from home:** install [Tailscale](https://tailscale.com) on both, signed in to the same account, and it works from anywhere.

If the phone says the computer did not answer, check that the computer is on and that the phone is on the same Wi-Fi or has Tailscale switched on.

## Help and privacy

- **Something not working, or a question:** [open an issue](https://github.com/slowgojoe/shootchute-downloads/issues) and say what you tried and what you saw.
- **Privacy:** ShootChute collects nothing and sends your files only to your own computer. The [privacy policy](PRIVACY.md) has the details.

---

© 2026 Joseph Riehl. All rights reserved. ShootChute is free: download it, use it, and pass unchanged copies on. It may not be sold or presented under another name. The terms are in [LICENSE.txt](LICENSE.txt).

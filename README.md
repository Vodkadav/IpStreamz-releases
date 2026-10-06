# IpStreamz

A family TV app for an **Xtream Codes** IPTV subscription: films, series and TV channels, with
profiles, a kids' guardrail, Resume, My list, downloads and history that follows you between
the family's phones, Android TVs and Windows PCs.

You need **your own Xtream subscription** from your IPTV provider. IpStreamz comes with no
channels, no account and no server. The app is free and asks for nothing else.

## 1. Install

The newest version is always on the
[latest release](https://github.com/Vodkadav/IpStreamz-releases/releases/latest) page.

**Android phone or tablet**
1. On the phone, open the latest release page and tap **IpStreamz.apk**.
2. Open the downloaded file. If Android asks, allow your browser or Files app to
   **install unknown apps**, then tap **Install**.

**Android TV / Google TV**
1. On the TV, install the free app **Downloader** (by AFTVnews) from the Play Store.
2. In Downloader, enter this address and press Go:
   `https://github.com/Vodkadav/IpStreamz-releases/releases/latest/download/IpStreamz.apk`
3. Allow Downloader to install unknown apps when asked, then **Install**.

**Windows PC**
1. Download **IpStreamz-Setup.exe** from the latest release and run it.
2. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
   It installs for your user only and needs no administrator.

## 2. First start: your login

Enter what your provider gave you:
- **Server addresses**: one per line (add the backup addresses too, if you have them).
- **Username** and **password**.

Press **Connect**. The login is kept only in this device's secure storage and is sent only to
your provider. The first start loads your provider's whole list, which can take a few minutes.

## 3. The owner PIN and the children

Open **Settings → Owner settings**. The first time, you choose a 4–8 digit **owner PIN**.
There you name the profiles, mark children, and tick the categories children must not see.
This is a family guardrail inside the app, not a lock.

## 4. More devices in the family

Log in once, then pair the other devices so history, My list and favourites follow everyone:
1. On the first device: **Settings → Family devices → Invite a device**. Keep the screen open.
2. On the new device: **Settings → Family devices → Join with a code**, and type the 6 characters.

Both devices must be on the same home network. If they are not (or the search finds nothing),
tap **Enter address manually** and type the other device's address (for example its
Tailscale address).

## 5. Updates

The app checks for a new version by itself and shows **Update now**. Your login, history and
downloads stay.

## 6. Leaving a device (for example a hotel TV)

**Settings → Log out of this device** (needs the owner PIN) removes the login, the pairing and
everything else from that device. Your other devices keep everything.

## Privacy

No account with us, no tracking, no analytics. Your devices talk only to your IPTV provider,
to each other, and (if you add a key in Owner settings) to TMDb for posters and suggestions.

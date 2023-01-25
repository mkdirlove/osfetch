<h1 align="center">
  <br>
  <a href="https://github.com/mkdirlove/osfetch"><img src="https://github.com/mkdirlove/osfetch/blob/main/osfetch.png" alt="osfetch"></a>
  <br>
  Yet another lightweight tool to fetch your system information.
  <br>
</h1>

#### Manually:

Copy-paste this into your terminal:

```sh
sudo curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch -o /usr/bin/nerdfetch
sudo chmod +x /usr/bin/nerdfetch
nerdfetch
```

#### Android with Termux:

Copy-paste this into Termux:

```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch -o /data/data/com.termux/files/usr/bin/nerdfetch
chmod a+x /data/data/com.termux/files/usr/bin/nerdfetch
nerdfetch
```

#### Run once:

Note that this will ***not*** install the program.
```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch | sh
```

### Features:
- Strong cross-OS compatability
- Not bloated
- Portable
- POSIX

### OSes supported:
- Debian based Linux
- Ubuntu based Linux
- Arch based Linux
- RedHat based Linux
- SUSE based Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Gentoo Linux
- Exherbo Linux
- NixOS Linux
- Solus Linux
- yiffOS Linux
- Slackware Linux\*
- macOS 10.x + 11.x
- Android

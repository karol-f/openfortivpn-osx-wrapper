<div align="center">

  <br />
  <a href="https://github.com/karol-f/openfortivpn-osx-wrapper">
    <img src="img/forti-wrapper-osx.jpg" alt="Logo" width="300">
  </a>

<h3 align="center">FortiVpnGui</h3>

  <div align="center">
    GUI for OpenFortiVpn CLI
  </div>
</div>

### Built With

- [Platypus](https://github.com/sveinbjornt/Platypus/)
- [openfortivpn](https://formulae.brew.sh/formula/openfortivpn)

## Installation

### Download
Download [OpenFortiGui.app](./FortiGui.app.zip) ZIP and unpack it.

### Check your VPN Gateway and Port

First you have to check your existing Forti connection details

<img src="img/vpn-connection-details.jpg" alt="Logo" width="300">

Then check Gateway and Port

<img src="img/vpn-gateway.jpg" alt="Logo" width="300">

And put that data into downloaded `FortiGui.app/Contents/Resources/script` file
<img src="img/vpn-script.jpg" alt="Logo" width="300">

After saving, you can move `FortiGui.app` to your OSX application folder and run it.

In the first run it will need Homebrew and openfortivpn installed but it will auto install it for you (if not please install it manually).

## How it's built

<div align="center">
    <img src="img/Platypus.jpg" alt="Logo" width="300">
</div>

It's a shell wrapper around openfortivpn CLI. [You can see script here](./FortiGui.app/Contents/Resources/script).


<p align="center">
  <a href="http://galaxy.ooo">
    <img src="https://media.githubusercontent.com/media/galaxypi/galaxy-design/master/social/social-galaxy-logo-rounded.png" width=72 height=72>
  </a>
  <h3 align="center">Galaxy</h3>
  <p align="center">
    Galaxy is a blockchain agnostic node network and protocol offering services to decentralized platforms
    <br/>
    <a href="http://galaxy.ooo"><strong>galaxy.ooo</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/galaxypi/galaxy/issues/new?template=feature_request.md">Request feature</a>
    &nbsp;&middot;&nbsp;
    <a href="https://github.com/galaxypi/">Explore</a>
    &nbsp;&middot;&nbsp;
    <a href="https://github.com/galaxypi/galaxy/issues/new?template=bug_report.md">
    Report bug</a>
    &nbsp;&middot;&nbsp;
    <a href="https://discord.gg/36K9nan">Chat</a>
    <br/>
    <br/>
    <a href="https://twitter.com/intent/follow?screen_name=galaxypilab">
      <img src="https://img.shields.io/twitter/url/https/twitter.com/galaxypilab.svg?style=social&label=Follow%20%40galaxypilab&logo=twitter" alt="follow on Twitter">
    </a>
    &nbsp;&middot;&nbsp;
    <a href="https://github.com/galaxypi/galaxy/stargazers">
      <img src="https://img.shields.io/github/stars/galaxypi/galaxy.svg?style=social&label=Star&maxAge=2592000" alt="Star Repo">
    </a>
  </p>
</p>
<br/>
<p align="center">
  <img src="https://user-images.githubusercontent.com/1711854/45527941-28b4de00-b7ac-11e8-9803-900e5022ce6b.png" width="800px">
</p>

<br/>

## Table of contents

- [Quick Start](#quick-start)
- [Status](#status)
- [Bug report](#bug-report)
- [Feature requests](#feature-requests)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [Community](#community)
- [Repository maintainers](#repository-maintainers)
- [License](#license)

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Quick start

Quick start options:

There are currently two supported operating system installations for Galaxy
Core Software.

1. Installation.
   #### Linux (Pi and x86 varieties)
   ```
   bash <(curl -s https://raw.githubusercontent.com/galaxypi/galaxy/master/install.sh)
   ```
   #### macOS
   ```
   bash <(curl -s https://raw.githubusercontent.com/galaxypi/galaxy/master/install-mac.sh)
   ```

2. Navigate to the Galaxy directory.

   ```
   cd ~/galaxy
   ```

3. Run the Galaxy blockchain
   The installer should prompt you to type `./galaxyd start` when it is
   finished. This will start syncing the blockchain.

4. Create a Galaxy wallet.
   Run the following in a second terminal window.
   ```
   ./galaxycli keys add <choose-a-passphrase>
   ```

<br/>
<br/>

```
Welcome to the Galaxy network .................................
```

<br/>

Read the [Getting started](/docs/getting-started.md) page for more detailed information on installing and
syncing Galaxy.

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Status

- Ability to sync Blockchain on both Linux & macOS devices.
- Ability to send Galaxy coin.

[![Galaxy Version](https://img.shields.io/badge/Galaxy-Testnet_v0.4.0--alpha-red.svg?colorA=212121&colorB=FF0000)](https://github.com/galaxypi/galaxy/releases)
[![Galaxy Chat](https://img.shields.io/badge/Galaxy_Chat-Discord-purple.svg?colorA=212121&colorB=7289da)](https://discord.gg/36K9nan)

[![CircleCI](https://circleci.com/gh/galaxypi/galaxy.svg?style=svg&circle-token=45e7031f4720e17a24978c9ee53c6340657cfac3)](https://circleci.com/gh/galaxypi/galaxy)
[![Go Version](https://img.shields.io/badge/Go-v1.10.3-blue.svg?colorA=212121&colorB=007BFF)](http://golang.org/)
[![Viper Version](https://img.shields.io/badge/Viper-v1.0.0-blue.svg?colorA=212121&colorB=007BFF)](http://github.com/spf13/viper)
[![Testify Version](https://img.shields.io/badge/Testify-v1.2.1-blue.svg?colorA=212121&colorB=007BFF)](http://github.com/stretchr/testify)
[![Go Protocol Buffers Version](https://img.shields.io/badge/ProtoBuf-v1.1.0-blue.svg?colorA=212121&colorB=007BFF)](http://github.com/golang/protobuf)
[![Tendermint Version](https://img.shields.io/badge/Tendermint-v0.22.0-red.svg?colorA=212121&colorB=FF0000)](http://github.com/tendermint/tendermint)
[![Cosmos-SDK Version](https://img.shields.io/badge/Cosmos_SDK-v0.22.0-red.svg?colorA=212121&colorB=FF0000)](http://github.com/cosmos/cosmos-sdk)
[![Cobra Version](https://img.shields.io/badge/Cobra-v0.0.1-red.svg?colorA=212121&colorB=FF0000)](http://github.com/spf13/cobra)

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Bug report

Found a bug or issue? Please first read the [issue & bug guidelines](/docs/CONTRIBUTING.md#using-the-issue-tracker)
and search for existing and closed issues. If your problem is not addressed yet, [please open a bug report](https://github.com/galaxypi/galaxy/issues/new?template=bug_report.md).

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Feature requests

Feature requests are highly encouraged. We want to hear from you on what
you'd like to see and/or how you'd like to utilize or access the Galaxy node
network.

<a href="https://github.com/galaxypi/galaxy/issues/new?template=feature_request.md">› Request a feature</a>

When submitting a feature request, take a moment to find out whether your idea
fits with the scope and aims of the project. It's up to *you* to make a strong
case to convince community members of the merits of this feature. Please
provide as much detail and context as possible, providing relevant links, prior
art, or live demos whenever possible.

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Contributing

Please read through our [contributing guidelines](/docs/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you
must include relevant unit tests. All code should conform to the [Code Guidelines](/docs/CONTRIBUTING.md#code-guidelines).

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Roadmap

View the detailed Galaxy Roadmap to see what's coming next.

[› Galaxy Roadmap page](/docs/roadmap.md)

Galaxy's mission is to become the world's largest blockchain agnostic, always on, node network and protocol offering services to decentralized platforms.

We are looking to accomplish this by executing the following;

- [ ] Building and maintaining the Galaxy blockchain and protocol.
- [ ] Designing and building beautiful modified tiny computers (Raspberry Pi) 
      as Galaxy nodes.
- [ ] Providing an exceptional API, SDK and marketplace experience that allows
      developers to easily access and build on top of the Galaxy node network. 
- [ ] A simple and easy node owner interface and incentive program to 
      incentivize node owners.
- [ ] Provide the best experience for developers to quickly deploy node 
      modules, apps and services to decentralized platforms.

View the detailed [Galaxy Roadmap page](/docs/roadmap.md) to learn more about project overview, goals, execution to date, milestones, current tech stack, and more...

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Community

Get updates on Galaxy's development and chat with the project maintainers and community members.

- Follow [@galaxypilab on Twitter](https://twitter.com/galaxypilab).
- Join the official [Galaxy Discord](https://discord.gg/36K9nan) chat room.

[› Galaxy Community page](/docs/community.md)

For more details on how to get involved in the Galaxy Community visit the [Galaxy Community page](/docs/community.md) and learn more about events, roadmap, weekly & daily scrum, past weekly community scrum calls, and more...

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## Repository maintainers

**Jacob Gadikian**, _Blockchain Engineer_
- <https://twitter.com/gadikian>
- <https://github.com/faddat>

**Guy Lepage**, _Product, Design & Development_
- <https://twitter.com/guylepage3>
- <https://github.com/guylepage3>

**Clint Nelsen**, _Operations & Marketing_
- <https://twitter.com/clintnelsen>
- <https://github.com/clintnelsen>

**Lukas Etter**, _Operations & Business Development_
- <https://twitter.com/Lukas_E>
- <https://github.com/lukasetter>

<div align="right">
    <b><a href="#galaxy">^ back to top</a></b>
</div>


## License

By contributing your code, you agree to license your contribution under the [
MIT License](LICENSE.md).

<div align="right">
  <a href="https://opensource.guide/how-to-contribute/#why-contribute-to-open-source">
    <img src="https://badges.frapsoft.com/os/v3/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/" alt="Open Source">
  </a>
</div>

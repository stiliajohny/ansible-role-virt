[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL3 License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Ask Me Anything][ask-me-anything]][personal-page]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/stiliajohny/ansible-role-virt">
    <img src="https://github.com/stiliajohny/ansible-role-virt/.assets/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">ansible-role-virt</h3>

  <p align="center">
    Install and configure virtualisation software
    <br />
    <a href="https://github.com/stiliajohny/ansible-role-virt/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/stiliajohny/ansible-role-virt/issues/new?labels=i%3A+bug&template=1-bug-report.md">Report Bug</a>
    ·
    <a href="https://github.com/stiliajohny/ansible-role-virt/issues/new?labels=i%3A+enhancement&template=2-feature-request.md">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

<!-- ABOUT THE PROJECT -->

## About The Project

This role will install all some and configure of the following software
In reagrds to docker, you lso have the option to download predevined docker images as part of the role execution

Software to be installed:

- docker
- vagrant
- k9s
- kubectl
- helm
- minikube
- lazydocker
- VirtualBox
- virt-manager

### Built With

- Ansible

---

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- Arch Based OS

### Installation

```yaml
- hosts: servers
  roles:
    - { role: ansible-role-virt }
```

---

<!-- USAGE EXAMPLES -->

## Usage

````yaml
docker_images:
  - alpine
  - amazonlinux
  etc

  users:
  - name: foo
```¬¬

---

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/stiliajohny/ansible-role-virt/raw/main/issues) for a list of proposed features (and known issues).

---

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<!-- LICENSE -->

## License

Distributed under the GPL-3.0 License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

John Stilia - stilia.johny@gmail.com

---

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Pages](https://pages.github.com)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/stiliajohny/ansible-role-virt.svg?style=for-the-badge
[contributors-url]: https://github.com/stiliajohny/ansible-role-virt/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/stiliajohny/ansible-role-virt.svg?style=for-the-badge
[forks-url]: https://github.com/stiliajohny/ansible-role-virt/network/members
[stars-shield]: https://img.shields.io/github/stars/stiliajohny/ansible-role-virt.svg?style=for-the-badge
[stars-url]: https://github.com/stiliajohny/ansible-role-virt/stargazers
[issues-shield]: https://img.shields.io/github/issues/stiliajohny/ansible-role-virt.svg?style=for-the-badge
[issues-url]: https://github.com/stiliajohny/ansible-role-virt/issues
[license-shield]: https://img.shields.io/github/license/stiliajohny/ansible-role-virt?style=for-the-badge
[license-url]: https://github.com/stiliajohny/ansible-role-virt/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/johnstilia/
[product-screenshot]: .assets/screenshot.png
[ask-me-anything]: https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg?style=for-the-badge
[personal-page]: https://github.com/stiliajohny

````

```

```

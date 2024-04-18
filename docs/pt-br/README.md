# termscp

<p align="center">
  <img src="/assets/images/termscp.svg" width="256" height="256" />
</p>

<p align="center">~ Uma transferência de arquivos de terminal rica em recursos ~</p>
<p align="center">
  <a href="https://termscp.veeso.dev" target="_blank">Pagina Web</a>
  ·
  <a href="https://termscp.veeso.dev/#get-started" target="_blank">Instalacao</a>
  ·
  <a href="https://termscp.veeso.dev/#user-manual" target="_blank">Manual do usuario</a>
</p>

<p align="center">
  <a href="https://github.com/veeso/termscp"
    ><img
      height="20"
      src="/assets/images/flags/gb.png"
      alt="English"
  /></a>
  &nbsp;
  <a
    href="/docs/de/README.md"
    ><img
      height="20"
      src="/assets/images/flags/de.png"
      alt="Deutsch"
  /></a>
  &nbsp;
  <a
    href="/docs/es/README.md"
    ><img
      height="20"
      src="/assets/images/flags/es.png"
      alt="Español"
  /></a>
  &nbsp;
  <a
    href="/docs/fr/README.md"
    ><img
      height="20"
      src="/assets/images/flags/fr.png"
      alt="Français"
  /></a>
  &nbsp;
  <a
    href="/docs/it/README.md"
    ><img
      height="20"
      src="/assets/images/flags/it.png"
      alt="Italiano"
  /></a>
  &nbsp;
  <a
    href="/docs/zh-CN/README.md"
    ><img
      height="20"
      src="/assets/images/flags/cn.png"
      alt="简体中文"
  /></a>
</p>

<p align="center">Desenvolvido por <a href="https://veeso.dev/" target="_blank">@veeso</a></p>
<p align="center">Versao atual: 0.13.0 (03/03/2024)</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT"
    ><img
      src="https://img.shields.io/badge/License-MIT-teal.svg"
      alt="License-MIT"
  /></a>
  <a href="https://github.com/veeso/termscp/stargazers"
    ><img
      src="https://img.shields.io/github/stars/veeso/termscp.svg"
      alt="Repo stars"
  /></a>
  <a href="https://crates.io/crates/termscp"
    ><img
      src="https://img.shields.io/crates/d/termscp.svg"
      alt="Downloads counter"
  /></a>
  <a href="https://crates.io/crates/termscp"
    ><img
      src="https://img.shields.io/crates/v/termscp.svg"
      alt="Latest version"
  /></a>
  <a href="https://ko-fi.com/veeso">
    <img
      src="https://img.shields.io/badge/donate-ko--fi-red"
      alt="Ko-fi"
  /></a>
</p>
<p align="center">
  <a href="https://github.com/veeso/termscp/actions"
    ><img
      src="https://github.com/veeso/termscp/workflows/Linux/badge.svg"
      alt="Linux CI"
  /></a>
  <a href="https://github.com/veeso/termscp/actions"
    ><img
      src="https://github.com/veeso/termscp/workflows/MacOS/badge.svg"
      alt="MacOS CI"
  /></a>
  <a href="https://github.com/veeso/termscp/actions"
    ><img
      src="https://github.com/veeso/termscp/workflows/Windows/badge.svg"
      alt="Windows CI"
  /></a>
  <a href="https://github.com/veeso/termscp/actions"
    ><img
      src="https://github.com/veeso/termscp/workflows/FreeBSD/badge.svg"
      alt="FreeBSD CI"
  /></a>
  <a href="https://coveralls.io/github/veeso/termscp"
    ><img
      src="https://coveralls.io/repos/github/veeso/termscp/badge.svg"
      alt="Coveralls"
  /></a>
</p>

---

## Sobre o termscp 🖥

Termscp e um gerenciador de arquivos e de transferencias rico em recursos com suporte para SCP/SFTP/FTP/S3. Basicamente, e uma interface de texto em terminal TUI para se conecttar a um servidor remoto que permite baixar e subir arquivos e para interagir com o sistema de arquivos local. Compativel com **Linux**, **MacOS**, **FreeBSD** y **Windows**.

![Explorer](/assets/images/explorer.gif)

---

## Características 🎁

- 📁  Diferentes protocolos de comunicacao
  - **SFTP**
  - **SCP**
  - **FTP** y **FTPS**
  - **S3**
  - **SMB**
  - **WebDAV**
- 🖥  Navege e use no sistema de arquivos local ou remoto com uma interface de usuario pratica.
  - Crie, apague, altera o nombe, busque, veja e edite arquivos.
- ⭐  Conecte a seus hosts favoritos e a conexoes recentes.
- 📝  Veja e edite arquivos comc suas aplicacoes favoritas.
- 💁  Autenticacao SFTP / SCP com chaves SSH ou nome de usuario / senha
- 🐧  Compativel com Linux, MacOS, FreeBSD y Windows
- 🎨  Personaliza!
  - Temas
  - Formato do navegador de arquivos personalizado.
  - Editor de texto personalizavel.
  - Classificacao de arquivos personalizavel.
  -  e muitos outros parametros ...
- 📫  Receba uma notificacao quando for transferido um arquivo grande.
- 🔭  Mantenha as alteracoes nos arquivos sincronizada com a maquina remota.
- 🔐  Guarde sua senha no gerenciador de chaves do seu sistema operacional.
- 🦀  Rust-powered
- 👀  Desenvolvido sem perder o rendimento.
- 🦄  Atualizacoes frequentes.

---

## Para comecar 🚀

Se voce esta considerando instalar termscp, quero dizer obrigado 💜! Espero que curta o termscp!
Se deseja contribuir com este projeto, nao esqueca de consultar nosso [guía de contribuicao](../../CONTRIBUTING.md).

Se voce e um usuario de Linux, FreeBSD o MacOS, este simples script de shell instalará termscp no seu sistema com somente um comando:

```sh
curl -sSLf http://get-termscp.veeso.dev | sh
```

Enquanto se for um usuario do Windows, voce pode instalar termscp com [Chocolatey](https://chocolatey.org/):

```sh
choco install termscp
```

Para obter mais informacao sobre outras plataformas, visite [termscp.veeso.dev](https://termscp.veeso.dev/termscp/#get-started) para ver todos os metodos de instalacao.

⚠️ Se estiver buscando como atualizar termscp, simplesmente execute termscp na CLI com:: `(sudo) termscp --update` ⚠️

### Requerimentos ❗

- **Linux** users:
  - libdbus-1
  - pkg-config
  - libsmbclient
- **FreeBSD** or, **NetBSD** users:
  - dbus
  - pkgconf
  - libsmbclient

### Requerimentos opcionais ✔️

Este requerimentos nao sao obrigatorio para executar termscp mas para curtir todas suas funcionalidades.

- Usuarios **Linux/FreeBSD**:
  - Para **abrir** arquivos com `V` (ao menos um destes)
    - *xdg-open*
    - *gio*
    - *gnome-open*
    - *kde-open*
- Usuarios **Linux**:
  - Um keyring manager: leia mais no [manual de usuario](man.md#linux-keyring)
- Usuarios **WSL**
  - Para **abrir** arquivos com `V` (al menos um destes)
    - [wslu](https://github.com/wslutilities/wslu)

---

## Nos apoie ☕

Se voce gostou do termscp y gostaria que o projeto cresca e melhore, considere uma pequena doacao para nos apoiar. 🥳

Voce pode fazer uma doacao em uma destas plataformas:

[![ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/veeso)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/chrisintin)

---

## Manual do usuario e documentacao 📚

O manual do usuario pode ser encontrado no [sitio web de termscp](https://termscp.veeso.dev/termscp/#user-manual) ou em [Github](man.md).

---

## Contribuir e problemas 🤝🏻

As contribuicoes, os relatos de erros, as novas funcionalidades e as perguntas sao bem-vindas! 😉
Se voce tem alguma pergunta ou duvida, se deseja propor uma nova funcionalidade ou se simplesmente deseja melhorar termscp, nao fique com duvidas e abra um novo issue ou PR.

Siga [nossas pautas de contribuicao](../../CONTRIBUTING.md)

---

## Changelog ⏳

Ver registro das alteracoes do termscp [AQUI](../../CHANGELOG.md)

---

## Powered by 💪

termscp funciona com estes projetos incriveis:

- [bytesize](https://github.com/hyunsik/bytesize)
- [crossterm](https://github.com/crossterm-rs/crossterm)
- [edit](https://github.com/milkey-mouse/edit)
- [keyring-rs](https://github.com/hwchen/keyring-rs)
- [open-rs](https://github.com/Byron/open-rs)
- [rpassword](https://github.com/conradkleinespel/rpassword)
- [rust-s3](https://github.com/durch/rust-s3)
- [self_update](https://github.com/jaemk/self_update)
- [ssh2-rs](https://github.com/alexcrichton/ssh2-rs)
- [suppaftp](https://github.com/veeso/suppaftp)
- [tui-rs](https://github.com/fdehau/tui-rs)
- [tui-realm](https://github.com/veeso/tui-realm)
- [whoami](https://github.com/libcala/whoami)
- [wildmatch](https://github.com/becheran/wildmatch)

---

## Galería 🎬

> Termscp Home

![Auth](/assets/images/auth.gif)

> Bookmarks

![Bookmarks](/assets/images/bookmarks.gif)

> Setup

![Setup](/assets/images/config.gif)

> Text editor

![TextEditor](/assets/images/text-editor.gif)

---

## Licencia 📃

termscp usa licenca MIT.

Voce pode ler a licenca completa [AQUI](../../LICENSE)

# Frappe Developer Setup (MacOS)

Quickly start developing using frappe/erpnext.

# Requirements :

- [Docker Desktop](https://docs.docker.com/desktop/install/mac-install/)
- [Node v18+](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)
- [Python v3.10+](https://github.com/pyenv/pyenv?tab=readme-ov-file#homebrew-in-macos)

```shell
$ git clone https://github.com/chaukematimu/frappe-setup.git
$ cd frappe-setup
$ script/setup
$ script/runserver
```

Creating new app :

```shell
$ script/console new-app --no-git <APP_NAME> 
```


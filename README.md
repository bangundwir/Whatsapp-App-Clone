# Whatsapp-App Desktop App

\[Unaffiliated]  Whatsapp-App as a desktop app using Tauri
![image](https://user-images.githubusercontent.com/17474376/211812541-07ec7f32-207c-4c01-a619-3463b3f8b552.png)
## How to run

```sh
yarn        # install package.json deps
yarn dev    # run debug mode
yarn rls    # build for release
yarn clean  # remove unused build files
```

### Updating .nvmrc File

```sh
node -v > .nvmrc
```

## How to Create Tauri Icons

```sh
yarn tauri icon PATH_TO_SOURCE_ICON.png
```

## Environment

- [Tauri Prerequisites](https://tauri.studio/docs/getting-started/prerequisites),
- Install [NodeJS](https://nodejs.org/en/) via [nvm](#how-to-use-nvm)
- Install `yarn` using `npm i -g yarn`
- Run `yarn` to install frontend dependencies

### How to use nvm

1. Install [`nvm`](https://github.com/nvm-sh/nvm) or [`nvm-windows`](https://github.com/coreybutler/nvm-windows/releases)
2. Open up an elevated command prompt (Windows) or use `sudo` (POSIX) for the below commands.
3. `nvm install latest` which will output a version (X.Y.Z) that was installed
4. `nvm use X.Y.Z`

## Resources

- [VS Code](https://code.visualstudio.com/) + [Tauri Extension](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer Extension](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
- [Tauri (JS)](https://tauri.studio/docs/api/js/)
- [Tauri (Rust)](https://docs.rs/tauri/)
- [React Icons](https://react-icons.github.io/react-icons)
- [Mantine Docs](https://mantine.dev/pages/basics/)
- [Mantine Default Theme](https://github.com/mantinedev/mantine/blob/master/src/mantine-styles/src/theme/default-theme.ts)
- [react-18next Trans Component](https://react.i18next.com/latest/trans-component)
- [Tauri Config](https://tauri.app/v1/api/config)


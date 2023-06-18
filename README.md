# Tauri + React

This small app should demonstrate how can existing web application be converted into desktop application using Tauri framework.
It was developed with Tauri and React in Vite.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

# How to try it

It was tested on Windows operating system.
- Use **npm install** (in a package directory, no arguments) to install the dependencies to the local node_modules folder
- Use **cargo tauri dev** to run app in development mode in local browser
- Use **cargo tauri build** to create installer in **src-tauri\target\release\bundle\msi**  and  executable in **src-tauri\target\release**
 

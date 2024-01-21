## 1.Install Bun
### 1.1 Install Bun
`curl -fsSL https://bun.sh/install | bash # for macOS, Linux, and WSL`

### 1.2 Reload zsh
`source ~/.zshrc`

### 1.3 Check bun
`bun -v`

## 2. Create project use bun and vite
### 2.1 Create project
`bun create vite YOUR_PROJECT_NAME`
### 2.2 Install
`bun install`
### 2.3 Start project
`bun run dev`

## 3. Install libs
`bun add @tanstack/react-query react-router-dom axios zustand`
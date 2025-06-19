<div align="center">
    <h1>Noob Muffin's Unblocked Games Portal!</h1>
    <img src="https://avatars.githubusercontent.com/u/82334654?v=4">
    <p>Welcome to the Noob Muffin Unblocked Games Portal—The ultimate proxy for unblocking websites, games, tools, and so much more!</p>
</div>

> [!IMPORTANT]
> If you fork this project, consider giving it a star in the original repository!

## Features

- About:Blank Cloaking
- Tab Cloaking
- Wide collection of apps & games
- Clean, Easy to use UI
- Inspect Element
- Various Themes
- Password Protection (Optional)
- Built-in Tab System
- Now.gg Support
- Fast Speeds
- Geforce NOW Support

#### Server Deployment

```bash
git clone --branch Ad-Free https://github.com/NoobBit/Noob-Muffins-Unblocked-Games-Portal
cd Noob-Muffins-Unblocked-Games-Portal
```

Next depending on your package manager, run one of the following commands:

#### Bun

If you are using Bun, run the following commands:

```bash
bun i
bun start
```

#### pnpm

If you are using pnpm, run the following commands:

```bash
pnpm i
pnpm start
```

#### npm

If you are using npm, run the following commands:

```bash
npm i
npm run start
```

### Updating

```bash
cd Noob-Muffins-Unblocked-Games-Portal
git pull --force --allow-unrelated-histories # This may overwrite your local changes
```

### GitHub Codespaces

> [!NOTE]
> If you're setting the port below 1023, then you must run `sudo PORT=1023`

1. Create a GitHub account if you haven't already.
2. Click "Code" (green button) and then "Create Codespace on main."
3. In the terminal at the bottom, paste `pnpm i && pnpm start`.
4. Respond to the application popup by clicking "Make public."
> [!IMPORTANT]
> Make sure you click the "Make public." button, or the proxy won't function properly.
5. Access the deployed website from the ports tab.
6. For subsequent uses in the same codespace, just run `pnpm start`

### Solution for if there is no popup.

1. Run `pnpm i`, and before `pnpm start`, prepend `PORT=8080`, replacing 8080 with another port. For example, `PORT=6969 pnpm start`.
2. If this does not work then you can prepend `$env:PORT=8080;`, replacing 8080 with another port. For example, `$env:PORT=6969; pnpm start`
3. Go to the ports tab, Click Forward A Port, And type the port number.
4. Right-click Visibility and set Port Visibility to Public.
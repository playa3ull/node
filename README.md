# PLAYA3ULL GAMES: Master Node

### Pull Latest Image
```bash
docker pull ghcr.io/playa3ull/node
```

### Run Image
```bash
docker run -it ghcr.io/playa3ull/node
```

Pass `-it` to run interactively, and use built-in menu features!
> [!TIP]
> You can optionally omit this if running in a headless environment

Follow on the on-screen prompts!

### Headless
In scenarios, such as headless environments where you do not have access to authenticate with your wallet, you can start the container by passing through either a license key flag, or setting the license key environment variable. This process will directly authenticate the service with the linked Master Node.

#### Argument Flag
```bash
docker run ghcr.io/playa3ull/node --license=############-####-####-####-############
```

#### Environment Variable
```bash
docker run ghcr.io/playa3ull/node -e LICENSE_KEY=############-####-####-####-############
```

Get your license key via your [Account page on the dApp](https://app.playa3ull.games/account).

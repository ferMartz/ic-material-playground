<img height=320 src="https://github.com/ferMartz/ic-material/blob/main/src/assets/ic-material-shot.png" />

# IC Material Playground

Modern dashboard playground for the Internet Computer powered by [Create IC APP](https://github.com/MioQuispe/create-ic-app), [ViteJS](https://vitejs.dev/), [ReactJS](https://reactjs.org/), & [Material UI](https://tailwindcss.com/)

## Includes :

- 4 Internet Computer examples
- Modern material-ui dashboard
- Dark theme
- Routing

## Requirements

- Install the following version of the DFINITY Canister SDK

```
DFX_VERSION=0.7.2 sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)"
```

- NodeJS >=16.0.0

## Get Started

With Git:

```
git clone https://github.com/ferMartz/ic-material.git
```

With NPM:

```
cd ic-material-playground
npm install
```

Start the backend

```
dfx start --background
dfx canister create --all
dfx build
dfx canister install --all
```

Start the frontend

```
npm run dev
```

Thats it! Play around on your local Internet Computer.

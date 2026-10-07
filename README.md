# MyApp

A mobile app built with [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/).

## Requirements

- [Node.js](https://nodejs.org/) (LTS version)
- [Git](https://git-scm.com/)
- A phone with the [Expo Go](https://expo.dev/go) app installed ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent) / [iOS](https://apps.apple.com/app/expo-go/id982107779)), or an Android emulator ([Android Studio](https://developer.android.com/studio))
- Phone and computer on the same Wi-Fi network

## Getting Started

### 1. Install Node.js (Linux Mint)

Install [nvm](https://github.com/nvm-sh/nvm) (Node Version Manager), then use it to install [Node.js](https://nodejs.org/):

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
```

Close the terminal and open it again, then run:

```bash
nvm install --lts
node -v
```

### 2. Clone the repository and install dependencies

```bash
git clone https://github.com/YOUR_USERNAME/MyApp.git
cd MyApp
npm install
```

### 3. Start the app

```bash
npx expo start
```

Scan the QR code in the terminal with **Expo Go** on your phone.

To use the Android emulator instead, press `a` in the terminal (requires Android Studio).

## Creating a New Project from Scratch

```bash
npx create-expo-app@latest MyApp
cd MyApp
npx expo start
```

## Project Structure

```
MyApp/
├── app/            # Screens and navigation
├── assets/         # Images and fonts
├── components/     # Reusable components
├── package.json    # Dependencies and scripts
└── README.md
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npx expo start` | Start the development server |
| `npm run android` | Open the app on an Android emulator or device |
| `npm run web` | Run the app in the browser |
| `npm run lint` | Check the code for issues |

## Troubleshooting

- **QR code does not connect:** make sure the phone and computer are on the same Wi-Fi network.
- **Emulator is slow or does not start:** enable virtualization (KVM) in your BIOS.
- **Stale cache or strange errors:** run `npx expo start -c` to clear the cache.

## Useful Links

| Tool | Official Website |
|------|------------------|
| React Native | https://reactnative.dev/ |
| Expo | https://expo.dev/ |
| Expo Documentation | https://docs.expo.dev/ |
| Expo Go | https://expo.dev/go |
| Node.js | https://nodejs.org/ |
| nvm | https://github.com/nvm-sh/nvm |
| Git | https://git-scm.com/ |
| Android Studio | https://developer.android.com/studio |
| GitHub | https://github.com/ |

## Contributing

1. Fork the repository
2. Create a branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push the branch: `git push origin feature/my-feature`
5. Open a Pull Request

# bw-guarded

## 🔎 Overview

`bw-guarded` is an overhead script for Bitwarden CLI that adds an extra layer of security by making the Bitwarden session guarded with root password and GPG encryption.

Inspirations from [this gist](https://gist.github.com/mietzen/f383d87c0973c1af877b39e09b50021e)

## 📥 Installation

1. Tap the custom formula repository:

    ```bash
    brew tap Drugsosos/bw-guarded
    ```

2. Install `bw-guarded`:

    ```bash
    brew install bw-guarded
    ```

3. Unlink Bitwarden CLI

    ```bash
    brew unlink bitwarden-cli
    ```

### 🔔 Optional but recommended

- Install [sudo-touchid](https://github.com/artginzburg/sudo-touchid)

## 💡 Usage Options

To initialize or regenerate session key:

```bash
bw --generate-session-key
```

For all other Bitwarden CLI commands, simply use `bw`:

```bash
bw [your-commands]
```

## 🌟 Contributing
Contributions are always welcome!\
If you have any ideas, suggestions, or bug reports, feel free to submit an issue or open a pull request.

## 📝 License
This project is licensed under the [Apache-2.0 License](/LICENSE).

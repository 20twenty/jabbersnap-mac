# Jabbersnap for Mac

Jabbersnap combines spoken words, screenshots and copied material into a
prompt you can send to an AI or paste into the app where you are working.
Use a Jabbersnap remote or your Mac's microphone and keyboard.

**[Download the latest Mac release](https://github.com/20twenty/jabbersnap-mac/releases/latest)** ·
[Windows downloads](https://github.com/20twenty/jabbersnap-windows/releases/latest) ·
[jabbersnap.com](https://jabbersnap.com)

## Install or update

1. Download **Jabbersnap-0.8.16.dmg** from the latest release.
2. Drag **Jabbersnap** to Applications, replacing the existing app if asked.
3. Open it from Applications and follow setup. Follow its instructions for
   permissions and pairing, and wait for any remote software update to finish.

The app is Developer ID signed and notarized by Apple. It requires
**macOS 15.2 or later**. Apple silicon Macs can transcribe locally after a
one-time model download; Intel Macs require a Groq API key. Transforms and
voice edit additionally require an Anthropic, Google Gemini or OpenAI API
key and screen access. Manage keys under **System › Your AI**.

Mac and Windows releases share a version number and core workflows, with
platform-specific controls and capabilities. Voice Commands and Statistics
are not available in ordinary installs.

## Find your way around

**Home** shows recent recordings; **History** keeps their words and captured
material. **Controls** configures keyboard and remote buttons.
**Behaviors › Transforms** lets you choose how each app receives dictation
and review a draft before pasting. **System › General** holds permissions,
launch-at-login, retention and data-removal controls.

With the default record key, **right ⌥**, hold to talk, or double-tap to start
and tap to finish. Change it under **Controls › Keyboard**. If you use a
remote, **Controls › Remote** shows its current button assignments.

## Reporting a problem

Open an [issue](https://github.com/20twenty/jabbersnap-mac/issues/new/choose)
with what happened, what you expected, and your macOS, app and remote
software versions. Use [discussions](https://github.com/20twenty/jabbersnap-mac/discussions)
for questions and ideas. Review any logs or screenshots before posting;
issues are public. Never include API keys or content you want to keep private.

Report security vulnerabilities through
[private vulnerability reporting](https://github.com/20twenty/jabbersnap-mac/security/advisories/new).

## Privacy and removal

Read [PRIVACY.md](PRIVACY.md) for local storage, AI requests and optional
usage statistics. Keys are stored in your login Keychain. Turn off usage
reporting under **System › General → Share anonymous usage statistics**.

Removing the app leaves its data and keys. Use **Delete Data** under
**System › General** to choose what to remove before uninstalling.

This repository holds public downloads and support. Jabbersnap's source
code is private. The product remains in development and is not yet offered
for sale; release notes describe the capabilities of each downloadable build.

# Jabbersnap privacy policy

Effective October 22, 2026. This policy covers the Jabbersnap Mac and
Windows apps and the Jabbersnap remote. Historical Windows Lite releases
have a separate policy in that repository's history.

## The short version

Recordings, transcripts, captures and drafts are stored on your computer.
Content goes to the apps where you paste it and to the AI providers you
configure, under your own API keys. Optional usage statistics report how
features are used without reporting your recorded or written content.

## Recordings, captures and AI services

- **Cloud transcription:** choosing Whisper on Groq sends recording audio
  directly to Groq under your key. This is the transcription path on Windows
  and Intel Macs.
- **Local transcription:** on supported Apple silicon Macs, Parakeet runs
  locally after its model download. Local transcription sends no audio to
  a transcription provider.
- **Transforms and spoken draft edits:** relevant text, spoken-change
  transcripts, captures and destination-window images go to the configured
  provider, Anthropic, Google Gemini or OpenAI, as the feature requires.
  Window images can contain other content visible in the destination app.
- **Pause summaries:** when enabled and configured, a recording's
  transcribed words go to the selected AI provider to summarize it.
- **Delivery:** copied or pasted output goes to the destination app or site.

Jabbersnap does not route this content through a server operated by its
makers. The providers handle requests under your accounts and their own
terms and privacy policies: [Groq](https://groq.com/privacy-policy/),
[Anthropic](https://www.anthropic.com/legal/privacy),
[Google](https://policies.google.com/privacy), and
[OpenAI](https://openai.com/policies/privacy-policy/).

API keys are stored in macOS Keychain or Windows Credential Manager and
sent to their corresponding services. The app also contacts GitHub when
you check for updates, and downloads the local transcription model on
supported Macs. Remote firmware is bundled with the app.

## Data on your computer

History can contain audio, transcripts, screenshots, copied material,
drafts and spoken changes. It is governed by the app's retention and
storage settings. Settings and local diagnostic logs are also kept on the
computer. Mac data lives under `~/Library/Application Support/Jabbersnap`;
Windows data lives under `%LOCALAPPDATA%\Jabbersnap`.

Uninstalling the app leaves its data and keys. **Delete Data** under
**System › General** lets you select what to remove. Windows and macOS can
retain their Bluetooth pairing independently of the app's stored remote.

## Anonymous usage statistics

With **Share anonymous usage statistics** enabled under **System › General**,
the app sends events to PostHog in the United States under a random install
ID. Events include app and operating-system versions, feature use, setting
choices, recording durations and counts, destination apps or sites, and
whether operations succeeded.

Events do not contain recordings, transcript text, prompt or clipboard
contents, screenshots, API keys, or user-entered names. The app does not
use session replay or screen recording for analytics.

Turn the switch off to stop usage reporting. The app sends one final
opt-out event. **Delete Data** lets you remove local usage information and
settings.

## Support

Logs, screenshots and other files are shared with the makers only when you
choose to provide them. Review them before posting: GitHub issues are
public. Never attach API keys or content you want to keep private.

Questions: [Mac issues](https://github.com/20twenty/jabbersnap-mac/issues)
or [Windows issues](https://github.com/20twenty/jabbersnap-windows/issues).
This policy is updated in place; repository history preserves prior text.

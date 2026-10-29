# MEGASTUDIO AI — Privacy Policy

*Last updated: October 29, 2026*

MEGASTUDIO AI ("the App", "we") is a Windows desktop application for AI chat, a coding agent, and image and video generation. This policy explains what data the App handles and where it goes. Publisher: **megastudioai**. Contact: **[[talbimaamoune9@gmail.com]**
## 1. Summary

- The App has no user accounts and does not require you to sign up.
- We do not run our own servers for your data, and the App contains no analytics or telemetry.
- Your data is stored on your device. It leaves your device only when you choose to use a cloud AI provider.
- We do not sell your data.

## 2. Data stored on your device

The App stores the following locally, in your Windows user profile (Local AppData):

- **Settings** (preferences, folder paths, chosen models and providers).
- **History** of your chats, prompts, and generated images and videos.
- **API keys** you enter for cloud providers. They are encrypted with Windows DPAPI and can be decrypted only by your Windows account on your device.

Generated images and videos are saved to the folders you choose (by default, subfolders named *AI_MStudio_Desk* inside your Pictures and Videos folders).

## 3. Data sent to third parties (only if you use them)

The App works with local engines and with cloud AI services. When you use a **cloud provider** that you configured with your own API key, the content of your request is sent directly from your device to that provider. This can include your text prompts, files or images you attach, and chat context. Supported providers include OpenAI, Google (Gemini), Mistral, Groq, DeepSeek, Together AI, OpenRouter, Stability AI, and Replicate.

These providers process data under **their own** terms and privacy policies, not ours. We do not receive a copy. Please review their policies before sending personal or sensitive content.

When you use **local engines** (for example Ollama, ComfyUI, LM Studio, Jan, or similar tools running on your own computer), your prompts and results stay on your machine and are not sent to the internet by the App.

## 4. Image and video generation

- Prompts and any source images you provide are sent to the engine you select: a local engine (stays on your device) or a cloud provider (sent to that provider).
- Results are saved on your device. Whether a cloud provider keeps your prompts or outputs is controlled by that provider.
- Do not upload images of other people unless you have their permission.
- You are responsible for the content you generate and how you use it. Do not use the App to create illegal content, sexual content involving minors, non-consensual or deceptive depictions of real people (deepfakes), harassment, or content that infringes others' rights.
- AI output can be inaccurate, biased, or unexpected. Review it before relying on it or publishing it.

## 5. Other network activity

The coding agent may run developer tools on your computer (such as dotnet or npm) at your request. These tools may contact public package registries such as nuget.org or npmjs.org to look up or download packages. The App also communicates with local services on your own machine (localhost) to control local AI engines.

## 6. Hardware information

The App reads system information (such as GPU and CPU usage and temperature) to show performance indicators. This information is used only inside the App and is not transmitted anywhere.

## 7. Files and permissions

The App is a full-trust desktop application. It accesses files and folders only to perform tasks you request, such as attaching a file, opening a project, or saving a generated result. It launches local programs (for example Ollama or ComfyUI) only when you ask it to.

## 8. Your choices and control

- Delete history entries inside the App at any time.
- Remove or replace your API keys in Settings.
- Delete generated files from your Pictures and Videos folders.
- Uninstalling the App removes its settings and history. Files you saved to your own folders remain until you delete them.
- Data sent to a cloud provider must be deleted through that provider.

## 9. Children

The App is not directed to children under 13 and is not intended for them. Because it can generate AI images and video, we recommend an appropriate age rating and adult supervision for younger users.

## 10. Security

API keys are encrypted at rest using Windows DPAPI, and communication with cloud providers uses HTTPS. No method of storage or transmission is completely secure, so please protect your Windows account and your API keys.

## 11. Changes to this policy

We may update this policy. The "Last updated" date will change, and significant changes will be noted in the App's Store listing or release notes.

## 12. Contact

Questions or requests: **[[talbimaamoune9@gmail.com](mailto:your-email@example.com)]**

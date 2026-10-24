# Install and start using PM Interview Copilot

**Release qualification is still in progress. No installer is published here yet.** This guide is for the upcoming personal BYOK desktop edition. Wait for a qualified release; the older prod-v1.8.2 app is a different edition.

## 1. Get access

For complimentary access, tell the owner which email you will use. They grant access to that email and send you the download link. You do not need a gift code, GitHub account, private repository invitation or source code.

Use your own account. Verify the same email that received access. A gift covers the app license; it does not pay your AI or transcription provider bills.

## 2. Download and install

When available, open [Releases](https://github.com/Iamsimpojack/offerpilot-byok-releases/releases) or the owner's hosted app download page. Read that release's tested platforms and setup notes.

- **Windows x64:** download and run the signed setup EXE.
- **Apple-silicon Mac:** download the DMG, open it and move the app into Applications. The release targets M-series Macs on macOS 13 or newer.
- Intel Mac and Linux are not currently qualified release targets.

If the signature or publisher cannot be verified, ask the owner for the qualified installer. Do not disable operating-system protections.

## 3. Sign in and activate

Sign in with your own verified email. If complimentary access is not recognized, open **License options → Refresh license**. Check the exact email with the owner before creating another account or paying.

Purchases are not open yet. Complimentary access uses the same installer as a personal paid license.

## 4. Add your provider keys

Open **API Keys** and follow the field labels:

- **Anthropic:** required for AI answers in this candidate.
- **Deepgram:** required for streaming voice transcription.
- **OpenAI:** optional/recommended for features using fallback transcription or text-to-speech.

Create keys in your own provider accounts and enable the API billing those providers require. A ChatGPT or Claude chat subscription is separate from API usage. Use each key's **Test** action, save, and restart if prompted. Set usage budgets with your providers.

Keys stay in desktop secure storage. Never send them to the owner, paste them into story notes, or include them in screenshots.

## 5. Try your first session

1. Select a role and add your resume, target job and a few story notes in My stories & materials.
2. Wait for the save/parse result. Review story drafts before confirming personal facts.
3. Try one behavioral practice question and a follow-up.
4. For voice, finish Live preflight and grant the requested microphone/system-audio permissions. Check the transcript before relying on generated answers.
5. Stop the session, reopen the app and check your saved materials under the same account and role.

Continue with the [user guide](USER_GUIDE.md) for story selection, expanded practice examples, case frameworks, Live and saved data.

## Troubleshooting

| Problem | What to check |
| --- | --- |
| No installer available | Release qualification/publication is not complete. |
| Access not found | Verified email matches the gift; ask the owner to check the grant, then Refresh license. |
| Key test fails | Correct provider, valid key, API billing and quota. |
| No audio | Selected source, operating-system permissions and Live preflight. |
| Materials seem missing | Same signed-in account and selected role; check the last save result. |
| Moving to another computer | Sign in again and add your own keys; local drafts/preferences do not necessarily sync. |

Account materials and saved stories use hosted Supabase services; the app is not local-only. Provider keys and some drafts/preferences are local.

For help, email **PMinterviewcopilot@gmail.com** with your version, operating system, error text and reproduction steps. Redact keys, credentials and private interview content.

> This guide describes the upcoming consolidated desktop release. No installer is published in this repository yet; older builds may differ.

# Using PM Interview Copilot

For installation, complimentary access and API keys, start with [the friend setup guide](SETUP.md). You do not need the source code or developer tools to use a published desktop installer.

## Your first session

1. Sign in and choose the role you are preparing for. Add the target job and company so answers use the right context.
2. Open **My stories & materials** and upload or paste your resume, job description and preparation notes. Give each material its correct purpose. Wait for the save/parse result; an original file can be saved even when readable text could not be extracted.
3. Organize personal notes into story drafts when useful. Review the extracted facts before confirming a story. Uploading and confirming a structured story are separate actions; original notes can still inform practice.
4. For an incomplete story, use **Add this detail** to answer a focused question, **Skip for now**, or **See expanded example**. Suggested example details are not automatically added to your confirmed story.
5. Choose a behavioral practice question, such as “Tell me about a time you disagreed with a stakeholder.” Read the example, answer in your own words, and try a follow-up.
6. Review the feedback and improve your answer or source story. Saving an answer draft and confirming personal facts are different actions.

## Behavioral examples and case frameworks

**Behavioral questions** ask about an experience: conflict, leadership, failure, execution or a technical retrospective. They receive a complete spoken example, not a sequence of case sections. Auto selects one primary experience based on relevant supplied evidence and useful detail; it does not randomly rotate stories.

Sparse inputs can produce an **Expanded practice example—includes suggested details**. The example can include plausible fictional details to demonstrate a strong response. Those details are practice scenario content, not proof of what happened in your career. Correct the example when needed and use your actual experience when describing your history.

Follow-ups continue the same scenario. Changing stories starts a different example; a correction should update the dependent explanation. Review checks reduce contradictions, but generated answers still need your judgment. Preparation/review can take time; errors remain retryable.

Open the answer's source disclosure to inspect available citations and the story-selection explanation. When eligible alternatives are available, choose a story and select **Regenerate with this story**. Changing the selector alone does not generate a new answer. If nothing matches, the app can give a labeled fictional example rather than pretend an unrelated story is a good match.

**Case questions** ask you to work through a problem: product design, metrics, estimation, strategy and similar exercises. The selected framework can guide progressive sections. Edit a framework's prompts in Frameworks to change how those sections are generated, then test the framework before a session.

## Live desktop flow

1. Open Live setup and choose the intended role, interview context and answer approach. **Auto** detects the question type; an explicit selection steers the approach.
2. Complete preflight: confirm API keys, input/audio source and requested operating-system permissions. Do a short rehearsal so you know what the app is capturing.
3. Start the session and check the transcript and detected question. Correct the question if it misunderstood the ask; the next generation should use that correction.
4. Read the current answer and continue with follow-ups. Behavioral examples stay complete; cases use their configured sections. Use source/story controls when the selected experience is wrong.
5. Stop the session deliberately. Review saved interview history and feedback. If generation fails, retry without assuming partial text is a finished answer.

Take-home mode uses the saved assignment/submission as its discussion context. It remains separate from the expanded behavioral example flow.

## What is saved where

- Account-linked roles, materials and saved stories use Supabase; original uploaded files use private storage.
- Some answer drafts, preferences and recovery state are local to the device/browser profile. Read the save indicator before closing a draft with an error.
- Provider keys use desktop secure storage. Add your own keys on each computer; never paste them into story notes or share them with another person.
- BYOK covers your provider choice/usage, not offline-only data storage. Hosted sign-in, saved-data and license services are still required.

## If something goes wrong

Check the visible error, current account/role, key tests and internet connection. Keep saved work open when a save failed. For support, record the app version, operating system, feature, error text and steps to reproduce; redact keys, credentials and private interview content. A useful report is “Windows, version X, uploading a PDF in Materials returned this error,” not a screenshot of your API key.

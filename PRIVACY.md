# Privacy Policy — BabelDOC 云端 PDF 翻译

**Publisher:** Shoujie Chen  
**Effective date:** October 25, 2026 (UTC).

## Scope and information processed

BabelDOC 云端 PDF 翻译 (`babeldoc-cloud`) is a community PDF translation workflow for ChatGPT Work. To perform a translation, the workflow processes the PDF you supply, extracted text and layout information, translation prompts and responses, glossaries, language and page selections, and generated output files. Documents may contain personal information. Job records also contain filenames, hashes, identifiers, timestamps, processing status, and diagnostic information. Provide only material necessary for your task, and do not upload credentials or restricted personal information.

These data are used to parse and translate documents, reconstruct layout, validate results, diagnose failures, and resume interrupted work. In the default conversation mode, translation is performed through the current ChatGPT Work conversation and files are processed in its task sandbox. The current workflow does not configure a publisher-operated document-upload or analytics endpoint. This is not a claim that the hosting platform or every third-party dependency performs no logging.

## Recipients and external connections

ChatGPT Work and its execution environment process the conversation and task files under the platform's own terms, settings, and privacy practices. This policy does not replace those practices or make promises about platform training, retention, or deletion.

Initial setup may contact package repositories and upstream font or layout-model hosts, including PyPI, GitHub, Hugging Face, or ModelScope and their configured mirrors. These services may receive ordinary download-request and network information. The setup workflow downloads resources; it is not designed to upload your PDF to those resource hosts.

If you explicitly choose the optional OpenAI-compatible API mode, document text, translation prompts, and related context are sent to your selected API provider for translation. That provider's policies and charges apply. The workflow reads an existing credential from an environment variable; do not paste credentials into chat, documents, Issues, or checkpoint files. The default conversation mode does not need a translation API credential.

## Storage, retention, and your controls

Task files, cached layout, job databases, translation requests and results, output PDFs, and diagnostic logs are stored in the task environment. There is no plugin-defined automatic deletion timer: files remain until they are removed or the host removes the environment, subject to host controls and retention practices. Stopping or cancelling a job does not itself delete its files. The publisher does not control the hosting platform's retention schedule.

Exported checkpoint ZIPs include the original PDF, submitted translations, glossary content, and job settings. Downloaded PDFs and checkpoints remain wherever you save or share them until you remove them, subject to that location's own retention and backups. Treat them as confidential when they contain confidential material. You can avoid optional API mode, limit the pages and documents supplied, stop processing, remove files where the environment permits, and use the hosting platform's controls for conversations and uploads. Deleting one copy does not necessarily delete other copies or provider records.

## Support and public disclosures

Support is provided through [GitHub Issues](https://github.com/Clair-ChenShoujie/Babeldoc4GPT/issues). Issues and attachments are public. Your GitHub profile, message, and any details you submit may be visible to the publisher and other people. Use minimal, redacted or synthetic examples; do not post private PDFs, checkpoint ZIPs, credentials, or sensitive logs. GitHub controls hosting and retention of its records. Public content may be copied by others even after you edit or remove it.

The publisher does not proactively collect users’ private information through this plugin and does not ask users to submit sensitive source documents, logs, or credentials through Issues. This does not prevent the publisher from seeing information you voluntarily post publicly. No separate publisher-operated document collection service is configured in the default workflow. No fixed publisher retention period for voluntarily submitted public Issues is promised here; GitHub controls the hosting and retention of those records. If support practices change to include collecting or retaining private files outside GitHub, this policy must be updated to describe those practices before they begin.

For a non-sensitive question about this policy, open an Issue without including the private data concerned. If a private channel is needed, request one without posting the data publicly; no private support channel is currently specified.

## Changes

Updates to these practices will be reflected in the published policy. The effective date above identifies this version.

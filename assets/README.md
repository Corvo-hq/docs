# Documentation visuals

## Screenshots

The WebP screenshots below are crops from the Corvo v0.2.0 product recordings captured on 2026-10-11. The originals are maintained in the Corvo repository under `tools/corvo-demo-video/footage/v0-2-0/raw/`; they are not bundled with the public docs.

The screenshots retain the real interface, button labels, and connection states. Solid masks hide binding credentials, project identifiers, repository names, and private example content. Captions describe the masks. English interface labels are shared by both documentation languages; captions and alt text are localized.

| Asset | Recording | Position | Crop or redaction |
| --- | --- | --- | --- |
| `telegram-start.webp` | `c4-discord-bind.mp4` | 00:01.3 | Telegram card before connection |
| `telegram-chat-connected.webp` | `c4-tg-bind.mp4` | 00:02.1 | Agent bot connected; alerts button visible |
| `telegram-notify-dialog.webp` | `c4-tg-bind.mp4` | 00:10.3 | Notify bot dialog; QR code and binding token hidden |
| `telegram-connected.webp` | `c4-tg-bind.mp4` | 00:41.2 | Both connection badges |
| `telegram-alert.webp` | `c4-tg-notify.mp4` | 00:18.5 | Alert message; project ID and service URL hidden |
| `discord-binding.webp` | `c4-discord-bind.mp4` | 00:19.3 | Server/channel selection; server name hidden |
| `discord-bound.webp` | `c4-discord-bind.mp4` | 00:30.3 | Saved connection; destination identifiers hidden |
| `discord-conversation.webp` | `c4-discord-notify.mp4` | 04:45.0 | Mention and the agent's initial work; no claim of a completed answer |
| `gcp-api-console.webp` | `c4-gcp-wizard.mp4` | 00:04.7 | API links; project ID hidden |
| `gcp-api-script.webp` | `c4-gcp-wizard.mp4` | 00:09.5 | Equivalent gcloud command; project ID hidden |
| `gcp-service-account.webp` | `c4-gcp-wizard.mp4` | 00:14.2 | Account creation; project ID hidden |
| `agent-environment.webp` | `c4-agent-env.mp4` | 00:14.0 | Repository setup and READY status; repository names hidden |
| `agent-instructions.webp` | `c1-instructions.mp4` | 00:19.7 | Custom instructions editor |
| `agent-skill-dialog.webp` | `c1-skills.mp4` | 00:24.3 | Completed custom skill form before Add |
| `agent-mcp-dialog.webp` | `c1-mcp.mp4` | 00:11.0 | Name, URL, and authentication choices |
| `report-schedule.webp` | `c1-settings.mp4` | 00:18.9 | Timezone and scheduled push controls |
| `report-detail.webp` | `c1-daily-push.mp4` | 03:28.0 | Summary and first error group; service hostname hidden |
| `workspace-invite.webp` | `c2-members.mp4` | 00:04.0 | Invite form; member list excluded |
| `investigation-alerts.webp` | `c3-investigation.mp4` | 01:50.4 | Alert entries and detail sections; service URL hidden |
| `memory-review.webp` | `c3-memory.mp4` | 00:07.2 | Review controls and pending proposal; fact content hidden |

`investigations.png` and `gcp-sources.png` come from the same recording set and were introduced in the first docs refresh. `reports-list.png` is an existing capture retained because its Report history layout and controls still match the product; its date and data are examples. The previous report detail and cropped Memory PNGs have been replaced by the WebP captures above.

## Diagrams

Each SVG has an English version and a Traditional Chinese `-zh` version, with accessible titles and descriptions. They are editable diagrams, not product screenshots.

| Pair | Purpose |
| --- | --- |
| `investigation-pipeline` | Shows alerts joining investigations by likely cause, including a later recurrence. |
| `gcp-architecture` | Separates outbound log delivery from investigation read access across the project boundary. |
| `gcp-iam` | Shows the different principals and scopes of the two IAM grants. |
| `telegram-bots` | Distinguishes Agent bot conversations from Notify bot updates and web links. |
| `discord-conversations` | Distinguishes channel mentions from investigation threads opened by alert replies. |
| `agent-access` | Separates repository access, environment preparation, and permitted Git/GitHub actions. |

Use white, ink, gray, and one blue accent. Keep connectors meaningful and labels readable at the documentation column width. Preview both languages after changing a diagram; translating text can change its width.

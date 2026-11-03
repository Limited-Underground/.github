# Limited Underground

Limited Underground builds practical hardware and software for independent, offline, and field use.

## Limited Underground Trail ecosystem

Product development in the Limited Underground Trail ecosystem is paused indefinitely while source preservation, documentation, and recovery validation continue. The descriptions below distinguish demonstrated work from planned capabilities and acceptance that remains open.

- **[Limited Underground Trail (Firmware)](https://github.com/Limited-Underground/Trail)** — open-source, offline-first ESP32, LoRa, and BLE communications firmware. A two-phone, two-Heltec bidirectional diagnostic exchange over unauthenticated diagnostic radio frames has been demonstrated; authenticated production messaging and V1 acceptance remain unfinished.
- **[Limited Underground Trail Android App](https://github.com/Limited-Underground/Trail/tree/main/android)** — the Android companion whose source lives in the Trail repository. It participated in that bounded diagnostic exchange; production messaging acceptance remains open. A separate public source repository is not currently established; iPhone support is a future possibility.
- **[Limited Underground Trail Repeater](https://github.com/Limited-Underground/Trail/blob/main/docs/PRODUCT_BOUNDARIES_V0.md)** — the intended radio-relay role, with host-tested components and limited target-build evidence. Field and physical relay acceptance remain open. [Trail source and status](https://github.com/Limited-Underground/Trail).
- **[Limited Underground Trail Tracker](https://github.com/Limited-Underground/Trail)** — the portable location and telemetry role, with target-neutral GNSS host components. A complete Tracker image, board qualification, power/privacy policies, and physical acceptance remain open. [Trail source and planning](https://github.com/Limited-Underground/Trail).
- **[Limited Underground Trail Console](https://github.com/Limited-Underground/Trail/blob/main/docs/PRODUCT_BOUNDARIES_V0.md)** — the planned standalone touchscreen LoRa field interface. Host UI and simulation work exist; target hardware and complete on-device acceptance remain open. [Trail source and planning](https://github.com/Limited-Underground/Trail).
- **[Limited Underground Trail Gateway](https://github.com/Limited-Underground/Trail-Server-Progress)** — experimental bridge components between field communications and optional local/server services. A selected live source, complete deployable image, target hardware, and physical interoperability acceptance remain unresolved. See [Trail](https://github.com/Limited-Underground/Trail) and [public Server progress](https://github.com/Limited-Underground/Trail-Server-Progress).
- **[Limited Underground Trail Server](https://github.com/Limited-Underground/Trail-Server-Progress)** — the privately developed optional server. [Public milestones](https://github.com/Limited-Underground/Trail-Server-Progress) report progress without distributing the private Server source. Deployment and operational recovery acceptance remain open.
- **[Limited Underground Firmware Loader](https://github.com/Limited-Underground/Firmware-Loader)** — a Windows .NET 10 inspection-only preview. It checks local candidate structure, image length/SHA-256, and signature presence. It does not authenticate signed releases, access devices, or install firmware.

## Other hardware and field systems

- [Limited Underground Display](https://github.com/Limited-Underground/Display) — a separate open-source ESP32 display and vehicle-data project. Its implementation and hardware acceptance are distinct from Limited Underground Trail Console.

## Desktop software and utilities

- **[Husky Performance by Limited Underground](https://github.com/Limited-Underground/Husky-Performance-Releases)** — Windows automotive diagnostics and analysis software. [Public demonstration releases](https://github.com/Limited-Underground/Husky-Performance-Releases). Published downloads do not establish production acceptance.
- **[Limited Underground Business™](https://github.com/Limited-Underground/Small-Business-Suite-Releases/releases/tag/v1.0.0)** — Free, offline-first Windows software for small businesses. [Full version 1.0 release and downloads](https://github.com/Limited-Underground/Small-Business-Suite-Releases/releases/tag/v1.0.0). Historical source recovery and release lineage remain separately qualified.
- **[TrackMyClicks](https://github.com/Limited-Underground/TrackMyClicks)** — an experimental Windows desktop activity-tracking and personal-achievement application. Public source is available; a current public executable release is not established.
- **[File Organizer](https://github.com/Limited-Underground/File-Organizer)** — a planned open-source file-management application. The published repository contains a planning foundation, without a functional release.
- **[Protocol Latency Analyzer](https://github.com/Limited-Underground/ProtocolLatencyAnalyzer)** — Windows network/protocol analysis tooling. Host-tested foundation work does not establish complete live protocol measurement acceptance.

Project details and current public status are available at [limitedunderground.com](https://limitedunderground.com).

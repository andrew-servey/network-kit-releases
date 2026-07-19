# Network Kit Beta 12

Network Kit is a local-first macOS workspace for building relationships and turning them into useful action. It keeps people, companies, outreach, meetings, opportunities, resumes, cover letters, reusable facts, goals, events, and follow-through connected without requiring an online account.

## Latest Download

- Release: [Network Kit Beta 12](https://github.com/andrew-servey/network-kit-beta/releases/tag/v0.3.0-beta.12)
- macOS ZIP: [Network.Kit.Beta.12.macOS.zip](https://github.com/andrew-servey/network-kit-beta/releases/download/v0.3.0-beta.12/Network.Kit.Beta.12.macOS.zip)
- SHA-256: `c781ac71f26fc1bd9841b6aca58cf3b2dd9582cdc62f6c3c677f92c4e4dec3ad`
- Architecture: Apple silicon (`arm64`)
- Signing: ad-hoc signed; not Apple-notarized

## Product Capabilities

- People and Company workspaces for relationship context and history.
- Engage workspaces for preparing Email, Text, LinkedIn, and Meeting outreach.
- Opportunity workspaces for Jobs, Internships, Scholarships, and other pursuits.
- Resume, Cover Letter, and Template editing with live PDF output.
- Events, reusable Facts, Goals, Upcoming commitments, and a justified Action Queue.
- Archive and recoverable Trash.
- Portable, review-based AI handoff without requiring an in-app AI subscription.
- Local data ownership with explicit import and export.

## Local-First Privacy and Data Ownership

Network Kit stores its working data locally on your Mac and does not require a Network Kit account. Your data enters or leaves the app only through the actions you choose, including explicit import and export.

## Opening on macOS

1. Download and unzip `Network.Kit.Beta.12.macOS.zip`.
2. Move `Network Kit Beta 12.app` to Applications.
3. On first launch, Control-click the app and choose **Open**, then confirm **Open**.

If macOS still blocks the app after that, use this fallback in Terminal:

```sh
xattr -dr com.apple.quarantine "/Applications/Network Kit Beta 12.app"
```

## Backups and Portable Data

Use **Settings → Data** to export a portable `network-kit-data.json` backup. Keep a current backup, especially while using a beta build, and import it explicitly when moving your workspace to another installation.

## Beta Software Expectations

Network Kit Beta 12 is functional beta software, so rough edges may remain. Use **Command–Option–I** to create a developer bug capture; the app saves captures to your `Downloads/developer-bug-captures` folder.

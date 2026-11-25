# work-hub-desktop

The desktop app of [work-hub](https://github.com/SrZafkiell/work-hub): one place for your
work and your personal projects, with tasks, meetings, notes and calendars kept in
separate workspaces.

> Status: planned, not started. The web app comes first. This repository gets its plan
> file and its issues when the desktop module is next; see
> [later modules](https://github.com/SrZafkiell/work-hub/blob/main/docs/PLAN.md#later-modules).

## What will live here

- A desktop shell around the web app: a tray icon, a global shortcut for quick add and
  native notifications.
- A local store that syncs with your account, so the app keeps working offline. The API
  already follows the conventions this needs: IDs that a client can generate, version
  counters and tombstones.
- Later, local recording and transcription for meeting notes, off by default and only
  with every attendee's consent.

## What lives elsewhere

- The API, the worker and the contract:
  [work-hub-backend](https://github.com/SrZafkiell/work-hub-backend).
- The web app: [work-hub-frontend](https://github.com/SrZafkiell/work-hub-frontend).
- The plan, the server setup, the deploy agent and the release manifests:
  [work-hub](https://github.com/SrZafkiell/work-hub).

## License

Apache-2.0. See [LICENSE](LICENSE).

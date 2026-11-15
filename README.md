# Network rule assets

Public, credential-free routing rule snapshots for Surge, mihomo and Shadowrocket.

- Public rule source: [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR), CC BY-SA 4.0.
- Modified: selected lists are normalized, device-specific process rules removed, and personal domain routing exceptions placed first.
- Personal routing domains are published with owner permission. Source comments, proxy nodes, credentials, subscription links and local chains are not published.
- `versions/<release>/` is immutable. Historical versions are retained for existing clients.
- `latest.json` lists the current snapshot and file checksums.
- `shadowrocket-core.conf` is a node-free rules/DNS base. Keep manual settings in a local extended profile.
- Public data and personal domain rules in this repository are licensed under CC BY-SA 4.0; see LICENSE.

Updates are built and checked in a separate private source repository, on source changes and a daily GitHub Actions schedule. A failed build does not replace the last successful version. Scheduled starts can be delayed by GitHub.

Surge and mihomo profiles reference versioned files here. Their managed profile must refresh to adopt a new snapshot, keeping traffic and DNS classifications together. Refreshing an old version URL does not advance it to the newest version.

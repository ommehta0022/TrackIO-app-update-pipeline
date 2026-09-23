# TrackIO Android OTA Distribution

This public repository stores only signed web-update manifests, immutable release archives, checksums, and public verification keys needed by the TrackIO Android app.

The editable frontend, native app source, build workflows, signing keys, and developer credentials are maintained in restricted private repositories. APKs verify manifest signatures and archive hashes before installation.

Distributed frontend code is inherently inspectable by users. No server-side secrets or credentials belong in Android packages or this repository.

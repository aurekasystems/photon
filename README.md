# Photon

Sovereign photo and video management, hosted in Europe.

Photon is the foundation of [aureka.photos](https://aureka.photos), a service by [Aureka Systems e.U.](https://aureka.at) (Austria).

> [!NOTE]
> Photon is a fork of [Immich](https://github.com/immich-app/immich), an excellent open-source,
> self-hosted photo and video management solution. Photon is **not affiliated with or endorsed by
> the Immich project**. For the original documentation, see the
> [Immich README](https://github.com/immich-app/immich#readme) and [docs.immich.app](https://docs.immich.app).
>
> If you want to run Immich yourself, please use the upstream project and consider
> [supporting it](https://docs.immich.app/overview/support-the-project).

## Project Status

> [!WARNING]
> Photon is at an early stage (alpha). It is not yet intended for production data.

## Differences from Immich

There are no functional changes yet. Changes made in this fork will be listed here.

## Development

Until Photon diverges from upstream, development follows the
[Immich developer documentation](https://docs.immich.app/developer/setup).

## Upstream Synchronization

Photon stays as close to upstream as possible and keeps its own changes minimal.

- The `upstream` remote points to [immich-app/immich](https://github.com/immich-app/immich) (fetch only).
- Photon follows upstream [release tags](https://github.com/immich-app/immich/releases), not upstream `main`.
- New releases are merged (not rebased) into `main` to preserve history.

```bash
git fetch upstream --tags
git merge vX.Y.Z
```

Fixes that are useful beyond Photon are offered back to [Immich](https://github.com/immich-app/immich) where possible.

## Security

Please report vulnerabilities in Photon privately via
[GitHub private vulnerability reporting](https://github.com/aurekasystems/photon/security/advisories/new).
Vulnerabilities in the upstream Immich code should be reported to the
[Immich project](https://github.com/immich-app/immich/security) directly.

## License

Photon is licensed under the [GNU Affero General Public License v3.0](LICENSE), like [Immich](https://github.com/immich-app/immich).
Copyright of the original code remains with the [Immich authors](https://github.com/immich-app/immich/graphs/contributors);
modifications are copyright [Aureka Systems e.U.](https://aureka.at)

In accordance with the AGPL, the source code of the Photon version running on
[aureka.photos](https://aureka.photos) is available in this repository.

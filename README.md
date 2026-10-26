# tooling-gofannon-fork

A GitHub fork of [The-AI-Alliance/gofannon](https://github.com/The-AI-Alliance/gofannon),
used only to open pull requests upstream.

**This is not a fork of `apache/tooling-gofannon`,** despite the name. Tooling's
working repository is
[apache/tooling-gofannon](https://github.com/apache/tooling-gofannon); this one
exists because a pull request to upstream has to come from a repository in
upstream's fork network.

## Branches

| Branch | Contents |
|---|---|
| `asf` (default) | This README, `.asf.yaml`, `LICENSE`, and the sync workflow. ASF metadata only — no project code. |
| `main` | An exact mirror of upstream's `main`, fast-forwarded daily by a workflow. Never committed to directly. |
| everything else | Contribution branches, each cut from `main` and carrying one squashed commit. Deleted once merged. |

The default branch is `asf` rather than `main` so that ASF metadata can live in
the repository without `main` diverging from upstream. A single commit on `main`
would break the daily fast-forward.

## Contributing

File issues and pull requests against
[upstream](https://github.com/The-AI-Alliance/gofannon) or
[apache/tooling-gofannon](https://github.com/apache/tooling-gofannon). Nothing
is developed here.

## Licence

Apache-2.0, as upstream.

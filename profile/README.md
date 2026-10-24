<p align="center"><img src="https://raw.githubusercontent.com/celestia-island/.github/refs/heads/main/profile/logo.png" /></p>

<h1 align="center">Celestia Project</h1>

<p align="center"><strong>The closed loop: discover → install → authenticate → deploy a model → chat and run agents → industrial control → verify and support.</strong></p>

## Start here

| Where | What |
| --- | --- |
| [docs.celestia.world](https://docs.celestia.world) | The ecosystem hub — philosophy, the project map, getting started |
| [dev.celestia.world](https://dev.celestia.world) | Developer portal |
| [e.celestia.world](https://e.celestia.world) | Public landing page |
| [celestia-devtools](https://github.com/celestia-island/celestia-devtools) | Shared toolchain: commit/PR gates, version checks, local `gate`, release notes |

## The layers

Work flows **one way**: services consume the platform, the platform consumes the auth primitives.

| Layer | Repositories |
| --- | --- |
| **L0 — auth primitives** | [kirino](https://github.com/celestia-island/kirino) |
| **L1 — platform** | [plana](https://github.com/celestia-island/plana), [provider-registry](https://github.com/celestia-island/provider-registry), [akivili](https://github.com/celestia-island/akivili) (plugin SDK) |
| **L2 — UI** | [hikari](https://github.com/celestia-island/hikari), [tairitsu](https://github.com/celestia-island/tairitsu) (WASM component framework) |
| **L3 — services** | [arona](https://github.com/celestia-island/arona), [shittim-chest](https://github.com/celestia-island/shittim-chest), [entelecheia](https://github.com/celestia-island/entelecheia), [evernight](https://github.com/celestia-island/evernight), [malkuth](https://github.com/celestia-island/malkuth) |
| **Edge & tooling** | [hare](https://github.com/celestia-island/hare) (no_std protocol core), [noa](https://github.com/celestia-island/noa), [shun](https://github.com/celestia-island/shun), [aoba](https://github.com/celestia-island/aoba), [official-plugins](https://github.com/celestia-island/official-plugins), [celestia-integration](https://github.com/celestia-island/celestia-integration) |

The complete inventory, including the frozen and peripheral libraries, lives on the
[Projects Map](https://docs.celestia.world/ecosystem/projects).

## Contributing

Every repository follows the same shape: `master` is production and only advances through
squash-merged pull requests, commit and PR titles start with a gitmoji, and no changelog is
maintained — the merged PRs are the changelog. See
[CONTRIBUTING](https://github.com/celestia-island/.github/blob/main/CONTRIBUTING.md) and
[SECURITY](https://github.com/celestia-island/.github/blob/main/SECURITY.md).

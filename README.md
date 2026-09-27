# Hi, I'm Chuanye Gao 👋

Python/Go backend developer. I contribute to open-source projects, mostly bug fixes.

## Open Source Contributions

### Merged

| Project | PR | Impact |
| --- | --- | --- |
| [prometheus/prometheus](https://github.com/prometheus/prometheus) | [#17795](https://github.com/prometheus/prometheus/pull/17795) | The `/-/ready` endpoint did not return the `X-Prometheus-Stopping` header while the instance was shutting down, so orchestrators and load balancers could not tell that it was stopping. Fixed the header and added tests. |
| [etcd-io/etcd](https://github.com/etcd-io/etcd) | [#20836](https://github.com/etcd-io/etcd/pull/20836) | Fixed a broken TestGrid badge link in `CONTRIBUTING.md`. |

### In review

| Project | PR | Impact |
| --- | --- | --- |
| [gin-gonic/gin](https://github.com/gin-gonic/gin) | [#4858](https://github.com/gin-gonic/gin/pull/4858) | Form binding left `map` fields modified when binding failed with the `jsoniter` build tag, while `encoding/json` left them untouched — the same request behaved differently depending on how the binary was built. Also added the missing `jsoniter` CI coverage that had been hiding this. |

## All my merged pull requests

[`is:pr author:chuanye-gao is:merged`](https://github.com/pulls?q=is%3Apr+author%3Achuanye-gao+is%3Amerged)

## Contact

- GitHub: [@chuanye-gao](https://github.com/chuanye-gao)

# Hi, I'm Chuanye Gao 👋

**Backend engineer (Python/Go). I fix subtle bugs in distributed systems — and I write and teach about what I learn.**

I'm drawn to the unglamorous parts of software: graceful shutdown, build-tag
consistency, error paths that quietly mutate state. That's where most
production incidents are born.

---

## Open Source

### Merged

| Project | PR | Impact |
| --- | --- | --- |
| **prometheus/prometheus** | [#17795](https://github.com/prometheus/prometheus/pull/17795) | `/-/ready` did not return `X-Prometheus-Stopping` during shutdown, so orchestrators and load balancers couldn't tell the instance was stopping. Fixed the header and added tests. |
| **etcd-io/etcd** | [#20836](https://github.com/etcd-io/etcd/pull/20836) | Fixed a broken TestGrid badge link in `CONTRIBUTING.md`. |

### In review

| Project | PR | Impact |
| --- | --- | --- |
| **gin-gonic/gin** | [#4858](https://github.com/gin-gonic/gin/pull/4858) | With the `jsoniter` build tag, failed form binding left `map` fields modified, while `encoding/json` left them untouched — the same request behaved differently depending on how the binary was built. Also added the missing `jsoniter` CI coverage that had been hiding it. |

[All merged pull requests →](https://github.com/pulls?q=is%3Apr+author%3Achuanye-gao+is%3Amerged)

---

## Writing & Teaching

- **[It Had Been Working Fine](https://dev.to/minghua_gao_78064e1d18655/it-had-been-working-fine-575c)** — a postmortem about process, testing, and one missing `AUTO_INCREMENT`. *(dev.to)*
- **CSDN** — [79 posts](https://blog.csdn.net/m0_53932372) on backend, cloud, and security fundamentals; 78k+ reads.
- **Bilibili** — [a 9-part, 3-hour video course](https://space.bilibili.com/476688832) on Linux and security fundamentals for beginners (in Chinese).
- **[pwn.college writeups](https://github.com/chuanye-gao/pwn.college-writeups)** — 27+ solved challenges, written as step-by-step teaching notes.

---

## Now

- Preparing for IELTS.
- Looking for backend / cloud / developer-education roles in Europe.

---

## Contact

- GitHub: [@chuanye-gao](https://github.com/chuanye-gao)
- dev.to: [@minghua_gao](https://dev.to/minghua_gao_78064e1d18655)

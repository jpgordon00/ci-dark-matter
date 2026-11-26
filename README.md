# What is dark matter?

Stars and gas near the edge of a spiral galaxy can orbit faster than their visible mass predicts. Measure how much faster in one galaxy, then compare it with a second.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/dark-matter/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-dark-matter/pulls)

## Why this matters

Astronomers infer dark matter from its gravity. At the outermost measured radius of galaxy NGC 3198, the observed orbital speed is 149 ± 3 km/s. The model for its stars and gas gives 64.71 km/s at the adopted stellar disk mass-to-light ratio of 0.5 in solar units. The speed difference constrains the gravitational field. The identity of dark matter remains open.

## What to contribute

Reproduce the NGC 3198 result, then test whether the gap persists in NGC 2403. Use every measured radius at or beyond half the last measured radius. Repeat the calculation at disk mass-to-light ratios of 0.3, 0.5 and 0.8.

## How reviewers check it

Use SPARC Table 2 for an independent calculation. Report the galaxy, radial range, number of measurements and median observed minus predicted speed in km/s for each ratio. Check the outermost point by hand and distinguish the measured speed error from model uncertainty.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/dark-matter
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/dark-matter/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-dark-matter/security/advisories/new) for security reports.

## Sources

- [SPARC rotation measurements and Newtonian mass models](<https://astroweb.case.edu/SPARC/>)
- [Lelli, McGaugh and Schombert on the SPARC mass models](<https://arxiv.org/abs/1606.09251>)
- [NASA on the evidence for dark matter](<https://science.nasa.gov/dark-matter/>)

## Starter

[Reproduce the rotation curve of NGC 3198](contributions/dark-matter-rotation/README.md)

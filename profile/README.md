<!-- PROJECT LOGO -->
<p align="center">
  <a href="https://github.com/hook0/hook0" aria-label="Hook0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hook0/hook0/master/mediakit/logo/logo-banner-white.svg">
      <img width="420" alt="Hook0 — open-source Webhooks-as-a-Service" src="https://raw.githubusercontent.com/hook0/hook0/master/mediakit/logo/logo-banner.svg">
    </picture>
  </a>
</p>

<p align="center">
  <strong>Open-source Webhooks-as-a-Service.</strong><br />
  Add webhooks to your product with a single API call. Hook0 takes care of delivery, retries, and HMAC signatures for your users.
</p>

<p align="center">
  <a href="https://www.hook0.com"><strong>Website</strong></a>
  ·
  <a href="https://documentation.hook0.com/"><strong>Documentation</strong></a>
  ·
  <a href="https://www.hook0.com/community"><strong>Discord</strong></a>
  ·
  <a href="https://gitlab.com/hook0/hook0/-/boards"><strong>Roadmap</strong></a>
</p>

<p align="center">
  <a href="https://github.com/hook0/hook0"><img src="https://img.shields.io/github/stars/hook0/hook0?style=flat&color=1D5AF3&label=GitHub%20stars" alt="GitHub stars"></a>
  <a href="https://github.com/hook0/hook0/blob/master/LICENSE.txt"><img src="https://img.shields.io/badge/license-SSPL--1.0-1D5AF3" alt="License: SSPL-1.0"></a>
</p>

## What is Hook0

Hook0 is an open-source, self-hostable Webhooks-as-a-Service. If you build a SaaS and want to send webhooks to your users, Hook0 gives you delivery, retries, HMAC signatures, and monitoring behind one API instead of building and running that infrastructure yourself. Run it self-hosted, or use [Hook0 Cloud](https://www.hook0.com).

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hook0/.github/main/profile/assets/what-is-hook0-dark.svg">
    <img width="820" alt="How Hook0 works: your SaaS makes one API call to Hook0, which delivers signed events with retries to your users' endpoints. Outbound only — Hook0 does not receive third-party webhooks." src="https://raw.githubusercontent.com/hook0/.github/main/profile/assets/what-is-hook0-light.svg">
  </picture>
</p>

## SDKs

Official SDKs for eleven languages. Each one sends events and verifies HMAC signatures on incoming webhooks, and most are built on the standard library alone, with no third-party runtime dependencies.

| Language | Repository |
|---|---|
| Rust | [hook0-rust](https://github.com/hook0/hook0-rust) |
| Go | [hook0-go](https://github.com/hook0/hook0-go) |
| Python | [hook0-python](https://github.com/hook0/hook0-python) |
| TypeScript / JavaScript | [hook0-typescript](https://github.com/hook0/hook0-typescript) |
| PHP | [hook0-php](https://github.com/hook0/hook0-php) |
| Ruby | [hook0-ruby](https://github.com/hook0/hook0-ruby) |
| Java | [hook0-java](https://github.com/hook0/hook0-java) |
| Kotlin | [hook0-kotlin](https://github.com/hook0/hook0-kotlin) |
| C# / .NET | [hook0-csharp](https://github.com/hook0/hook0-csharp) |
| Lua | [hook0-lua](https://github.com/hook0/hook0-lua) |
| Zig | [hook0-zig](https://github.com/hook0/hook0-zig) |

Browse them all: https://github.com/orgs/hook0/repositories?q=topic%3Asdk

## Resources

- [Website](https://www.hook0.com/)
- [Documentation](https://documentation.hook0.com/)
- [Brand kit](https://github.com/hook0/hook0/tree/master/mediakit)

## Community

- [Discord](https://www.hook0.com/community)
- [X (Twitter)](https://x.com/hook0_)
- [YouTube](https://www.youtube.com/channel/UCFGvNaoV6Ycdb6uh1rIvMcg)

## Contributing

The code is hosted on [GitHub](https://github.com/hook0/hook0); the public roadmap lives on [GitLab](https://gitlab.com/hook0/hook0/-/boards).

- [Contributing guide](https://github.com/hook0/hook0/blob/master/contributing.md)
- [Code of conduct](https://github.com/hook0/hook0/blob/master/CODE_OF_CONDUCT.md)
- [Issue tracker](https://github.com/hook0/hook0/issues)

## License

Hook0 is released under the [Server Side Public License (SSPL v1)](https://github.com/hook0/hook0/blob/master/LICENSE.txt). You are free to self-host it.

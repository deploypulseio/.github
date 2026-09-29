<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/deploypulseio/.github/main/profile/assets/logo-dark.png">
    <img src="https://raw.githubusercontent.com/deploypulseio/.github/main/profile/assets/logo-light.png" width="320" alt="DeployPulse" />
  </picture>
</p>

<h3 align="center">Hosted over-the-air updates for React Native and Expo</h3>

<p align="center">
  Ship a fix in seconds, not in a week of app store review.
</p>

<p align="center">
  <a href="https://deploypulse.io"><strong>deploypulse.io</strong></a> ·
  <a href="https://docs.deploypulse.io">Documentation</a> ·
  <a href="https://deploypulse.io/migrate">Migrate from CodePush</a> ·
  <a href="https://status.deploypulse.io">Status</a>
</p>

<br />

App Center CodePush shut down, and every replacement asks you to change something: a new SDK, a new
protocol, a rewrite of the release step you already trust.

DeployPulse does not. Point the SDK you already use at our server and keep shipping.

```shell
npm install -g @deploypulseio/dpctl
dpctl login
dpctl release-react MyApp-iOS ios -d Production
```

<br />

## Why teams move here

**Switch in minutes, not days.** Keep `react-native-code-push` and the workflow your team knows.
Migrating from App Center or another CodePush host is one server URL: no native rebuild, no app store
re-release, and your application code stays exactly as it is.

**It speaks both protocols.** Most services implement CodePush or Expo Updates. DeployPulse serves
both, so a bare React Native app and an `expo-updates` app can live in the same account, on the same
plan, with the same CLI.

**Your keys stay yours.** Turn on RS256 code signing and upload your own key. Every release is
verified on device against a key only you hold.

**It catches a bad release before you do.** Auto-rollback watches the error rate on every release and
reverts to the last good version the moment it crosses your threshold, whether or not anyone is
awake to notice.

<br />

## What you get

|  |  |
|---|---|
| **Instant delivery** | Releases go live across 34 global edge regions in seconds |
| **Gradual rollouts** | Ship to a percentage of devices and raise it as confidence grows |
| **Automatic rollback** | Error-rate thresholds per deployment, reverting without you |
| **Differential updates** | Only the files that changed are sent, so updates stay small |
| **Code signing** | RS256, verified on device, with customer-held keys |
| **Real analytics** | Version adoption curves, per-country downloads, per-release failure reports |
| **Built for CI** | Scoped access keys, a GitHub Action, and webhooks for your own tooling |

<br />

## Start free

**10,000 monthly active users, no credit card.** Paid plans start at $20/month and never block your
updates: go over and we email you, we do not switch your app off.

<a href="https://deploypulse.io/register"><strong>Create an account</strong></a> or read the
<a href="https://docs.deploypulse.io/quickstart">quickstart</a>.

<br />

## Open source

| Repository | |
|------------|--|
| [**dpctl**](https://github.com/deploypulseio/dpctl) | The CLI. Create apps, release, promote, roll back, read failure reports. |
| [**react-native-code-push**](https://github.com/deploypulseio/react-native-code-push) | The React Native SDK, preconfigured for DeployPulse. |
| [**setup-dpctl**](https://github.com/deploypulseio/setup-dpctl) | GitHub Action that installs `dpctl` in a workflow. |

<br />

## Help

[Documentation](https://docs.deploypulse.io) covers setup, releasing, CI and troubleshooting. Bugs and
feature requests belong in the issues of the repository they affect. Anything else, including account
and billing questions, reaches a human at <support@deploypulse.io>.

Found a security vulnerability? Email <support@deploypulse.io> with "Security" in the subject rather
than opening a public issue.

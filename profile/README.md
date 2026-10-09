<div align="center">
  <a href="https://fixapi.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.svg">
      <img alt="FixApi" src="assets/wordmark-light.svg" width="240">
    </picture>
  </a>

  <h3>Third-party APIs change, your code adapts</h3>

  <p>
    <a href="https://fixapi.ai">Website</a>
    &nbsp;·&nbsp;
    <a href="https://fixapi.ai">Request a demo</a>
    &nbsp;·&nbsp;
    <a href="https://x.com/FixApi_ai">X</a>
    &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/company/fixapi">LinkedIn</a>
  </p>
</div>

<br>

FixApi watches the third-party APIs your code depends on. When a provider makes a breaking change that affects your product, FixApi finds the affected code and opens a tested pull request with the fix.

Providers rename parameters, deprecate endpoints and replace SDKs on their own schedule. Nobody knows which files call the thing that changed, so teams often find out through a failed request in production. FixApi closes that gap.

### How it works

1. **Install the GitHub App.** Pick the repositories FixApi may read. The app asks only for the permissions it needs.
2. **Map your API integrations.** FixApi finds the third-party APIs your code calls, down to each call site, through official SDKs and direct HTTP requests.
3. **Watch the providers.** Official OpenAPI specs, SDK releases and changelogs are checked for changes that touch your code.
4. **Review a tested pull request.** The fix has already passed your CI commands in a sandbox. Review it and merge it like any other pull request.

### Built for teams that are careful with their code

- **You approve every change.** Fixes arrive as pull requests on a new branch. Nothing is merged until your team merges it.
- **Least-privilege access.** You choose the repositories. FixApi can read your code, create a branch and open a pull request.
- **Ephemeral by default.** Your source code is used for the scan and is not stored. Only facts such as file paths are kept.
- **Only what the fix needs goes to the model.** To write a fix, the one affected file is sent to an AI model, never your whole repository.

### Availability

JavaScript and TypeScript today, with providers such as Stripe, OpenAI, Anthropic, Twilio, Slack and GitHub. We are onboarding teams in small batches. [Request a demo](https://fixapi.ai) to see FixApi on your own code.

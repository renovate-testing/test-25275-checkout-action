# 25275

## Current behavior

Renovate says: `Could not determine new digest for update` when it tries to update `actions/checkout` from `v4.1.0` -> `v4.1.1`.
Here's the relevant part of the update PR from Renovate:

This PR contains the following updates:

| Package | Type | Update | Change |
|---|---|---|---|
| [actions/checkout](https://togithub.com/actions/checkout) | action | patch | `v4.1.0` -> `v4.1.1` |

# Warnings (1)

Please correct - or verify that you can safely ignore - these warnings before you merge this PR.

-   `actions/checkout`: Could not determine new digest for update (github-tags package actions/checkout)

---

---

> [!WARNING]
> Some dependencies could not be looked up. Check the Dependency Dashboard for more information.

---

### Is the hash correct?

The hash that Renovate uses (`b4ffde65f46336ab88eb53be808477a3936bae11`) is the correct hash for `v4.1.1`.

[`actions/checkout` v4.1.1 release on GitHub](https://github.com/actions/checkout/releases/tag/v4.1.1)

## Expected behavior

Renovate creates the PR without a error message.

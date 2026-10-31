# onboarding-clients

Client contracts. One folder per client with a single `Client`. The platform creates
the client's namespace itself: `<environment>-<name>`, e.g. `dev-acme`.

This is the only repo a delivery team touches. The recipe behind the
contract lives in [onboarding-platform](https://github.com/RalphieKay/onboarding-platform).
Flux applies this repo with an account that may create only
`Client` objects, so nothing else gets in.

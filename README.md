# Macawg specification

Macawg is a protocol for asking a person's wallet for a CAWG identity assertion. A C2PA device, such as a camera, sends the request and gets the signed assertion back. The protocol is designed as a companion to the [CAWG Identity Assertion specification](https://cawg.io/identity/1.2/).

The specification is in [`macawg.adoc`](macawg.adoc) (AsciiDoc). The Rust crate [`macawg`](https://github.com/Cognitive-Proof/macawg) is its reference implementation. Rules that the crate does not enforce yet are marked *(proposed)*.

## Status

This is a draft, not a CAWG work product.

## Commenting

Review happens on pull requests. To comment on a draft, open its pull request, go to **Files changed**, and comment on the lines in question. For broader questions, open an issue.

## Rendering

```bash
npx @asciidoctor/cli macawg.adoc
```

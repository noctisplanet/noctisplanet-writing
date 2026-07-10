# Writing (磨译) — public pages

The Privacy Policy and Support pages for **Writing**, an English-grammar practice
app for Chinese speakers on macOS and iOS.

App Store Connect requires both to be reachable at a public URL. This repo exists
to serve them, and nothing else — no application source code, no submission
metadata.

## Pages

Served by GitHub Pages from `docs/` on `main`:

- Privacy Policy (English) — `docs/privacy/`
- 隐私政策 (简体中文) — `docs/privacy/zh-hans/`
- Support / 支持 (bilingual) — `docs/support/`

The HTML is the source of truth. There is no generator and no build step.

## About the app

Writing generates Chinese-to-English translation exercises and grades your answers
with a large language model. It has **no backend** and **collects no data**: you
bring your own API key for DeepSeek or Alibaba Qwen, and requests go directly from
your device to that provider. Papers and keys are encrypted on-device. One-time
purchase, no subscription, no in-app purchase.

Contact: panghu.lee@gmail.com

## License

Copyright 2026 Chengzhi Li. All rights reserved — see [LICENSE](LICENSE).

This repository is public so that the Privacy Policy and Support pages have a URL
Apple can reach. It is not open source, and the pages and app names are not
licensed for reuse.

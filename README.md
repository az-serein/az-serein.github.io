# xingyezhang.com

Source for Xingye Zhang’s personal portfolio at [www.xingyezhang.com](https://www.xingyezhang.com/).

The site is a GitHub Pages-compatible Jekyll project. It presents public-safe summaries of research, engineering, and course work. Private repositories, application records, credentials, client code, detailed contact information, and unapproved research artifacts are intentionally excluded.

## Local preview

Use Ruby 3.3 and Bundler 2.6.9. The lock file pins the GitHub Pages dependency set.

```bash
gem install bundler -v 2.6.9
bundle _2.6.9_ install
bundle _2.6.9_ exec jekyll build --safe --trace
bundle _2.6.9_ exec jekyll serve --safe --host 127.0.0.1 --port 4000
```

## Publishing boundary

The live site deploys from `master`. Work should be built and reviewed locally before any push. Publishing, DNS changes, analytics, credential changes, and repository visibility changes require explicit human approval.

## Content and licensing

- Site code retains the applicable MIT-licensed Academic Pages / Minimal Mistakes foundations from the repository history.
- Personal writing and photographs are not offered under an open-source license unless stated otherwise; see [CONTENT_LICENSE.md](CONTENT_LICENSE.md).
- The New Haven case study uses UT-GLOBUS data under CC BY 4.0 and retains source and basemap attribution; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
- Course-project excerpts represent Xingye Zhang’s reviewed personal contributions; original course repositories are not modified or republished.

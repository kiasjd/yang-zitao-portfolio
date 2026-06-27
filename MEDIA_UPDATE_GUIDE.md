# Media Update Guide

## Images

Put portfolio images inside:

```text
public/works/covers/
public/works/extracted/
```

Images can be committed to GitHub as long as each file is under GitHub's file size limits. JPG is recommended for future updates.

## Videos

Do not upload large video files to GitHub. Host videos externally, then update the portfolio data with direct video URLs.

Recommended video hosts:

- Tencent Cloud COS
- Alibaba Cloud OSS
- Cloudflare R2
- Bilibili, only if using an external watch link instead of direct in-page playback

For direct in-page playback, use an `.mp4` URL that can open directly in the browser.

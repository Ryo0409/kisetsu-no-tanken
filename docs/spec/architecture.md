# きせつのたんけん 基本設計

## 方針

- 使用する言語、フレームワーク、外部サービスはなるべく少なくなるようにする。
  - なるべく自前実装を避ける。
  - マネージドサービスを活用する。
- スモールスタート。過度な性能対策はしない。
- ランニングコストは小さくなるようにする。
- UI/UXは頻繁に変更が入るため、

## 技術スタック

| 領域            | 技術                                |
| --------------- | ----------------------------------- |
| Frontend        | Next.js / TypeScript / Tailwind CSS |
| Authenticationz | Auth.js                             |
| Infrastructure  | Cloudflare Workers                  |
| Observability   | New Relic                           |
| Design          | Figma / Storybook                   |
| E2E Testing     | Playwright                          |
| CI/CD           | GitHub Actions                      |

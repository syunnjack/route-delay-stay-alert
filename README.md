# Route Delay Stay Alert

高速バス・電車遅延・到着後スポット通知

## Repository

Recommended repository name: `route-delay-stay-alert`

## Domain candidates

Confirmed domain: `delaystay.jp`

Other candidates:

- `delaystay.jp`
- `routealert.jp`
- `busdelaystay.jp`
- `arrivalspot.jp`

## Concept

遅延、終電後、早朝到着時に宿、漫画喫茶、飲食店、タクシーへ送客する移動者向け通知ナビ。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 宿泊予約
- 漫画喫茶送客
- 飲食店送客
- タクシー広告
- 旅行アフィリエイト

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```

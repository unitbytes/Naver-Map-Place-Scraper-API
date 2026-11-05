# 🇰🇷 Naver Map & Naver Place Korea Scraper API Suite: Business Leads, KRW Menus & Visitor Receipt Reviews (`$0.50 / 1K`)

<div align="center">

[![Available on Apify](https://img.shields.io/badge/Available_on-Apify-28B52A?style=for-the-badge&logo=apify&logoColor=white)](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver)
[![Open in Colab](https://img.shields.io/badge/Open_in-Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/unitbytes/Naver-Map-Place-Scraper-API/blob/main/notebooks/quickstart.ipynb)
[![n8n Creator Hub](https://img.shields.io/badge/n8n_Creator_Hub-@unitbytes-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io/creators/unitbytes/)
[![Release](https://img.shields.io/github/v/release/unitbytes/Naver-Map-Place-Scraper-API?style=for-the-badge&logo=github&color=10b981)](https://github.com/unitbytes/Naver-Map-Place-Scraper-API/releases)
[![Pricing](https://img.shields.io/badge/Pricing-Pay_Per_Result-orange?style=for-the-badge)](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver)

**Complete South Korea (대한민국) Naver Map (`map.naver.com`) & Naver Place (`m.place.naver.com`) 3-Engine Data Extraction Suite on Apify (`$0.50–$1.00 / 1,000 items`). Extract verified Korean POI business leads, phones, road/jibun addresses, WGS84 coordinates, KRW menu prices, SmartPlace/Naver Booking/NPay flags, and receipt-verified Visitor Reviews (영수증 방문자 리뷰) with zero login or Korean phone number required.**

[**🚀 Try Live on Apify**](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver) • [**📓 Open in Google Colab**](https://colab.research.google.com/github/unitbytes/Naver-Map-Place-Scraper-API/blob/main/notebooks/quickstart.ipynb) • [**⚡ Official n8n Creator Hub**](https://n8n.io/creators/unitbytes/) • [**🔧 41 Free n8n Templates**](https://unitbytes.com/n8n/) • [**📖 Documentation & Schemas**](https://unitbytes.com/actors/) • [**📚 Engineering Playbooks**](https://unitbytes.com/blog/)

</div>

---

<p align="center">
  <a href="https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver" target="_blank">
    <img src="https://raw.githubusercontent.com/unitbytes/.github/main/assets/banners/unitbytes-naver-map-place-scraper-korea-business-leads-reviews-banner.jpg" alt="🇰🇷 Naver Map & Naver Place Korea Scraper API Suite: Business Leads, KRW Menus & Visitor Receipt Reviews (`$0.50 / 1K`)" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver" target="_blank">
    <img src="https://raw.githubusercontent.com/unitbytes/.github/main/assets/try-it-for-free.svg" width="240" height="48" alt="Try it for Free">
  </a>
  <br>
  <sub>⚡ <b>1-Click Free Trial:</b> Test live queries using Apify's `$5` free monthly credit • Zero login or cookies required</sub>
</p>

---

<!-- UNITBYTES_REPO_KIT_START -->
## 📦 Included in This Repository (Python Quickstarts, Google Colab, n8n Workflows, MCP & Sample Data)

This repository contains ready-to-run **Python SDK scripts**, an **interactive 1-Click Google Colab notebook (`notebooks/quickstart.ipynb`)**, **9-node n8n automation workflow `.json` templates**, **AI Agent MCP configuration (`.cursor/mcp.json`)**, and **sample output datasets (JSON & CSV)**:

| Extraction Engine | 🐍 Python SDK Quickstart | ⚡ n8n Workflow Template | 📊 Sample Output | 🚀 Cloud Console |
| :--- | :--- | :--- | :---: | :---: |
| **Naver Map Scraper: Korean Leads & Menus**<br><sub>[`unitbytes/naver-map-scraper`](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver) • [Full Schema](https://unitbytes.com/actors/naver-map-scraper/) • [Engineering Playbook](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)</sub> | [`examples/run_naver_map_scraper.py`](examples/run_naver_map_scraper.py) | [`n8n/naver-map-scraper-n8n-workflow.json`](n8n/naver-map-scraper-n8n-workflow.json) | [`JSON`](samples/naver-map-scraper-sample.json) · [`CSV`](samples/naver-map-scraper-sample.csv) | [⚡ **Run on Apify**](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver) |
| **Naver Place Scraper: Places & Menus**<br><sub>[`unitbytes/naver-place-scraper`](https://apify.com/unitbytes/naver-place-scraper?fpr=939u3w&fp_sid=gh_naver) • [Full Schema](https://unitbytes.com/actors/naver-place-scraper/) • [Engineering Playbook](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)</sub> | [`examples/run_naver_place_scraper.py`](examples/run_naver_place_scraper.py) | [`n8n/naver-place-scraper-n8n-workflow.json`](n8n/naver-place-scraper-n8n-workflow.json) | [`JSON`](samples/naver-place-scraper-sample.json) · [`CSV`](samples/naver-place-scraper-sample.csv) | [⚡ **Run on Apify**](https://apify.com/unitbytes/naver-place-scraper?fpr=939u3w&fp_sid=gh_naver) |
| **Naver Place Reviews Scraper**<br><sub>[`unitbytes/naver-place-reviews-scraper`](https://apify.com/unitbytes/naver-place-reviews-scraper?fpr=939u3w&fp_sid=gh_naver) • [Full Schema](https://unitbytes.com/actors/naver-place-reviews-scraper/) • [Engineering Playbook](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)</sub> | [`examples/run_naver_place_reviews_scraper.py`](examples/run_naver_place_reviews_scraper.py) | [`n8n/naver-place-reviews-scraper-n8n-workflow.json`](n8n/naver-place-reviews-scraper-n8n-workflow.json) | [`JSON`](samples/naver-place-reviews-scraper-sample.json) · [`CSV`](samples/naver-place-reviews-scraper-sample.csv) | [⚡ **Run on Apify**](https://apify.com/unitbytes/naver-place-reviews-scraper?fpr=939u3w&fp_sid=gh_naver) |

- 📓 **1-Click Interactive Google Colab Notebook:** Open [`notebooks/quickstart.ipynb`](notebooks/quickstart.ipynb) directly in your browser via [**Google Colab ↗**](https://colab.research.google.com/github/unitbytes/Naver-Map-Place-Scraper-API/blob/main/notebooks/quickstart.ipynb) to inspect sample DataFrames and test live API queries with zero local setup.
- 🤖 **Cursor, Windsurf & Claude Code MCP Ready:** Includes [`.cursor/mcp.json`](.cursor/mcp.json) pre-configured with `https://mcp.apify.com` so AI coding agents can invoke these UnitBytes scrapers natively.
- 💡 **Using n8n?** Explore our official creator profile at **[n8n.io/creators/unitbytes](https://n8n.io/creators/unitbytes/)** or copy all 41 pre-built 9-node scraping workflows (`Ctrl+V`) at **[unitbytes.com/n8n](https://unitbytes.com/n8n/)**.
- 📚 **Engineering Playbook:** Read **[How to Scrape Naver Map & Naver Place (2026): South Korea Business Leads, Menus & Visitor Reviews Guide (`$0.50–$1.00/1K`)](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)** or browse all scraping & automation guides at **[unitbytes.com/blog](https://unitbytes.com/blog/)**.
<!-- UNITBYTES_REPO_KIT_END -->

---

## ⚡ Pre-Configured 1-Click Task Presets

Launch pre-configured extraction templates directly in the Apify Cloud Console with zero parameter setup:

| Task Preset | Target Extraction Use Case | Direct Launch |
| :--- | :--- | :---: |
| **Scrape Naver Place (네이버 플레이스) Korean Businesses, Menus & Receipt Reviews** | Extract South Korean restaurants, clinics, cafes, KRW menu prices, and verified receipt reviews (`영수증 리뷰`) from Naver Place without Korean IP blocks. | [⚡ Run Task Preset](https://apify.com/unitbytes/naver-place-scraper?fpr=939u3w&fp_sid=gh_naver) |

---

## 🧭 Which South Korea Naver Map & Naver Place Engine Should You Use? (3-Engine Suite)

| Engine | Apify Actor Slug | Primary Use Case | Key Extracted Fields | Starting Price |
| :--- | :--- | :--- | :--- | :---: |
| **🇰🇷 Naver Place Scraper: Places & Menus (네이버 플레이스)** | [`unitbytes/naver-place-scraper`](https://apify.com/unitbytes/naver-place-scraper?fpr=939u3w&fp_sid=gh_naver) | All-in-one storefront enrichment including 36 place fields, KRW menu price catalogs, SmartPlace/Booking/NPay flags, and embedded visitor reviews | `place_id`, `name`, `category`, `road_address`, `address`, `phone`, `virtual_phone`, `menus` (`price_krw`), `facilities`, `homepage_url`, `sns_links`, and `reviews` | `$1.00 / 1K places` (`$0.001/item`) |
| **🗺️ Naver Map Scraper: Korea Business Leads (네이버 지도)** | [`unitbytes/naver-map-scraper`](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver) | High-speed South Korea POI discovery, local B2B lead generation, and multi-district search | `place_id`, `name`, `category`, `phone`, `virtual_phone`, `road_address`, `address`, `latitude`/`longitude`, `homepage_url`, `sns_links`, and NPay/SmartOrder flags | `$1.00 / 1K places` (`$0.001/item`) |
| **⭐ Naver Place Reviews Scraper (영수증 방문자 리뷰)** | [`unitbytes/naver-place-reviews-scraper`](https://apify.com/unitbytes/naver-place-reviews-scraper?fpr=939u3w&fp_sid=gh_naver) | Deep Korean consumer sentiment and receipt-verified Visitor Reviews (영수증/결제 인증 방문자 리뷰) | `review_id`, `author_nickname`, `review_text`, `rating`, `visit_count`, `visit_verification_type`, `visit_keywords`, `owner_reply_text`, and review photos/videos | `$0.50 / 1K reviews` (`$0.0005/item`) |

---

## 🛠️ Extraction Engines in This Suite

### 🚀 Naver Map Scraper: Korean Leads & Menus (`unitbytes/naver-map-scraper`)

Scrape Naver Map (네이버 지도) & Naver Place (네이버 플레이스) business leads from `$1.00/1K`: Korean company names, phone numbers (0507), road addresses, GPS coordinates, websites, opening hours, KRW menus & ratings. 지역·업종별 상호명, 전화번호, 주소, 위경도, 메뉴 가격표 B2B DB 추출.

- **Pricing:** `$0.0014 / item` (Pay-Per-Event — `$0.0014` business lead scraped (volume tiers from `$0.001`))
- **Cloud Console:** [https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver](https://apify.com/unitbytes/naver-map-scraper?fpr=939u3w&fp_sid=gh_naver)
- **Full Documentation & Schema:** [https://unitbytes.com/actors/naver-map-scraper/](https://unitbytes.com/actors/naver-map-scraper/)
- **n8n Workflow File:** [`n8n/naver-map-scraper-n8n-workflow.json`](n8n/naver-map-scraper-n8n-workflow.json)
- **Engineering Playbook:** [How to Scrape Naver Map & Naver Place (2026): South Korea Business Leads, Menus & Visitor Reviews Guide (`$0.50–$1.00/1K`)](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)

#### Key Capabilities
- **Complete 45+ Field Korean B2B Lead Records:** Captures company/store names, categories across all verticals (restaurant, hospital, hairshop, accommodation, place), phone & SmartCall (0507) numbers, road & lot addresses, GPS coordinates, websites, Instagram links, Naver TalkTalk (talktalkUrl), and Naver Booking (bookingUrl).
- **All-in-One Transparent Pricing:** Pay one flat rate (result-scraped) per business lead with full place details, menus, 7-day hours, websites, and embedded reviews included at `$0.00` extra add-on charge.
- **GPS Coordinate Centering & Server-Side Distance Sorting:** Pass any searchCoordinates (latitude,longitude, e.g., 37.497942,127.027610) and sortBy: "distance" or "popular" to map hyper-local commercial districts (상권 분석) across Seoul, Busan, Incheon, Daegu, and nationwide.
- **Full Menus, KRW Prices & Spend Analytics:** Extracts every menu item with integer KRW price (priceKrw), description, recommended flags, high-resolution menu photos, popular dishes (popularMenusText), average spend, and average stay time.

#### ⚙️ Input Parameters (Schema)

| Parameter | Type | Default / Prefill | Description |
| :--- | :---: | :--- | :--- |
| `queries` | `array` | `["강남 맛집"]` | Keywords to search on Naver Map (map.naver.com, e.g., 강남 맛집, 성수동 카페, 강남 피부과, 명동 호텔, 홍대 미용실). You can also paste direct Naver Map URLs or Place IDs here. |
| `placeUrls` | `array` | — | Optional list of direct Naver Map URLs (https://map.naver.com/p/entry/place/2000000001), Map Search URLs (https://map.naver.com/p/search/강남%20맛집), Mobile Place URLs, naver.me shortlinks, or numeric Place IDs (2000000001). Overrides prefilled search queries. |
| `scrapeDetails` | `boolean` | `True` | When enabled (default), extracts 7-day opening hours, full menu list with KRW prices & photos, walking directions, nearest subway stations, parking fees, website/Instagram links, sentiment keyword breakdown, and recent reviews. Disable for rapid 50-per-page map search cards. |
| `maxItems` | `integer` | `20` | Maximum number of business listings (or reviews in reviews mode) to collect across the run. |
| `sortBy` | `string` | `popular` | Server-side sorting order for Naver Map search results (popular / relevance default, precision, or distance from searchCoordinates). |
| `searchCoordinates` | `string` | — | Optional GPS center point as latitude,longitude (e.g., 37.497942,127.027610 for Gangnam Station, Seoul) used for localized map search ranking and distance sorting. |
| `maxReviewsPerPlace` | `integer` | `10` | Maximum number of visitor reviews (방문자 리뷰) to embed per business when scrapeDetails is enabled. |
| `includeBlogReviews` | `boolean` | `True` | Include Naver Blog and Cafe review posts linked to each business. |
| `maxBlogReviewsPerPlace` | `integer` | `10` | Maximum number of linked Naver Blog / Cafe reviews to fetch per business. |
| `onlyPhotoReviews` | `boolean` | `False` | Filter visitor reviews server-side to only return reviews that include customer-uploaded photos. |
| `mode` | `string` | `places` | Outputs one record per business (places, default) or one row per review (reviews). |
| `language` | `string` | `ko` | Language preference for Naver Map category and address fields (ko for original Korean, en for English localized strings where available). |
| `startPage` | `integer` | `1` | 1-indexed search page to start from (50 businesses per page). |
| `resumptionToken` | `string` | — | Optional compact continuation token emitted at the end of a previous batch run (RESUMPTION_TOKEN in Key-Value Store) to resume pagination with 0 duplicate overlap. |
| `proxyConfiguration` | `object` | `{"useApifyProxy": true}` | Proxy settings for accessing Naver Map endpoints reliably. |

#### Python SDK Quickstart (`examples/run_naver_map_scraper.py`)
```python
from apify_client import ApifyClient

APIFY_TOKEN = os.getenv("APIFY_API_TOKEN", "YOUR_APIFY_API_TOKEN")
if not APIFY_TOKEN or APIFY_TOKEN.startswith("YOUR_"):
    raise SystemExit("Please set your Apify API token: export APIFY_API_TOKEN='apify_api_...'")

client = ApifyClient(APIFY_TOKEN)

run_input = {
    "queries": ["강남 맛집"],
    "scrapeDetails": True,
    "maxItems": 20,
    "sortBy": "popular",
    "maxReviewsPerPlace": 10,
    "includeBlogReviews": True
}

run = client.actor("unitbytes/naver-map-scraper").call(run_input=run_input)

for item in client.dataset(run["defaultDatasetId"]).iterate_items():
    print(item.get("name"), item.get("searchQuery"), item.get("rating"))
```

#### Sample Output Schema (`samples/naver-map-scraper-sample.json`)
```json
{
  "placeId": "2000000001",
  "name": "서울 미식 다이닝 강남점",
  "businessCategory": "restaurant",
  "category": "한식",
  "categoryCode": "220053",
  "phone": "0507-0000-0000",
  "virtualPhone": "0507-0000-0000",
  "roadAddress": "서울 강남구 테헤란로 100 1층",
  "address": "서울 강남구 역삼동 100-1",
  "commonAddress": "서울 강남구 역삼동",
  "fullAddress": "서울 강남구 테헤란로 100 1층",
  "postalCode": "09680108",
  "latitude": 37.5206335,
  "longitude": 127.0361667,
  "distance": "2.6km",
  "directions": "역삼역 3번 출구에서 테헤란로 방향으로 도보 3분 거리 (시그니처타워 1층)",
  "nearestSubway": "역삼역 2호선",
  "parkingInfo": "2시간 4000원 (발렛파킹 가능)",
  "businessStatus": "영업 중",
  "businessHoursText": "02:00에 영업 종료",
  "businessHours": [
    {
      "day": "월",
      "start": "11:00",
      "end": "02:00"
    }
  ],
  "rating": 4.97,
  "visitorReviewCount": 177,
  "blogCafeReviewCount": 37,
  "bookingReviewCount": 0,
  "imageReviewCount": 143,
  "popularMenusText": "소금김밥, 대물 숙성회 정식(광어), 1% 대광어 숙성회",
  "menuCount": 6,
  "menus": [
    {
      "name": "1% 대광어 숙성회",
      "priceText": "56,000원",
      "priceKrw": 56000,
      "description": "중 56000 / 대 78000",
      "isRecommended": true,
      "imageUrl": "https://ldb-phinf.pstatic.net/example_place_photo_01.jpg"
    }
  ],
  "topVotedKeywords": [
    {
      "code": "food_good",
      "keyword": "음식이 맛있어요",
      "count": 165
    },
    {
      "code": "fresh",
      "keyword": "재료가 신선해요",
      "count": 121
    }
  ],
  "conveniences": [
    "포장",
    "단체 이용 가능",
    "예약"
  ],
  "paymentMethods": [
    "간편결제"
  ],
  "hasBooking": true,
  "homepageUrl": "https://map.naver.com/p/entry/place/2000000001",
  "instagramUrl": null,
  "allLinks": [
    "https://map.naver.com/p/entry/place/2000000001"
  ],
  "microReview": "한 점 한 점 정성 가득한 숙성회",
  "mainImage": "https://ldb-phinf.pstatic.net/example_place_photo_01.jpg",
  "imageCount": 57,
  "url": "https://map.naver.com/p/entry/place/2000000001",
  "mapUrl": "https://m.place.naver.com/restaurant/2000000001/home",
  "searchQuery": "강남 맛집",
  "detailLevel": "full",
  "language": "ko",
  "scrapedAt": "2026-10-28T12:00:00.000000+00:00"
}
```

#### Frequently Asked Questions
**Q: Do I need my own proxies or account login for naver-map-scraper?**
No. UnitBytes manages residential proxy rotation and automated request orchestration so you never need personal accounts or proxies.

**Q: What output formats are supported?**
All data can be downloaded in JSON, CSV, or Excel formats, or consumed directly via the Apify REST API and webhooks.

**Q: How does pricing work?**
You only pay for successful records extracted under Apify Pay-Per-Event pricing, with zero monthly minimums or idle compute costs.

**Q: Can this actor be integrated into automated workflows?**
Yes. You can trigger runs via Apify API, Python/JavaScript clients, Make, Zapier, or scheduled cron workflows.

---

### 🚀 Naver Place Scraper: Places & Menus (`unitbytes/naver-place-scraper`)

Scrape Naver Place (네이버 플레이스) & Naver Map (네이버 지도) from `$1.00/1K`: Korean local business leads, phone numbers (0507), road addresses, GPS coordinates, 7-day hours, KRW menus, visitor & blog reviews. 상호명, 전화번호, 주소, 영업시간, 메뉴·가격, 방문자·블로그 리뷰 초고속 추출.

- **Pricing:** `$0.0014 / item` (Pay-Per-Event — `$0.0014` place or review scraped (volume tiers from `$0.001`))
- **Cloud Console:** [https://apify.com/unitbytes/naver-place-scraper?fpr=939u3w&fp_sid=gh_naver](https://apify.com/unitbytes/naver-place-scraper?fpr=939u3w&fp_sid=gh_naver)
- **Full Documentation & Schema:** [https://unitbytes.com/actors/naver-place-scraper/](https://unitbytes.com/actors/naver-place-scraper/)
- **n8n Workflow File:** [`n8n/naver-place-scraper-n8n-workflow.json`](n8n/naver-place-scraper-n8n-workflow.json)
- **Engineering Playbook:** [How to Scrape Naver Map & Naver Place (2026): South Korea Business Leads, Menus & Visitor Reviews Guide (`$0.50–$1.00/1K`)](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)

#### Key Capabilities
- **Complete 45+ Field Korean Business Profiles:** Extracts Korean business names, categories, phone and SmartCall (0507) numbers, road (도로명) and lot (지번) addresses, postal codes, WGS84 GPS coordinates, 7-day hours, Naver Booking, and Instagram links.
- **Full Menus, KRW Prices & POS Insights:** Captures every menu item with KRW price, menu description, recommended badges, high-resolution menu photos, popular dishes, average customer spend, and average stay time.
- **Verified Visitor Reviews & Naver Blog Reviews:** Collects receipt-verified visitor reviews (방문자 리뷰), photo-only review filtering (onlyPhotoReviews), customer sentiment keyword votes (topVotedKeywords), owner replies, and linked Naver Blog reviews.
- **All-in-One Pricing & `$0.00` Empty Search Protection:** Pay a single transparent rate from `$2.80/1,000 results` with menus, hours, and reviews included at no extra add-on fee, and `$0.00` charged for missing Place IDs or empty searches.

#### ⚙️ Input Parameters (Schema)

| Parameter | Type | Default / Prefill | Description |
| :--- | :---: | :--- | :--- |
| `queries` | `array` | `["강남 맛집"]` | Keywords to search on Naver Map / Naver Place (e.g., 강남 맛집, 성수동 카페, 강남 피부과, 명동 호텔, 홍대 미용실). You can also paste direct Naver Map / Place URLs or numeric Place IDs here. |
| `placeUrls` | `array` | — | Optional list of direct Naver Map URLs (https://map.naver.com/p/entry/place/2000000001), Mobile Place URLs (https://m.place.naver.com/restaurant/2000000001/home), naver.me shortlinks, search URLs (https://map.naver.com/p/search/강남%20맛집), or raw numeric Place IDs (2000000001). Takes precedence over prefilled search queries. |
| `mode` | `string` | `places` | Select whether to output enriched Place records (places — includes menus, hours, contacts, sentiment stats, and embedded reviews) or dedicated individual review rows (reviews — outputs one row per visitor/blog review for deep sentiment analysis). |
| `scrapeDetails` | `boolean` | `True` | When enabled (default), extracts 7-day opening hours, full menu list with KRW prices & photos, walking directions, nearest subway stations, parking fees, website/Instagram links, sentiment keyword breakdown, and recent visitor/blog reviews. Disable for ultra-fast summary search cards. |
| `maxItems` | `integer` | `20` | Maximum number of items (places in places mode, or reviews in reviews mode) to collect across the run. |
| `maxReviewsPerPlace` | `integer` | `10` | Maximum number of visitor reviews (방문자 리뷰) to fetch per place when scrapeDetails is enabled or in reviews mode. |
| `includeBlogReviews` | `boolean` | `True` | Include Naver Blog and Cafe review posts linked to each place (author name, post title, URL, snippet, date, and thumbnail). |
| `maxBlogReviewsPerPlace` | `integer` | `10` | Maximum number of linked Naver Blog / Cafe reviews to fetch per place. |
| `onlyPhotoReviews` | `boolean` | `False` | Filter visitor reviews server-side to only return reviews that include customer-uploaded photos or receipt images. |
| `sortBy` | `string` | `popular` | Server-side sorting order for Naver Place search results (popular / relevance default, or distance from search coordinates). |
| `searchCoordinates` | `string` | — | Optional GPS center point as latitude,longitude (e.g., 37.497942,127.027610 for Gangnam Station, Seoul) used for localized ranking and distance sorting. |
| `language` | `string` | `ko` | Language preference for Naver Place category and address fields (ko for original Korean, en for English localized strings where available). |
| `startPage` | `integer` | `1` | 1-indexed search page to start from (50 places per page). |
| `resumptionToken` | `string` | — | Optional compact continuation token emitted at the end of a previous batch run (RESUMPTION_TOKEN in Key-Value Store) to resume pagination with 0 duplicate overlap. |
| `proxyConfiguration` | `object` | `{"useApifyProxy": true}` | Proxy settings for accessing Naver Place endpoints reliably. |

#### Python SDK Quickstart (`examples/run_naver_place_scraper.py`)
```python
from apify_client import ApifyClient

APIFY_TOKEN = os.getenv("APIFY_API_TOKEN", "YOUR_APIFY_API_TOKEN")
if not APIFY_TOKEN or APIFY_TOKEN.startswith("YOUR_"):
    raise SystemExit("Please set your Apify API token: export APIFY_API_TOKEN='apify_api_...'")

client = ApifyClient(APIFY_TOKEN)

run_input = {
    "queries": ["강남 맛집"],
    "mode": "places",
    "scrapeDetails": True,
    "maxItems": 20,
    "maxReviewsPerPlace": 10,
    "includeBlogReviews": True
}

run = client.actor("unitbytes/naver-place-scraper").call(run_input=run_input)

for item in client.dataset(run["defaultDatasetId"]).iterate_items():
    print(item.get("name"), item.get("category"), item.get("phone"), item.get("visitorReviewScore"))
```

#### Sample Output Schema (`samples/naver-place-scraper-sample.json`)
```json
{
  "placeId": "2000000001",
  "name": "강남 시그니처 다이닝",
  "businessCategory": "restaurant",
  "category": "한식",
  "categoryCode": "220053",
  "phone": "0507-0000-0000",
  "virtualPhone": "0507-0000-0000",
  "roadAddress": "서울 강남구 테헤란로 100 1층",
  "address": "서울 강남구 역삼동 100-1",
  "commonAddress": "서울 강남구 역삼동",
  "fullAddress": "서울 강남구 테헤란로 100 1층",
  "postalCode": "09680108",
  "latitude": 37.5206335,
  "longitude": 127.0361667,
  "distance": "2.6km",
  "directions": "역삼역 3번 출구에서 테헤란로 방향으로 도보 3분 거리 (시그니처타워 1층)",
  "nearestSubway": "역삼역 2호선",
  "parkingInfo": "2시간 4000원 (발렛파킹 가능)",
  "businessStatus": "영업 중",
  "businessHoursText": "02:00에 영업 종료",
  "businessHours": [
    {
      "day": "월",
      "start": "11:00",
      "end": "02:00"
    }
  ],
  "rating": 4.97,
  "visitorReviewCount": 177,
  "blogCafeReviewCount": 37,
  "bookingReviewCount": 0,
  "imageReviewCount": 143,
  "popularMenusText": "소금김밥, 대물 숙성회 정식(광어), 1% 대광어 숙성회",
  "menuCount": 6,
  "menus": [
    {
      "name": "1% 대광어 숙성회",
      "priceText": "56,000원",
      "priceKrw": 56000,
      "description": "중 56000 / 대 78000",
      "isRecommended": true,
      "imageUrl": "https://ldb-phinf.pstatic.net/example_place_photo_01.jpg"
    }
  ],
  "topVotedKeywords": [
    {
      "code": "food_good",
      "keyword": "음식이 맛있어요",
      "count": 165
    },
    {
      "code": "fresh",
      "keyword": "재료가 신선해요",
      "count": 121
    }
  ],
  "conveniences": [
    "포장",
    "단체 이용 가능",
    "예약"
  ],
  "paymentMethods": [
    "간편결제"
  ],
  "hasBooking": true,
  "homepageUrl": "https://map.naver.com/p/entry/place/2000000001",
  "instagramUrl": null,
  "allLinks": [
    "https://map.naver.com/p/entry/place/2000000001"
  ],
  "microReview": "한 점 한 점 정성 가득한 숙성회",
  "mainImage": "https://ldb-phinf.pstatic.net/example_place_photo_01.jpg",
  "imageCount": 57,
  "url": "https://map.naver.com/p/entry/place/2000000001",
  "mapUrl": "https://m.place.naver.com/restaurant/2000000001/home",
  "searchQuery": "강남 맛집",
  "detailLevel": "full",
  "language": "ko",
  "scrapedAt": "2026-10-24T16:30:00.000000+00:00"
}
```

#### Frequently Asked Questions
**Q: What is the difference between places mode and reviews mode?**
Places mode (default) extracts complete 45+ field business profiles including menus, hours, sentiment keywords, and embedded visitor/blog reviews. reviews mode streams up to 500 individual receipt-verified visitor reviews per business (1 row per review).

**Q: What Naver Map and Naver Place input formats are supported?**
You can pass Korean search queries (e.g. '강남 맛집', '성수동 카페', '명동 피부과'), desktop Naver Map URLs (map.naver.com/p/entry/place/...), mobile Naver Place URLs (m.place.naver.com/...), naver.me shortlinks, or numeric Place IDs.

**Q: Does this scraper extract full restaurant menus and KRW prices?**
Yes. When includeMenus is enabled (default: true), every business record includes the full menus array with dish name, numeric KRW price, formatted price, menu description, isRecommended badge, and high-resolution menu photo.

**Q: Can I filter for photo-only visitor reviews or sort by newest?**
Yes. In reviews mode, set reviewSort to 'recent' (Newest) or 'recommend' (Most Relevant), and enable onlyPhotoReviews: true to collect exclusively receipt-verified visitor reviews with customer photos.

---

### 🚀 Naver Place Reviews Scraper (`unitbytes/naver-place-reviews-scraper`)

Scrape Naver Place reviews (네이버 플레이스 리뷰 · 블로그 리뷰) from `$0.50/1K`: receipt-verified visitor reviews, star ratings, voted sentiment keywords, owner replies, HD photos & linked Naver Blog posts by URL, ID or keyword. 영수증 방문자 리뷰, 별점, 사장님 답글, 블로그 리뷰 추출.

- **Pricing:** `$0.0008 / item` (Pay-Per-Event — `$0.0008` review scraped (volume tiers from `$0.0005`))
- **Cloud Console:** [https://apify.com/unitbytes/naver-place-reviews-scraper?fpr=939u3w&fp_sid=gh_naver](https://apify.com/unitbytes/naver-place-reviews-scraper?fpr=939u3w&fp_sid=gh_naver)
- **Full Documentation & Schema:** [https://unitbytes.com/actors/naver-place-reviews-scraper/](https://unitbytes.com/actors/naver-place-reviews-scraper/)
- **n8n Workflow File:** [`n8n/naver-place-reviews-scraper-n8n-workflow.json`](n8n/naver-place-reviews-scraper-n8n-workflow.json)
- **Engineering Playbook:** [How to Scrape Naver Map & Naver Place (2026): South Korea Business Leads, Menus & Visitor Reviews Guide (`$0.50–$1.00/1K`)](https://unitbytes.com/blog/how-to-scrape-naver-map-place-reviews-korea-business-leads-guide/)

#### Key Capabilities
- **Lowest Price on Apify Store:** Collect up to 5,000 visitor reviews and 500 blog reviews per business starting at `$0.0005` per review (Gold+ tier; `$0.80/1K` on Free tier) with zero extra charges for photos or parent place metadata.
- **Both Visitor Reviews & Blog Reviews:** Captures verified in-store customer reviews alongside long-form Naver Blog and Cafe review posts in one unified flat schema.
- **100% Server-Side Photo Review Filtering:** Filter directly on Naver's review server (isPhotoUsed) to pull exclusively reviews containing customer-uploaded photos without wasting quota on text-only reviews.
- **`$0.00` for Missing Targets or Empty Searches:** Non-existent Place IDs, zero-result queries, and input validation errors are never billed.

#### ⚙️ Input Parameters (Schema)

| Parameter | Type | Default / Prefill | Description |
| :--- | :---: | :--- | :--- |
| `placeUrls` | `array` | `["https://map.naver.com/p/entry/place/2000000001` | Direct Naver Map URLs (https://map.naver.com/p/entry/place/2000000001), Mobile Place URLs (https://m.place.naver.com/restaurant/2000000001/home), naver.me shortlinks, or numeric Place IDs (2000000001) to extract visitor & blog reviews from. |
| `queries` | `array` | — | Optional search keywords on Naver Map / Place (e.g., 강남 맛집, 성수동 카페, 강남 피부과). When provided, overrides the prefilled Place URL and extracts reviews across matching businesses. |
| `maxItems` | `integer` | `20` | Maximum total number of reviews (visitor + blog reviews) to collect across the run. |
| `maxReviewsPerPlace` | `integer` | `20` | Maximum number of receipt-verified visitor reviews (방문자 리뷰) to fetch per place (0–5000). Automatically scales up to maxItems when scraping direct Place URLs. |
| `onlyPhotoReviews` | `boolean` | `False` | Filter visitor reviews 100% server-side on Naver (isPhotoUsed) to only return reviews that include customer-uploaded photos. |
| `includeBlogReviews` | `boolean` | `True` | Include Naver Blog and Cafe review posts linked to each place (author name, post title, URL, snippet, date, and thumbnail). |
| `maxBlogReviewsPerPlace` | `integer` | `10` | Maximum number of linked Naver Blog / Cafe reviews to fetch per place. |
| `mode` | `string` | `reviews` | Outputs one flat row per review (reviews, default) or one row per place with embedded reviews (places). |
| `language` | `string` | `ko` | Language preference for Naver Place category and address fields (ko for original Korean, en for English localized strings where available). |
| `resumptionToken` | `string` | — | Optional compact continuation token emitted at the end of a previous batch run (RESUMPTION_TOKEN in Key-Value Store) to resume pagination with 0 duplicate overlap. |
| `proxyConfiguration` | `object` | `{"useApifyProxy": true}` | Proxy settings for accessing Naver Place review endpoints reliably. |

#### Python SDK Quickstart (`examples/run_naver_place_reviews_scraper.py`)
```python
from apify_client import ApifyClient

APIFY_TOKEN = os.getenv("APIFY_API_TOKEN", "YOUR_APIFY_API_TOKEN")
if not APIFY_TOKEN or APIFY_TOKEN.startswith("YOUR_"):
    raise SystemExit("Please set your Apify API token: export APIFY_API_TOKEN='apify_api_...'")

client = ApifyClient(APIFY_TOKEN)

run_input = {
    "placeUrls": ["https://map.naver.com/p/entry/place/2000000001"],
    "maxItems": 20,
    "maxReviewsPerPlace": 20,
    "onlyPhotoReviews": False,
    "includeBlogReviews": True,
    "maxBlogReviewsPerPlace": 10
}

run = client.actor("unitbytes/naver-place-reviews-scraper").call(run_input=run_input)

for item in client.dataset(run["defaultDatasetId"]).iterate_items():
    print(item.get("placeName"), item.get("bookingItemName"), item.get("authorNickname"))
```

#### Sample Output Schema (`samples/naver-place-reviews-scraper-sample.json`)
```json
{
  "reviewId": "670000000000000000000001",
  "reviewType": "visitor",
  "placeId": "2000000001",
  "placeName": "서울 미식 다이닝 강남점",
  "placeCategory": "한식",
  "businessCategory": "restaurant",
  "placeAddress": "서울 강남구 테헤란로 100 1층",
  "placeRating": 4.97,
  "placeUrl": "https://map.naver.com/p/entry/place/2000000001",
  "rating": 5.0,
  "title": null,
  "text": "숙성회가 정말 두툼하고 신선해요! 소금김밥이랑 같이 먹으면 궁합이 최고입니다. 직원분들도 친절하셔서 다음 모임 때 또 방문할 예정이에요.",
  "createdAt": "10.24.토",
  "visitedAt": "10.24.토",
  "visitCount": 2,
  "viewCount": 48,
  "verificationMethod": "영수증",
  "bookingItemName": "네이버 예약",
  "votedKeywords": [
    "음식이 맛있어요",
    "재료가 신선해요",
    "친절해요"
  ],
  "votedKeywordsText": "음식이 맛있어요, 재료가 신선해요, 친절해요, 매장이 넓어요",
  "mainPhotoUrl": "https://pup-review-phinf.pstatic.net/example_review_photo_01.jpg",
  "photoUrls": [
    "https://pup-review-phinf.pstatic.net/example_review_photo_01.jpg",
    "https://pup-review-phinf.pstatic.net/example_review_photo_02.jpg"
  ],
  "photoCount": 2,
  "hasPhotos": true,
  "authorId": "user_4c9b",
  "authorNickname": "reviewer_4a9c",
  "authorProfileUrl": "https://m.place.naver.com/my/user_4c9b/review",
  "authorImageUrl": null,
  "authorTotalReviews": 84,
  "ownerReplyText": "소중한 영수증 리뷰와 멋진 사진 감사드립니다! 언제나 신선한 숙성회로 보답하겠습니다.",
  "ownerReplyCreatedAt": "10.25.일",
  "reviewUrl": "https://m.place.naver.com/place/2000000001/review/visitor",
  "searchQuery": null,
  "language": "ko",
  "scrapedAt": "2026-10-28T12:00:00.000000+00:00"
}
```

#### Frequently Asked Questions
**Q: Do I need my own proxies or account login for naver-place-reviews-scraper?**
No. UnitBytes manages residential proxy rotation and automated request orchestration so you never need personal accounts or proxies.

**Q: What output formats are supported?**
All data can be downloaded in JSON, CSV, or Excel formats, or consumed directly via the Apify REST API and webhooks.

**Q: How does pricing work?**
You only pay for successful records extracted under Apify Pay-Per-Event pricing, with zero monthly minimums or idle compute costs.

**Q: Can this actor be integrated into automated workflows?**
Yes. You can trigger runs via Apify API, Python/JavaScript clients, Make, Zapier, or scheduled cron workflows.


---

## ⚡ Quick Installation & Local Usage

### 1. Run Interactively in Google Colab (Zero Local Setup)
Click **[Open in Google Colab ↗](https://colab.research.google.com/github/unitbytes/Naver-Map-Place-Scraper-API/blob/main/notebooks/quickstart.ipynb)** ([`notebooks/quickstart.ipynb`](notebooks/quickstart.ipynb)) to inspect the sample output DataFrame immediately and run live extractions in your browser without installing Python locally.

### 2. Run Locally with Python (`apify-client`)
```bash
git clone https://github.com/unitbytes/Naver-Map-Place-Scraper-API.git
cd Naver-Map-Place-Scraper-API
pip install -r requirements.txt
export APIFY_API_TOKEN="your_apify_api_token"
python examples/run_naver_map_scraper.py
```

### 3. Import into n8n (Self-Hosted or Cloud)
1. Open any `.json` file inside the [`n8n/`](n8n/) folder (or copy in 1 click from **[unitbytes.com/n8n](https://unitbytes.com/n8n/)** / **[n8n.io/creators/unitbytes](https://n8n.io/creators/unitbytes/)**).
2. Press **`Ctrl+V` / `Cmd+V`** directly onto your n8n workflow canvas.
3. Configure your Apify API Token in the `HTTP Header Auth` credential on Node `2. Run UnitBytes (...)` (and customize your search inputs in Node `1. Configure Search & Rules`), then click **Test Workflow**.

### 4. Use with AI Coding Agents (Cursor, Windsurf & Claude Code MCP)
This repository includes a ready-to-use Model Context Protocol configuration at [`.cursor/mcp.json`](.cursor/mcp.json) pointing to `https://mcp.apify.com` with this suite's UnitBytes actors pre-registered. Open this folder in **Cursor** or **Windsurf** to let your AI agent run live extractions and inspect schemas automatically.

---

## 💼 Need Done-For-You Datasets or Custom Pipelines?

Don't want to manage API tokens or scripts? **UnitBytes Data Delivery** provides ready-to-use **CSV, Excel (.xlsx), Google Sheets, or Webhook feeds** tailored to your exact target keywords, cities, or categories.

- 🌐 **Request a Sample Dataset:** [https://unitbytes.com/#enterprise-intake](https://unitbytes.com/#enterprise-intake)
- 📧 **Direct Engineering Contact:** [contact@unitbytes.com](mailto:contact@unitbytes.com)
- ⚡ **Explore All 41 Scrapers:** [https://unitbytes.com/actors/](https://unitbytes.com/actors/)
- 📚 **Engineering Playbooks & Guides:** [https://unitbytes.com/blog/](https://unitbytes.com/blog/)
- 🔗 **Official n8n Creator Profile:** [https://n8n.io/creators/unitbytes/](https://n8n.io/creators/unitbytes/)

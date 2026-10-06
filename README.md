<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Video Personalization &amp; Monetization (SSAI) Banner" width="100%" />
</p>

# 🎬 Awesome Video Personalization & Monetization (SSAI)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome List"/></a>
  <a href="https://github.com/topics/ssai"><img src="https://img.shields.io/badge/topic-SSAI-blue.svg" alt="Topic: SSAI"/></a>
  <a href="https://github.com/topics/video-streaming"><img src="https://img.shields.io/badge/topic-video--streaming-green.svg" alt="Topic: Video Streaming"/></a>
  <a href="https://github.com/topics/ad-insertion"><img src="https://img.shields.io/badge/topic-ad--insertion-orange.svg" alt="Topic: Ad Insertion"/></a>
  <a href="https://github.com/topics/video-monetization"><img src="https://img.shields.io/badge/topic-video--monetization-purple.svg" alt="Topic: Video Monetization"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 💡 **Curated Ecosystem Guide**: Commercial SaaS Platforms, Infrastructure Engines & Open-Source Projects for Server-Side Ad Insertion (SSAI), Server-Guided Ad Insertion (SGAI), Dynamic Ad Decisioning, VAST/VMAP Parsing, and Stream Personalization.

---

## 📋 Table of Contents

- [🌐 Overview & Industry Trends](#-overview--industry-trends)
- [📊 Market Landscape & Ecosystem Structure](#-market-landscape--ecosystem-structure)
- [🚀 SaaS & Hosted Enterprise Platforms](#-saas--hosted-enterprise-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [⚡ SSAI vs. SGAI vs. CSAI Architecture Comparison](#-ssai-vs-sgai-vs-csai-architecture-comparison)
- [📖 Key Standards & Protocols Glossary](#-key-standards--protocols-glossary)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🌐 Overview & Industry Trends

Server-Side Ad Insertion (**SSAI**), also known as Dynamic Ad Insertion (**DAI**), stitches targeted ad content directly into HTTP video stream manifests (HLS and MPEG-DASH) on the server side 📡. By eliminating client-side ad player dependencies and ad-blocking vulnerabilities 🛡️, SSAI provides broadcast-quality playback, reduced stream latency, and consistent video monetization across Connected TV (CTV), OTT apps, web players, and Smart TVs 📺.

Recent industry developments in **October 2026** focus on the transition toward **Server-Guided Ad Insertion (SGAI)**, utilizing native HLS Interstitials (`EXT-X-DATERANGE`) to combine server-side manifest control with client-side interactive telemetry and dynamic ad resolution ⚙️.

---

## 📊 Market Landscape & Ecosystem Structure

> 💡 **Market Size & Fragmented Sector Analysis**  
> The global **Server-Side Ad Insertion (SSAI) & Dynamic Ad Insertion market** is estimated at **$2.8 Billion USD**, growing at a **17.8% CAGR** within the broader **$320+ Billion digital video advertising market** 📈. The sector is **highly fragmented**—characterized by a mix of hyperscale Cloud Service Providers (AWS, Google), premium media ad-decisioning platforms (FreeWheel, Publica), broadcast infrastructure leaders (Harmonic, Broadpeak), specialty analytics vendors (MediaMelon, Yospace), and emerging open-source stitching engines (Eyevinn, Kaltura) 🧱. No single entity holds a dominant monopoly; publishers choose solutions based on CDN architecture, ad decisioning integrations, and monetization scale.

---

## 🚀 SaaS & Hosted Enterprise Platforms

The table below lists leading commercial SSAI, DAI, and ad decisioning platforms, sorted in descending order by **Company Valuation / Revenue Size** 🏆.

| 🏢 SaaS Platform & Solution | 🏛️ Parent / Operating Entity | 💰 Company Size / Valuation | 🏷️ Specific Starting Tier Pricing | 🎁 Free Tier & Free Trial Limits | 🎯 Key Features & Target Deployment |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Google Ad Manager DAI](https://admanager.google.com/)** | Alphabet Inc. (Google) | **$2.1 Trillion** *(Market Cap)* | **$0.010 – $0.015 CPM** *(Tech fee per 1,000 video ad inserts; bundled with GAM 360)* | **5 Million video impressions/month free** *(Standard GAM); 30-day Google Cloud $300 trial* | Industry-standard DAI for publishers with native Google Ad Manager programmatic demand. |
| **[AWS Elemental MediaTailor](https://aws.amazon.com/mediatailor/)** | Amazon Web Services (AWS) | **$2.0 Trillion** *(Market Cap)* | **$0.25 per 1,000 VOD inserts** / **$0.50 per 1,000 Live inserts** | **2 Months Free Tier** *(up to 1,000 ad inserts/mo) + $300 AWS trial credit* | Hyperscale AWS manifest manipulation with CloudFront & CloudWatch integration. |
| **[FreeWheel SSAI](https://www.freewheel.com/)** | Comcast Corporation | **$150 Billion** *(Market Cap)* | **$0.01 – $0.05 CPM** *(Tech fee per 1,000 ads; enterprise base tier from $5,000/mo)* | **No free tier**; *14-day dedicated staging/sandbox environment during sales onboarding* | Enterprise broadcast & pay-TV ad decisioning with advanced yield management. |
| **[Publica](https://www.publica.com/)** | Integral Ad Science (IAS) | **$1.8 Billion** *(Market Cap)* | **$0.03 – $0.10 CPM** *(Ad tech fee; minimum contract starting at $2,500/mo)* | **No free tier**; *30-day enterprise proof-of-concept (PoC) sandbox for qualified publishers* | Leading independent CTV ad server with header bidding & audience segmentation. |
| **[Harmonic SSAI (VOS360)](https://www.harmonicinc.com/)** | Harmonic Inc. | **$1.3 Billion** *(Market Cap)* | **$0.005 per ad insert** / **$0.04 per channel hour** *(Base plan from $500/mo)* | **30-Day Free Trial** *on VOS360 Cloud platform with $500 usage credits* | Broadcast-grade SaaS for low-latency live sports streaming & FAST channel stitching. |
| **[Equativ SSAI](https://equativ.com/)** | Equativ (Smart AdServer) | **$500 Million** *(Valuation)* | **5% – 10% Revenue Share** or **$0.02 – $0.08 CPM** *per delivered ad* | **No free tier**; *14-day publisher test environment during custom integration* | Unified programmatic ad server combining SSAI manifest manipulation with yield optimization. |
| **[Brightcove SSAI](https://www.brightcove.com/)** | Brightcove Inc. | **$80 Million** *(Market Cap)* | **$199/month starting plan** *(Includes Video Cloud streaming and basic SSAI delivery)* | **30-Day Free Trial** *(Includes 10 video uploads and 10,000 stream plays)* | End-to-end OTT video platform with integrated server-side ad stitching. |
| **[Broadpeak broadplay](https://broadpeak.tv/)** | Broadpeak S.A. | **$40 Million** *(Market Cap)* | **$0.004 per ad delivery** / **$0.005 per stream hour** *(Pay-as-you-go, min plan $50/mo)* | **30-Day Free Trial** *(Includes 1,000 ad insertions + 100 stream hours free)* | Smart CDN integration with edge-based SSAI manifest personalization. |
| **[Yospace](https://yospace.com/)** | RTL Group / SpotX | **$33 Million** *(Acquisition Price)* | **$0.01 – $0.03 per ad insert** *(Enterprise commitment baseline starting at $3,000/mo)* | **No free tier**; *30-day staging evaluation environment for broadcast network trials* | SSAI pioneer specializing in live event ad replacement with frame-accurate stitching. |
| **[MediaMelon SmartSight](https://www.mediamelon.com/)** | MediaMelon Inc. | **$20 Million** *(Valuation)* | **$99/month base plan** *($0.001 per stream hour + $0.002 per ad break session)* | **Free Developer Tier** *up to 10,000 stream views/month free forever* | Streaming QoE analytics paired with real-time SSAI optimization. |

---

## 🔓 Open-Source GitHub Projects

The following curated open-source engines, proxies, parsers, and companion tools are sorted in descending order by **GitHub Stars_Counts** ⭐. Each Stars_Badge links directly to the project's stargazers page.

1. **[kaltura/nginx-vod-module](https://github.com/kaltura/nginx-vod-module)** [![GitHub_Stars](https://img.shields.io/github/stars/kaltura/nginx-vod-module?style=social&color=white)](https://github.com/kaltura/nginx-vod-module/stargazers)  
   ⚡ **NGINX-based MP4 repackager & manifest stitcher** — Enables dynamic HLS and DASH manifest generation, live segment stitching, and SCTE-35 cue marker handling directly inside NGINX. Highly performant infrastructure choice for custom streaming setups.

2. **[openplayerjs/openplayerjs](https://github.com/openplayerjs/openplayerjs)** [![GitHub_Stars](https://img.shields.io/github/stars/openplayerjs/openplayerjs?style=social&color=white)](https://github.com/openplayerjs/openplayerjs/stargazers)  
   ▶️ **Lightweight HTML5 video/audio player with ad engine** — Offers seamless client and hybrid SSAI integration, supporting VAST, VMAP, SIMID, OMID, and non-linear ad rendering with SCTE-35 cue detection across modern web and Smart TV runtimes.

3. **[OpenVisualCloud/Ad-Insertion-Sample](https://github.com/OpenVisualCloud/Ad-Insertion-Sample)** [![GitHub_Stars](https://img.shields.io/github/stars/OpenVisualCloud/Ad-Insertion-Sample?style=social&color=white)](https://github.com/OpenVisualCloud/Ad-Insertion-Sample/stargazers)  
   🤖 **Intelligent reference SSAI pipeline with OpenVINO™** — Demonstrates how to build an end-to-end server-side ad insertion workflow combining microservices with AI-powered video analytics for targeted ad decisioning and segment replacement.

4. **[flipkart-incubator/madman-android](https://github.com/flipkart-incubator/madman-android)** [![GitHub_Stars](https://img.shields.io/github/stars/flipkart-incubator/madman-android?style=social&color=white)](https://github.com/flipkart-incubator/madman-android/stargazers)  
   📱 **High-performance Android video ad manager** — Developed by Flipkart as an open-source alternative to Google's standard IMA Android SDK. Provides full UI control, low latency, and direct custom VAST response rendering for native video applications.

5. **[Eyevinn/chaos-stream-proxy](https://github.com/Eyevinn/chaos-stream-proxy)** [![GitHub_Stars](https://img.shields.io/github/stars/Eyevinn/chaos-stream-proxy?style=social&color=white)](https://github.com/Eyevinn/chaos-stream-proxy/stargazers)  
   🧪 **Chaos engineering proxy for HTTP video streams** — Injects simulated latency, manifest errors, and segment drops into HLS/DASH streams. Essential tool for testing SSAI player failover mechanisms and client error handling.

6. **[basil79/ads-manager](https://github.com/basil79/ads-manager)** [![GitHub_Stars](https://img.shields.io/github/stars/basil79/ads-manager?style=social&color=white)](https://github.com/basil79/ads-manager/stargazers)  
   📦 **HTML5 Video Ads Manager library** — Built on top of `@dailymotion/vast-client`, providing scheduled linear and non-linear ad pod playback management for HTML5 video players.

7. **[dailymotion/vmap-js](https://github.com/dailymotion/vmap-js)** [![GitHub_Stars](https://img.shields.io/github/stars/dailymotion/vmap-js?style=social&color=white)](https://github.com/dailymotion/vmap-js/stargazers)  
   📋 **Official Dailymotion VMAP JavaScript parser** — Parses IAB VMAP (Video Multiple Ad Playlist) XML specs to structure complex ad schedules, break timings, and ad tag URLs for web streaming integrations.

8. **[Eyevinn/test-adserver](https://github.com/Eyevinn/test-adserver)** [![GitHub_Stars](https://img.shields.io/github/stars/Eyevinn/test-adserver?style=social&color=white)](https://github.com/Eyevinn/test-adserver/stargazers)  
   🛠️ **Specialized testing ad server for SSAI development** — Consistently outputs standardized VAST/VMAP test payloads, records incoming request headers and query parameters, and exposes a Swagger UI for validating SSAI manifest proxies.

9. **[glomex/vast-ima-player](https://github.com/glomex/vast-ima-player)** [![GitHub_Stars](https://img.shields.io/github/stars/glomex/vast-ima-player?style=social&color=white)](https://github.com/glomex/vast-ima-player/stargazers)  
   🎮 **Convenience video wrapper for Google IMA SDK** — Simplifies embedding Google Interactive Media Ads (IMA) HTML5 SDK into standard web players for linear video ad serving.

10. **[SimpleSSAI/SimpleSSAI](https://github.com/SimpleSSAI/SimpleSSAI)** [![GitHub_Stars](https://img.shields.io/github/stars/SimpleSSAI/SimpleSSAI?style=social&color=white)](https://github.com/SimpleSSAI/SimpleSSAI/stargazers)  
    🚀 **API-driven server-side ad insertion engine** — Lightweight open-source solution designed for stitching ad breaks into HLS stream manifests to bypass ad blockers with minimal configuration overhead.

11. **[Eyevinn/vast-info](https://github.com/Eyevinn/vast-info)** [![GitHub_Stars](https://img.shields.io/github/stars/Eyevinn/vast-info?style=social&color=white)](https://github.com/Eyevinn/vast-info/stargazers)  
    🔍 **VAST/VMAP inspection CLI & Node module** — Command-line utility to parse, validate, and display human-readable diagnostic trees from complex VAST and VMAP XML responses.

12. **[Eyevinn/sgai-ad-proxy](https://github.com/Eyevinn/sgai-ad-proxy)** [![GitHub_Stars](https://img.shields.io/github/stars/Eyevinn/sgai-ad-proxy?style=social&color=white)](https://github.com/Eyevinn/sgai-ad-proxy/stargazers)  
    📡 **Experimental Server-Guided Ad Insertion (SGAI) HTTP proxy** — Implements Apple HLS Interstitial tags (`EXT-X-DATERANGE`) to deliver personalized ad breaks with dynamic macro replacements (`[template.duration]`, `[template.sessionId]`).

13. **[dds05/videojs-mediatailor-ssai](https://github.com/dds05/videojs-mediatailor-ssai)** [![GitHub_Stars](https://img.shields.io/github/stars/dds05/videojs-mediatailor-ssai?style=social&color=white)](https://github.com/dds05/videojs-mediatailor-ssai/stargazers)  
    🔌 **Video.js plugin for AWS Elemental MediaTailor** — Automates client-side tracking beacon firing, UI controls, and ad break state sync when streaming MediaTailor-stitched HLS feeds.

14. **[aviral-zype/videojs-vast-plugins](https://github.com/aviral-zype/videojs-vast-plugins)** [![GitHub_Stars](https://img.shields.io/github/stars/aviral-zype/videojs-vast-plugins?style=social&color=white)](https://github.com/aviral-zype/videojs-vast-plugins/stargazers)  
    📺 **Single video element VAST/VMAP plugin for VideoJS** — Lightweight VideoJS plugin optimized for HTML5 Smart TV devices, offering preroll, midroll, and postroll execution without multiple DOM elements.

15. **[matvp91/hlspresso](https://github.com/matvp91/hlspresso)** [![GitHub_Stars](https://img.shields.io/github/stars/matvp91/hlspresso?style=social&color=white)](https://github.com/matvp91/hlspresso/stargazers)  
    ⚡ **Edge-native HLS interstitial insertion proxy** — Lightweight proxy built for Cloudflare Workers and AWS Lambda. Dynamically injects HLS Interstitial markers on the fly driven by manual APIs or VMAP schedules.

16. **[etf1/IAB](https://github.com/etf1/IAB)** [![GitHub_Stars](https://img.shields.io/github/stars/etf1/IAB?style=social&color=white)](https://github.com/etf1/IAB/stargazers)  
    📝 **TypeScript IAB VAST & VMAP parser library** — Node.js library for strict parsing, validation, and object serialization of Interactive Advertising Bureau (IAB) VAST and VMAP specs.

17. **[Eyevinn/ritcher](https://github.com/Eyevinn/ritcher)** [![GitHub_Stars](https://img.shields.io/github/stars/Eyevinn/ritcher?style=social&color=white)](https://github.com/Eyevinn/ritcher/stargazers)  
    🦀 **Production-grade Rust-based HLS/DASH manifest stitcher** — High-performance open-source SSAI and SGAI stitching engine featuring VAST tag resolution, Valkey/Redis distributed session storage, Prometheus observability, and frame-accurate segment replacement.

---

## ⚡ SSAI vs. SGAI vs. CSAI Architecture Comparison

| 📐 Feature / Dimension | 💻 Client-Side Ad Insertion (CSAI) | 🖥️ Server-Side Ad Insertion (SSAI) | 📡 Server-Guided Ad Insertion (SGAI) |
| :--- | :--- | :--- | :--- |
| **Manifest Manipulation** | Client player fetches separate ad manifests. | Server rewrites manifest to stitch ad segments into main stream. | Server inserts `EXT-X-DATERANGE` interstitial tags; client fetches ad playlist. |
| **Ad Blocker Resilience** | Vulnerable (easy to block client ad requests). | Highly resistant (ad traffic is part of primary video stream). | High (interstitial asset requests mimic main content stream). |
| **Playback Seamlessness** | Potential buffering between content and ad. | Zero buffering; seamless broadcast-like experience. | Smooth transition managed natively by modern OS media frameworks. |
| **Client Analytics & Interactivity** | Full DOM/SDK access (clickable CTAs, overlay cards). | Requires client tracking proxy or sideband beaconing. | Combines native client events with server-managed ad schedules. |

---

## 📖 Key Standards & Protocols Glossary

- **SSAI (Server-Side Ad Insertion)**: Technology that stitches ad content directly into master streaming playlists (HLS/DASH) at the media server level 🖥️.
- **SGAI (Server-Guided Ad Insertion)**: Standard utilizing HLS Interstitial structures to allow servers to signal ad breaks while clients fetch and render standalone ad playlists seamlessly 📡.
- **VAST (Digital Video Ad Serving Template)**: Universal IAB XML schema enabling ad servers to supply video creative URLs, tracking pixels, and metadata to video players 📜.
- **VMAP (Video Multiple Ad Playlist)**: Standard XML format describing ad break schedules (preroll, midroll, postroll) across video content timelines ⏱️.
- **SCTE-35**: Signaling standard used in digital video streams to trigger downstream ad insertion breaks and splice points ⚡.

---

## 🤝 How to Contribute

Contributions are welcome! Please follow these simple guidelines:

1. 🍴 Fork this repository.
2. 🌿 Create a new topic branch (`git checkout -b feature/add-new-project`).
3. 📝 Add your entry to `README.md` maintaining the existing table or list structure. Ensure GitHub links and Stars_Badges are included for open-source repositories.
4. 📬 Submit a Pull Request detailing the solution features and target deployment.

---

## 💖 Support & Sponsorship

Thank you for exploring the **Awesome Video Personalization & Monetization (SSAI)** ecosystem repository! 🌟

If you find this curated reference list helpful for your video engineering projects, adtech research, or streaming architecture builds, please consider supporting the project:

- ⭐ **Star this repository** on GitHub to increase its visibility.
- 🔀 **Fork and share** it with your fellow video engineers, ad ops teams, and developers.
- 📢 **Spread the word** on LinkedIn, Twitter/X, Discord, and streaming developer forums.

### ☕ Buy Me a Coffee / Sponsor
If you'd like to sponsor the ongoing maintenance, expansion, and research behind this repository, you can sponsor the project via GitHub Sponsors:

👉 **[Sponsor on GitHub Sponsors](https://github.com/sponsors/ishandutta2007)** 💖

Your support helps keep this ecosystem repository up to date with the latest commercial platforms, open-source stitchers, and ad insertion specs!

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Video-Personalization-Monetization-SSAI&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Video-Personalization-Monetization-SSAI&type=date&legend=top-left)

---

## ⚠️ Disclaimer

This repository is a community-curated collection intended for educational and informational purposes. Mention of commercial enterprise platforms or open-source software does not constitute an endorsement. SSAI implementations must adhere to user privacy frameworks (GDPR, CCPA) and IAB advertising standards.

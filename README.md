# Awesome-Video-Personalization-Monetization-SSAI

## Top Video Personalization & Monetization (SSAI) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Server-Side Ad Insertion, Dynamic Ad Decisioning & Open-Source Stitching Engines*  

**Last updated: October 2026**



This repository tracks notable **commercial SSAI platforms** and **open-source projects** that stitch personalized ads into video streams server-side — providing a seamless, ad-blocker-resistant viewing experience for live and VOD content. These tools handle manifest manipulation, ad decisioning, and segment replacement without requiring client-side ad players.



**Examples** include AWS Elemental MediaTailor, Google Ad Manager DAI, Harmonic SSAI, Brightcove SSAI, Broadpeak broadplay, FreeWheel SSAI, Publica, Equativ SSAI, MediaMelon, and Yospace (the category leaders).



**Open-source emphasis**: SSAI is a growing open-source domain. **Ritcher (Eyevinn)** leads as a production-grade Rust-based HLS/DASH stitcher with VAST and SGAI support . **SGAI Ad Proxy (Eyevinn)** provides server-guided ad insertion with ad personalization . **HLSpresso** offers a lightweight HLS proxy for interstitials . **OpenVisualCloud Ad-Insertion-Sample** demonstrates intelligent SSAI with OpenVINO . **Eyevinn Test Adserver** provides the essential testing infrastructure for SSAI workflows . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Elemental MediaTailor](https://aws.amazon.com/mediatailor/)**  

  **The leading cloud SSAI platform** — performs real-time manifest manipulation and ad insertion for live and VOD streams. **Personalization at scale** — each viewer can receive a unique manifest with targeted ads. **Deep AWS integration** with CloudFront, S3, and CloudWatch analytics . **Best for AWS-native video workflows** .



- **[Google Ad Manager DAI](https://admanager.google.com/)**  

  Google's Dynamic Ad Insertion — server-side stitching for live and VOD with Ad Manager integration. **The standard for Google Ad Manager users** .



- **[Harmonic SSAI](https://www.harmonicinc.com/)**  

  Enterprise SSAI with manifest manipulation, ad decisioning, and low-latency support. **Best for broadcast-grade deployments** .



- **[Brightcove SSAI](https://www.brightcove.com/)**  

  SSAI integrated with Brightcove's video platform — seamless ad insertion for live and VOD.



- **[Broadpeak broadplay](https://broadpeak.tv/)**  

  SSAI and streaming optimization with CDN integration. **Best for CDN-integrated deployments** .



- **[FreeWheel SSAI](https://www.freewheel.com/)**  

  Comcast's SSAI solution with advanced ad decisioning and measurement.



- **[Publica](https://www.publica.com/)**  

  **The leading independent SSAI platform** — server-side ad insertion with audience targeting and measurement.



- **[Equativ SSAI](https://equativ.com/)**  

  SSAI with programmatic ad decisioning and yield optimization.



- **[MediaMelon](https://www.mediamelon.com/)**  

  Streaming intelligence and SSAI optimization with QoE analytics.



- **[Yospace](https://yospace.com/)**  

  **The pioneer of SSAI** — server-side ad insertion with dynamic ad decisioning and seamless playback.



## Open-Source GitHub Projects



- **[Ritcher (Eyevinn)](https://github.com/Eyevinn/ritcher)**  

  **The leading open-source SSAI stitcher**, Rust-based with **production-grade HLS and DASH support** . **Two stitching modes**: `ssai` (replaces content segments with ad segments server-side) and `sgai` (injects HLS Interstitial `EXT-X-DATERANGE` tags for client-side ad fetching) . **VAST ad provider** with `[DURATION]` and `[CACHEBUSTING]` macro support, plus static ad fallback . **Prometheus metrics** at `/metrics`, health checks, and JSON session management . **Distributed sessions** via Valkey/Redis for load-balanced deployments . **Demo mode** with built-in test streams for immediate testing . **Best for production SSAI with Rust performance** .



- **[SGAI Ad Proxy (Eyevinn)](https://github.com/Eyevinn/sgai-ad-proxy)**  

  **Experimental HTTP proxy for Server Guided Ad Insertion (SGAI)**, designed for players that support SGAI (e.g., QuickTime Player, Safari) . **Inserts ads into the media playlist as interstitials** at specified time points . **Ad personalization via query parameters** — ad server URL can include `[template.duration]`, `[template.sessionId]`, and `[template.pod]` placeholders replaced dynamically . **Session-specific ad requests** via master playlist URL query parameters . **Dynamic ad break insertion** via `/command?in=5&dur=10&pod=2` endpoint . **Best for SGAI testing and personalization research** .



- **[HLSpresso](https://github.com/matvp91/hlspresso)**  

  **Lightweight HLS proxy that inserts HLS interstitials on the fly**, designed for edge and serverless platforms (Cloudflare Workers, AWS Lambda) . **VOD with precise insertion points**, manual or VMAP-driven . **VAST support** (up to 4 ads) . **Live streams with CUE-IN and CUE-OUT markers** for ad replacement . **Ad Creative Signaling (SVTA2053-2) spec** support . **API-driven session creation** via `POST /api/v1/sessions` . **Best for edge-based SSAI with minimal infrastructure** .



- **[OpenVisualCloud Ad-Insertion-Sample](https://github.com/OpenVisualCloud/Ad-Insertion-Sample)**  

  **Intelligent server-side ad insertion reference pipeline**, open-source with **OpenVINO analytics** . **Demonstrates how to integrate media building blocks** for SSAI workflows . **Best for understanding SSAI pipeline architecture with AI-powered ad decisioning** .



- **[Eyevinn Test Adserver](https://github.com/Eyevinn/test-adserver)**  

  **Specialized testing service for SSAI workflows**, open-source . **Always returns ads** in standardized VAST/VMAP format for consistent testing . **Comprehensive tracking** — stores query parameters and tracks playback events . **Custom ad support** via MRSS feed . **Swagger API documentation** with session management endpoints . **Best for validating SSAI implementations before production** .



- **[SimpleSSAI](https://github.com/SimpleSSAI/SimpleSSAI)**  

  **Simple API-driven Server Side Ad Insertion**, open-source . **Easy-to-use solution for stitching ads into content** to protect ad monetization . **Best for lightweight SSAI proof-of-concept** .



- **[OpenPlayerJS Ads Plugin](https://www.npmjs.com/package/@openplayerjs/ads)**  

  **Hybrid CSAI/SSAI ad plugin for HLS players**, open-source . **Hybrid mode combines CSAI rendering with SCTE-35 cue detection** — `resolveScteUrl` maps splice-out cues to VAST tag URLs . **Async URL resolution** — call your ad decision server and skip cues via `null` return . **Static breaks for preroll** alongside SCTE-triggered midrolls . **Waterfall ad sources** with fallback to house ads . **Best for HLS players needing hybrid ad strategies** .



- **[hlspresso](https://github.com/matvp91/hlspresso)** — Already listed. **Edge-based HLS interstitial insertion** .



### Client-Side Ad Libraries (Companion Tools)



- **[VideoJS VAST Plugin](https://github.com/aviral-zype/videojs-vast-plugins)**  

  **VAST/VMAP ad plugin for VideoJS**, open-source . **Full control over player UI during ads** — no opinionated ad UI . **Preroll, midroll, and postroll support** for HTML5 Smart TVs . **CTA clickzone and skip button handling** via events . **Best for VideoJS players needing client-side ads** .



- **[dailymotion/vmap-js](https://github.com/dailymotion/vmap-js)**  

  **VMAP JavaScript library** for ad schedule parsing . **Best for VMAP-compliant ad scheduling** .



- **[basil79/ads-manager](https://github.com/basil79/ads-manager)**  

  **HTML5 Video Ads Manager** based on Dailymotion VAST client . **Best for HTML5 video ad management** .



- **[etf1/IAB](https://github.com/etf1/IAB)**  

  **IAB VAST & VMAP formats handling for Node.js**, TypeScript . **Best for Node.js ad server integrations** .



### Additional Strong Open-Source Options



- **Google Cloud Video Stitcher API** — Cloud-based SSAI with ad decisioning, Apache-2.0 licensed client libraries .

- **flipkart-incubator/madman-android** — High-performance alternative to Google IMA Android SDK for VAST rendering .

- **glomex/vast-ima-player** — Convenience wrapper for Google IMA HTML5 SDK .

- **ExoPlayer IMA Extension** — Client-side and server-side ad insertion for Android, integrates IMA DAI SDK .



**Frameworks for building custom SSAI solutions**: Combine **Ritcher** for production-grade SSAI with HLS/DASH support, VAST decisioning, and Prometheus observability . Use **SGAI Ad Proxy** for server-guided ad insertion with personalization via query parameters . Deploy **HLSpresso** for edge-based interstitial insertion on Cloudflare Workers or AWS Lambda . Integrate **Eyevinn Test Adserver** for SSAI workflow validation before production . Use **OpenVisualCloud Ad-Insertion-Sample** for AI-powered ad decisioning with OpenVINO . Note that true enterprise SSAI with global CDN integration, real-time ad decisioning at scale, and vendor-supported SLAs (MediaTailor, Yospace, Publica) remains primarily commercial territory; open-source stacks provide strong stitching engines, ad decisioning, and testing foundations that require integration for complete monetization workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- SSAI platforms manipulate video manifests and insert ads into streams. **Ad decisioning and targeting involve user data** — ensure compliance with privacy regulations (GDPR, CCPA) and ad industry standards.

- **SSAI is designed to resist ad blockers** — this is a feature for monetization but raises ethical considerations around user consent and transparency.

- **Open-source SSAI tools vary in maturity** — Ritcher is production-grade; SGAI Ad Proxy and HLSpresso are experimental . Evaluate before relying on them for critical monetization.

- **CDN configuration is critical for SSAI performance** — each viewer may receive a unique manifest, which fragments caching. MediaTailor documentation provides detailed CDN optimization guidance .

- The open-source ecosystem provides strong stitching engines, ad decisioning, and testing foundations, but **global CDN integration, real-time decisioning at scale, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for video engineers, ad operations teams, and streaming platform developers.**

Let's make video personalization and monetization more open, transparent, and efficient.

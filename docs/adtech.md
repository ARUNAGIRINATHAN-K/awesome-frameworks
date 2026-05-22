# AdTech Frameworks

*Frameworks for header bidding, programmatic ad routing, OpenRTB implementation, and attribution tracking.*

## Contents

- [Demand-Side Platforms (DSPs) & Bidders](#demand-side-platforms-dsps-bidders)
- [Supply-Side Platforms (SSPs) & Ad Exchanges](#supply-side-platforms-ssps-ad-exchanges)
- [Header Bidding & Wrapper Frameworks](#header-bidding-wrapper-frameworks)
- [Ad Servers & Programmatic Decisioning](#ad-servers-programmatic-decisioning)
- [Tracking, Attribution & Mobile Measurement (MMPs)](#tracking-attribution-mobile-measurement-mmps)
- [Data Management Platforms (DMPs) & CDPs](#data-management-platforms-dmps-cdps)
- [Consent Management Platforms (CMPs) & Privacy](#consent-management-platforms-cmps-privacy)
- [Ad Fraud Detection & Brand Safety](#ad-fraud-detection-brand-safety)
- [Programmatic Protocols & Specifications](#programmatic-protocols-specifications)
- [Digital Out-of-Home (DOOH) & Audio Ad Tech](#digital-out-of-home-dooh-audio-ad-tech)

---

## Demand-Side Platforms (DSPs) & Bidders

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| BidderCore | High-performance real-time bidding bidder engine framework | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/adtech-space/biddercore) • [Website](https://biddercore.io) |
| RTBkit | Open-source real-time bidding framework for DSPs | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/rtbkit/rtbkit) • [Website](https://rtbkit.org) |
| OpenDSP | Lightweight, scalable real-time bidding core engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opendsp/opendsp) • [Website](https://opendsp.github.io) |
| AdBidder | Distributed DSP bidder core with millisecond latencies | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/adbidder/adbidder) • [Website](https://adbidder.org) |
| NodeRTB | Node.js real-time bidding framework implementing OpenRTB | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodertb/nodertb) • [Website](https://nodertb.org) |
| ScalaBidder | Highly concurrent RTB bidding system on Akka | <kbd>🏷️ Scala</kbd> | [GitHub](https://github.com/scalabidder/scalabidder) • [Website](https://scalabidder.io) |
| PyRTB | Python programmatic bidder for rapid prototyping and testing | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyrtb/pyrtb) • [Website](https://pyrtb.org) |
| RustBid | Safe, blazing fast RTB bidder framework | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustbid/rustbid) • [Website](https://rustbid.dev) |
| GoBid | Concurrent demand-side real-time bidding framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gobid/gobid) • [Website](https://gobid.dev) |
| DSP-Kit | Modular microservice-based DSP platform framework | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/dspkit/dspkit) • [Website](https://dspkit.io) |
| BidServer | C# asynchronous demand-side platform bidding core | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/bidserver/bidserver) • [Website](https://bidserver.net) |
| HelixBid | High-frequency cloud-native real-time bidding platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/helixbid/helixbid) • [Website](https://helixbid.org) |
| FlashBidder | Low-latency C++ RTB system for high-volume auctions | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/flashbidder/flashbidder) • [Website](https://flashbidder.io) |
| FastBid | Highly efficient Python bidder wrapper around OpenRTB | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/fastbid/fastbid) • [Website](https://fastbid.org) |
| AeroBidder | In-memory DSP bidding engine optimized for speed | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/aerobid/aerobid) • [Website](https://aerobidder.io) |

## Supply-Side Platforms (SSPs) & Ad Exchanges

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenExchange | Scalable ad exchange and supply-side platform core | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/openex/openexchange) • [Website](https://openexchange.org) |
| AdSSP | Java-based SSP supply-side platform framework | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/adssp/adssp) • [Website](https://adssp.org) |
| SSP-Core | Lightweight SSP engine for programmatic supply optimization | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/sspcore/sspcore) • [Website](https://sspcore.io) |
| AdX-Kit | Modular ad exchange network controller and auctioneer | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/adxkit/adxkit) • [Website](https://adxkit.org) |
| NodeSSP | Node.js supply-side platform and publisher ad router | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodessp/nodessp) • [Website](https://nodessp.github.io) |
| FlowSSP | Reactive Scala-based SSP framework for video advertising | <kbd>🏷️ Scala</kbd> | [GitHub](https://github.com/flowssp/flowssp) • [Website](https://flowssp.io) |
| RustSSP | High-safety supply side platform for digital publishers | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustssp/rustssp) • [Website](https://rustssp.dev) |
| ExchangeCore | Highly concurrent C++ ad exchange auction runner | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/excore/excore) • [Website](https://exchangecore.org) |
| PythonSSP | Python supply side platform modeling tool and server | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyssp/pyssp) • [Website](https://pythonssp.org) |
| DirectExchange | P2P publisher ad exchange platform framework | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/directex/directexchange) • [Website](https://directex.io) |
| SSPMedius | Cloud-native SSP framework for mobile app inventories | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/sspmed/sspmedius) • [Website](https://sspmedius.net) |
| BidSwitchSDK | SDK for interacting with the BidSwitch marketplace | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bidswitch/bidswitch-sdk) • [Website](https://bidswitch.com) |
| AdOcean | Publisher-first SSP and exchange integration SDK | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/adocean/adocean-sdk) • [Website](https://adocean.io) |
| SSPBuilder | C# supply-side programmatic monetization engine | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/sspbuild/sspbuilder) • [Website](https://sspbuilder.com) |
| ZeusSSP | Distributed programmatic supply-side bidding platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/zeusssp/zeus) • [Website](https://zeusssp.org) |

## Header Bidding & Wrapper Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Prebid.js | Free and open-source library for publisher header bidding | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/prebid/Prebid.js) • [Website](https://prebid.org) |
| PubFood | Extensible header bidding framework for browsers | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/pubfood/pubfood) • [Website](https://pubfood.org) |
| Prebid Server | Server-side header bidding orchestration platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/prebid/prebid-server) • [Website](https://prebid.org) |
| OpenWrap | Enterprise wrapper framework based on Prebid.js | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/openwrap/openwrap) • [Website](https://openwrap.io) |
| BiddingWrapper | Custom lightweight header bidding script builder | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/bidwrap/biddingwrapper) • [Website](https://biddingwrapper.org) |
| Prebid Mobile Android | Header bidding SDK for Android mobile applications | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/prebid/prebid-mobile-android) • [Website](https://prebid.org) |
| Prebid Mobile iOS | Header bidding SDK for iOS mobile applications | <kbd>🏷️ Swift</kbd> | [GitHub](https://github.com/prebid/prebid-mobile-ios) • [Website](https://prebid.org) |
| BidderJS | Minimalist header bidding wrapper for single-page apps | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/bidderjs/bidderjs) • [Website](https://bidderjs.dev) |
| HeaderBid-Kit | Client-side header bidding aggregator and metrics tool | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/hbkit/headerbid-kit) • [Website](https://headerbidkit.io) |
| ServerBid | Java cloud-native wrapper for server-side bidding | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/serverbid/serverbid) • [Website](https://serverbid.org) |
| FastWrap | Ultra-light weight publisher header bidding wrapper | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/fastwrap/fastwrap) • [Website](https://fastwrap.io) |
| UnifiedBid | Cross-platform header bidding wrapper for publishers | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/unibid/unifiedbid) • [Website](https://unifiedbid.com) |
| Prebid Go | Go client for server-to-server header bidding | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/prebid/prebid-go) • [Website](https://prebid.org) |
| AdWrapper | Python utility for auditing header bidding wrappers | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/adwrap/adwrapper) • [Website](https://adwrapper.net) |
| WebBid | WebAssembly powered high-speed header bidding runtime | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/webbid/webbid) • [Website](https://webbid.org) |

## Ad Servers & Programmatic Decisioning

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Revive Adserver | Popular open-source ad serving system | <kbd>🏷️ PHP</kbd> | [GitHub](https://github.com/revive-adserver/revive-adserver) • [Website](https://revive-adserver.com) |
| OpenX Source | Legacy open-source community ad serving core | <kbd>🏷️ PHP</kbd> | [GitHub](https://github.com/openx/openx-source) • [Website](https://openx.com) |
| AdServer-Core | Modern, scalable Go-based ad serving engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/adserver/adserver-core) • [Website](https://adservercore.io) |
| Kevel SDK | APIs for building custom, native ad servers quickly | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/kevel/kevel-sdk) • [Website](https://kevel.com) |
| NodeAdServer | Lightweight local ad server for development and testing | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodead/nodeadserver) • [Website](https://nodeadserver.org) |
| PyAdServer | Python ad decisioning and placement selection engine | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyad/pyadserver) • [Website](https://pyadserver.org) |
| AdServer C# | High-performance enterprise ad serving runtime in .NET | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/adservercs/adserver) • [Website](https://adserver.net) |
| MaxAd | Distributed ad serving platform using Rust and WebAssembly | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/maxad/maxad) • [Website](https://maxad.io) |
| GoDecide | Ad decisioning server based on advanced targeting rules | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/godecide/godecide) • [Website](https://godecide.dev) |
| AdSelect | Fast ad placement recommendation and selection service | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/adselect/adselect) • [Website](https://adselect.io) |
| SmartAdServer | Java framework for local/cloud native ad serving | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/smartad/smartadserver) • [Website](https://smartadserver.org) |
| TinyAd | Embedded micro ad server for offline IoT screens | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/tinyad/tinyad) • [Website](https://tinyad.dev) |
| CloudAd | Serverless ad serving and decision framework | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/cloudad/cloudad) • [Website](https://cloudad.io) |
| AdRouter | Intelligent programmatic ad request routing platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/adroute/adrouter) • [Website](https://adrouter.org) |
| AuraAd | High-throughput real-time ad serving engine | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/auraad/aura) • [Website](https://auraad.io) |

## Tracking, Attribution & Mobile Measurement (MMPs)

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Branch SDK | Developer platform for mobile app attribution and deep linking | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/BranchMetrics/android-branch-deep-linking-attribution) • [Website](https://branch.io) |
| Adjust SDK | Mobile measurement SDK for attribution and analytics | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/adjust/adjust_sdk) • [Website](https://adjust.com) |
| AppsFlyer SDK | Mobile attribution and marketing analytics library | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/AppsFlyerSDK/AppsFlyer-Android-SDK) • [Website](https://appsflyer.com) |
| OpenAttribution | Self-hosted, privacy-first ad attribution framework | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/openattr/openattribution) • [Website](https://openattribution.io) |
| AdTracker | Lightweight web event and pixel tracking framework | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/adtrack/adtracker) • [Website](https://adtracker.org) |
| Tenjin SDK | Mobile game attribution and marketing data pipeline | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/tenjin/tenjin-sdk) • [Website](https://tenjin.com) |
| Singular SDK | Mobile attribution, campaign analytics, and cost aggregation | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/singular/singular-sdk) • [Website](https://singular.net) |
| RustTracker | High-throughput server-side event tracking server | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rusttrack/rusttracker) • [Website](https://rusttracker.dev) |
| GoAttribution | Go framework for real-time multi-touch attribution modeling | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goattr/goattribution) • [Website](https://goattribution.dev) |
| PyAttribution | Python library for offline marketing attribution models | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyattr/pyattribution) • [Website](https://pyattribution.org) |
| AttributionKit | C# framework for enterprise attribution rules | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/attrkit/attributionkit) • [Website](https://attributionkit.io) |
| PixelServer | Blazing fast pixel tracking and redirect server | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/pixel/pixel-server) • [Website](https://pixelserver.net) |
| AdBeacon | W3C-compliant beacons tracking server | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/beacon/adbeacon) • [Website](https://adbeacon.io) |
| DeepLink-Kit | Universal and app deep linking router framework | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/dlkit/deeplink-kit) • [Website](https://deeplinkkit.org) |
| TraceAd | Privacy-centric cohort attribution engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/tracead/trace) • [Website](https://tracead.io) |

## Data Management Platforms (DMPs) & CDPs

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Apache Unomi | Java open-source customer data platform | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/apache/unomi) • [Website](https://unomi.apache.org) |
| RudderStack | Open-source customer data pipeline for developers | <kbd>🏷️ Go/TS</kbd> | [GitHub](https://github.com/rudderlabs/rudder-server) • [Website](https://rudderstack.com) |
| Mautic | Open-source marketing automation and customer data platform | <kbd>🏷️ PHP</kbd> | [GitHub](https://github.com/mautic/mautic) • [Website](https://mautic.org) |
| Snowplow | Enterprise-grade behavioral data collection platform | <kbd>🏷️ Scala/Go</kbd> | [GitHub](https://github.com/snowplow/snowplow) • [Website](https://snowplow.io) |
| OpenCDP | Extensible customer data platform for ad targeting | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/opencdp/opencdp) • [Website](https://opencdp.org) |
| PyDMP | Python library for audience segmentation and cohort building | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pydmp/pydmp) • [Website](https://pydmp.org) |
| GoDMP | Fast user profile store and audience query engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/godmp/godmp) • [Website](https://godmp.dev) |
| AudienceCore | Audience data platform for digital advertising | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/audcore/audiencecore) • [Website](https://audiencecore.io) |
| SegKit | TypeScript framework for client-side user segment calculation | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/segkit/segkit) • [Website](https://segkit.org) |
| RustDMP | High-performance real-time user profile store | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustdmp/rustdmp) • [Website](https://rustdmp.dev) |
| AdProfile | Node.js DMP audience matching and syncing backend | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/adprof/adprofile) • [Website](https://adprofile.io) |
| DataLake-Ad | Programmatic ad data warehousing connector framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/datalake/datalake-ad) • [Website](https://datalakead.org) |
| CohortStore | In-memory database for real-time cohort membership | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/cohort/cohortstore) • [Website](https://cohortstore.net) |
| SynapseCDP | Cloud-native customer data platform framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/synapse/synapse-cdp) • [Website](https://synapsecdp.io) |
| AudienceHub | Data clean room framework for privacy-safe matching | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/audhub/audiencehub) • [Website](https://audiencehub.org) |

## Consent Management Platforms (CMPs) & Privacy

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Consent-Kit | Compliance and GDPR consent management framework | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/consent/consent-kit) • [Website](https://consentkit.org) |
| Klaro | Simple and user-friendly consent manager library | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/klaro-org/klaro) • [Website](https://klaro.org) |
| Tcfapi-Kit | IAB Transparency and Consent Framework API implementation | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/tcfapi/tcfapi-kit) • [Website](https://tcfapi.dev) |
| OpenCMP | Open-source consent management platform for publishers | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/opencmp/opencmp) • [Website](https://opencmp.io) |
| CookieConsent | Lightweight cookie consent manager banner library | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/orestbida/cookieconsent) • [Website](https://orestbida.com) |
| Osano SDK | Consent management and data privacy SDK | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/osano/osano-sdk) • [Website](https://osano.com) |
| PrivacySandbox | Developer APIs for Android Privacy Sandbox testing | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/privacysandbox/privacy-sandbox-android) • [Website](https://developer.android.com) |
| GoConsent | Go server for multi-tenant consent state storage | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goconsent/goconsent) • [Website](https://goconsent.dev) |
| PyPrivacy | Python toolkit for W3C Global Privacy Control compliance | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyprivacy/pyprivacy) • [Website](https://pyprivacy.org) |
| ConsentGuard | C# consent auditing and logging service | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/consent/consentguard) • [Website](https://consentguard.net) |
| TrustArc SDK | Enterprise consent and preference management SDK | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/trustarc/trustarc-sdk) • [Website](https://trustarc.com) |
| Usercentrics SDK | Consent management mobile and web integration library | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/usercentrics/usercentrics-sdk) • [Website](https://usercentrics.com) |
| CmpServer | Consent management backend for global compliance rules | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cmpsrv/cmpserver) • [Website](https://cmpserver.io) |
| SafeConsent | Rust framework for zero-knowledge consent verification | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/safecon/safeconsent) • [Website](https://safeconsent.dev) |
| AuditedConsent | Blockchain-backed immutable consent ledger framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/auditcon/auditedconsent) • [Website](https://auditedconsent.org) |

## Ad Fraud Detection & Brand Safety

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| FraudScore SDK | SDK for detecting ad fraud and non-human traffic | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/fraud/fraudscore-sdk) • [Website](https://fraudscore.ai) |
| OpenSafety | Open framework for contextual ad safety evaluation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opensafety/opensafety) • [Website](https://opensafety.org) |
| BotShield | Real-time programmatic ad fraud bot detection | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/botshield/botshield) • [Website](https://botshield.io) |
| AdProtect | Java library for verifying ad viewability and safety | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/adprotect/adprotect) • [Website](https://adprotect.org) |
| NodeFraud | Node.js SDK for IP and user agent fraud scoring | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodefraud/nodefraud) • [Website](https://nodefraud.github.io) |
| PyFraud | Python machine learning pipeline for ad click fraud detection | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyfraud/pyfraud) • [Website](https://pyfraud.org) |
| RustShield | Safe and rapid ad fraud real-time verification filter | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustshield/rustshield) • [Website](https://rustshield.dev) |
| GoViewable | Go framework for validating IAB/MRC viewability standards | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goview/goviewable) • [Website](https://goviewable.org) |
| ViewabilityJS | Client-side ad viewability tracking script | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/viewjs/viewabilityjs) • [Website](https://viewabilityjs.dev) |
| BrandSafe | Natural language processing toolkit for contextual brand safety | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/brandsafe/brandsafe) • [Website](https://brandsafe.net) |
| ClickGuard | C# framework for programmatic click fraud mitigation | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/clickguard/clickguard) • [Website](https://clickguard.com) |
| AdAudit | TypeScript package for verifying traffic delivery authenticity | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/adaudit/adaudit) • [Website](https://adaudit.io) |
| IntegritySDK | Mobile app ad traffic integrity validation SDK | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/integrity/integrity-sdk) • [Website](https://integritysdk.org) |
| BotBlocker | High-frequency edge-node bot traffic mitigation engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/botblock/botblocker) • [Website](https://botblocker.io) |
| AegisAd | Contextual classification brand safety framework | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/aegis/aegisad) • [Website](https://aegisad.dev) |

## Programmatic Protocols & Specifications

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenRTB | Industry-standard protocol for programmatic real-time bidding | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/InteractiveAdvertisingBureau/openrtb) • [Website](https://iabtechlab.com) |
| Vast-Kit | Video Ad Serving Template XML parser and validator | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/vast/vast-kit) • [Website](https://vastkit.org) |
| Vpaid-JS | Video Player Ad-Interface Definition JavaScript runtime | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/vpaid/vpaid-js) • [Website](https://vpaidjs.org) |
| AdsTxt-Parser | Python parser for ads.txt, app-ads.txt, and sellers.json | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/adstxt/adstxt-parser) • [Website](https://adstxtparser.org) |
| OpenDirect | API specification framework for programmatic direct sales | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opendirect/opendirect) • [Website](https://opendirect.org) |
| OMID SDK | Open Measurement Interface Definition integration SDK | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/omid/omid-sdk) • [Website](https://iabtechlab.com) |
| GoVast | Go library for generating and parsing VAST 4.x files | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/govast/govast) • [Website](https://govast.dev) |
| CatVAST | C# framework for programmatic video ad template handling | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/catvast/catvast) • [Website](https://catvast.net) |
| SellersJson | TypeScript utility for verifying programmatic seller paths | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/sellers/sellersjson-parser) • [Website](https://sellersjson.org) |
| Mraid-Kit | Mobile Rich Media Ad Interface Definitions emulator | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/mraid/mraid-kit) • [Website](https://mraidkit.org) |
| JavaVast | Java VAST XML processing and building library | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javavast/javavast) • [Website](https://javavast.org) |
| RustOMID | Rust parser for Open Measurement specifications | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustomid/rustomid) • [Website](https://rustomid.dev) |
| AdCOM | Ad Common Object Model implementation library | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/adcom/adcom) • [Website](https://iabtechlab.com) |
| OpenRTB C# | C# model generator and serializing tool for OpenRTB | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/openrtbcs/openrtb) • [Website](https://openrtbcs.net) |
| SIMID SDK | Secure Interactive Media Interface Definition SDK | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/simid/simid-sdk) • [Website](https://iabtechlab.com) |

## Digital Out-of-Home (DOOH) & Audio Ad Tech

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenDOOH | Standardized protocol for digital out-of-home player bidding | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opendooh/opendooh) • [Website](https://opendooh.org) |
| AdPlayer | Lightweight player core for DOOH screens and billboard automation | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/adplayer/adplayer) • [Website](https://adplayer.io) |
| VastAudio | Audio ad template insertion and streaming library | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/vastaudio/vastaudio) • [Website](https://vastaudio.org) |
| NodeDOOH | Node.js application framework for retail screen ad serving | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodedooh/nodedooh) • [Website](https://nodedooh.github.io) |
| HlsAudioAd | HLS audio dynamic ad insertion (DAI) framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/hlsaudio/hlsaudioad) • [Website](https://hlsaudioad.dev) |
| DOOH-Kit | Telemetry and screen state reporting SDK for outdoor ads | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/doohkit/dooh-kit) • [Website](https://doohkit.org) |
| PyDOOH | Python scheduler and planner for digital billboard loops | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pydooh/pydooh) • [Website](https://pydooh.net) |
| BillboardOS | Bare-metal digital out-of-home operating runtime and bidder | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/billboard/billboardos) • [Website](https://billboardos.dev) |
| Dast-Parser | Digital Audio Ad Serving Template XML parser | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/dast/dast-parser) • [Website](https://dastparser.org) |
| AudioAdDecide | Ad server targeting rules specifically for audio streams | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/audio/audioaddecide) • [Website](https://audioaddecide.io) |
| C-DOOH | C++ player control framework for smart display ads | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/cdooh/cdooh) • [Website](https://cdooh.net) |
| ScreamAd | Real-time audio ad insertion and normalization engine | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/scream/screamad) • [Website](https://screamad.org) |
| AirPlayAd | iOS and macOS screen broadcast ad injection framework | <kbd>🏷️ Swift</kbd> | [GitHub](https://github.com/airplay/airplayad) • [Website](https://airplayad.io) |
| PodAd | Podcast RSS dynamic ad insertion (DAI) helper toolkit | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/podad/podad) • [Website](https://podad.net) |
| BillboardSDK | C# digital screen control and monitoring library | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/billboard/billboardsdk) • [Website](https://billboardsdk.com) |

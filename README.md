# Brightcove Ingest Profiles

Custom and experimental Ingest Profiles for Brightcove Video Cloud.

## EMEA-VERTICAL-SHORT
Optimised for low-bandwidth vertical videos, short format. 9x16 MP4 + HLS, up to 900Kbps 576x1024 (576p vertical), VBR capped at 1800Kbps.

## EMEA-STARTER
Low-bandwidth short-form videos for mobile-first viewers. 16x9 MP4 + HLS, up to 600Kbps 768x432, VBR capped at 780Kbps.

## EMEA-STANDARD
Default for news and entertainment content monetised via ads. 16x9 MP4 + HLS, up to 900Kbps 960x540, VBR capped at 1.2Mbps.

## EMEA-PREMIUM
Premium, directly monetised content: Pay-per-View, Subscription VOD, Sponsored. 16x9 MP4 + HLS, up to 1.5Mbps 1280x720 (720p), VBR capped at 1.8Mbps.

## EMEA-COMPLETE
Most complete set of renditions, ranging from 144p to 1080p. 360p, 480p, 576p and 720p are in multiple bitrates.
Recommended for testing with network throttlers. 16x9 MP4 + HLS, up to 3.5Mbps 1920x1080 (1080p), VBR capped at 7Mbps.

## EMEA-PREMIUM DASH-CENC
Based on Asia-PREMIUM, DRM-protected with DASH-CENC, packaged for **Widevine Modular**, PlayReady, Marlin

## EMEA-PREMIUM DASH-CENC and Widevine Classic
Based on Asia-PREMIUM, DRM-protected with Widevine Classic and DASH-CENC, packaged for **Widevine Classic**, PlayReady, Marlin

## EMEA-PREMIUM DASH-CENC and FairPlay
Based on Asia-PREMIUM, DRM-protected with Apple FairPlay and DASH-CENC, packaged for **Widevine Classic**, **HLS FairPlay**, PlayReady, Marlin

## EMEA Audio Only
Single bitrate audio-only, 48Khz 192Kbps AAC, HLS + MP4

## Asia-VERTICAL-SHORT
Optimised for low-bandwidth vertical videos, short format. 9x16 MP4 + HLS, up to 900Kbps 576x1024 (576p vertical), VBR capped at 1800Kbps.

## Asia-STARTER
Low-bandwidth short-form videos for mobile-first viewers. 16x9 MP4 + HLS, up to 600Kbps 768x432, VBR capped at 780Kbps.

## Asia-STANDARD
Default for news and entertainment content monetised via ads. 16x9 MP4 + HLS, up to 900Kbps 960x540, VBR capped at 1.2Mbps.

## Asia-PREMIUM
Premium, directly monetised content: Pay-per-View, Subscription VOD, Sponsored. 16x9 MP4 + HLS, up to 1.5Mbps 1280x720 (720p), VBR capped at 1.8Mbps.

## Asia-COMPLETE
Most complete set of renditions, ranging from 144p to 1080p. 360p, 480p, 576p and 720p are in multiple bitrates.
Recommended for testing with network throttlers. 16x9 MP4 + HLS, up to 3.5Mbps 1920x1080 (1080p), VBR capped at 7Mbps.

## Asia-PREMIUM DASH-CENC
Based on Asia-PREMIUM, DRM-protected with DASH-CENC, packaged for **Widevine Modular**, PlayReady, Marlin

## Asia-PREMIUM DASH-CENC and Widevine Classic
Based on Asia-PREMIUM, DRM-protected with Widevine Classic and DASH-CENC, packaged for **Widevine Classic**, PlayReady, Marlin

## Asia-PREMIUM DASH-CENC and FairPlay
Based on Asia-PREMIUM, DRM-protected with Apple FairPlay and DASH-CENC, packaged for **Widevine Classic**, **HLS FairPlay**, PlayReady, Marlin

## Mezzanine + Watermark
Creates mezzanine file from source, stores it as digital master, adds watermark to all other renditions. Watermarks are placed and scaled differently on MP4 vs. HLS

## Audio Only
Single bitrate audio-only, 48Khz 192Kbps AAC, HLS + MP4

Documentation on Ingest Profiles: https://docs.brightcove.com/en/video-cloud/ingest-profiles-api/reference/profile-fields-reference.html

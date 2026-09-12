# Vertex Dungeon — Store Submission Privacy Checklist

Updated: September 12, 2026

This checklist is a practical starting point based on the standard Google Mobile Ads / AdMob SDK behavior. If you add another analytics, crash-reporting, ad-mediation, login, cloud, or telemetry SDK, reassess these answers.

## Google Play

### App content
- **Contains ads:** Yes
- **Privacy Policy URL:** use your published `privacy.html`
- Make the Privacy Policy accessible inside the app.

### Target audience
Vertex Dungeon is described as a general-audience app that is not directed to children under 13.

Do not select children's age groups merely because the content is appropriate for them. Select the audience you actually design and market the app for. If you intentionally include children as a target audience, additional Families Policy and child-directed advertising requirements apply.

### Data Safety — AdMob baseline
The Google Mobile Ads SDK may automatically collect/share:
- IP address (may be used to estimate general/approximate location)
- User/app interactions such as app launches, taps, and video views
- Diagnostics/performance information
- Device/account identifiers, including advertising identifiers where enabled

Typical purposes include:
- Advertising or marketing
- Analytics
- Fraud prevention, security, and compliance

Google states that Mobile Ads SDK data is encrypted in transit.

Your exact Data Safety answers depend on:
- the Mobile Ads SDK version;
- whether advertising ID collection is enabled;
- whether you use personalized ads, limited ads, or consent controls;
- whether you use AdMob mediation or additional ad networks;
- whether you use any other SDKs.

## Apple App Store

### URLs
- **Privacy Policy URL:** use your published `privacy.html`
- **Support URL:** use your published `support.html`

### App Privacy — AdMob baseline
Google states that the iOS Mobile Ads SDK may process:
- IP address / general location
- Device ID / advertising identifiers
- Advertising data
- Product/app interactions
- Crash data / diagnostics
- Performance data

Some of these may be used for:
- Third-party advertising
- Analytics
- App functionality / performance measurement, depending on SDK behavior and configuration

If you use personalized advertising or tracking across companies' apps/websites, Apple's tracking/ATT rules may also apply. Your App Privacy answers must reflect your actual AdMob configuration.

## Purchase
The only paid feature is a one-time purchase, currently $1.99 in the U.S., to remove advertisements. Payment is processed by Google Play or Apple rather than directly by CD Industries.

## Re-check before every release
Re-check the store disclosures whenever you:
- change AdMob SDK versions;
- enable ad mediation;
- add Firebase Analytics, Crashlytics, or other telemetry;
- add accounts/cloud sync;
- add any new data collection;
- change the intended audience.

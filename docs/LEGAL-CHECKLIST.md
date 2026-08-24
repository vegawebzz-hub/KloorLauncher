# Public-release legal checklist

Reward advertising must remain disabled until every blocking item is complete.

- [ ] Add verified publisher legal name, address, privacy email, and support channel; obtain Estonian/EU legal review and handle tax/consumer obligations.
- [ ] Publish account export/deletion and complaint/appeal processes; verify retention, DPIA, processor agreements, transfers, backups, incident response, and secret rotation.
- [ ] Obtain Minecraft Services approval for the Microsoft client ID and seek written Mojang/Microsoft permission before monetizing the third-party launcher.
- [ ] Keep rewards limited to original launcher UI cosmetics; retain the unofficial-product disclaimer and licensed-play-only flow.
- [ ] Select a provider expressly approving rewarded Windows/Electron use. Do not embed AdSense or use mobile-only Unity Ads.
- [ ] Keep ads 18+, non-personalized, optional, individually chosen, and disabled before consent; make refusal and withdrawal equally easy.
- [ ] Never share Xbox/Minecraft tokens, identifiers, profiles, friends, or activity with an ad provider.
- [ ] Deploy the API/PostgreSQL behind publisher-controlled HTTPS with signed callbacks, replay protection, daily limits, monitoring, and production rate-limit storage.
- [ ] Pin the publisher API and approved ad origin in the EXE build; code-sign the EXE or use Microsoft Store; run WACK, clean-VM, dependency-license, and external security reviews.

Primary references: [Minecraft EULA](https://www.minecraft.net/en-us/eula), [Usage Guidelines](https://www.minecraft.net/en-us/usage-guidelines), [Microsoft Store policies](https://learn.microsoft.com/en-us/windows/apps/publish/store-policies-and-code-of-conduct), [GDPR](https://eur-lex.europa.eu/eli/reg/2016/679/oj), and [EDPB consent guidance](https://www.edpb.europa.eu/our-work-tools/our-documents/guidelines/guidelines-052020-consent-under-regulation-2016679_en).

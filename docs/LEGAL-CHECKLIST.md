# Public-release legal checklist

Reward advertising must remain disabled until every blocking item is complete.

## Publisher

- [ ] Register the appropriate Estonian business/tax structure and declare advertising revenue.
- [ ] Add the legal name, postal address, private privacy email, and support channel to every policy and Store listing.
- [ ] Obtain qualified Estonian/EU legal review of the Privacy Notice, Terms, Reward Rules, consumer information, and retention schedule.
- [ ] Publish an accessible account deletion/export process and complaints/appeal process.

## Minecraft and Microsoft

- [ ] Obtain Minecraft Services approval for the Microsoft Application client ID.
- [ ] Seek written Mojang/Microsoft permission before monetizing the third-party launcher or connecting rewards to Minecraft/in-game content.
- [ ] Keep all rewards limited to original KloorLauncher UI cosmetics unless written approval says otherwise.
- [ ] Display the unofficial-product disclaimer in the launcher, README, website, GitHub, and Store listing.
- [ ] Confirm no cracked account path, ownership bypass, bundled game jar/assets, or unauthorized Minecraft content exists.

## Advertising and privacy

- [ ] Select a provider that expressly supports rewarded advertising on Windows/Electron, or obtain approval for a separately hosted HTTPS flow. Do not use AdSense inside the desktop app or Unity Ads for Electron.
- [ ] Sign a data-processing agreement, list the provider and subprocessors, document transfers, and complete a DPIA.
- [ ] Verify contextual/non-personalized operation and disable ads for users under 18.
- [ ] Keep Reject/Not now as easy as Accept, provide withdrawal controls, and avoid advertising identifiers before consent.
- [ ] Never share Xbox/Minecraft identifiers, gamertags, profile data, friends, or tokens with the provider.
- [ ] Test signed callbacks, replay prevention, daily caps, fraud controls, deletion, retention, backup, and incident response.

## Distribution and operations

- [ ] Deploy the Kloor API and PostgreSQL behind publisher-controlled HTTPS; do not use a user's localhost database for public balances.
- [ ] Configure production secrets, provider keys, TLS, backups, monitoring, rate-limit storage, and secret rotation.
- [ ] Sign Windows executables or distribute through Microsoft Store.
- [ ] Complete Store privacy URL, age rating, advertising, in-product purchase, and commercial declarations.
- [ ] Run Windows App Certification, clean-VM tests, dependency/license review, and external security review.

## Primary policy references

- [Minecraft EULA](https://www.minecraft.net/en-us/eula) and [Usage Guidelines](https://www.minecraft.net/en-us/usage-guidelines)
- [Minecraft partner/contact request](https://partnerships.minecraft.net/hc/en-us/requests/new?ticket_form_id=360001261291)
- [Microsoft Store policies](https://learn.microsoft.com/en-us/windows/apps/publish/store-policies-and-code-of-conduct)
- [Google AdSense program policies](https://support.google.com/adsense/answer/1346295) and [Unity Ads platform FAQ](https://docs.unity.com/grow/ads/references/faq)
- [EU GDPR](https://eur-lex.europa.eu/eli/reg/2016/679/oj) and [EDPB consent guidance](https://www.edpb.europa.eu/our-work-tools/our-documents/guidelines/guidelines-052020-consent-under-regulation-2016679_en)

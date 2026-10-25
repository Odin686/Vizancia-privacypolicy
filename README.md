# Vizancia privacy policy links

The public policy for both mobile apps and the website is:
https://vizancia.com/privacy.html

Both legacy HTML entry points redirect there, with an accessible link fallback
when automatic navigation is disabled. They load no scripts or measurement.
Keep both entry points identical so existing app-store and installed-app links
continue to work. The canonical policy is maintained in Odin686/-vizancia-site;
its app disclosures are checked against the reviewed iOS source and Android
platform adaptations. This repository does not change DNS or the hosting
provider of vizancia.com.

Verification: parse both HTML files, verify identical contents and HTTPS
canonical/refresh/fallback destinations, and check the branded destination.

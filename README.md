# RevFirma sales website

A static customer website for RevFirma’s managed location-based advertising around workplaces, properties and operating areas. No build step is required.

## Pages and assets

- `index.html`: “Be the business they keep seeing” sales opening, interactive controller in the hero, three customer use cases, controller advantages, city and industrial evidence, area directory, pricing example and inquiry form.
- `how-it-works/index.html`: delivery, frequency goals, auction-share limits, cost, competitor evidence, permissions and outcome measurement.
- `sample-plan.pdf`: one-page illustrative commercial scope.
- `case-studies/nabors-scalable-growth.pdf`: unchanged supplied Nabors case study, with its buyer alias preserved.
- `examples/controller-week.csv` and `.json`: explicitly fictional readings used by the walkthrough.

Publish the folder as static assets. The `/how-it-works/` directory serves its own index. No production deployment is implied by a review-branch commit.

The $1,200–$2,200 monthly planning example is calculated from the activation calculator rates retrieved September 6, 2026, for an illustrative 500-person planning audience. It separates media from the remaining service component and does not claim to describe typical customer spend. Creative counts and the one-business-day response target are proposed customer-facing operating scope for this review. No campaign or spend is created by this website update.

The lead form uses the existing inquiry endpoint. Selections are shown in the form card and included in the inquiry; live lead submissions are not used for verification. Homepage analytics are restricted to the production domains. Matomo site 2 receives explicit trackEvent calls rather than relying on missing tag-manager event triggers; the Meta pageview and lead pixel are preserved. Fonts, inquiry handling and external resources require internet access.

The controller is a fictional week, separate from the smaller pricing example. Actual recorded spend, configured budget and authorized changes are distinct. The Nabors summary leads with campaign process and identifies historical contract revenue as reported in the source, not measured incremental advertising revenue. The hospitality traffic example is omitted from the homepage to keep its proof focused. Private source material is not included in the public assets.

The Tulsa photograph by Nils Huenerfuerst is licensed CC BY-SA 4.0; source and adaptation details remain in the homepage footer.

The existing `/deployments/` address is included in the static build. `/clients` returned 404 and is not linked. The apex redirected to www during verification, matching the canonical metadata. Existing social and icon assets are included at their original root paths. Photography is a separate lazy-loaded image asset. The redesign combines a dark product opening, white editorial sections and brand cyan with Inter and JetBrains Mono. The headline sells repeated visibility; the controller shows delivery, paid cost, authorization and next-day readings. Carlton Landing is explicitly described as a city in Oklahoma. Its dated 17.4 modeled exposure example links to the archived source and current reporting. No supported auction-share percentage is claimed. Supporting pages share the same typography and visual theme.

## Image-led edition

The homepage now opens with an original conceptual city visualization, followed immediately by the interactive controller. The Tulsa photograph is displayed across the page. Headline and use-case copy are shorter. Entrance and scroll motion respect reduced-motion preferences. The city illustration is conceptual artwork, not a measured coverage map. The new web-optimized image is `assets/city-presence.webp`. No campaign controls or spend were changed.

The product walkthrough now animates the selected place, illustrative Feed and Stories ads, delivery, paid cost, recommendation, creative approval and next-day review. Playback runs once when the scene enters view, pauses when it leaves view or the document is hidden, and yields to manual controller tabs. Play, pause, replay and step controls are provided. Reduced-motion preferences disable automatic start and visual transitions. All tour behavior is local and never invokes advertising APIs.

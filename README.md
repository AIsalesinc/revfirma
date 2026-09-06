# RevFirma sales website

A static customer website for a managed advertising presence around workplaces, properties and operating areas. No build step is required.

## Pages and assets

- `index.html`: opening offer, fixed illustrative controller week, jobs to be done, Carlton Landing measurement case, worked first-plan range, brief industrial lane, area inquiries and three essential FAQs.
- `how-it-works/index.html`: delivery, frequency goals, auction-share limits, cost, competitor evidence, permissions and outcome measurement.
- `sample-plan.pdf`: one-page illustrative commercial scope.
- `case-studies/nabors-scalable-growth.pdf`: unchanged supplied Nabors case study, with its buyer alias preserved.
- `examples/controller-week.csv` and `.json`: explicitly fictional readings used by the walkthrough.

Publish the folder as static assets. The `/how-it-works/` directory serves its own index. No production deployment is implied by a review-branch commit.

The $1,200–$2,200 monthly planning example is calculated from the activation calculator rates retrieved September 6, 2026, for an illustrative 500-person planning audience. It separates media from the remaining service component and does not claim to describe typical customer spend. Creative counts and the one-business-day response target are proposed customer-facing operating scope for this review. No campaign or spend is created by this website update.

The lead form uses the existing inquiry endpoint. Selections are shown in the form card and included in the inquiry; live lead submissions are not used for verification. Homepage analytics are restricted to the production domains. Matomo site 2 receives explicit trackEvent calls rather than relying on missing tag-manager event triggers; the Meta pageview and lead pixel are preserved. Fonts, inquiry handling and external resources require internet access.

The controller is a fictional week, separate from the smaller pricing example. Actual recorded spend, configured budget and authorized changes are distinct. The Nabors summary leads with campaign process and identifies historical contract revenue as reported in the source, not measured incremental advertising revenue. The private hotel remains anonymous.

The Tulsa photograph by Nils Huenerfuerst is licensed CC BY-SA 4.0; source and adaptation details remain in the homepage footer.

The existing `/deployments/` address is included in the static build. `/clients` returned 404 and is not linked. The apex redirected to www during verification, matching the canonical metadata. Existing social and icon assets are included at their original root paths. Photography is a separate lazy-loaded image asset. The dark visual treatment is the deliberate redesign used in the preceding reviews. The dated Carlton snapshot lives in the guide, with a source CSV; the homepage directs readers to current reporting.

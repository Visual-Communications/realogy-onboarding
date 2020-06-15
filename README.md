# realogyonboarding.com

Developed by [DScape Interactive][d-scape] for Realogy Human Resources.

- Account manager at DScape: **Dave McNulty**
  - dmcnulty@d-scape.com
  - +1-201-400-3489
- Realogy project owner: **Darcy Semple**
- Realogy project manager: **Danielle Gratkowski**

## Infrastructure

### Code repository

The code for this website lives in [this GitHub repository][github]. To deploy changes to the website, fork the `master` branch, commit changes, and submit a Pull Request to `master`. Merging the Pull Request will automatically trigger a deployment to Netlify.

### Server / CDN deployment

The site is hosted by Netlify in the [Visual Communications team account][netlify], and is owned and maintained by Visual Communications. Netlify is configured for automatic deployment via GitHub to a CDN.

#### Rewrites

`./netlify.toml` contains a server rewrite from `/` to `/story_html5.html`. This way visiting the top level domain _just works_, instead of requiring the user to type `/story_html5.html` at the end.

### Domain registration

The realogyonboarding.com domain is registered at [Hover][hover], in an account owned and maintained by Realogy Human Resources. The domain is setup to auto-renew yearly, with automatic SSL certificate renewal. DNS nameservers are pointed at Netlify.

### DNS

DNS is managed by [Netlify][netlify-dns].

[d-scape]: http://www.dscape.com/
[github]: https://github.com/Visual-Communications/realogy-onboarding
[netlify]: https://app.netlify.com/teams/visual-communications
[hover]: https://www.hover.com/
[netlify-dns]: https://app.netlify.com/teams/visual-communications/dns/realogyonboarding.com

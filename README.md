# 🔗 mon.icu

[![Netlify Status][4]][5]

## ☁️ What mon.icu is, a tl;dr

mon.icu (read as moni-kyu, short for 'Monika is cute') is a link shortener
service we at [Friends of Monika][1] use for providing quick to access and easy
to remember links for all MAS related stuff.

Moreover, the service is public! Everyone can help the community by
[submitting their URL proposal][2] which will then be immediately deployed and
available globally~

## 🙋 FAQ

### Does mon.icu collect user data, can it track me?

No, our service merely provides HTTP redirects and does not inject any analytics
scripts, trackers, etc. and does not collect any info
[beyond what Netlify can log and store on their server side][3]. Additionally,
we don't pay for and we don't use their analytics services. **We cannot see your
IP address, your country, or your browser.** In the event we'll decide to start
collecting any sort of info, we  will update our FAQ here, come up with proper
Privacy Policy and announce such a breaking change publicly in our Discord
server.

### Where can I see all the available links?

All links are available in [LINKS.md][6]. When people propose their links, we
always ensure we keep this page up to date with actual links currently in use.
However, if you feel like anything is missing, check out [_redirects][7] file
which is the actual 'source code' for the links Netlify performs redirections
for; this configuration file is guaranteed to contain all links mon.icu
provides.

### Do you delete links, how do I know if a link was removed?

While we generally stay by our principle of keeping all links forever (in order
not to be the cause of [link rot][8]), we might be obligated to remove links for
any reasons, including our own decisions if necessary. However, we promise to
keep track of deleted links in the event of this happening in [LINKS.md][6]
file, along with the actual links. If necessary, we will also wipe introducing
commit from the Git history.

### Can I demand a link to be removed?

Sure, you can either [create an issue][9] or reach any of the repository
maintainers directly and explain why do you believe certain URL has to be
removed. We will immediately remove any URLs that their author demand to be only
shared privately (e.g. 'ask for a link') and links that point at personal or
inappropriate content. Please keep in mind that deletion of links is an
*exception* and we generally do not delete links.


[1]: https://github.com/Friends-of-Monika/monicu
[2]: CONTRIBUTING.md
[3]: https://www.netlify.com/gdpr-ccpa/
[4]: https://api.netlify.com/api/v1/badges/2c803c94-db9c-40bc-9a06-005361a0d873/deploy-status
[5]: https://app.netlify.com/sites/monicu/deploys
[6]: CONTRIBUTING.md
[7]: _redirects
[8]: https://en.wikipedia.org/wiki/Link_rot
[9]: https://github.com/Friends-of-Monika/monicu/issues/new
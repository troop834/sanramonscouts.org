# sanramonscouts.org

## Architecture

### Site sources

sanramonscouts.org uses Hugo to generate a website from simple Markdown or HTML
sources using templates.

Site sources are hosted in a Git repository on GitHub:
[https://github.com/troop834/sanramonscouts.org](https://github.com/troop834/sanramonscouts.org).
The repository is private, so only members of the [Troop 834 GitHub
Organization](https://github.com/troop834) can view it. If you'd like to be
added to the organization, [contact Kian Kasad](mailto:kian@kasad.com).

### Web hosting

The website itself is hosted on [Dreamhost](https://dreamhost.com).

#### TLS

sanramonscouts.org uses a TLS certificate from [Let's
Encrypt](https://letsencrypt.org). This is handled automatically by Dreamhost.

### Building site from sources

Every time a change is pushed to the source repository, it is automatically
built and uploaded to Dreamhost using GitHub Actions. The
[`.github/workflows/build-site.yml`](https://github.com/troop834/sanramonscouts.org/blob/master/.github/workflows/build-site.yml)
file in the repository contains this script.

### Editing the site

[Forestry](https://forestry.io) can be used to edit the site. It provides a
simple WYSIWYG editor and CMS interface for those who aren't comfortable with
using Markdown and Git directly.

[Contact Kian Kasad](mailto:kian@kasad.com) to get access to edit the site on
Forestry.

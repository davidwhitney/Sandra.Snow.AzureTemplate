Sandra.Snow.AzureTemplate
========================

A Snow template that uses Bootstrap 3, and is designed for static site deployment Azure websites.
The template is pre-configured to play nicely with Azure website deployments via Kudu, so simply creating your own Git repo on GitHub and pointing Azure to it will have you launched instantly.

# Usage

1. Create your own repository on GitHub
2. Clone Sandra.Snow.AzureTemplate
3. Copy all files into your repository
4. Push to your GitHub
5. Edit Snow/snow.config - change the siteUrl to your azure site Url.
6. Edit Snow/CNAME - to contain your azure site Url.
7. Edit Snow/_layouts/default.cshtml - To tweak the default bootstrap template layouts.
8. Edit Snow/about.cshtml to update your about blurb
9. Configure Azure Websites autodeploy to point to your new repository.
10. Profit!

<div align="center">
  <div>
    <img width="500" height="375" src="media/awesome-strapi-logo.png" alt="Awesome Strapi">
  </div>
</div>

# Awesome Strapi [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to [Strapi](https://github.com/strapi/strapi).

Strapi is an open source Node.js Headless CMS to easily build customisable APIs

---

<!-- vscode-markdown-toc -->
* [Documentation, Tutorials, and Meetups](#DocumentationTutorialsandMeetups)
* [Showcase](#Showcase)
* [One-Click & Deployment](#One-ClickDeployment)
* [Starters & Examples](#StartersExamples)
	* [React](#React)
	* [Gatsby](#Gatsby)
	* [Vue.js](#Vue.js)
	* [Next.js](#Next.js)
	* [Nuxt.js](#Nuxt.js)
	* [Angular](#Angular)
	* [Sapper](#Sapper)
* [Plugin & Providers](#PluginProviders)
	* [Official Plugins](#OfficialPlugins)
	* [Community Plugins](#CommunityPlugins)
	* [Community Middlewares](#CommunityMiddlewares)
	* [Email Providers](#EmailProviders)
	* [Upload Providers](#UploadProviders)
* [Ecosystem](#Ecosystem)
	* [SDKs](#SDKs)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

---

## <a name='DocumentationTutorialsandMeetups'></a>Documentation, Tutorials, and Meetups

- [Strapi](https://github.com/strapi/strapi) - Official Strapi repository.
- [Product Board](https://portal.productboard.com/strapi/) - Strapi roadmap and feature requests.
- [Docs](https://strapi.io/documentation/3.0.0-beta.x/getting-started/introduction.html) - Official Documentation.
- [Tutorials](https://strapi.io/tutorials) - Official and Community Tutorials ([Submit](https://github.com/strapi/strapi-tutorials) new tutorials).
- [RFC](https://github.com/strapi/rfcs) - Offical Request for Comments.
- [Meetups](https://github.com/strapi/strapi-meetups) - Meetups and Webinars.
- [Slack](http://slack.strapi.io/) - Offical Strapi Slack.
- [Spectrum](https://spectrum.chat/strapi) - Spectrum Chat forums.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/strapi) - Stack Overflow tagged questions.

## <a name='Showcase'></a>Showcase
 - [Projects using Strapi](https://strapi.io/showcase)
## <a name='One-ClickDeployment'></a>One-Click & Deployment

- [DigitalOcean](https://marketplace.digitalocean.com/apps/strapi) - DigitalOcean Marketplace One-Click.
- [Platform.sh](https://console.platform.sh/projects/create-project?template=https://raw.githubusercontent.com/platformsh/template-builder/master/templates/strapi/.platform.template.yaml&utm_content=strapi&utm_source=github&utm_medium=button&utm_campaign=deploy_on_platform) - _Platform_.sh One-Click.
- [Docker](https://github.com/strapi/strapi-docker) - Official Docker container.

## <a name='StartersExamples'></a>Starters & Examples

- [Examples](https://github.com/strapi/strapi-examples) - General examples (Outdated).

### <a name='React'></a>React

- [Food Advisor](https://github.com/strapi/foodadvisor) - THE Strapi demo application.
- [React Blog](https://github.com/strapi/strapi-starter-react-blog) - Blog example using React and GraphQL.

### <a name='Gatsby'></a>Gatsby

- [Gatsby Blog](https://github.com/strapi/strapi-starter-gatsby-blog) - Blog example using Gatsby and GraphQL.

### <a name='Vue.js'></a>Vue.js

- [Vue Blog](https://github.com/strapi/strapi-starter-vue-blog) - Blog example using Vue and GraphQL.

### <a name='Next.js'></a>Next.js

- [Next Blog](https://github.com/strapi/strapi-starter-next-blog) - Blog example using Next and GraphQL.

### <a name='Nuxt.js'></a>Nuxt.js

- [Nuxt Blog](https://github.com/strapi/strapi-starter-nuxt-blog) - Blog example using Nuxt and GraphQL.

### <a name='Angular'></a>Angular

- [Angular Blog](https://github.com/strapi/strapi-starter-angular-blog) - Blog example using Angular and GraphQL.

### <a name='Sapper'></a>Sapper

- [Sapper Blog](https://github.com/malgamves/strapi-starter-minimal-sapper-blog) - Minimal blog example using Sapper and GraphQL.

## <a name='PluginProviders'></a>Plugin & Providers

### <a name='OfficialPlugins'></a>Official Plugins

- [GraphQL](https://github.com/strapi/strapi/tree/master/packages/strapi-plugin-graphql) - Official GraphQL plugin including GraphQL Playground.
- [Documentation](https://github.com/strapi/strapi/tree/master/packages/strapi-plugin-documentation) - Offical SwaggerUI/OpenAPI Documentation.

### <a name='CommunityPlugins'></a>Community Plugins

- [Sitemap](https://github.com/boazpoolman/strapi-plugin-sitemap) - Generate a sitemap.xml.
- [Import content](https://github.com/pouyamiralayi/strapi-import-content-plugin-tutorial) - Import content with a csv file, external url or raw text.
- [Responsive image](https://github.com/nicolashmln/strapi-plugin-responsive-image) - Custom responsive image formats.
- [Entity Relationship Chart](https://github.com/node-vision/strapi-plugin-entity-relationship-chart) - Display Entity Relationship Diagram of all models, fields and relations.
- [ToastUI Wysiwyg](https://github.com/fagbokforlaget/strapi-plugin-wysiwyg-toastui) - ToastUI based Wysiwyg replacement for strapi.

### <a name='CommunityMiddlewares'></a>Community Middlewares

- [LRU Caching](https://github.com/patrixr/strapi-middleware-cache) - LRU caching for the api.

### <a name='EmailProviders'></a>Email Providers

- [Amazon-SES](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-amazon-ses) - Amazon SES email provider.
- [Mailgun](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-mailgun) - Mailgun email provider.
- [Sendgrid](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-sendgrid) - Sendgrid email provider.
- [Sendinblue](https://github.com/eddybordi/strapi-provider-email-sendinblue) - Sendinblue email provider.
- [Sendmail](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-sendmail) - Sendmail email provider.
- [Nodemailer](https://github.com/Stun3R/strapi-provider-email-nodemailer-refactor) - Nodemailer email provider.

### <a name='UploadProviders'></a>Upload Providers

- [Amazon S3](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-aws-s3) - Amazon S3 bucket upload provider.
- [Cloudinary](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-cloudinary) - Cloudinary upload provider.
- [Google Cloud Storage](https://github.com/Lith/strapi-provider-upload-google-cloud-storage) - Google Cloud Storage upload provider.
- [Rackspace](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-rackspace) - Rackspace upload provider.
- [WeTransfer](https://github.com/zeybek/strapi-provider-upload-wt) - WeTransfer upload provider.
- [Scaleway](https://github.com/Sqveeze/strapi-provider-upload-scaleway) - Scaleway upload provider.

## <a name='Ecosystem'></a>Ecosystem

- [Buffet.js](https://github.com/strapi/buffet) - React components library for Strapi plugins.
- [One-Click](https://github.com/strapi/one-click-deploy) - One-Click source scripts used to build all official one-click apps.

### <a name='SDKs'></a>SDKs

- [Javascript SDK](https://github.com/strapi/strapi-sdk-javascript) - Official Javascript SDK (Currently outdated).
- [Jekyll](https://github.com/strapi/jekyll-strapi) - Jekyll plugin to retrieve content from a Strapi API.

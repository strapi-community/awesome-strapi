<div align="center">
  <div>
    <img src="media/awesome-strapi-logo.png" alt="Awesome Strapi">
  </div>
</div>

# Awesome Strapi [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to [Strapi](https://github.com/strapi/strapi).

Strapi is an open source Node.js Headless CMS to easily build customisable APIs

---

<!-- vscode-markdown-toc -->

- [Documentation, Tutorials, and Meetups](#DocumentationTutorialsandMeetups)
- [Showcase](#Showcase)
- [One-Click & Deployment](#One-ClickDeployment)
- [ Templates](#Templates)
- [Starters & Examples](#StartersExamples)
  - [Angular](#Angular)
  - [Gatsby](#Gatsby)
  - [Gridsome](#Gridsome)
  - [Next.js](#Next.js)
  - [Nuxt.js](#Nuxt.js)
  - [React](#React)
  - [Sapper](#Sapper)
  - [Vue.js](#Vue.js)
- [Plugin & Providers](#PluginProviders)
  - [Official Plugins](#OfficialPlugins)
  - [Community Plugins](#CommunityPlugins)
  - [Community WYSIWYG Replacements](#CommunityWYSIWYGReplacements)
  - [Community Custom Field Plugins](#CommunityCustomFieldPlugins)
  - [Community Middlewares](#CommunityMiddlewares)
  - [Community Hooks](#CommunityHooks)
  - [Email Providers](#EmailProviders)
  - [Upload Providers](#UploadProviders)
- [Ecosystem](#Ecosystem)
  - [SDKs](#SDKs)
  - [Third Party Modules](#ThirdPartyModules)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

---

## <a name='DocumentationTutorialsandMeetups'></a>Documentation, Tutorials, and Meetups

- [Strapi](https://github.com/strapi/strapi) - Official Strapi repository.
- [Try live demo](https://strapi.io/demo) - Official Strapi demo.
- [Product Board](https://portal.productboard.com/strapi/) - Strapi roadmap and feature requests.
- [Developer Docs](https://strapi.io/documentation/developer-docs/latest/getting-started/introduction.html) - Official Developer Documentation.
- [User Docs](https://strapi.io/documentation/user-docs/latest/getting-started/introduction.html) - Official User Documentation.
- [Tutorials](https://strapi.io/tutorials) - Official and Community Tutorials ([Submit](https://github.com/strapi/strapi-tutorials) new tutorials).
- [RFC](https://github.com/strapi/rfcs) - Official Request for Comments.
- [Meetups](https://github.com/strapi/strapi-meetups) - Meetups and Webinars.
- [Forum](https://forum.strapi.io) - Official Strapi forum.
- [Discord](https://discord.strapi.io/) - Official Strapi Discord.

## <a name='Showcase'></a>Showcase

- [Projects using Strapi](https://strapi.io/showcase)
- [Community Content](https://github.com/strapi/community-content) - User content created by the community

## <a name='One-ClickDeployment'></a>One-Click & Deployment

- [DigitalOcean](https://marketplace.digitalocean.com/apps/strapi) - DigitalOcean Marketplace One-Click.
- [Platform.sh](https://console.platform.sh/projects/create-project?template=https://raw.githubusercontent.com/platformsh/template-builder/master/templates/strapi/.platform.template.yaml&utm_content=strapi&utm_source=github&utm_medium=button&utm_campaign=deploy_on_platform) - _Platform_.sh One-Click.
- [Docker](https://github.com/strapi/strapi-docker) - Official Docker container.

## <a name='Templates'></a> Templates

- [Blog](https://github.com/strapi/strapi-template-blog) - Template to create Strapi projects pre-configured for blogs
- [Catalog](https://github.com/strapi/strapi-template-catalog) - Template to create Strapi projects pre-configured for catalog sites
- [Corporate](https://github.com/strapi/strapi-template-corporate) - Template to create Strapi projects pre-configured for corporate sites
- [E-commerce](https://github.com/strapi/strapi-template-ecommerce) - Template to create Strapi projects pre-configured for e-commerce apps
- [Heroku](https://github.com/strapi/strapi-heroku-template) - Official template for Heroku 1 click deploy button
- [Portfolio](https://github.com/strapi/strapi-template-portfolio) - Template to create Strapi projects pre-configured for portfolio sites

## <a name='StartersExamples'></a>Starters & Examples

- [Examples](https://github.com/strapi/strapi-examples) - General examples (Outdated).
- [OrgServer](https://github.com/kaiyuanshe/OrgServer) - **Data Server** scaffold for all kinds of **Organizations**

### <a name='Angular'></a>Angular

- [Angular Blog](https://github.com/strapi/strapi-starter-angular-blog) - Blog example using Angular and GraphQL.

### <a name='Gatsby'></a>Gatsby

- [Gatsby Blog](https://github.com/strapi/strapi-starter-gatsby-blog) - Blog example using Gatsby and GraphQL.
- [Gatsby Catalog](https://github.com/strapi/strapi-starter-gatsby-catalog) - Gatsby Catalog starter.

### <a name='Gridsome'></a>Gridsome

- [Gridsome Blog](https://github.com/strapi/strapi-starter-gridsome-blog) - Blog example using Gridsome

### <a name='Next.js'></a>Next.js

- [Next Blog](https://github.com/strapi/strapi-starter-next-blog) - Blog example using Next and GraphQL.
- [Next Corporate](https://github.com/strapi/strapi-starter-next-corporate) - Next.js starter for creating a corporate site.
- [Next E-commerce](https://github.com/strapi/strapi-starter-next-ecommerce) - Starter Next.js E-commerce.

### <a name='Nuxt.js'></a>Nuxt.js

- [Nuxt Blog](https://github.com/strapi/strapi-starter-nuxt-blog) - Blog example using Nuxt and GraphQL.
- [Nuxt E-commerce](https://github.com/strapi/strapi-starter-nuxt-e-commerce) - Starter Nuxt.js E-commerce.

### <a name='React'></a>React

- [Food Advisor](https://github.com/strapi/foodadvisor) - THE Strapi demo application.
- [React Blog](https://github.com/strapi/strapi-starter-react-blog) - Blog example using React and GraphQL.

### <a name='Sapper'></a>Sapper

- [Sapper Blog](https://github.com/malgamves/strapi-starter-minimal-sapper-blog) - Minimal blog example using Sapper and GraphQL.

### <a name='Vue.js'></a>Vue.js

- [Vue Blog](https://github.com/strapi/strapi-starter-vue-blog) - Blog example using Vue and GraphQL.

## <a name='PluginProviders'></a>Plugin & Providers

### <a name='OfficialPlugins'></a>Official Plugins

- [Documentation](https://github.com/strapi/strapi/tree/master/packages/strapi-plugin-documentation) - Official SwaggerUI/OpenAPI Documentation.
- [GraphQL](https://github.com/strapi/strapi/tree/master/packages/strapi-plugin-graphql) - Official GraphQL plugin including GraphQL Playground.
- [Sentry](https://github.com/strapi/strapi/tree/master/packages/strapi-plugin-sentry) - Official Sentry plugin.

### <a name='CommunityPlugins'></a>Community Plugins

- [Comments](https://github.com/VirtusLab/strapi-plugin-comments) - End to end comments feature with their moderation panel, bad words filtering, abuse reporting and more.
- [Config Sync](https://github.com/boazpoolman/strapi-plugin-config-sync) - Manage database config (core_store e.g.) as partial JSON files. Import/Export across environments.
- [Email Designer](https://github.com/alexzaganelli/strapi-plugin-email-designer) - Design your own **email templates** w/ visual composer directly inside the Strapi admin panel and send composed emails programmatically from your controllers / services.
- [Entity Relationship Chart](https://github.com/node-vision/strapi-plugin-entity-relationship-chart) - Display Entity Relationship Diagram of all models, fields and relations.
- [Expo Notifications](https://github.com/Lith/strapi-plugin-notification-expo) - Send Expo notification to mobile app
- [Github Publish](https://github.com/phantomstudios/strapi-plugin-github-publish) - Lets you publish content changes using a GitHub Actions workflow.
- [Import content](https://github.com/pouyamiralayi/strapi-import-content-plugin-tutorial) - Import content with a csv file, external url or raw text.
- [Meilisearch](https://github.com/meilisearch/strapi-plugin-meilisearch) - Add your Strapi collections into a MeiliSearch instance.
- [Migrate](https://github.com/ijsto/strapi-plugin-migrate) - Migrate Settings & Layouts, User Permissions between environments. (Webhooks & Content migrations coming soon).
- [Moesif](https://github.com/bglidwell/strapi-plugin-moesif) - Plugin to add Moesif API Analytics and Monitoring (https://www.moesif.com/).
- [Navigation Builder](https://github.com/VirtusLab/strapi-plugin-navigation) - Navigation / menu builder feature with possibility to control the audience and different output structure renderers like (flat, tree and RFR - ready for handling by Redux First Router)
- [oEmbed](https://github.com/nicolashmln/strapi-plugin-oembed) - Embed content from third party sites (Youtube, Vimeo, Soundcloud, ...).
- [Responsive image](https://github.com/nicolashmln/strapi-plugin-responsive-image) - Custom responsive image formats.
- [Raw Query](https://github.com/creazy231/strapi-plugin-raw-query) - Sends raw query strings to the database.
- [Sitemap](https://github.com/boazpoolman/strapi-plugin-sitemap) - Generate a sitemap.xml.
- [Sync Roles And Permissions](https://github.com/alan2207/strapi-plugin-sync-roles-permissions) - Store user roles and permissions configuration as a JSON file and then import and reuse it any time.
- [Testing](https://github.com/Antoine-lb/strapi-plugin-testing) - Out of the box Unit/Integration testing with mocking functions.
- [Video Thumbnail](https://github.com/darron1217/strapi-plugin-video-thumbnail) - Add video thumbnail functionality to Upload plugin (using FFmpeg).
- [Zeasy Image Api](https://github.com/kwinyyyc/strapi-plugin-zeasy-image-api) - Search and import image from Unsplash / Giphy to the rich text field with appropriate attribution.

### <a name='CommunityWYSIWYGReplacements'></a>Community WYSIWYG Replacements

- [CKEditor 5](https://github.com/Roslovets-Inc/strapi-plugin-ckeditor5) - Replace Strapi default WYSIWYG editor with enhanced build of **CKEditor** 5.
- [React MD Editor](https://github.com/kwinyyyc/strapi-plugin-wysiwsg-react-md-editor) - Replace Strapi default WYSIWYG editor with **React MD Editor**.
- [Toast UI Editor](https://github.com/fagbokforlaget/strapi-plugin-wysiwyg-toastui) - Replace Strapi default WYSIWYG editor with **Toast UI Editor**.

### <a name='CommunityCustomFieldPlugins'></a>Community Custom Field Plugins

- [Point List Field](https://github.com/akcyp/strapi-plugin-point-list) - Mark an area on the image and save the list of points to the database.
- [Internaional Fields](https://github.com/MattieBelt/strapi-plugin-international-fields) - Add localized fields: Country, Language, Nationality

### <a name='CommunityMiddlewares'></a>Community Middlewares

- [LRU Caching](https://github.com/patrixr/strapi-middleware-cache) - LRU caching for the api.
- [Upload Plugin Cache](https://github.com/alexkainzinger/strapi-middleware-upload-plugin-cache) - Configurable middleware for caching uploaded assets when using strapi-provider-upload-local.

### <a name='CommunityHooks'></a>Community Hooks

- [Algolia](https://github.com/MattieBelt/strapi-hook-algolia) - Maintain search indexes with the Agolia service.

### <a name='EmailProviders'></a>Email Providers

- [Amazon-SES](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-amazon-ses) - Amazon SES email provider.
- [Mailgun](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-mailgun) - Mailgun email provider.
- [MailJet](http://github.com/ijsto/strapi-provider-email-mailjet) - MailJet email provider.
- [Mailtrap](https://github.com/alessandrocaprarelli/strapi-provider-email-mailtrap) - Mailtrap email provider.
- [Nodemailer](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-nodemailer) - Nodemailer email provider.
- [Sendgrid](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-sendgrid) - Sendgrid email provider.
- [Sendinblue](https://github.com/eddybordi/strapi-provider-email-sendinblue) - Sendinblue email provider.
- [Sendmail](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-email-sendmail) - Sendmail email provider.

### <a name='UploadProviders'></a>Upload Providers

- [Amazon S3](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-aws-s3) - Amazon S3 bucket upload provider.
- [Azure](https://github.com/jakeFeldman/strapi-provider-upload-azure-storage) - Azure Storage upload provider.
- [Cloudinary](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-cloudinary) - Cloudinary upload provider.
- [DigitalOcean](https://github.com/shorwood/strapi-provider-upload-do) - DigitalOcean S3 upload provider.
- [Google Cloud Storage](https://github.com/Lith/strapi-provider-upload-google-cloud-storage) - Google Cloud Storage upload provider.
- [HubSpot](https://github.com/gkemp94/strapi-provider-upload-hubspot) - HubSpot upload provider.
- [Rackspace](https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-rackspace) - Rackspace upload provider.
- [Scaleway](https://github.com/Sqveeze/strapi-provider-upload-scaleway) - Scaleway upload provider.
- [WeTransfer](https://github.com/zeybek/strapi-provider-upload-wt) - WeTransfer upload provider.
- [Yandex Cloud](https://github.com/teinett/strapi-provider-upload-yandex-cloud) - Yandex Cloud Object Storage upload provider.

## <a name='Ecosystem'></a>Ecosystem

- [Buffet.js](https://github.com/strapi/buffet) - React components library for Strapi plugins.
- [One-Click](https://github.com/strapi/one-click-deploy) - One-Click source scripts used to build all official one-click apps.

### <a name='SDKs'></a>SDKs

- [Javascript SDK](https://github.com/strapi/strapi-sdk-javascript) - Official Javascript SDK (Currently outdated).
- [Jekyll](https://github.com/strapi/jekyll-strapi) - Jekyll plugin to retrieve content from a Strapi API.
- [MobX-Strapi](https://github.com/EasyWebApp/MobX-Strapi) - **MobX** v5 SDK for Strapi v3

### <a name='ThirdPartyModules'></a>Third Party Modules

- [NgxStrapiAuth](https://github.com/jabali2004/ngx-strapi-auth) - Angular authentication library with pre-built components.

<div align="center">
  <div>
    <img src="media/awesome-strapi-logo.png" alt="Awesome Strapi">
  </div>
</div>

# Awesome Strapi [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

> A curated list of awesome things related to [Strapi](https://github.com/strapi/strapi).

Strapi is an open source Node.js Headless CMS to easily build customizable APIs

---

- [Official Sources](#official-sources)
  - [Documentation](#documentation)
  - [GitHub Repos](#github-repos)
  - [Community Platforms](#community-platforms)
  - [Other](#other)
- [Showcase](#showcase)
- [One-Click & Deployment](#one-click--deployment)
- [Strapi v4](#strapi-v4)
  - [Starters & Templates](#starters--templates)
  - [Plugins & Providers](#plugins--providers)
    - [Official Plugins](#official-plugins)
    - [Official Providers](#official-providers)
    - [Community Plugins & Providers](#community-plugins--providers)
    - [SDKs](#sdks)
- [Strapi v3](#strapi-v3)
  - [Templates - v3](#templates---v3)
  - [Starters & Examples - v3](#starters--examples---v3)
    - [Angular - v3](#angular---v3)
    - [Gatsby - v3](#gatsby---v3)
    - [Gridsome - v3](#gridsome---v3)
    - [Next.js - v3](#nextjs---v3)
    - [Nuxt.js - v3](#nuxtjs---v3)
    - [React - v3](#react---v3)
    - [Sapper - v3](#sapper---v3)
    - [Vue.js - v3](#vuejs---v3)
  - [Plugin & Providers - v3](#plugin--providers---v3)
    - [Official Plugins - v3](#official-plugins---v3)
    - [Community Plugins - v3](#community-plugins---v3)
    - [Community WYSIWYG Replacements - v3](#community-wysiwyg-replacements---v3)
    - [Community Custom Field Plugins - v3](#community-custom-field-plugins---v3)
    - [Community Middlewares - v3](#community-middlewares---v3)
    - [Community Hooks - v3](#community-hooks---v3)
    - [Email Providers - v3](#email-providers---v3)
    - [Upload Providers - v3](#upload-providers---v3)
    - [Ecosystem - v3](#ecosystem---v3)
    - [SDKs - v3](#sdks---v3)
    - [Third Party Modules - v3](#third-party-modules---v3)

---

## Official Sources

- [Strapi](https://github.com/strapi/strapi) - Official Strapi repository.
- [Try live demo](https://strapi.io/demo) - Official Strapi demo.
- [Strapi Feedback](https://feedback.strapi.io/) - Strapi roadmap and feature requests.

### Documentation

- [**v4 Developer Docs**](https://docs.strapi.io/developer-docs/latest/getting-started/introduction.html) - Official Developer Documentation for v4.
- [**v4 User Docs**](https://docs.strapi.io/user-docs/latest/getting-started/introduction.html) - Official User Documentation for v4.
- [v3 Developer Docs](https://docs-v3.strapi.io/developer-docs/latest/getting-started/introduction.html) - Official Developer Documentation for v3.
- [v3 User Docs](https://docs-v3.strapi.io/user-docs/latest/getting-started/introduction.html) - Official User Documentation for v3.

### GitHub Repos

- [strapi/strapi](https://github.com/strapi/strapi) - Official Strapi code repository.
- [strapi/documentation](https://github.com/strapi/documentation) - Official Strapi documentation repository.
- [strapi/design-system](https://github.com/strapi/design-system) - Official Design System repository.
- [strapi/codemods](https://github.com/strapi/codemods) - Official CodeMods repository.
- [strapi/rfcs](https://github.com/strapi/rfcs) - Official Request for Comments.

### Community Platforms

- [Forum](https://forum.strapi.io) - Official Strapi forum.
- [Discord](https://discord.strapi.io/) - Official Strapi Discord.

### Other

- [Tutorials](https://strapi.io/tutorials) - Official and Community Tutorials ([Submit](https://github.com/strapi/strapi-tutorials) new tutorials).
- [Meetups](https://github.com/strapi/strapi-meetups) - Meetups and Webinars.

## Showcase

- [Projects using Strapi](https://strapi.io/showcase)
- [Community Content](https://github.com/strapi/community-content) - User content created by the community.

## One-Click & Deployment

As of December 2021, we no longer support one-click options as it goes against the methodology of how we hope to see Strapi users deploying their projects.

## Strapi v4

### Starters & Templates

We are currently working on porting our starters & templates from v3, you can follow the progress in this monorepo: [strapi/starters-and-templates](https://github.com/strapi/starters-and-templates)!

- [Starter - Next - Blog](https://github.com/strapi/starters-and-templates/tree/main/packages/starters/next-blog)
- [Starter - Next - Corporate](https://github.com/strapi/starters-and-templates/tree/main/packages/starters/next-corporate)
- [Template - Blog](https://github.com/strapi/starters-and-templates/tree/main/packages/templates/blog)
- [Template - Corporate](https://github.com/strapi/starters-and-templates/tree/main/packages/templates/corporate)
- [Template - Ecommerce](https://github.com/strapi/starters-and-templates/tree/main/packages/templates/ecommerce)

### Plugins & Providers

#### Official Plugins

_Note: All official Strapi v4 Plugins will start with `@strapi/`_

- [Swagger Documentation](https://github.com/strapi/strapi/tree/master/packages/plugins/documentation)
- [GraphQL](https://github.com/strapi/strapi/tree/master/packages/plugins/graphql)
- [Internationalization (i18n)](https://github.com/strapi/strapi/tree/master/packages/plugins/i18n)
- [Sentry](https://github.com/strapi/strapi/tree/master/packages/plugins/sentry)
- [Users-Permissions](https://github.com/strapi/strapi/tree/master/packages/plugins/users-permissions)

#### Official Providers

_Note: All official Strapi v4 Providers will start with `@strapi/`_

- [Email - Amazon SES](https://github.com/strapi/strapi/tree/master/packages/providers/email-amazon-ses)
- [Email - Mailgun](https://github.com/strapi/strapi/tree/master/packages/providers/email-mailgun)
- [Email - Nodemailer](https://github.com/strapi/strapi/tree/master/packages/providers/email-nodemailer)
- [Email - SendGrid](https://github.com/strapi/strapi/tree/master/packages/providers/email-sendgrid)
- [Email - Sendmail](https://github.com/strapi/strapi/tree/master/packages/providers/email-sendmail)
- [Upload - Amazon S3](https://github.com/strapi/strapi/tree/master/packages/providers/upload-aws-s3)
- [Upload - Cloudinary](https://github.com/strapi/strapi/tree/master/packages/providers/upload-cloudinary)
- [Upload - Local](https://github.com/strapi/strapi/tree/master/packages/providers/upload-local)
- [Upload - Rackspace](https://github.com/strapi/strapi/tree/master/packages/providers/upload-rackspace)

#### Community Plugins & Providers

For community packages and providers, we currently are promoting a community project instead of this repo:

[IsStrapiReady.com](https://isstrapiready.com/)
[Submit your Plugin or Provider](https://github.com/Stun3R/isstrapiready/issues/new?assignees=&labels=&template=plugin-request.yml&title=%5BPLUGIN%2FPROVIDER+REQUEST%5D+%3Ctitle%3E)

#### SDKs

- [strapi-sdk-js](https://github.com/Stun3R/strapi-sdk-js) - Community built SDK for Javascript

## Strapi v3

**Please Note:** as of Nov 30th, 2021 Strapi v3 is now in a **maintenance only status for 6 months**, for more information see this [NOTICE Issue](https://github.com/strapi/strapi/issues/11726) on our main code repo.

**Following the maintenance status it will go EOL on May 30th, 2022.**

### Templates - v3

- [Blog](https://github.com/strapi/strapi-template-blog) - Template to create Strapi projects pre-configured for blogs
- [Catalog](https://github.com/strapi/strapi-template-catalog) - Template to create Strapi projects pre-configured for catalog sites
- [Corporate](https://github.com/strapi/strapi-template-corporate) - Template to create Strapi projects pre-configured for corporate sites
- [E-commerce](https://github.com/strapi/strapi-template-ecommerce) - Template to create Strapi projects pre-configured for e-commerce apps
- [Heroku](https://github.com/strapi/strapi-heroku-template) - Official template for Heroku 1 click deploy button
- [Portfolio](https://github.com/strapi/strapi-template-portfolio) - Template to create Strapi projects pre-configured for portfolio sites

### Starters & Examples - v3

- [Examples](https://github.com/strapi/strapi-examples) - General examples (Outdated).
- [OrgServer](https://github.com/kaiyuanshe/OrgServer) - **Data Server** scaffold for all kinds of **Organizations**

#### Angular - v3

- [Angular Blog](https://github.com/strapi/strapi-starter-angular-blog) - Blog example using Angular and GraphQL.

#### Gatsby - v3

- [Gatsby Blog](https://github.com/strapi/strapi-starter-gatsby-blog) - Blog example using Gatsby and GraphQL.
- [Gatsby Catalog](https://github.com/strapi/strapi-starter-gatsby-catalog) - Gatsby Catalog starter.

#### Gridsome - v3

- [Gridsome Blog](https://github.com/strapi/strapi-starter-gridsome-blog) - Blog example using Gridsome

#### Next.js - v3

- [Next Blog](https://github.com/strapi/strapi-starter-next-blog) - Blog example using Next and GraphQL.
- [Next Corporate](https://github.com/strapi/strapi-starter-next-corporate) - Next.js starter for creating a corporate site.
- [Next E-commerce](https://github.com/strapi/strapi-starter-next-ecommerce) - Starter Next.js E-commerce.

#### Nuxt.js - v3

- [Nuxt Blog](https://github.com/strapi/strapi-starter-nuxt-blog) - Blog example using Nuxt and GraphQL.
- [Nuxt E-commerce](https://github.com/strapi/strapi-starter-nuxt-e-commerce) - Starter Nuxt.js E-commerce.

#### React - v3

- [Food Advisor](https://github.com/strapi/foodadvisor) - THE Strapi demo application.
- [React Blog](https://github.com/strapi/strapi-starter-react-blog) - Blog example using React and GraphQL.

#### Sapper - v3

- [Sapper Blog](https://github.com/malgamves/strapi-starter-minimal-sapper-blog) - Minimal blog example using Sapper and GraphQL.

#### Vue.js - v3

- [Vue Blog](https://github.com/strapi/strapi-starter-vue-blog) - Blog example using Vue and GraphQL.

### Plugin & Providers - v3

#### Official Plugins - v3

- [Documentation](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-plugin-documentation) - Official SwaggerUI/OpenAPI Documentation for v3.
- [GraphQL](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-plugin-graphql) - Official GraphQL plugin including GraphQL Playground for v3.
- [Sentry](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-plugin-sentry) - Official Sentry plugin for v3.

#### Community Plugins - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Comments](https://github.com/VirtusLab/strapi-plugin-comments) - End to end comments feature with their moderation panel, bad words filtering, abuse reporting and more.
- [Config Sync](https://github.com/boazpoolman/strapi-plugin-config-sync) - Manage database config (core_store e.g.) as partial JSON files. Import/Export across environments.
- [Email Designer](https://github.com/alexzaganelli/strapi-plugin-email-designer) - Design your own **email templates** w/ visual composer directly inside the Strapi admin panel and send composed emails programmatically from your controllers / services.
- [Entity Relationship Chart](https://github.com/node-vision/strapi-plugin-entity-relationship-chart) - Display Entity Relationship Diagram of all models, fields and relations.
- [Expo Notifications](https://github.com/Lith/strapi-plugin-notification-expo) - Send Expo notification to mobile app
- [Github Publish](https://github.com/phantomstudios/strapi-plugin-github-publish) - Lets you publish content changes using a GitHub Actions workflow.
- [Import content](https://github.com/pouyamiralayi/strapi-import-content-plugin-tutorial) - Import content with a csv file, external url or raw text.
- [Medusa](https://github.com/Deathwish98/medusa-plugin-strapi) - Open-source Node.js commerce engine for Strapi.
- [Meilisearch](https://github.com/meilisearch/strapi-plugin-meilisearch) - Add your Strapi collections into a MeiliSearch instance.
- [Migrate](https://github.com/ijsto/strapi-plugin-migrate) - Migrate Settings & Layouts, User Permissions between environments. (Webhooks & Content migrations coming soon).
- [Moesif](https://github.com/bglidwell/strapi-plugin-moesif) - Plugin to add Moesif API Analytics and Monitoring (https://www.moesif.com/).
- [Navigation Builder](https://github.com/VirtusLab/strapi-plugin-navigation) - Navigation / menu builder feature with possibility to control the audience and different output structure renderers like (flat, tree and RFR - ready for handling by Redux First Router)
- [oEmbed](https://github.com/nicolashmln/strapi-plugin-oembed) - Embed content from third party sites (Youtube, Vimeo, Soundcloud, ...).
- [Passwordless](https://github.com/kucherenko/strapi-plugin-passwordless) - A plugin that provides ability to sign-in/sign-up to an application by link had sent to email.
- [Responsive image](https://github.com/nicolashmln/strapi-plugin-responsive-image) - Custom responsive image formats.
- [Raw Query](https://github.com/creazy231/strapi-plugin-raw-query) - Sends raw query strings to the database.
- [Sitemap](https://github.com/boazpoolman/strapi-plugin-sitemap) - Generate a sitemap.xml.
- [Sync Roles And Permissions](https://github.com/alan2207/strapi-plugin-sync-roles-permissions) - Store user roles and permissions configuration as a JSON file and then import and reuse it any time.
- [Testing](https://github.com/Antoine-lb/strapi-plugin-testing) - Out of the box Unit/Integration testing with mocking functions.
- [Video Thumbnail](https://github.com/darron1217/strapi-plugin-video-thumbnail) - Add video thumbnail functionality to Upload plugin (using FFmpeg).
- [Zeasy Image Api](https://github.com/kwinyyyc/strapi-plugin-zeasy-image-api) - Search and import image from Unsplash / Giphy to the rich text field with appropriate attribution.

#### Community WYSIWYG Replacements - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [CKEditor 5](https://github.com/Roslovets-Inc/strapi-plugin-ckeditor5) - Replace Strapi default WYSIWYG editor with enhanced build of **CKEditor** 5.
- [React MD Editor](https://github.com/kwinyyyc/strapi-plugin-wysiwsg-react-md-editor) - Replace Strapi default WYSIWYG editor with **React MD Editor**.
- [Toast UI Editor](https://github.com/fagbokforlaget/strapi-plugin-wysiwyg-toastui) - Replace Strapi default WYSIWYG editor with **Toast UI Editor**.
- [Editor.js](https://github.com/melishev/strapi-plugin-react-editorjs) - Replace Strapi default WYSIWYG editor with **Editor.js**.

#### Community Custom Field Plugins - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Point List Field](https://github.com/akcyp/strapi-plugin-point-list) - Mark an area on the image and save the list of points to the database.
- [Internaional Fields](https://github.com/MattieBelt/strapi-plugin-international-fields) - Add localized fields: Country, Language, Nationality

#### Community Middlewares - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [LRU Caching](https://github.com/patrixr/strapi-middleware-cache) - LRU caching for the api.
- [Upload Plugin Cache](https://github.com/alexkainzinger/strapi-middleware-upload-plugin-cache) - Configurable middleware for caching uploaded assets when using strapi-provider-upload-local.

#### Community Hooks - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Algolia](https://github.com/MattieBelt/strapi-hook-algolia) - Maintain search indexes with the Agolia service.

#### Email Providers - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Amazon-SES](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-email-amazon-ses) - Amazon SES email provider.
- [Mailgun](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-email-mailgun) - Mailgun email provider.
- [MailJet](http://github.com/ijsto/strapi-provider-email-mailjet) - MailJet email provider.
- [Mailtrap](https://github.com/alessandrocaprarelli/strapi-provider-email-mailtrap) - Mailtrap email provider.
- [Nodemailer](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-email-nodemailer) - Nodemailer email provider.
- [Postmark](https://github.com/ijsto/strapi-provider-email-postmark) - Postmark email provider.
- [Sendgrid](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-email-sendgrid) - Sendgrid email provider.
- [Sendinblue](https://github.com/eddybordi/strapi-provider-email-sendinblue) - Sendinblue email provider.
- [Sendmail](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-email-sendmail) - Sendmail email provider.

#### Upload Providers - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Amazon S3](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-upload-aws-s3) - Amazon S3 bucket upload provider.
- [Azure](https://github.com/jakeFeldman/strapi-provider-upload-azure-storage) - Azure Storage upload provider.
- [Cloudinary](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-upload-cloudinary) - Cloudinary upload provider.
- [DigitalOcean](https://github.com/shorwood/strapi-provider-upload-do) - DigitalOcean S3 upload provider.
- [Google Cloud Storage](https://github.com/Lith/strapi-provider-upload-google-cloud-storage) - Google Cloud Storage upload provider.
- [HubSpot](https://github.com/gkemp94/strapi-provider-upload-hubspot) - HubSpot upload provider.
- [Rackspace](https://github.com/strapi/strapi/tree/v3.6.8/packages/strapi-provider-upload-rackspace) - Rackspace upload provider.
- [Scaleway](https://github.com/Sqveeze/strapi-provider-upload-scaleway) - Scaleway upload provider.
- [WeTransfer](https://github.com/zeybek/strapi-provider-upload-wt) - WeTransfer upload provider.

#### Ecosystem - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Buffet.js](https://github.com/strapi/buffet) - React components library for Strapi plugins.

#### SDKs - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [Javascript SDK](https://github.com/strapi/strapi-sdk-javascript) - Official Javascript SDK (Currently outdated).
- [Jekyll](https://github.com/strapi/jekyll-strapi) - Jekyll plugin to retrieve content from a Strapi API.
- [MobX-Strapi](https://github.com/EasyWebApp/MobX-Strapi) - **MobX** v5 SDK for Strapi v3

#### Third Party Modules - v3

**Note that all of these plugins/providers/packages are currently for v3**

- [NgxStrapiAuth](https://github.com/jabali2004/ngx-strapi-auth) - Angular authentication library with pre-built components.

## Notice

As of January 2022, this repo is no longer maintained by Strapi LLC. nor Strapi SAS and the ownership has been collectively transferred to the Strapi Community who has no directly relation to either Strapi LLC. nor Strapi SAS. Strapi is a registered trademark of Strapi LLC and the Strapi Community have been granted exclusive inherited rights to use the name "Strapi" as well as the Strapi logo contained in the following files: [awesome-strapi-logo.jpg](./media/awesome-strapi-logo.jpg) and [awesome-strapi-logo.png](./media/awesome-strapi-logo.png). Further modification of this logo is allowed under the MIT license stored in this repo by the new maintainers.

If anyone has any questions regarding the transfer of the repo or the rights granted please feel free to email Strapi LLC directly at community@strapi.io

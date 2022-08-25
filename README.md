# Architecture checklist

### Functional requirements that (might be) important:



- Editing experience
  - Structured or WYSIWYG?
  - Admin panel or inline editing?
  - Editing on mobile / tablet
- Ecommerce features
  - Cart / checkout management, or handover to another service?
- User accounts and private content
- Image / asset management
- Content previews
- Commenting
- Federated posting to social networks
- Search
- Forms (i.e. for a Contact Us page)
- Analytics
- Customer segmentation and personalisation




### Cross functional requirements that (might be) important:



- Headless or traditional approach. Do we need to manage two codebases or one? Do the components need to upgrade together?
- Hosting. Hosted as a Docker container? Deployed to a VPS? Are there managed hosting options?
- Updates from the provider. How frequently are new versions released? Can upgrade happen unattended? Do upgrade require technical expertise?
- Deploying our changes / implementation. Deployable from a devops pipeline? Easy to deploy test environments?
- Security. What is the security history of the project? How are security incidents handled? Is there a security policy?
- Performance. Where are the bottle necks? Do we need to have a caching layer? How does the solution scale?
- Community. What's the community support story? Are there developers available to hand over to?
- Extensibility. How easy is it for us to add a features? Plug-in architecture, or would we extend an open source codebase? Are there lots of community plugins available?

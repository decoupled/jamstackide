----
This is work in progress
----

# JAMStack IDE

* The JAMStack IDE Is a VSCode Extension that provides high-quality support for a set of technologies, services and frameworks that adhere to the JAMStack architecture.

Participants:

* Frameworks:
  * Redwood.js, Next.js, Gatsby.js, Nuxt, Svelte, ...
* Clouds
  * Netlify
* DB related
  * FaunaDB
  * Prisma
* APIs
  * Contentful
* ...

# Why did we build this?

Sort answer:
* To make the JAMStack experience better for everyone!

Longer answer:

* Writing VSCode extensions is hard.
* It requires knowledge that is sometimes beyond the abilities of the core team behind a web framework, for example.
* Keeping the developer experience consistent when using multiple extensions requires coordination across teams

# Contributing to the JAMStack IDE

* If you are working on a web framework, API service, CSS library, etc that you believe adheres to the JAMStack architecture

## Language Servers and The JAMStack IDE SDK

* Contributions to the IDE have two parts
  * You can add some logic to the main extension here
  * Your framework can contribute a Language Server that uses an extended version of the Language Server Protocol
  

### Diagnostics and Language Features

* Diagnostics and Language features are provided by a Language Server that you implement, and publish, alongside your framework.


### Project Outline, Lifecycle, Preview and others


# FAQ

* I can write VSCode extensions. Why would I build an extension for the JAMStack IDE?


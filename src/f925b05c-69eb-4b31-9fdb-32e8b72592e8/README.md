### JCB! Snippet
# [Data Spy](https://getbootstrap.com/docs/4.0/components/scrollspy/)

## data-spy

Scrollspy has a few requirements to function properly:

    If building our JS from source, it requires util.js.
    It must be used on a Bootstrap nav component or list group.
    Scrollspy requires position: relative; on the element you’re spying on, usually the .
    When spying on elements other than the , be sure to have a height set and overflow-y: scroll; applied.
    Anchors () are required and must point to an element with that id.

When successfully implemented, your nav or list group will update accordingly, moving the .active class from one item to the next based on their associated targets.

### Snippet
```
<!-- Custom css that makes this example work like it does: -->
<style type="text/css" scoped="">
.scrollspy-example {
    position: relative;
    height: 200px;
    margin-top: .5rem;
    overflow: auto;
}
</style>

<!-- Actual scrollspy markup: -->
<nav id="navbar-example2" class="navbar navbar-light bg-light">
  <h3 class="navbar-brand">Project Name</h3>
  <ul class="nav nav-pills">
    <li class="nav-item"><a class="nav-link" href="#verse1">Verse 1</a></li>
    <li class="nav-item"><a class="nav-link" href="#verse2">Verse 2</a></li>
  </ul>
</nav>
<div data-spy="scroll" data-target="#navbar-example2" data-offset="0" class="scrollspy-example">
  <h4 id="verse1">Verse 1</h4>
  <p>May <br> the <br> gods <br> forgive <br> me.</p>
  <h4 id="verse2">Verse 2</h4>
  <p>For <br> this <br> rampant <br> abuse <br> of <br> br-tags.</p>
</div>
```

### Usage
> When successfully implemented, your nav or list group will update accordingly, moving the .active class from one item to the next based on their associated targets.

### Contributor
- Most Wanted Web Services, Inc.
- Steve Voorhees
- [email](mailto:sales@mwweb.host)
- [website](https://mostwantedwebhosting.com)

> Streamline your Joomla development with a single, reusable snippet designed for flexibility, consistency, and easy updates.

### Used in [Joomla Component Builder](https://www.joomlacomponentbuilder.com) - [Source](https://git.vdm.dev/joomla/Component-Builder) - [Mirror](https://github.com/vdm-io/Joomla-Component-Builder) - [Download](https://git.vdm.dev/joomla/pkg-component-builder/releases)

---
[![Joomla Volunteer Portal](https://img.shields.io/badge/-Joomla-gold?logo=joomla)](https://volunteers.joomla.org/joomlers/1396-llewellyn-van-der-merwe "Join Llewellyn on the Joomla Volunteer Portal: Shaping the Future Together!") [![Octoleo](https://img.shields.io/badge/-Octoleo-black?logo=linux)](https://git.vdm.dev/octoleo "--quiet") [![Llewellyn](https://img.shields.io/badge/-Llewellyn-ffffff?logo=gitea)](https://git.vdm.dev/Llewellyn "Collaborate and Innovate with Llewellyn on Git: Building a Better Code Future!") [![Telegram](https://img.shields.io/badge/-Telegram-blue?logo=telegram)](https://t.me/Joomla_component_builder "Join Llewellyn and the Community on Telegram: Building Joomla Components Together!") [![Mastodon](https://img.shields.io/badge/-Mastodon-9e9eec?logo=mastodon)](https://joomla.social/@llewellyn "Connect and Engage with Llewellyn on Joomla Social: Empowering Communities, One Post at a Time!") [![X (Twitter)](https://img.shields.io/badge/-X-black?logo=x)](https://x.com/llewellynvdm "Join the Conversation with Llewellyn on X: Where Ideas Take Flight!") [![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github)](https://github.com/Llewellynvdm "Build, Innovate, and Thrive with Llewellyn on GitHub: Turning Ideas into Impact!") [![YouTube](https://img.shields.io/badge/-YouTube-ff0000?logo=youtube)](https://www.youtube.com/@OctoYou "Explore, Learn, and Create with Llewellyn on YouTube: Your Gateway to Inspiration!") [![n8n](https://img.shields.io/badge/-n8n-black?logo=n8n)](https://n8n.io/creators/octoleo "Effortless Automation and Impactful Workflows with Llewellyn on n8n!") [![Docker Hub](https://img.shields.io/badge/-Docker-grey?logo=docker)](https://hub.docker.com/u/llewellyn "Llewellyn on Docker: Containerize Your Creativity!") [![Open Collective](https://img.shields.io/badge/-Donate-green?logo=opencollective)](https://opencollective.com/joomla-component-builder "Donate towards JCB: Help Llewellyn financially so he can continue developing this great tool!") [![GPG Key](https://img.shields.io/badge/-GPG-blue?logo=gnupg)](https://git.vdm.dev/Llewellyn/gpg "Unlock Trust and Security with Llewellyn's GPG Key: Your Gateway to Verified Connections!")
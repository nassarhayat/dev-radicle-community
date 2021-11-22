<script>
  import Community from "./Community.svelte";
  import Distribute from "./Distribute.svelte";
  import Collab from "./Collab.svelte";
  import Funding from "./Funding.svelte";
  import HIW from "./HIW.svelte";
  import Logo from "./Logo.svelte";
</script>

<div id="wrap">
  <main>
    <div id="logo">
      <Logo />
    </div>
    <h1>Build your DevDAO.</h1>
    <h3>
      p2p code collab + funding + DAOs = <a
        href="https://twitter.com/radicle"
        target="_blank">@radicle</a
      >
    </h3>
    <img class="heroimage" src="assets/images/ui/org-page.png" alt="org page" />
  </main>
  <Community />
  <Distribute />
  <Collab />
  <Funding />
  <HIW />
</div>

<div id="apply-button">
  <form action="https://l57by8cmnip.typeform.com/to/zLsgh566" target="_blank">
    <input type="submit" value="Apply to join the beta →" />
  </form>
</div>

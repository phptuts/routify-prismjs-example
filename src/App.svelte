<script>
  import { Router } from "@sveltech/routify";
  import { routes } from "../.routify/routes";
</script>

<style global>
  @import "../static/global.css";
  @import "../static/extra.css";
</style>

<Router {routes} />

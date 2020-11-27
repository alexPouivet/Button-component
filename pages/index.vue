<template>
  <div>
    <header>
      <h1>Buttons</h1>
    </header>
    <main>
      <div class="main">
        <div class="lign">
          <div class="button-container">
            <p>< Button /></p>
            <b-button class="button-classic">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button variant="outline" /></p>
            <b-button class="button-variant-outline">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button variant="text" /></p>
            <b-button class="button-variant-text">Default</b-button>
          </div>
        </div>
        <div class="lign">
          <div class="button-container">
            <p>< Button disableShadow /></p>
            <b-button  class="button-disableShadow">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button disabled /></p>
            <b-button disabled class="button-disabled">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button variant="text" disabled /></p>
            <b-button disabled class="button-variant-text-disabled">Default</b-button>
          </div>
        </div>
        <div class="lign">
          <div class="button-container">
            <p>< Button startIcon="local_grocery_store" /></p>
            <b-button  class="button-startIcon"><i class="material-icons">local_grocery_store</i>Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button endIcon="local_grocery_store" /></p>
            <b-button  class="button-endIcon">Default<i class="material-icons">local_grocery_store</i></b-button>
          </div>
        </div>
        <div class="lign">
          <div class="button-container">
            <p>< Button size="sm" /></p>
            <b-button size="sm" class="button-small">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button size="md" /></p>
            <b-button class="button-medium">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button size="lg" /></p>
            <b-button size="lg" class="button-large">Default</b-button>
          </div>
        </div>
        <div class="lign">
          <div class="button-container">
            <p>< Button color="default" /></p>
            <b-button class="button-classic">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button color="primary" /></p>
            <b-button variant="primary" class="button-color-primary">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button color="secondary" /></p>
            <b-button variant="secondary" class="button-color-secondary">Default</b-button>
          </div>
          <div class="button-container">
            <p>< Button color="danger" /></p>
            <b-button variant="danger" class="button-color-danger">Default</b-button>
          </div>
        </div>
      </div>
    </main>
    <footer>
      <p>Alexandre Pouivet @DevChallenges.io</p>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

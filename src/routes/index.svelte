<script>
	import About from './about.svelte';
  import Header from "./header.svelte";

</script>
<Header />

<div class="interaction-top"><h1 id="headline"><span>To Do Application!</span></h1><img src="https://to-do-cdn.microsoft.com/static-assets/da7ea2e49739d43b8e3a4d59c6029b078a13f81b18a7b236cd0ebfc41495dfd1/icons/welcome-center.png" class="image-center" alt=""><p class="description"><span>To Do vous aide à vous concentrer, aussi bien dans vos activités personnelles que professionnelles.</span></p></div>

<style>
  .interaction, .interaction-top, .interaction-signin, .interaction-bottom {
    justify-content: center;
    flex-direction: column;
}
.interaction {
    min-width: 450px;
}
.interaction, .presentation-left, .presentation-right, .interaction-top, .interaction-signin, .interaction-bottom {
    display: flex;
    align-items: center;
}
* {
    margin: 0;
    padding: 0;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
user agent stylesheet
div {
    display: block;
}
body {
    color: #34373d;
    font-size: 14px;
    -webkit-touch-callout: none !important;
    font-weight: 500;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
body, button {
    font-family: 'Segoe', 'Segoe UI', Arial, 'sans-serif';
}
html, body {
    height: 100%;
    font-size: 62.5%;
}
.interaction-top{
  margin-top: 100px;
}
</style>
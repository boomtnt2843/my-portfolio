<script>
  import "../app.css";
  import "@fontsource/sriracha"
  import 'iconify-icon'
</script>

<slot />

<footer class="flex fixed py-4 px-2 bottom-0 w-screen bg-cyan-700 justify-center items-center text-white space-x-4">
  <a href="https://github.com/boomtnt2843/my-portfolio">
    <button class="flex items-center bg-cyan-500 rounded-lg p-1"><iconify-icon class=" text-xl" icon="line-md:github-loop" /> source code</button>
  </a>
  <p>by saynumB</p>
</footer>
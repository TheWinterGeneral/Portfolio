<script>
  import Navagation from "./navbar.svelte";
</script>

<main class="bg-othergray h-screen">
  <Navagation></Navagation>
  <div class="flex text-othergray space-x-4 p-4">
    <div class=" bg-divgray w-1/2 rounded-xl hover:w-4/5">
      <h1
        class="laptop:text-5xl desktop:text-5xl tablet:text-4xl font-bold text-wrap text-center justify-center"
      >
        About Me
      </h1>
      <p class="laptop:text-2xl desktop:text-2xl tablet:text-1xl font-bold">
        I am a self taught programmer. I have been programming for about a year.
        I mainly do web development, specializing in Svelte. I have also coded a
        few discord bots before, but haven't gone far into bot development as I
        much prefer web development.
      </p>
    </div>
    <div class="bg-divgray w-1/2 mx-4 rounded-xl hover:w-4/5">
      <h1 class="laptop:text-5xl desktop:text-5xl tablet:text-4xl font-bold text-wrap text-center justify-center">
        Technologies
      </h1>
      <ul class="laptop:text-2xl desktop:text-2xl tablet:text-1xl font-bold list-disc pl-5">
        <li>Svelte <br/><br/></li>
        <li>Basic Python<br/><br/></li>
        <li>Pycord<br/><br/></li>
        <li>Linux<br/><br/></li>
      </ul>
    </div>
  </div>
</main>

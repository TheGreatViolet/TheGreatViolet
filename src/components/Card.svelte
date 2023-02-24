<script lang="ts">
  export let title: string;
  export let description: string;
  export let link: string;
  export let image: string;
  export let alt: string;
</script>

<div
  class="bg-gray-700 m-6 w-1/5 h-1/2
  rounded-md shadow-lg hover:shadow-2xl"
>
  <a href={link}>
    <div class="border-b-2 border-gray-500 flex flex-col">
      <h1 class="text-2xl text-gray-100 p-2">{title}</h1>

      <p class="text-gray-100 p-2 pt-0">{description}</p>
    </div>

    <div class="h-full w-full">
      <img src={image} {alt} class="rounded-b-md h-full " />
    </div>
  </a>
</div>

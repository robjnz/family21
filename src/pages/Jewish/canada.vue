<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/canada-flag.jpg"
          alt="image of canadian flag"
        />
        Canadian Jewish Family History Resourses
      </h1>

      <div class="grid sm:flex">
        <network />
      </div>

      <br />
      <p>
       
        <dropdown />
      
      </p>
      <br />
      <p>
        Add
        <g-link
          class="text-red-600 hover:text-yellow-600"
          to="http://bit.ly/2SxWdgt"
          target="_blank"
        >
          google translate
        </g-link>
        to your browser extensions, to view foreign language web sites.
      </p>

      <br />
    </div>
  </Layout>
</template>

<script>
import network from "@/components/Canada/Jewish/network";


import dropdown from "@/components/Dropdown/dropdown";



export default {
  metaInfo: {
    title: "Canadian",
    meta: [
      {
        name: "description",
        content:
          "Canadian Jewish Family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    network,
    

    dropdown,
  },
};
</script>

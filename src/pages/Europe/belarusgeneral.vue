<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/belarus-flag.jpg"
          alt="austria flag"
        />
        Belarus Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <statearchives />
        <mogilev />

        <br />
      </div>
    </div>

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
  </Layout>
</template>

<script>
import statearchives from "@/components/Belarus/General/statearchives";
import mogilev from "@/components/Belarus/General/mogilev";

import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Belarus",
    meta: [
      {
        name: "description",
        content: "Belarus family history records of birth death and marriages",
      },
    ],
  },
  components: {
    statearchives,
    mogilev,
    dropdown,
  },
};
</script>

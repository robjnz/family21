<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> The O2 arena</h1>
      <g-link href="http://bit.ly/2PpXswU" target="_blank"
        ><g-image
         
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594204405/02_london_voe73e.jpg"
          alt = "The O2 arena Poster"
      /></g-link>

      <p class="text-blue-200">
        Peninsula Square<br />Greenwich London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/3aY1yDA"
          target = "_blank"
        >
         SE10 0DX
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       <!-- Fri 27 March -->
      </p>
<!--
      <article class="text-blue-200">
        Carlos Santana European Tour......
        <input
          id    = "read-more-two-1"
          class = "read-more-two"
          type  = "checkbox"
        />
        <div class="read-more-content ">
         .....  
        </div>
        <label
          class = "read-more-two-label text-red-700 hover:text-white"
          for   = "read-more-two-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2PpXswU"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

<style>
.read-more-content {
  max-height: 0;
  overflow  : hidden;
  transition: max-height 0.5s ease;
}
.read-more-two {
  display: none;
}
.read-more-two-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-two-label:after {
  content: "More";
  display: inline-block;
}
.read-more-two:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-two:checked + .read-more-content + .read-more-two-label:after {
  content: "Less";
}
</style>

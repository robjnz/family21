<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
           <i class="fas fa-arrow-alt-circle-shirley"></i>
        </span> Shirley Windmill</h1>
      <g-link href="https://bit.ly/2RajpzS" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/shirley.jpg"
          alt = "Shirley Windmill"

      /></g-link>
      <p class="text-blue-200">
        Postmill Close<br /> Croydon Surrey

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2V1JKkK"
          target = "_blank"
        >
          CR0 5DY
        </g-link>
      </p>
      
        <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>

      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
  One of the last windmills<br /> to be built...... 
  <input id="read-more-shirley-1" class="read-more-shirley" type="checkbox">
  <div class="read-more-content">
     in this country, a fascinating piece of <br />industrial archaeology of<br />a tower Mill built in 1854.

  </div>
  <label class="read-more-shirley-label postcode hover:text-white" for="read-more-shirley-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2RajpzS"
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
  transition: max-height .5s ease;
}
.read-more-shirley {
  display: none;
}
.read-more-shirley-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-shirley-label:after {
  content: "More";
  display: inline-block;
}
.read-more-shirley:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-shirley:checked + .read-more-content + .read-more-shirley-label:after {
  content: "Less";
}
</style>

<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Pitzhanger Manor</h1>
      <g-link href="https://bit.ly/2RscMsO" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/pitzhanger.jpg"
          alt   = "pitzhanger manor"
      /></g-link>
      <p class="text-blue-200">
    Mattock Lane<br />Ealing London


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2xZuAo8"
          target = "_blank"
        >
          W5 5EQ
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
Was the home of Sir John Soane<br /> one of the most influential architects..... 
<input id="read-more-pitzhanger-1" class="read-more-pitzhanger" type="checkbox">
  <div class="read-more-content">

 in British history. <br /><br />Soane designed many <br />extraordinary buildings,<br /> but Pitzhanger is almost unique<br /> as a building designed,<br /> built and lived in<br /> by Soane himself.

  </div>
<label class="read-more-pitzhanger-label postcode hover:text-white" for="read-more-pitzhanger-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2RscMsO"
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
.read-more-pitzhanger {
  display: none;
}
.read-more-pitzhanger-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-pitzhanger-label:after {
  content: "More";
  display: inline-block;
}
.read-more-pitzhanger:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-pitzhanger:checked + .read-more-content + .read-more-pitzhanger-label:after {
  content: "Less";
}
</style>

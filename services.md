---
layout: page
title: Services
---
<style>

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 5px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.card {
    width: 175px;
    height: 195px;
    position: relative;
    display: inline-block;
}
.card .img-top {
    display: none;
    position: absolute;
    top: 0;
    left: 0;
    z-index: 99;
}
.card:hover .img-top {
    display: inline;
}

.center {
        text-align: center;
      }

</style>

<div class="row">
<div class="center">

  <div class="column">
    <div class="card">
      <a href="/birth">
        <img src="assets/images/BirthBlue.svg" width="175" alt="Birth" />
        <img src="assets/images/BirthPink.svg" width="175" alt="Birth" class="img-top" />
      </a>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <a href="/postpartum">
        <img src="assets/images/PostBlue.svg" width="175" alt="Postpartum" />
        <img src="assets/images/PostPink.svg" width="175" alt="Postpartum" class="img-top" />
      </a>
    </div>
  </div>


    <!-- <div class="column">
      <div class="card">
        <a href="/chefathome">
          <img src="assets/images/ChefBlue.svg" width="175" alt="Chef at Home" />
          <img src="assets/images/ChefPink.svg" width="175" alt="Chef at Home" class="img-top" />
        </a>
      </div>
    </div> -->

</div>
</div>

<hr>

<p><i>I am dedicated to accessible doula care for everyone. If you would benefit from sliding scale fees, please contact me.</i></p>

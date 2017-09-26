<template>
  <div class="container-fluid">
      <div class="row header">
          <div class="col">Logo Buraya</div>
      </div>
    <div class="row">
       <div class="col5 col-margin">
           <div class="row">
               <div class="col-12 col-border" >
                   <div class="row">
                       <div class="col-4 title dotted">Name</div>
                       <div class="col-8 dotted">Cronir Fleece</div>
                   </div>
                   <div class="row">
                       <div class="col-4 title dotted">Player</div>
                       <div class="col-8 dotted">Sarp Doruk ASLAN</div>
                   </div>
                   <div class="row">
                       <div class="col-4 title">Campaign</div>
                       <div class="col-8 dotted">Living Kule</div>
                   </div>
               </div>
           </div>

           <div class="row">
               <div class="col-12 col-border" >
                   <div class="row">
                       <div class="col-4 title dotted">Place Of Birth</div>
                       <div class="col-8 dotted">Sirius Omega</div>
                   </div>
                   <div class="row">
                       <div class="col-4 title dotted">Religion</div>
                       <div class="col-8 dotted">Sarp Doruk ASLAN</div>
                   </div>
               </div>
           </div>
       </div>
        <div class="col-3 col-border">
            <div class="row">
                <div class="col-5 title dotted">RACE</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">GENDER</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">AGE</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">HEIGHT</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">WEIGHT</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">HAIR</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">EYES</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">SIGN</div>
                <div class="col-7 dotted"></div>
            </div>
            <div class="row">
                <div class="col-5 title dotted">MARKS</div>
                <div class="col-7 dotted"></div>
            </div>
        </div>
    </div>

  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    * {
        font-family: "Times New Roman";
    }
    .no-padding {
        padding:0 !important;
    }
    .col-border {
        border:1px solid gray;
        margin:10px;
    }

    .col-margin {
        margin: 10px;
    }

    .title {
        background: gray;
        color:white;
    }
    .title.dotted {
        border-bottom: 1px dotted white;
    }

    .dotted {
        border-bottom: 1px dotted gray;
    }


</style>

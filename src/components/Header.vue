<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
    import FooterV from './Footer.vue'
</script>

<template>

  <div id="headerMain">
      
    
      <div id="headerBg" class="container">
          <!-- <div id="headerTitle"> <span id="st">&lt;</span> <span id="nd">DIA</span> <span id="st">/></span> </div> -->
          <div id="headerTitle"> <div id="title">Student Coder DIA.</div> <div id="desc2">I like programming.</div>  </div> 
          <!-- <div id="count">About</div> <div id="desc">15 years old middle school student.</div> <div id="desc">My favorite food is The Monster Energy Drink.</div> <div id="desc">I play Minecraft Hypixel.</div> <div id="desc">I usually use Js and Ts etc.</div> -->
          <!-- <div id="shape" /> -->
          <div id="headerAbout2"> <span id="title">I mainly use</span> <img id="jsImg" class="shadow" src="../assets/js.png" /> <img id="jsImg" class="shadow" src="../assets/ts.png" />  </div>
          <div id="headerAbout2"> <span id="desc2"> I can use </span> <img id="jsImg" class="shadow" src="../assets/c.png" /> <img id="jsImg" class="shadow" src="../assets/cs.png" /> <img id="jsImg" class="shadow" src="../assets/python.png" /> <img id="jsImg" class="shadow" src="../assets/rust.png" /> </div>
          <div id="headerAbout"> <span id="desc2"> I'm learning </span> <img id="jsImg" class="shadow" src="../assets/rust.png" /> </div>

          <div id="msL">I made this projects</div>

          <div id="headerProject"> 
              <div id="cardPj" class="shadow" ><div id="cardTitle">Annumity</div><div id="cardAb">daily anime site.</div>
                <button type="button" id="gitBtn" class="btn btn-dark"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="32" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                    <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                </svg></button>
              </div>
              <div id="cardPj" class="shadow"><div id="cardTitle">Cominfo</div><div id="cardAb">view your spec in website.</div> 
                  <button type="button" id="gitBtn" class="btn btn-dark"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="32" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                    <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                  </svg></button>
                  
              </div> <!-- <button type="button" class="btn btn-dark">Github</button> -->
          </div> 

          <div id="msL">I like Monter Energy</div>

          <div id="msPgs" class="progress">
            <div class="progress-bar mango" role="progressbar" style="width: 35%" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100"></div>
            <div class="progress-bar ultra" role="progressbar" style="width: 20%" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100"></div>
            <div class="progress-bar orgl" role="progressbar" style="width: 15%" aria-valuenow="15" aria-valuemin="0" aria-valuemax="100"></div>
            <div class="progress-bar pl" role="progressbar" style="width: 15%" aria-valuenow="15" aria-valuemin="0" aria-valuemax="100"></div>
            <div class="progress-bar citra" role="progressbar" style="width: 10%" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100"></div>
            <div class="progress-bar prds" role="progressbar" style="width: 5%" aria-valuenow="5" aria-valuemin="0" aria-valuemax="100"></div>
          </div>

          <div id="headerMs">
              
              <div id="msBg" class="shadow">
                  <img id="msImg" src="../assets/monster/mango.png" />
                  <div id="msTitle">Mango Loco</div>
                  <div id="msPgss">35%</div>
              </div>

               <div id="msBg" class="shadow">
                  <!-- <span id="first">My First Monter</span> -->
                  <img id="msImg" src="../assets/monster/ultra.png" />
                  <div id="msTitle">Ultra</div>
                  <div id="msPgss">20%</div>
              </div>

              <div id="msBg" class="shadow">
                  <!-- <span id="first">My First Monter</span> -->
                  <img id="msImg" src="../assets/monster/original.png" />
                  <div id="msTitle">Original</div>
                  <div id="msPgss">15%</div>
              </div>

          </div>
          
          <div id="headerMs">
              <div id="msBg" class="shadow">
                      <!-- <span id="first">My First Monter</span> -->
                      <img id="msImg" src="../assets/monster/pink.png" />
                      <div id="msTitle">Pipeline</div>
                      <div id="msPgss">15%</div>
                  </div>
    
                  <div id="msBg" class="shadow">
                      <!-- <span id="first">My First Monter</span> -->
                      <img id="msImg" src="../assets/monster/citra.png" />
                      <div id="msTitle">Citra</div>
                      <div id="msPgss">10%</div>
                  </div>
    
                  <div id="msBg" class="shadow">
                      <!-- <span id="first">My First Monter</span> -->
                      <div id="msM">
                          <img id="msImg" src="../assets/monster/green.png" />
                          <div id="msTitle">Paradise</div>
                          <div id="msPgss">5%</div>
                      </div>
                  </div>

          </div>


          <div id="L"></div>

      </div>

      
  </div>

  <!-- <FooterV /> -->
</template>

<style>

#msPgs {
    width: 700px;
    position: relative;
    transform: translateX(42%);
    border-radius: 30px;
    height: 5px;
}
.mango {
    background: #DCAC4E;
}
.ultra {
    background: #E5E5E5;
}
.orgl {
    background: #14CE39;
}
.pl {
    background: #B86B78;
}
.citra {
    background: #EFD440;
}
.prds {
    background: #80AB4E;
}

#headerMs {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    /* display: table-cell; */
    vertical-align: middle;
}


#first {
    font-size: 20px;
    
}

#msL {
    font-size: 50px;
    font-weight: bold;
    margin-bottom: 100px;
}

#msPgss {
    font-size: 20px;
}

#msTitle {
    font-size: 30px;
}

#msImg {
    width: 150px;
    height: auto;
}

#msBg {
    width: 220px;
    height: 400px;
    padding: 20px;
    /* display: table-cell;
    vertical-align: middle; */
    border-radius: 30px;
    margin: 50px;
    
}

#L {
    margin-top: 200px;
    /* margin-bottom: 200px; */
}

#gitBtn {
    border-radius: 50px;
}

#headerProject {
    display: flex;
    justify-content: center;
    margin-bottom: 500px;
}

#cardPj {
    /* width: 300px;
    height: 200px; */
    border-radius: 20px;
    /* border: solid; */
    border-width: 1px;
    border-color: rgb(145, 145, 145);
    margin: 30px;
    padding: 0;
    width: 300px;
    
}
#cardTitle {
    font-size: 30px;
    font-weight: bold;
    
}
#cardAb {
    font-size: 20px;
}

#jsImg {
    width: 100px;
    height: auto;
}

#shape {
    width: 80%;
    height: 1px;
    background: rgb(145, 145, 145);
    
}

#headerBg {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  background: #282C34;
  color: rgb(145, 145, 145);
  padding: 20px;
  font-size: 100px;
  position: flex;
  justify-content: center;
  flex-direction: column;
  margin-top: 20%;
}

/* #headerMain {
    height: 400px;
} */

#headerTitle {
    margin-bottom: 600px;
}
#headerAbout {
    margin-bottom: 600px;
}

#headerLeft {
    flex-grow: 100px;
}

#headerRight {
    flex-grow: 100px;
}

#desc2 {
    font-size: 25px;
    margin-bottom: 50px;
}

#desc {
    font-size: 20px;
}

#title {
    font-size: 45px;
    font-weight: bold;
}

#count {
    font-size: 20px;
}

#st {
    color: rgb(146, 142, 184);
}
#nd {
    color: rgb(189, 189, 189);
}
#rd {
    color: rgb(23, 102, 82);
}
#rs {
    color: rgb(218, 218, 69);
}

#logoL {
    width: 20px;
    height: auto;
    position: sticky;

    left: 300px;
    top: 70px;
}
</style>

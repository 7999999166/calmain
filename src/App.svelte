<script>
  import { RouterView, Link } from '@bjornlu/svelte-router';
  import './w3.css';
  import './bootstrap.min.css';
</script>

 <style>
   .aa{
     display: flex;
     flex-direction: column;
     flex: 1;
     height:100%;
     background-color: #c9ada7;
   }
   .bb{
     height: 10%;
     background-color: #22223b;
     display: flex;
     align-items: center;
   }
   .cc{
     height:80%;
     background-color: #c9ada7;
     margin-top: 60px;
   }
   .dd{
     height: 10% ;
     background-color: #22223b;
     display: flex;
     justify-content: space-between;
     align-items: center;
     
   }
   .ll{
     margin-left: 20px;
   }
   .mm{
     margin-right: 20px;
   }
   a{
     text-decoration: none;
     color: #f2e9e4 ;
   }
   a:hover{
     color: #22223b ;
   }
.ee{
  display: flex;
  color: #f2e9e4;
  flex-grow: 6;
  margin-left: 10px;
}
.ff{
flex-grow:2 ;
display: flex;
justify-content: center;
}
.gg{
flex-grow:2 ;
display: flex;
justify-content: center;
}
.xx{
  font-family: monospace;
  font-size: 1.7rem;
}
 </style>
  <div class="aa">
      <div class="bb w3-top w3-card">
        <div class="ee"><h3 class="xx">Calculator</h3></div>
        <div class="ff"><button type="button" class="btn btn-outline-light">Clear</button></div>
        <div class="gg"><button type="button" class="btn btn-outline-light">Calculate</button></div>
      
     </div>


      <div class="cc">
       <RouterView /> 
      </div>


     <div class="dd w3-bottom w3-card">
       <div class="hh"><button type="button" class="btn btn-outline-light ll"><a href="/">Blank</a></button></div>
       <div class="ii"><button type="button" class="btn btn-outline-light"><a href="/circle">Circle</a></button></div>
       <div class="jj"><button type="button" class="btn btn-outline-light"><a href="/sheet">Sheet</a></button></div>
       <div class="kk"><button type="button" class="btn btn-outline-light mm"><a href="/cost">Cost</a></button></div>      
     </div>
  </div>


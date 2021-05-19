<script>    
</script>
<style>
.aa{
    display: flex;
    flex: 1;
    flex-direction: column;
    height: 90vh;
}
.bb{
flex-grow: 2;
background-color: #9a8c98;
display: flex;
justify-content: center;
align-items: center;
}

.dd{
 display: flex;
    flex: 4;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.ee{
 display: flex;
    flex: 4;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.gg{
    font-family: monospace;

}
.hh{
width: 80px;
}
input{
    margin-left: 30px;
}
.xx{
    margin-bottom: 80px;
    padding-bottom: 40px;
}
</style>
<div class="aa">
    <div class="bb"><h3 class="gg">Weight (Kg) : </h3></div>
    <div class="bb"><h3 class="gg">Volume (ltr) : </h3></div>
   
    <div class="dd">
    <h3 class="gg">Diameter (inch) :</h3>
    <input type="number" class="form-control hh">

    </div>
   
    <div class="ee xx">
    <h3 class="gg">Thickness (mm)  :</h3>
    <input type="number" class="form-control hh"> 


    </div>
    
</div>
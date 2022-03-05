<!DOCTYPE html>
<html>
    <head>
        <title>Mini Project of ON/OFF bulb</title>
    </head>
    <style>
        *{
            padding: 0%;
            margin: 0%;
        }
        body{
            margin: 0px;
            padding: 0px;
            background-color:white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            box-sizing: border-box;    
        }
        
        .bulb{
            text-align: center;
            padding: 35px 7px;
            margin: 35px 35px;
        }
        .container{
            background-color: rgb(221, 163, 86);
            padding: 5px; 
            text-decoration: none;
            overflow: hidden;
        }
    </style>
    <body>
        
        
        <section class="container">
              <img src="night-on-off.gif" width="100%" height="300">     
              <p>Click to the turn on button for on the Bulb and Click to the turn off button for off the bulb. </p>
          </section>  
          <script>
    function light(sw){

        var pic;

        if(sw==0){
            pic="off bulb.png"
        } else{
            pic="on bulb.png"
        }
        document.getElementById('bulb').src=pic;
    }
</script>
    <div class="bulb">
        <img id="bulb" src="off bulb.png"  width="200" height="280"  >      
    <p>
        <button type="button" onclick="light(1)" style="background-color:#f3971b;padding: 6px;mm;margin:6mm;" >Turn On</button>

        <button type="button" onclick="light(0)" style="background-color:darkgray;padding: 6px;mm;margin: 6px;mm;">Turn Off</button> 
        
    </p>      

</div>    
    </body>
</html>

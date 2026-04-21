

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./styles.css">  <title>Availability Table</title>
</head>

<body>
<table>
    <thead>
        <tr class="days">
            <th>Sunday</th>
             <th>Monday</th>
              <th>Tuesday</th>
               <th>Wednesday</th>
                <th>Thursday</th>
        </tr>
<tr class="half">
            <th class="time">5:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
            <tr class="half">
            <th class="time">16:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
            <tr class="sharp">
            <th class="time">12:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
            <tr class="sharp">
            <th class="time">2:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
            <tr>
            <th class="time">1:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
        </tr>
        
                    <tr>
            <th class="time">3:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
        </tr>
        
                    <tr>
            <th class="time">1:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
        </tr>
                    <tr>
            <th class="time">7:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
                        <tr>
            <th class="time">9:00</th>
                    <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
             <td class="available-5"></td>
            </tr>
        </tr>

        </tr>
        
        
           
    </thead>
    <tbody>
        
          <div id="legend"><span>Availability</span>
          <div id="legend-gradient"></div>
          </div>
    </tbody>
</table>
</body>

</html>
   Styles.css
 
:root{


 --color0:#ccc;
  --color1:#fdc;
  --color2:#fd2e;
  --color3:#c2e;
  --color4:#de7;
  --color5:#b32c;
 --solid-border: 2px solid black; 
--dashed-border: 1px dashed red;
}
*{

background-color:#cbc;

border:2px solid black; 
text-align:center;
font-family:bold;


}








.available-0 { background-color: var(--color0); }
.available-1 { background-color: var(--color1); }
.available-2 { background-color: var(--color2); }
.available-3 { background-color: var(--color3); }
.available-4 { background-color: var(--color4); }
.available-5 { background-color: var(--color5); }

.sharp td{

border-bottom: var(--solid-border)



}
.half td{


border-bottom: var(--dashed-border)

}
#legend-gradient{



  background-image: linear-gradient(
    to right,
    var(--color0) 0%  16%,
    var(--color1) 16% 32%,
    var(--color2)  32% 48%,
    var(--color3) 48% 64%,
    var(--color4) 64% 80%,
    var(--color5) 80% 100%
  );
}

}
:root{
  --color0:#ccc;
  --color1:#fdc;
  --color2:#fd2e;
  --color3:#c2e;
  --color4:#de7;
  --color5:#b32c;
 --solid-border: 2px solid black; 
--dashed-border: 1px dashed red;
}
*{

background-color:#cbc;

border:2px solid black; 
text-align:center;
font-family:bold;


}








.available-0 { background-color: var(--color0); }
.available-1 { background-color: var(--color1); }
.available-2 { background-color: var(--color2); }
.available-3 { background-color: var(--color3); }
.available-4 { background-color: var(--color4); }
.available-5 { background-color: var(--color5); }

.sharp td{

border-bottom: var(--solid-border)



}
.half td{


border-bottom: var(--dashed-border)

}
#legend-gradient{



  background-image: linear-gradient(
    to right,
    var(--color0) 0%  16%,
    var(--color1) 16% 32%,
    var(--color2)  32% 48%,
    var(--color3) 48% 64%,
    var(--color4) 64% 80%,
    var(--color5) 80% 100%
  );
}

}

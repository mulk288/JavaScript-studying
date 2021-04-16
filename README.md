# JavaScript-studying

     <style>
        .Js{
           font-weight: bold;
           color: red;
        }
        #first{
           color: green;
        }
        span{
           color: blue;
        }
      </style>
   </head>
  <span id="first" class="Js">JavaScript</span> // <--1
  <span class="Js">JavaScript</span>            // <--2 
  <span>JavaScript</span>                       // <--3
  
  선택자의 적용순서 Id>Class>Span.
  
1 의 경우 "JavaScript" 의 색상은 Green.

2 의 경우 "JavaScript" 의 색상은 Red

3 의 경우 "JavaScript" 의 색상은 Blue

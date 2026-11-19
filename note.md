# =================================================== after every session
git add .
git commit -m "What I did ...." 
git push
# =================================================== shortcuts and emmmet
!                    html main structer
crtl + s             save
crtl + z             undo
crtl + y             redo change
crtl + /             add and delete line comment 
crtl + d             select the match next word
crtl + p             quick file openning
crtl + shift + p     command palette
crtl + shift + k     delete a complete line 
crtl + ``            open and close treminal
alt + shift +⬇️      copy a line to down
alt + shift + f      farmat the code
alt + ⬇️ / ⬆️       move the line down and up

p*5                  create 5 paragraphes
ul>li*3              create  unorderd list has 3 items
div.comtainer        create a div with a class named container
button.btn           create a botton a class named btn
header+main+footer   create the 3 elements


# chrome
ctrl + shift + i    open developer tools (devtools)
ctrl + shift + m    toggle device toolbar (mobile responsive mode)
# =================================================== css
# -----selector
*{} global selector
element-selector{------ }
.class-selector{------ }
#id-selector{------ } 
# -----css properties
color           لون الخط
background-color لون الخلفية
font-size       حجم الخط
font-weight     سمك الخط
text-align      مجاذاة النص
margin          المسافة الخارجية
padding         المسافة الداخلية
border          الاطار
border-radius   تدوير الزوايا
width           العرض
height          الارتفاع
# -----css shortcuts and emmet
margin :10px                  m10 
padding :20px                 p20
width :100px                  w100
height :100px                 h100
display :flex                 df
justify-content :center       gcc
align-items :center           aic
# -----css flex
parent{
    display:flex;
    flex-direction:row/column;
    justify-content:flex-start/center/flex-end/space-between/space-around/space-evenly;
    align-items:flex-start/center/flex-end/stretch =(تمديد العناصر);  //whene flex-direction:row;
    gap:20px;                space between elements
}
# -----css responsive
2 ways 
Desktop first
mobile first : the modern way start width mobile design and go to desktop next
ex:
h1:{
    font-size:30px;
}
@media (min-width:768px){
    h1{
        font-size:40px;
    }
}

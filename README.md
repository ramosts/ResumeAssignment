Following is CSS
img{
    width: 300px;
}

body{
    background-color: lightgray;
    font-size: 16px;
}

/* About/Profile */
header{
    background:palevioletred;
    font-family:Georgia, 'Times New Roman', Times, serif;
}

h1, h2 ,h3{
    color:purple;
    transition: 0.5s;
}
h1:hover{
    text-shadow: 0 1px 0 #ccc, 0 2px 0 #ccc,
    0 3px 0 #ccc, 0 4px 0 #ccc,
    0 5px 0 #ccc, 0 6px 0 #ccc,
    0 7px rgba(0, 0, 0, 0.5);
}
h2:hover{
    text-shadow: 0 1px 0 #ccc, 0 2px 0 #ccc,
    0 3px 0 #ccc, 0 4px 0 #ccc,
    0 5px 0 #ccc, 0 6px 0 #ccc,
    0 7px rgba(0, 0, 0, 0.5);
}
h3:hover{
    text-shadow: 0 1px 0 #ccc, 0 2px 0 #ccc,
    0 3px 0 #ccc, 0 4px 0 #ccc,
    0 5px 0 #ccc, 0 6px 0 #ccc,
    0 7px rgba(0, 0, 0, 0.5);
}

/*Would like to add a border around each section*/

/*class="featured"*/
.featured{
    border-style: groove;
    border-color: palevioletred;
}
/*class="work"*/
.work{
    border-style: groove;
    border-color: palevioletred;
}
/*class="Education"*/
.Education{
    border-style: groove;
    border-color: palevioletred;
}
/*class="end"*/
.end{
    background: palevioletred;
}

/*Styles for highlighted links*/
a{
    color:purple;
    font-size: 16px;
}
a:visited{
    color: darkmagenta;
}
a:hover{
    color:darkviolet;
}


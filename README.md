/* ===== Page Background ===== */

body{
    background-image: url("background.jpg"); /* replace with your image */
    background-repeat: no-repeat;
    background-size: cover;
    background-color: #f0f4f8;

    font-family: Arial, sans-serif;
    color: #333;
}

/* ===== Container Layout ===== */

#container{
    display: grid;

    grid-template-areas:
        "hd hd hd"
        "lnav bd rnav"
        "ft ft ft";

    grid-gap: 10px;
    padding: 10px;
}


/* ===== Header (Name & Contact) ===== */

#hd{
    grid-area: hd;
    padding: 50px;
    background-color: #dbe9f4;
    opacity: 0.8;
    text-align: center;
}

#hd img{
    margin-top: 10px;
}


/* ===== Left Navigation ===== */

#lnav{
    grid-area: lnav;
    padding: 10px;
    background-color: #cce0ff;
    opacity: 0.8;
}

#lnav ul{
    list-style-type: none;
    padding: 0;
}


/* ===== Right Navigation (Table of Contents) ===== */

#rnav{
    grid-area: rnav;
    padding: 10px;
    background-color: #cce0ff;
    opacity: 0.8;
}

#rnav ul{
    list-style-type: none;
    padding: 0;
}


/* ===== Main Body (Resume Content) ===== */

#bd{
    grid-area: bd;
    padding: 10px;
    background-color: white;
    opacity: 0.8;
}

table{
    border-collapse: collapse;
    width: 100%;
}

table, th, td{
    border: 1px solid black;
    padding: 8px;
}

th{
    background-color: #cce0ff;
}


/* ===== Footer ===== */

#ft{
    grid-area: ft;
    padding: 10px;
    background-color: #dbe9f4;
    opacity: 0.8;
    text-align: center;
}


/* ===== Hyperlink Styling ===== */

a{
    text-decoration: underline;
    color: #003366;
    font-size: 16px;
}

a:hover{
    font-size: 18px;
    color: #003366;
}

a:visited{
    color: #800000;
    font-size: 16px;
}


/* ===== Horizontal List for Footer ===== */

.hList{
    list-style-type: none;
    text-align: center;
    margin: 0;
    padding: 0;
}

.hList li{
    display: inline;
    margin: 0 10px;
}

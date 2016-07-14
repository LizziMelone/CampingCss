body, header, nav, div, p, li {
    margin: 0;
}



header {
    background-color: #ff9966;
    color: white;
    padding: 20px;
    font-size: 1.2em;
    max-width: inherit;
    text-align: center;
}


/* Navigation Styles */
nav {
    width: 100%;
    float: left;
    background-color:#ffcc99;
    margin-bottom: 20px;
    padding: 20px 0;
}

nav ul {
    margin: 0;
    padding: 0;
}

nav li {
    list-style: none;
    color: white;
    margin-left: 25px;
    float: left;
    font-size: 1.2em;
}

nav li a { 
    color: white;    
    text-decoration: none;
}

nav li a:hover {
    text-decoration: underline;
}

/* Content */
#main-content {
    display: block;
    clear: both;
    width: 85%;
    margin: 20px auto;        
    min-height: 450px;
    color: white;
    background-color: #ffcccc;
    border-radius: 10px;
    text-align: center;
}


.center {
    text-align: center;
}


/* Form Styles */
form {
    padding: 10px;    
}

form div {
    margin: 15px auto;
    max-width: 800px;    
}

form div label {
    font-size: 1.1em;
    width: 300px;
    display: inline-block;
}

div input[type=text], input[type=password], select {
    height: 25px;
    font-size: 1.1em;
    width: 300px;   
    float: right;
}

input[type=radio] {
    padding-right: 20px;
}

form div button {
    padding: 5px;
    background-color: white;
    font-size: 1.1em;
    float: right;
}


/* Table Styles */
table {
    margin: 20px auto;
}

table.shopping-cart {
    border-spacing: unset;    
}

table.shopping-cart tr, table.shopping-cart td {
    padding: 10px;
}

table.shopping-cart td {
    width: 200px;
    border: 1px solid;    
}

/*Footer*/
footer{
    background-color: #ffcc99;
    color: white;
    padding: 20px;
    font-size: 1.2em;
    text-align: center;
}

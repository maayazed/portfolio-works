/*general selectors*/
* {
    margin: 0;
}

body {
   background-color:lightgoldenrodyellow;
}

/*header selectors*/
header {
   background-color:azure; 
   width: 100%;
   border-bottom: 10px solid coral;
   position: fixed;
}

header section {
    height: 90px;
    display: inline-flex;
    justify-content: flex-end;
    align-items: center;
    width: 100%;
}

header section span {
    font-weight: bolder;
    color:gray;
    position: static;
}

nav ul, li { 
    display: flex;
    font-weight: bold;
    margin-right: 1vmax;
}

/*main selectors*/

main {
   padding: 100px 0;
}

/*redo refer to Home block*/
main h1 {
    padding-top: 2vmax;
    padding-bottom: 1vmax;
    margin-left: 5vmax;
    margin-right: 5vmax;
    border-bottom: 10px solid rgba(255, 144, 131, 0.849);
    border-top: 10px solid rgba(255, 144, 131, 0.849);
    background-color:rgb(255, 228, 225);
}

main section {
    background-color:peachpuff;
}

main section p {
    margin-top: 3vmax;
    padding-bottom: 10px;
    border-bottom: 5px solid rgb(189, 154, 124);
}

section article {
    background-color: salmon;
    margin-top: 15px;
    padding: 2vmax;
    border-bottom: 5px solid rgb(119, 60, 54);
}

section figure {
    margin: 0 auto;
    width: 100px;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: blue;
    padding: 20px;
    color: white;
    border: 5px solid rgb(0, 0, 200);
}

form {
    padding-top: 10px;
    display: inline-flex;
}

form button {
    margin: auto 0;
}

form ul li {
    margin-bottom: 10px;
}

/*footer selectors*/
footer {
    background-color:azure; 
    position: sticky;
    bottom: 0;
}

/*class selectors*/

.text-center {
    text-align: center;
}

.text-right {
    text-align: right;
}

.text-left {
    text-align: left;
}

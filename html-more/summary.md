## audio tag
<audio controls src = "..."></audio>

- 'controls' na dile audio port show hoy nah and controls or show hoy nah


## video tag
<video src = "..."></video>

- 'controls' na dile video with controls visible hobe nah. just video thumbail show hobe with space

- or, we can use autoplay="autoplay;" attribute to autoplay one time

    #### another way:
    - <video controls>
        <source src="">
        <!-- we can use mane source -->
    </video>


## youtube video embed
- youtube video te giye share option a click korbo. then embed option theke link copy korbo. R kono tag charai paste korbo, html file a.



# basic structure
<body>
    <header>...</header>
    <main> ... </main>
    <footer> ... </footer>
</body>


# Form
<form>
    <label for="same">Label
        <input type="" name="" id="same">
    </label>
</form>


- label er jaygay amra <fieldset> use korte pari
    - <fieldset>
        <lagend>box er line er likha ta</lagend>
    </fieldset>
<br>

- radio-type input a ekbar select korle r unselect kora jay nah
- kintu checkbox-type input er jonno ucselect kora jay
- jodi ekadhik label er radio-type input er same name hoy, then ekta select korle onnogula auto unselected hoye jabe
- kintu checkbox-type input er khetre same name a o onekgula select kora jay.
- input:reset a click korlei puro form reset hoye jabe
- input:submit a click korlei puro form reset hoye jabe
    - aigular value te ja dibo, button er nam tai hobe



# Table
<table>
    <caption>...</caption>
    <thead>
        <tr>
            <th>...</th>
            <th>...</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>...</td>
            <td>...</td>
        </tr>
    </tbody>
    <tfoot>
        <td colspan=""></td> 
    <tfoot>
</table>

- th: table heading
- td: table data
- td: table row
- tr*4>td*4 ==> then 'tab' click korlei porer td te jabe



# Nav
- navigate: ek page theke onno page a jawa
- default: anchor tag a
    * blue: active but not clicked yet
    * purple: active and clicked also
    * red: when we clicked
    - also we can customized the colors

- nav li:hover{
    - hover korar por ja ja customization korte chai
}
- li er list-style a jeye amra none, circle, etc add korte pari


## nested menu
- nav li .className{
    display: none;
}
- className of nested <ul>
<br>

- nav li:hover .className{
    display: block;
}
- nav er moddhe thaka li a hover korle, j li te className nam a ul er class thakbe oi khetre ul display hobe
- li a hover korbo, karon className ul already display te nai.

-     position: absolute;
    => means just className wala <ul> ta li theke upore uthe jabe. tai <ul> tar mother li te include thakbe nah

### css cheat-sheet
1. nav > ul > li{

}
    ==> aita bojhay 'nav' er moddhe thaka 'ul' er moddhe thata shob 'li' selected
- '>' use korar khetre imidiate parent and child er moddhe boshate hobe
- '>' means left er imidiate chele right
<br>

2. nav a {

}
    ==> 'nav' er moddhe thaka shob 'a' selected

- width change korle picture er ratio change hoy nah. so oi onujayi height o addjust hoye jay
<br>


## emmet

1. ul>li*4>a ==> then just tab click kore kore switch korbo

2. main>article.blog*3>h3{My Blog}+p>lorem100

- '.' => used for className
- '#' => used for idName
- '>' => used for child
- '+' => used for siblings
- '{..}' => we can give also content inside the tags
- '^' => used for uncle

#### exection
- '>' ==> imidiate first child er jonno boshe, shob child k select korbe nah.
- '{..}' ==> er moddhe flat text thake
- '{.. $} ==> ekhane '$' er value 1 theke start hoy and then update hote thake
- 'lorem' k child hishebe use kora hoy karon aita kono flat value nah, borong aita ekta child
- 'lorem' er por '+' dile eita lorem er siblings hoye jay, jodi lorem er parent tag <p> er siblings chai tahole '+' na diye '^' dibo


## display
- flex: shob ek line a chole asha
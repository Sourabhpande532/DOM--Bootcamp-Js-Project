# DOM--Bootcamp-Js-Project

<!-- @format -->

# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Assets/Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Code

    document.querySelector(".crayons-subtitle-2").innerHTML = "Saurabh prashant pande"

    document.querySelector(".crayons-card p").innerHTML = "Passion to become Full Stack Web developer"

### Output

![Output](./Images/1.png)

2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Assets/Picture_3.png)

### Fetch all the product name and store in an array

###
```
const listNsmr = document.querySelectorAll(".as-imagegrid-item");
//console.log(listNsmr)
const storeValHouse =  [];
listNsmr.forEach((item)=>{
let x = item.innerText.replace("\nSupport", "");
storeValHouse.push(x);
})
console.log(storeValHouse)
```
### Output

![](./Images/Screenshot%202022-09-25%20094142.png)

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Assets/Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Code

```
const targetMain = document.querySelector(".accordion-homepage");
const addSection = document.createElement("section");
addSection.className = "parent";
const addTag = document.createElement("h3");
addTag.textContent = "My New FAQ"
targetMain.appendChild(addSection)
addSection.appendChild(addTag);
```

### Output

![Output](./Images/2.png)

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Assets/Pic6.png)

### Tasks

      Change the contact number

### Code

     document.querySelector(".customer-support a").innerText = '+09665083954'

### Output

![Output](./Images/Screenshot%202022-09-21%20101532.png)

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Assets/Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

### Code

```
document.querySelector(".diwali-deals-product-sale-btn").innerText="Check Out";
```

### Output

![Output](./Images/5.png)

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Assets/Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### Code

      const find = document.querySelector(".searchinput___19uW0")
      find.addEventListener("mouseover", changbg)
      function changbg(){
      find.style.backgroundColor = "red"
      };

      /*or*/
                 document.querySelector(".searchinput___zXLAR").addEventListener("mouseover", function() {
     document.querySelector(".searchinput___zXLAR").style.   backgroundColor = "red";
     });

### Output

![Output](./Images/6.png)

7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Assets/Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### Output

![Output](./Assets/Pic13.png)

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Assets/Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Code

    let x = document.querySelectorAll('.z4hgWe a')
    x.forEach((a,index)=>{
    index % 2 == 0 && a.remove()
    })

### Output

![Output](./Assets/Pic15.png)

9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Assets/Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

### Code

```
document.querySelector(".text-align-center").style.fontFamily="monospace";
document.querySelector(".text-align-center").style.fontFamily="orange";
```

### Output

![Output](./Images/Screenshot%202022-12-09%20184958.png)

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style

### Sample Image

![Sample One](./Assets/Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Code

      document.querySelector(".btn-cta-big .login-btn-text ").addEventListener("mouseover",function(){

      document.querySelector(".btn-cta-big .login-btn-text ").style.backgroundColor="red"

});

### Output

![Output](./Assets/Pic19.png)

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Assets/Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Code

```
document.querySelector(".gtag .icon").style.backgroundImage="url('https://ineuron.ai/images/ineuron-logo.png')"
```

### Output

![Output](./Images/Screenshot%202022-12-09%20190849.png)

12. Webiste Name: [Github](https://github.com/new)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Assets/Pic22.png)

### Tasks

     change the background colour of the button to blue.

### Code

    document.querySelector(".Subhead mb-3 , h1").style.backgroundColor = "blue"

    document.querySelector(".Subhead mb-3 , h1").style.fontFamily = "roman"

'roman'

### Output

![Output](./Images/Screenshot%202022-09-22%20162739.png)

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Assets/Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Code

     document.querySelector("h1 span").innerHTML = "JSBOOTCAMP"

### Output

![Output](./Assets/Pic25.png)

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Assets/Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Code

     document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "80px"

### Output

![Output](./Assets/Pic27.png)

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Assets/Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### code

     document.querySelector("h1 span").style.textAlign = "right";

### Output

![Output](./Assets/Pic29.png)

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Assets/Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Code

    document.querySelector("section-label_label__IXpQ5 ,h4").innerHTML = "Start with Scratch"

### Output

![Output](./Images/Screenshot%202022-09-22%20160635.png)

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Assets/Pic33.png)

### Tasks

     change the button text To current Date.

### Code

```
document.querySelector(".btn-container").innerHTML=new Date()
```

### Output

![Output](./Assets/Pic32.png)

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Assets/Pic34.png)

### Tasks

    change the background colour blue to orange

### Code

```
document.querySelector(".p-f03-footer-container .p-footer").style.backgroundColor="orange"
```

### Output

![Output](./Assets/Pic35.png)

19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Assets/Pic36.png)

### Tasks

    extract the canon logo

### Code

```
     document.querySelector(".logo").src
```

### Output

![Output](./Assets/Pic37.png)

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./Assets/Pic38.png)

### Tasks

      Change the description colour black to orange

### Code

     document.querySelector(".section-box h3").style.color = "orange"

### Output

![Output](./Assets/Pic39.png)

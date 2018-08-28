<!-- Put the name of the project after the # -->
<!-- the # means h1  -->
#Bootstrap Portfolio

<!-- Put a description of what the project is -->
Portfolio website created using bootstrap css

# Link to deployed site
<!-- make a link to the deployed site --> 
<!-- [What the user will see](the link to the deployed site) -->

[Website](https://atton88.github.io/Bootstrap-Portfolio/)
[GitHub Profile](https://github.com/atton88)

# Images
<!-- take a picture of the image and add it into the readme  -->
<!-- ![image title](path or link to image) -->
![About Me](assets\images\1.png)
![Portfolio](assets\images\2.PNG)
![Contact](assets\images\3.PNG)

# technology used
<!-- make a list of technology used -->
<!-- what you used for this web app, like html css -->

- HTML
- CSS
- Bootstrap

<!-- 
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item. 
-->


# code snippets
<!-- put snippets of code inside ``` ``` so it will look like code -->
<!-- if you want to put blockquotes use a > -->
NAV BAR
```
<nav class="navbar navbar-expand-lg navbar-light bgwhite headerfix">
    <h1 class="headertext textwhite bgteal">Andrew Ton</h1>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
        <div class="navbar-nav">
        <a class="nav-item nav-link active" href="index.html">About Me</a>
        <a class="nav-item nav-link" href="portfolio.html">Portfolio</a>
        <a class="nav-item nav-link" href="contact.html">Contact</a>
        </div>
    </div>
</nav>
```
Portfolio Grid
```
<div class="row">
<div class="col-md-6">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="assets/images/p1.jpg" alt"pic 1">
        <div class="card-body">
            <p class="card-text">Hangman</p>
        </div>
    </div>
</div>
<div class="col-md-6">
    <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="assets/images/p2.jpg" alt="pic 2">
            <div class="card-body">
                <p class="card-text">RPG Game</p>
            </div>
        </div>
</div>
```
Form and Button
```
<form>
    <div class="form-group">
        <label for="exampleFormControlInput1">Name:</label>
        <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="John Smith">
    </div>

    <div class="form-group">
            <label for="exampleFormControlInput1">Email:</label>
            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
        </div>


    <div class="form-group">
        <label for="exampleFormControlTextarea1">Message:</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
    </div>
</form>
<button class="btn btn-primary textwhite bgteal" type="Submit">Submit</button>

```
# Learning points
<!-- Learning points where you would write what you thought was helpful -->
Learned how to incorporate bootstrap CSS and manipulate them. Learned different components in bootstrap. Learned how to integrate and supplement bootstrap with own CSS.

# Author 
<!-- make a link to the deployed site and have your name as the link -->
[Andrew Ton GitHub](https://github.com/atton88)
# License
Standard MIT License
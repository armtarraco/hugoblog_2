+++
categories = ["css"]
date = "2018-04-27T09:19:50+02:00"
tags = ["display"]
title = "How `display:flex` or `display: grid` redefines what `margin: auto` does on top & bottom, allowing for vertical centering"

+++
<!--more-->

Source: Jen Simmons (@jensimmons) twit  [https://t.co/tCEWDvuCbZ](https://t.co/tCEWDvuCbZ)

    <header>
      <h1>Hello world</h1>
    </header>
    
    
    header {
      min-height: 70vh;
      background: #FFD4DE;
    /* Try out any of the next three lines of code to see how they differ. Or don't differ.*/   
      display: block;
      display: flex;
      display: grid;
    }
    h1 {
      margin: auto;
    }
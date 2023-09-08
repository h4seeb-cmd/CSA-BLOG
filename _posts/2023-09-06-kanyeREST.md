---
toc: true
comments: false
layout: post
title: KanyeREST
description: "george bush doesnt care about black people"
type: hacks
courses: { compsci: {week: 3} }
---
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
</head>

<h1 id="ye"></h1>

https://api.kanye.rest

<script>
function getQuote(){
    $(document).ready(function(){
        const grab = $.get("https://api.kanye.rest", function(result){
            const quote = result.quote;
            document.getElementById("ye").innerHTML=quote
        });
        });
    }
const interval = 5000;
getQuote();
const intervalId = setInterval(getQuote, interval);

</script>
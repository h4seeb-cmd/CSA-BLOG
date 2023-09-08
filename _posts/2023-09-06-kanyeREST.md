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
<button>KANYE REST</button>
<h1 id="ye"></h1>

https://api.kanye.rest

<script>
$(document).ready(function(){
    $("button").click(function(){
        $.get("https://api.kanye.rest", function(result){
            console.log(result);
            $("#ye").text(result);
            });
        })
    });


</script>
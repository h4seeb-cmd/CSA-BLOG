---
toc: true
comments: false
layout: post
title: KanyeREST
description: "kanyeRest"
type: hacks
courses: { compsci: {week: 3} }
---
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
</head>
<button id="a">KANYE REST</button>
<h1 id="ye"></h1>

https://api.kanye.rest

<script>
function getQuote(){
    $(document).ready(function(){
        const grab = $.get("https://api.kanye.rest", function(result){
            const quote = result.quote;
            document.getElementById("ye").innerHTML=quote;
            var msg = new SpeechSynthesisUtterance();
            msg.text=quote;
            msg.rate = 1.75;
            window.speechSynthesis.speak(msg);
        });
        });
    }

// TTS SYNTHESIS TESTER
//const button = document.getElementById("a");
//function testTTS(){
//    if ('speechSynthesis' in window) {
 //       console.log("monke");
//       }else{
         // Speech Synthesis Not Supported 😣
//         alert("Sorry, your browser doesn't support text to speech!");
  //     }
//}
//button.addEventListener("click", testTTS);
const interval = 10000;
getQuote();
const intervalId = setInterval(getQuote, interval);

</script>
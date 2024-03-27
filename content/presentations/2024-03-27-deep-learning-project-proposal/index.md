---
title: Deep Learning Project Proposal
author: 'Caleb Fox'
date: '2024-03-27'
slug: []
categories: []
tags: []
draft: no
---


<div id="presentation-container">
    <iframe id="presentation-iframe" src="deep_learning_final_proposal.html" frameborder="0"></iframe>
    <button onclick="toggleFullscreen()" id="fullscreen-button">Fullscreen</button>
</div>

<style>
#presentation-container {
    position: relative;
}
#presentation-iframe {
    width: 1000px;
    height: 600px; /* Adjust this height as needed */
    border: none;
}
#fullscreen-button {
    background-color: rgb(var(--color-primary-800)); /* Primary color */
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
}
#fullscreen-button:hover {
    background-color: rgb(var(--color-secondary-800)); /* Secondary color */
}
</style>

<script>
function toggleFullscreen() {
    var iframe = document.getElementById('presentation-iframe');
    if (iframe.requestFullscreen) {
        iframe.requestFullscreen();
    } else if (iframe.mozRequestFullScreen) { /* Firefox */
        iframe.mozRequestFullScreen();
    } else if (iframe.webkitRequestFullscreen) { /* Chrome, Safari & Opera */
        iframe.webkitRequestFullscreen();
    } else if (iframe.msRequestFullscreen) { /* IE/Edge */
        iframe.msRequestFullscreen();
    }
}
</script>



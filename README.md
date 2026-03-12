<!-- Nothing weird to see here -->
<svg width="400" height="120" viewBox="0 0 400 120"
xmlns="http://www.w3.org/2000/svg">

<style>
.bar {
  fill: #1DB954;
  animation: bounce 1s infinite ease-in-out;
}

.bar:nth-child(1){animation-delay:0s}
.bar:nth-child(2){animation-delay:0.1s}
.bar:nth-child(3){animation-delay:0.2s}
.bar:nth-child(4){animation-delay:0.3s}
.bar:nth-child(5){animation-delay:0.4s}

@keyframes bounce {
  0%,100% { height:10px }
  50% { height:30px }
}

.title {
  font: bold 16px sans-serif;
  fill: white;
}

.artist {
  font: 14px sans-serif;
  fill: #b3b3b3;
}
</style>

<rect width="100%" height="100%" fill="#121212" rx="12"/>

<!-- album cover -->
<image
x="15"
y="20"
width="80"
height="80"
href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAA..."
/>

<text x="110" y="45" class="title">Like a Rolling Stone</text>
<text x="110" y="70" class="artist">Bob Dylan</text>

<g transform="translate(110,85)">
<rect class="bar" x="0" width="6" height="10"/>
<rect class="bar" x="10" width="6" height="10"/>
<rect class="bar" x="20" width="6" height="10"/>
<rect class="bar" x="30" width="6" height="10"/>
<rect class="bar" x="40" width="6" height="10"/>
</g>

</svg>

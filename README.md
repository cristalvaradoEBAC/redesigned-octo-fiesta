# redesigned-octo-fiesta
CARD GAME - For trainings
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Card Shuffler</title>
<link rel="stylesheet" href="styles.css" />
</head>
<body>
<main class="wrap">
<h1>Digital Card Shuffler</h1>

<section class="controls">
<label class="upload-btn">
Choose images
<input id="file-input" type="file" accept="image/*" multiple />
</label>

<div id="drop-zone" class="drop-zone" tabindex="0" aria-label="Drop images here or press Enter to pick files">
Drag & drop images here
</div>

<div class="buttons">
<button id="shuffle-btn">Shuffle</button>
<button id="reset-btn">Reset Order</button>
<button id="clear-btn">Clear All</button>
<button id="save-btn">Save to Local</button>
</div>
</section>

<section class="gallery" id="cards-container" aria-live="polite">
<!-- cards rendered here -->
</section>

<footer class="notes">
<p>Click a card to flip it. Files are stored in browser localStorage when you click "Save to Local".</p>
</footer>
</main>

<script src="script.js"></script>
</body>
</html>

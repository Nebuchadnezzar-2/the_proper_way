<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Embedded Google Doc</title>
<style>
.google-doc-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 9999;
}

.google-doc-container iframe {
  width: 100%;
  height: 100%;
  border: none;
}

@media (max-width: 767px) {
  .google-doc-container {
    position: static;
    height: auto;
  }

  .google-doc-container iframe {
    height: 80vh;
  }
}
</style>
</head>
<body>

<section class="google-doc-container">
<!-- Paste your Google Doc embed code here -->
<iframe src="https://docs.google.com/document/d/e/2PACX-1vTh5SvMIwkZpjFNtH5i1Q_TCjHaJBWcEIxgCNGjUWO-QwryeX3GlbjK2APULyZXOLqyskN9wG61Ap6T/pub?embedded=true"></iframe>
</section>

</body>
</html>

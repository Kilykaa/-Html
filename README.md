# -Html

<div class="static-banner">
  <img src="https://files.catbox.moe/1v5bu1.png" alt="Static Banner">
</div>

<style>
  .static-banner {
    width: 400px;         /* задаёшь нужную ширину */
    margin: 40px auto;    /* по центру с отступами */
    border-radius: 12px;
    overflow: hidden;
    box-shadow:
      0 0 10px #ff0000aa,
      0 0 20px #ff000055,
      0 0 30px #ff000033;
  }

  .static-banner img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 12px;
  }
</style>

================================================================================================

<a href="https://example.com" target="_blank" class="promo-banner">
  <img src="https://files.catbox.moe/1v5bu1.png" alt="Promo Banner">
</a>

<style>
  .promo-banner {
    display: block;
    margin: 0 auto 40px auto;
    width: 80%;
    max-width: 600px;
    border: 3px solid #5a0000;
    box-shadow: 0 0 20px #ff000044, 0 0 60px #8b000088;
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.4s;
  }

  .promo-banner img {
    width: 100%;
    height: auto;
    display: block;
    filter: hue-rotate(-10deg) saturate(1.5) brightness(0.9);
  }

  .promo-banner:hover {
    transform: scale(1.02);
    box-shadow: 0 0 30px #ff3333, 0 0 90px #ff0000;
  }
</style>

# ladakeebella.com
Brilla con confianza y sonríe a tu belleza interior
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Tienda Gratis</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Mi Tienda de Joyas</h1>
    <p>Brilla con confianza y sonríele a tu belleza interior</p>
  </header>

  <main>
    <div class="producto">
      <img src="https://via.placeholder.com/200" alt="Collar de ejemplo">
      <h2>Collar Elegante</h2>
      <p>Precio: $20</p>
      <!-- Botón PayPal -->
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
        <input type="hidden" name="cmd" value="_xclick">
        <input type="hidden" name="business" value="TU_EMAIL_PAYPAL">
        <input type="hidden" name="item_name" value="Collar Elegante">
        <input type="hidden" name="amount" value="20.00">
        <input type="hidden" name="currency_code" value="USD">
        <input type="submit" value="Comprar con PayPal">
      </form>
    </div>

    <div class="producto">
      <img src="https://via.placeholder.com/200" alt="Anillo de ejemplo">
      <h2>Anillo Brillante</h2>
      <p>Precio: $15</p>
      <!-- Botón PayPal -->
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
        <input type="hidden" name="cmd" value="_xclick">
        <input type="hidden" name="business" value="TU_EMAIL_PAYPAL">
        <input type="hidden" name="item_name" value="Anillo Brillante">
        <input type="hidden" name="amount" value="15.00">
        <input type="hidden" name="currency_code" value="USD">
        <input type="submit" value="Comprar con PayPal">
      </form>
    </div>
  </main>

  <footer>
    <p>© 2025 Mi Tienda Gratis</p>
  </footer>
</body>
</html>

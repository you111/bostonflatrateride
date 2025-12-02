# bostonflatrateride
<!DOCTYPE html>	
<html lang="en">	
<head>	
  <meta charset="UTF-8">	
  <meta name="viewport" content="width=device-width, initial-scale=1.0">	
  <title>Boston Flat Rate Ride | Fixed-Price Airport & City Transport</title>	
  <style>	
    :root { --primary: #0047ab; --accent: #00c896; }	
    body { font-family: system-ui, -apple-system, sans-serif; margin: 0; line-height: 1.6; }	
    header { background: var(--primary); color: white; padding: 1rem 0; position: sticky; top: 0; z-index: 100; }	
    nav { max-width: 1100px; margin: auto; display: flex; justify-content: space-between; align-items: center; padding: 0 20px; }	
    nav h1 { margin: 0; font-size: 1.4rem; }	
    .hero { background: linear-gradient(rgba(0,71,171,0.9), rgba(0,71,171,0.9)), url('https://images.unsplash.com/photo-1558618666-fcd25c85cd64?w=1200') center/cover; color: white; text-align: center; padding: 120px 20px; }	
    .hero h2 { font-size: 2.2rem; margin: 0 0 10px; }	
    .hero p { font-size: 1.2rem; margin: 0 0 25px; }	
    .phone-btn { background: var(--accent); color: white; padding: 16px 32px; text-decoration: none; border-radius: 8px; font-size: 1.3rem; font-weight: bold; display: inline-block; }	
    .rates { background: #f8f9fa; padding: 50px 20px; text-align: center; }	
    .rates-grid { max-width: 1100px; margin: 30px auto 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 20px; }	
    .rate-card { background: white; padding: 25px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }	
    .rate-card .price { font-size: 2rem; color: var(--primary); font-weight: bold; }	
    .rate-card .dest { color: #666; margin-top: 8px; }	
    .services { max-width: 1100px; margin: 60px auto; padding: 0 20px; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; }	
    .service-card { padding: 30px; border-left: 4px solid var(--accent); background: #f8f9fa; }	
    .service-card h3 { margin-top: 0; color: var(--primary); }	
    .booking { background: white; padding: 60px 20px; text-align: center; }	
    .booking-container { max-width: 700px; margin: auto; background: #f8f9fa; padding: 30px; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }	
    .booking h2 { color: var(--primary); margin-bottom: 10px; }	
    footer { background: var(--primary); color: white; text-align: center; padding: 30px 20px; margin-top: 60px; }	
    @media(max-width: 600px) { .hero h2 { font-size: 1.8rem; } .phone-btn { font-size: 1.1rem; } }	
  </style>	
</head>	
<body>	
  <header>	
    <nav>	
      <h1>Boston Flat Rate Ride</h1>	
      <div>	
        <a href="#rates" style="color:white; margin-left: 20px;">Rates</a>	
        <a href="#services" style="color:white; margin-left: 20px;">Services</a>	
        <a href="#booking" style="color:white; margin-left: 20px;">Book</a>	
        <a href="tel:6173311654" style="color:white; margin-left: 20px;">Call</a>	
      </div>	
    </nav>	
  </header>	
  	
  <section class="hero">	
    <h2>No Surprises. Just Flat Rates.</h2>	
    <p>Logan Airport • Seaport • Cambridge • Back Bay</p>	
    <a href="tel:6173311654" class="phone-btn">📞 (617) 331-1654</a>	
  </section>	
  	
  <section id="rates" class="rates">	
    <h2 style="color: var(--primary); margin-bottom: 10px;">Popular Flat Rates</h2>	
    <div class="rates-grid">	
      <div class="rate-card">	
        <div class="price">$35</div>	
        <div class="dest">Logan ↔ Back Bay</div>	
      </div>	
      <div class="rate-card">	
        <div class="price">$45</div>	
        <div class="dest">Logan ↔ Cambridge</div>	
      </div>	
      <div class="rate-card">	
        <div class="price">$55</div>	
        <div class="dest">Logan ↔ Newton</div>	
      </div>	
      <div class="rate-card">	
        <div class="price">$28</div>	
        <div class="dest">Seaport ↔ Downtown</div>	
      </div>	
    </div>	
    <p style="margin-top: 30px; color: #666;">All rates include tolls & fees. No surge pricing, ever.</p>	
  </section>	
  	
  <section id="services" class="services">	
    <div class="service-card">	
      <h3>📍 Airport Transfers</h3>	
      <p>On-time pickups at Logan. Flight tracking included. 24/7 dispatch.</p>	
    </div>	
    <div class="service-card">	
      <h3>🏢 Corporate Accounts</h3>	
      <p>Monthly billing, dedicated drivers, executive vehicles available.</p>	
    </div>	
    <div class="service-card">	
      <h3>⚡ Instant Booking</h3>	
      <p>Call, text, or use the form below. Real driver, real service.</p>	
    </div>	
  </section>	
	
  <!-- GOOGLE FORM EMBED SECTION -->	
  <section id="booking" class="booking">	
    <div class="booking-container">	
      <h2>Book Your Ride</h2>	
      <p style="color: #666; margin-bottom: 25px;">We’ll confirm within 5 minutes during business hours.</p>	
      <!-- === PASTE YOUR GOOGLE FORM IFRAME CODE BELOW THIS LINE === -->	
      <iframe src="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?embedded=true" width="100%" height="600" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>	
    </div>	
  </section>	
  	
  <footer>	
    <p><strong>Boston Flat Rate Ride</strong></p>	
    <p>📞 (617) 331-1654 | 📧 Abadir982@outlook.com</p>	
    <p>DPU License #123456 | Fully insured</p>	
    <p style="margin-top: 20px;">&copy; 2025 Boston Flat Rate Ride</p>	
  </footer>	
</body>	
</html>	

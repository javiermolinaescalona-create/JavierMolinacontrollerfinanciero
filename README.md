<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Controller Financiero | Javier Molina</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Inter', sans-serif;
      color: #1a1a1a;
      background-color: #f4f6f8;
    }

    :root {
      --azul-petroleo: #0A3D62;
      --azul-corporativo: #0d6efd;
      --gris-profesional: #f4f6f8;
      --gris-oscuro: #1a1a1a;
      --blanco: #ffffff;
    }

    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeIn 1s ease forwards;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .navbar {
      padding: 18px 0;
      background: var(--blanco) !important;
      border-bottom: 1px solid #e5e7eb;
    }

    .navbar-brand {
      font-weight: 600;
      color: var(--gris-oscuro) !important;
    }

    .nav-link {
      color: #333 !important;
      font-weight: 500;
      margin-left: 20px;
    }

    .nav-link:hover {
      color: var(--azul-corporativo) !important;
    }

    .hero {
      background: linear-gradient(rgba(10, 10, 10, 0.65), rgba(10, 10, 10, 0.65)),
        url('https://picsum.photos/1600/800?blur=4');
      background-size: cover;
      background-position: center;
      padding: 160px 0;
      color: white;
    }

    .section-title {
      font-size: 2.2rem;
      font-weight: 700;
      margin-bottom: 1rem;
      color: var(--gris-oscuro);
    }

    .section-subtitle {
      font-size: 1.1rem;
      color: #555;
      max-width: 650px;
      margin: 0 auto 40px;
    }

    .service-card {
      background: var(--blanco);
      padding: 40px;
      border-radius: 12px;
      border: 1px solid #e5e7eb;
      transition: all .25s ease;
      height: 100%;
    }

    .service-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 12px 35px rgba(0, 0, 0, 0.08);
    }

    .about-img {
      border-radius: 12px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
      width: 100%;
      height: auto;
      background: #e5e7eb;
    }

    .dashboard-img {
      border-radius: 12px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
      width: 100%;
    }

    .logos-clientes img {
      max-height: 40px;
      margin: 0 20px;
      opacity: 0.85;
    }

    .testimonio-cita {
      font-size: 1.2rem;
      font-weight: 500;
      color: var(--azul-petroleo);
    }

    footer {
      background: var(--gris-oscuro);
      color: #ccc;
      padding: 40px 0;
    }

    footer a {
      color: #ccc;
      text-decoration: none;
    }

    footer a:hover {
      color: var(--azul-corporativo);
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
      <a class="navbar-brand" href="#">Javier Molina · Controller Financiero</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#valor">Valor</a></li>
          <li class="nav-item"><a class="nav-link" href="#pymes-malaga">Pymes Málaga</a></li>
          <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
          <li class="nav-item"><a class="nav-link" href="#dashboards">Dashboards</a></li>
          <li class="nav-item"><a class="nav-link" href="#testimonios">Testimonios</a></li>
          <li class="nav-item"><a class="nav-link" href="#sobre-mi">Sobre mí</a></li>
          <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header class="hero fade-in">
    <div class="container">
      <h1 class="fw-bold">Control Financiero Estratégico para Pymes que Quieren Crecer con Seguridad</h1>
      <p class="mt-3">
        Transformo tus datos en decisiones claras, anticipación y rentabilidad.<br>
        Un servicio de Controller externo pensado para pymes de Málaga que necesitan más control sin aumentar
        estructura.
      </p>
      <a href="#contacto" class="btn btn-primary btn-lg mt-4 px-5">Quiero mejorar el control de mi empresa</a>
    </div>
  </header>

  <!-- PROPUESTA DE VALOR -->
  <section id="valor" class="py-5 fade-in">
    <div class="container text-center">
      <h2 class="section-title">Propuesta de Valor</h2>
      <p class="section-subtitle">
        Ayudo a pymes y directivos a tomar decisiones con claridad, basadas en datos reales y análisis profesional.
      </p>

      <div class="row g-4 mt-4">
        <div class="col-md-4">
          <div class="service-card">
            <h5 class="fw-bold">📌 Precisión que reduce la incertidumbre</h5>
            <p>KPIs, modelos y reporting que te muestran exactamente qué está pasando en tu negocio.</p>
          </div>
        </div>

        <div class="col-md-4">
          <div class="service-card">
            <h5 class="fw-bold">📌 Visión estratégica para crecer</h5>
            <p>Análisis claro, orientado a decisiones y enfocado en rentabilidad.</p>
          </div>
        </div>

        <div class="col-md-4">
          <div class="service-card">
            <h5 class="fw-bold">📌 Control total sin contratar personal</h5>
            <p>Un Controller externo que te acompaña, te guía y te da tranquilidad.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PYMES DE MÁLAGA -->
  <section id="pymes-malaga" class="py-5 fade-in" style="background-color: #ffffff;">
    <div class="container">
      <div class="row align-items-center">

        <div class="col-md-6">
          <h2 class="section-title">Especialista en Pymes de Málaga que Quieren Profesionalizar su Gestión</h2>
          <p class="section-subtitle">
            Claridad, control y previsión para tomar decisiones con seguridad.
          </p>

          <p>
            Málaga vive un momento de crecimiento único. Muchas pymes están dando el salto hacia una gestión más
            profesional, pero siguen sin tener un control financiero sólido que les permita anticiparse, planificar y
            decidir con seguridad.
          </p>

          <p>
            Mi servicio está diseñado para empresas malagueñas que quieren:
          </p>

          <ul class="mt-3" style="line-height: 1.8;">
            <li>✔ Tener claridad sobre su rentabilidad real</li>
            <li>✔ Evitar sorpresas de tesorería</li>
            <li>✔ Planificar con previsiones fiables</li>
            <li>✔ Tomar decisiones basadas en datos</li>
            <li>✔ Profesionalizar su gestión sin contratar personal interno</li>
          </ul>

          <a href="#contacto" class="btn btn-primary btn-lg mt-4">Quiero un diagnóstico para mi pyme</a>
        </div>

        <div class="col-md-6 text-center">
          <img src="https://picsum.photos/600/400?blur=2" alt="Pymes de Málaga" class="about-img"
            style="border-radius: 12px;">
        </div>

      </div>
    </div>
  </section>

  <!-- SERVICIOS -->
  <section id="servicios" class="py-5 fade-in">
    <div class="container text-center">
      <h2 class="section-title">Servicios</h2>
      <p class="section-subtitle">Soluciones financieras con enfoque consultivo y rigor técnico.</p>

      <div class="row g-4">
        <div class="col-md-4">
          <div class="service-card">
            <h5 class="fw-bold">📊 Análisis Financiero Avanzado</h5>
            <p>Descubre qué funciona, qué no y dónde estás perdiendo dinero. Reporting ejecutivo para decisiones rápidas
              y seguras.</p>
          </div>
        </div>

        <div class="col-md-4">
          <div class="service-card">
            <h5 class="fw-bold">📈 Presupuestos & Forecast</h5>
            <p>Modelos financieros que anticipan riesgos, escenarios y necesidades futuras. Planifica con meses de
              ventaja.</p>
          </div>
        </div>

        <div class="col-md-4">
          <div class="service-card">
            <h5 class="fw-bold">💼 Control de Gestión</h5>
            <p>Procesos, dashboards y seguimiento continuo para que tu empresa funcione con precisión y sin
              improvisaciones.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- DASHBOARDS -->
  <section id="dashboards" class="py-5 fade-in">
    <div class="container text-center">
      <h2 class="section-title">Dashboards & Power BI</h2>
      <p class="section-subtitle">Visualizaciones profesionales para decisiones basadas en datos.</p>

      <div class="row g-4">
        <div class="col-md-6">
          <img src="https://picsum.photos/800/450?random=1" class="dashboard-img" alt="Mockup Dashboard 1">
        </div>
        <div class="col-md-6">
          <img src="https://picsum.photos/800/450?random=2" class="dashboard-img" alt="Mockup Dashboard 2">
        </div>
      </div>
    </div>
  </section>

  <!-- TESTIMONIOS -->
  <section id="testimonios" class="py-5 fade-in">
    <div class="container text-center">
      <h2 class="section-title">Testimonios</h2>
      <p class="section-subtitle">Lo que dicen directivos y empresas con las que he trabajado.</p>

      <div class="mb-4">
        <p class="testimonio-cita">
          “El control financiero no es un informe: es la capacidad de tomar decisiones con seguridad.”
        </p>
      </div>

      <div class="logos-clientes mb-4 d-flex justify-content-center align-items-center flex-wrap">
        <img src="elcorteingles-logo.png" alt="El Corte Inglés">
        <img src="unicaja-logo.png" alt="Unicaja">
      </div>

      <div id="carouselTestimonios" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">

          <div class="carousel-item active">
            <div class="service-card mx-auto" style="max-width: 800px;">
              <p class="fst-italic">
                “Gracias al reporting de Javier, por fin entendemos qué líneas de negocio son rentables y cuáles no.
                Ahora tomamos decisiones con datos, no con intuiciones.”
              </p>
              <h6 class="fw-bold mt-3">— Director General, Empresa Industrial de Málaga</h6>
            </div>
          </div>

          <div class="carousel-item">
            <div class="service-card mx-auto" style="max-width: 800px;">
              <p class="fst-italic">
                “Sus modelos de forecast nos han permitido anticipar tensiones de tesorería y planificar con meses de
                ventaja. Profesional, claro y muy riguroso.”
              </p>
              <h6 class="fw-bold mt-3">— CFO, Empresa de Servicios</h6>
            </div>
          </div>

          <div class="carousel-item">
            <div class="service-card mx-auto" style="max-width: 800px;">
              <p class="fst-italic">
                “El dashboard financiero que nos diseñó cambió nuestra forma de gestionar. Información clave en un
                vistazo.”
              </p>
              <h6 class="fw-bold mt-3">— CEO, Startup Tecnológica</h6>
            </div>
          </div>

        </div>

        <button class="carousel-control-prev" type="button" data-bs-target="#carouselTestimonios" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Anterior</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselTestimonios" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Siguiente</span>
        </button>
      </div>
    </div>
  </section>

  <!-- SOBRE MÍ -->
  <section id="sobre-mi" class="py-5 bg-white fade-in">
    <div class="container">
      <div class="row align-items-center">

        <div class="col-md-6">
          <h2 class="section-title">Sobre mí</h2>
          <p>
            Soy <strong>Javier Molina</strong>, Controller Financiero especializado en análisis, reporting, presupuestos
            y transformación digital.
          </p>
          <p>
            Ayudo a pymes y directivos a tener claridad, control y previsión para tomar decisiones con seguridad.
            Mi enfoque combina rigor técnico, visión estratégica y una comunicación clara, directa y orientada a
            resultados.
          </p>
        </div>

        <div class="col-md-6 text-center">
          <img src="ruta-de-tu-foto-profesional.jpg" class="about-img" alt="Foto profesional de Javier Molina">
        </div>

      </div>
    </div>
  </section>

  <!-- CONTACTO -->
  <section id="contacto" class="py-5 fade-in">
    <div class="container text-center">
      <h2 class="section-title">Contacto</h2>
      <p class="section-subtitle">
        Cuéntame qué necesita tu empresa y te prepararé un diagnóstico inicial sin compromiso.
        Te responderé en menos de 24 horas.
      </p>

      <form class="mx-auto" style="max-width: 600px;">
        <div class="mb-3">
          <input type="text" class="form-control" placeholder="Nombre completo">
        </div>
        <div class="mb-3">
          <input type="email" class="form-control" placeholder="Correo electrónico">
        </div>
        <div class="mb-3">
          <textarea class="form-control" rows="4" placeholder="Cuéntame sobre tu proyecto"></textarea>
        </div>
        <button class="btn btn-primary btn-lg w-100" type="submit">Enviar mensaje</button>
      </form>
    </div>
  </section>

  <!-- FOOTER CORPORATIVO -->
  <footer>
    <div class="container">
      <div class="row">

        <div class="col-md-4">
          <h5 class="fw-bold">Javier Molina</h5>
          <p>Controller Financiero · Consultoría Estratégica</p>
        </div>

        <div class="col-md-4">
          <h5 class="fw-bold">Enlaces</h5>
          <ul class="list-unstyled">
            <li><a href="#valor">Propuesta de valor</a></li>
            <li><a href="#pymes-malaga">Pymes Málaga</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#dashboards">Dashboards</a></li>
            <li><a href="#testimonios">Testimonios</a></li>
            <li><a href="#contacto">Contacto</a></li>
          </ul>
        </div>

        <div class="col-md-4">
          <h5 class="fw-bold">Contacto</h5>
          <p>Email: contacto@tudominio.com</p>
          <p>Málaga, España</p>
        </div>

      </div>

      <div class="text-center mt-4">
        © 2026 Javier Molina · Todos los derechos reservados
      </div>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html># JavierMolinacontrollerfinanciero
Servicios de controller financieros para PYMES en Málaga

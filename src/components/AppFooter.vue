<script>
export default {

};
</script>

<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-3">
          <img src="../assets/logo.png" alt="NexGen Logo" class="logo img-fluid" />
          <p>A Functional HTML Template for Corporate & Business.</p>
          <ul class="contact-info">
            <li><i class="fas fa-phone"></i> +1 (305) 1234-5678</li>
            <li><i class="fas fa-envelope"></i> hello@example.com</li>
            <li><i class="fas fa-map-marker-alt"></i> Main Avenue, 987</li>
          </ul>
          <button class="btn btn-outline-light mt-2">GET IN TOUCH</button>
        </div>
        <div class="col-12 col-md-3">
          <h5>About</h5>
          <ul>
            <li><a href="#">The Company</a></li>
            <li><a href="#">Institutional</a></li>
            <li><a href="#">Social & Events</a></li>
            <li><a href="#">Innovation</a></li>
            <li><a href="#">Environment</a></li>
            <li><a href="#">Technology</a></li>
          </ul>
        </div>
        <div class="col-12 col-md-3">
          <h5>Services</h5>
          <ul>
            <li><a href="#">Audit & Assurance</a></li>
            <li><a href="#">Financial Advisory</a></li>
            <li><a href="#">Analytics M&A</a></li>
            <li><a href="#">Middle Marketing</a></li>
            <li><a href="#">Legal Consulting</a></li>
            <li><a href="#">Regulatory Risk</a></li>
          </ul>
        </div>
        <div class="col-12 col-md-3">
          <h5>Support</h5>
          <ul>
            <li><a href="#">Responsibility</a></li>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">About Cookies</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Accessibility</a></li>
            <li><a href="#">Information</a></li>
          </ul>
        </div>
      </div>
      <div class="row mt-4">
        <div class="col-6 text-center">
          <p class="mb-0">Enjoy the low price. We are tracking any intention of piracy.</p>
        </div>
        <div class="col-6 text-center">
            <p class="mb-0">&copy; 2023 NexGen is Proudly Powered by <a href="#" class="text-info">Codings</a>.</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  padding: 3rem 0;
  background-color: #0b0e14;
  color: #ffffff;

  .logo {
    width: 150px;
    margin-bottom: 1rem;
  }

  p {
    margin-bottom: 0.5rem;
    font-size: 0.9rem;
  }

  h5 {
    font-weight: bold;
    margin-bottom: 1rem;
    color: #ffffff;
  }

  ul {
    list-style: none;
    padding: 0;
  }

  ul li {
    margin-bottom: 0.5rem;
  }

  ul li a {
    color: #b0b0b0;
    text-decoration: none;
    font-size: 0.9rem;

    &:hover {
      text-decoration: underline;
    }
  }

  .contact-info {
    list-style: none;
    padding: 0;
    margin-top: 1rem;

    li {
      font-size: 0.9rem;
      margin-bottom: 0.5rem;
      display: flex;
      align-items: center;

      i {
        color: #058283;
        margin-right: 10px;
      }
    }
  }

  .btn-outline-light {
    border: 1px solid #058283;
    color: #058283;
    padding: 0.5rem 1rem;

    &:hover {
      background-color: #058283;
      color: #ffffff;
    }
  }

  .text-info {
    color: #00b7c2;

    &:hover {
      text-decoration: underline;
    }
  }

  .row.mt-4 {
    border-top: 1px solid #2c3e50;
    padding-top: 1rem;
  }
}
</style>

<script>
export default {
}
</script>

<template>
    <div class="services-section">
      <div class="container">
        <div class="row">
            <div class="col-12">
                <h6>our bussiness area</h6>
                <h2>Excellence in <span class="text-highlight">Service</span></h2>
            </div>
        </div>
        <div class="row">
            <div class="col-8">
                <p>We are leaders in providng consultacy services with a set of cutting-edge technologies and a team of experienced and renowned professionals. These are some options that you can hire.</p>
            </div>
            <div class="col-4 text-end">
                <button class="btn btn-primary">See All</button>
            </div>
        </div>
  
        <div class="row">
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <i class="icon fas fa-box"></i>
                <h5 class="card-title">Audit & Assurance</h5>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                <span class="arrow-icon fas fa-arrow-right"></span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <i class="icon fas fa-briefcase"></i>
                <h5 class="card-title">Financial Advisory</h5>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                <span class="arrow-icon fas fa-arrow-right"></span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <i class="icon fas fa-chart-bar"></i>
                <h5 class="card-title">Analytics and M&A</h5>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                <span class="arrow-icon fas fa-arrow-right"></span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <i class="icon fas fa-plane"></i>
                <h5 class="card-title">Middle Marketing</h5>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                <span class="arrow-icon fas fa-arrow-right"></span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <i class="icon fas fa-gavel"></i>
                <h5 class="card-title">Legal Consulting</h5>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                <span class="arrow-icon fas fa-arrow-right"></span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <i class="icon fas fa-file-alt"></i>
                <h5 class="card-title">Regulatory Risk</h5>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                <span class="arrow-icon fas fa-arrow-right"></span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Services Section -->
    <div class="about-company-section">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-6">
            <h6>ABOUT THE NETWORK</h6>
            <h2>The <span class="highlight">Company</span></h2>
            <p>For 12 years we have been providing audit and warranty, financial advice, risk advice, taxes, and related services to select clients.</p>
            <div class="features">
              <div class="feature">
                <i class="icon fas fa-award"></i>
                <h5>Tradition</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="feature">
                <i class="icon fas fa-shield-alt"></i>
                <h5>Security</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="feature">
                <i class="icon fas fa-certificate"></i>
                <h5>Certificate</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
              <div class="feature">
                <i class="icon fas fa-briefcase"></i>
                <h5>Expertise</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
              </div>
            </div>
            <div class="buttons">
              <button class="btn btn-primary">Get in Touch</button>
              <button class="btn btn-outline-primary">Read More</button>
            </div>
          </div>
          <div class="col-12 col-md-6">
            <img src="../assets/about-4.jpg" alt="Company Image" class="img-fluid">
          </div>
        </div>
      </div>
    </div>
  </template>
  
  

  <style lang="scss" scoped>
  .services-section {
    background-color: #f5f9f7;
    padding: 60px 0;

    .header {
      text-align: center;
      margin-bottom: 40px;

      .subtitle {
        color: #5ea3a3;
        text-transform: uppercase;
        font-weight: bold;
        letter-spacing: 1px;
        margin-bottom: 10px;
      }

      .title {
        font-size: 2.5rem;
        font-weight: bold;
        color: #354052;

        .highlight {
          background-color: #e2e3e799;
          color: #058283;
          padding: 0 0.5rem;
        }
      }

      .description {
        color: #7a8a97;
        margin-bottom: 20px;
      }

      .see-all-btn {
        background-color: #5ea3a3;
        color: white;
        border: none;
        padding: 10px 20px;
        font-weight: bold;
        cursor: pointer;
        border-radius: 5px;

        &:hover {
          background-color: #499090;
        }
      }
    }

    .card {
      background-color: white;
      border: none;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      margin-bottom: 30px;
      padding: 20px;

      .card-body {
        position: relative;

        .icon {
          font-size: 2rem;
          color: #5ea3a3;
          margin-bottom: 15px;
        }

        .card-title {
          font-weight: bold;
          color: #354052;
          margin-bottom: 10px;
        }

        .card-text {
          color: #7a8a97;
        }

        .arrow-icon {
          font-size: 1.5rem;
          color: #5ea3a3;
          position: absolute;
          top: 20px;
          right: 20px;
        }
      }
    }
  }

  .about-company-section {
    background-color: #0d1b2a;
    padding: 60px 0;
    color: #ffffff;

    .highlight {
      background-color: #05445e;
      padding: 0 5px;
      color: #ffffff;
    }

    h6 {
      color: #00b7c2;
      text-transform: uppercase;
      letter-spacing: 1px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 3rem;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .features {
      margin-top: 40px;

      .feature {
        display: flex;
        align-items: center;
        margin-bottom: 20px;

        i.icon {
          font-size: 2rem;
          color: #00b7c2;
          margin-right: 15px;
        }

        h5 {
          margin-bottom: 0;
          font-weight: bold;
        }

        p {
          margin-bottom: 0;
          color: #b0b0b0;
        }
      }
    }

    .buttons {
      margin-top: 30px;

      .btn-primary {
        background-color: #00b7c2;
        border: none;
      }

      .btn-outline-primary {
        border-color: #00b7c2;
        color: #00b7c2;
      }
    }

    img {
      max-width: 100%;
      height: auto;
      margin-top: 20px;
    }
  }
</style>


   

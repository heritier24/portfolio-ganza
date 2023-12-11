<template>
  <!-- Navbar Start -->
  <nav
    class="navbar navbar-expand-lg bg-white navbar-light fixed-top shadow py-lg-0 px-4 px-lg-5 wow fadeIn"
    data-wow-delay="0.1s"
  >
    <a href="/" class="navbar-brand d-block d-lg-none">
      <h1 class="text-primary fw-bold m-0">Heritier Ganza Tamba</h1>
    </a>
    <button
      type="button"
      class="navbar-toggler"
      data-bs-toggle="collapse"
      data-bs-target="#navbarCollapse"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div
      class="collapse navbar-collapse justify-content-between py-4 py-lg-0"
      id="navbarCollapse"
    >
      <div class="navbar-nav ms-auto py-0">
        <a href="#home" class="nav-item nav-link active">Home</a>
        <a href="#about" class="nav-item nav-link">About</a>
        <a href="#skill" class="nav-item nav-link">Skills</a>
        <a href="#service" class="nav-item nav-link">Services</a>
      </div>
      <a
        href="index.html"
        class="navbar-brand bg-secondary py-3 px-4 mx-3 d-none d-lg-block"
      >
        <h1 class="text-primary fw-bold m-0">Heritier Ganza</h1>
      </a>
      <div class="navbar-nav me-auto py-0">
        <a href="#project" class="nav-item nav-link">Projects</a>
        <a href="#testimonial" class="nav-item nav-link">Testimonial</a>
        <a href="#contact" class="nav-item nav-link">Contact</a>
      </div>
    </div>
  </nav>
  <!-- Navbar End -->
  <!-- Header Start -->
  <div class="container-fluid bg-light my-6 mt-0" id="home">
    <div class="container">
      <div class="row g-5 align-items-center">
        <div class="col-lg-6 py-6 pb-0 pt-lg-0">
          <h3 class="text-primary mb-3">I'm</h3>
          <h1 class="display-3 mb-3">Heritier Ganza Tamba</h1>
          <h2 class="typed-text-output d-inline"></h2>
          <div class="typed-text d-block">
            Web Designer, Web Developer, Front End Developer, Back End
            Developer, Apps Developer
          </div>
          <div class="d-flex align-items-center pt-5">
            <a href="" class="btn btn-primary py-3 px-4 me-5">Download CV</a>
            <button
              type="button"
              class="btn-play"
              data-bs-toggle="modal"
              data-src="https://www.youtube.com/embed/DWRcNpR6Kdc"
              data-bs-target="#videoModal"
            >
              <span></span>
            </button>
            <h5 class="ms-4 mb-0 d-none d-sm-block">Play Video</h5>
          </div>
        </div>
        <div class="col-lg-6">
          <img class="img-fluid" src="img/tamba.jpeg" alt="" />
        </div>
      </div>
    </div>
  </div>
  <!-- Header End -->
  <!-- Video Modal Start -->
  <div
    class="modal modal-video fade"
    id="videoModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content rounded-0">
        <div class="modal-header">
          <h3 class="modal-title" id="exampleModalLabel">Youtube Video</h3>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">
          <!-- 16:9 aspect ratio -->
          <div class="ratio ratio-16x9">
            <iframe
              class="embed-responsive-item"
              src=""
              id="video"
              allowfullscreen
              allowscriptaccess="always"
              allow="autoplay"
            ></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Video Modal End -->
  <!-- About Start -->
  <div class="container-xxl py-6" id="about">
    <div class="container">
      <div class="row g-5">
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
          <div class="d-flex align-items-center mb-5">
            <div class="years flex-shrink-0 text-center me-4">
              <h1 class="display-1 mb-0">5</h1>
              <h5 class="mb-0">Years</h5>
            </div>
            <h3 class="lh-base mb-0">
              of working experience as a FullStack Developer
            </h3>
          </div>
          <p class="mb-4">
            "I have a strong command of backend technologies such as PHP and
            Node.js, complemented by my expertise in managing MySQL databases.
            I'm highly proficient in using Git for version control, enabling
            smooth collaboration and organized development among team members.
            In project management, I've effectively applied Agile methodologies,
            ensuring efficient task assignment, timely deliveries, and clear
            communication within diverse teams. These skills have enabled me to
            successfully lead projects, fostering an environment of innovation
            and achievement in my career."
          </p>
          <p class="mb-3">
            <i class="far fa-check-circle text-primary me-3"></i>Afordable
            Prices
          </p>
          <p class="mb-3">
            <i class="far fa-check-circle text-primary me-3"></i>High Quality
            Product
          </p>
          <p class="mb-3">
            <i class="far fa-check-circle text-primary me-3"></i>On Time Project
            Delivery
          </p>
          <a class="btn btn-primary py-3 px-5 mt-3" href="">Read More</a>
        </div>
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.5s">
          <div class="row g-3 mb-4">
            <div class="col-sm-6">
              <img class="img-fluid rounded" src="img/logo-white.svg" alt="" />
            </div>
            <div class="col-sm-6">
              <img class="img-fluid rounded" src="img/fashionox.jpeg" alt="" />
            </div>
          </div>
          <div class="d-flex align-items-center mb-3">
            <h5 class="border-end pe-3 me-3 mb-0">Happy Clients</h5>
            <h2 class="text-primary fw-bold mb-0" data-toggle="counter-up">
              > 10
            </h2>
          </div>
          <p class="mb-4">
            Working as a full-stack developer, I collaborated closely with a
            different clients to build a tailored solution. Our teamwork
            resulted in an application that exceeded their expectations. The
            client was thrilled with the user-friendly design and the
            application's capability to grow with their business. Their positive
            feedback highlighted the significant impact our work had on
            enhancing their efficiency and user engagement. Overall, our
            successful collaboration left a lasting positive impression on their
            business.
          </p>
          <div class="d-flex align-items-center mb-3">
            <h5 class="border-end pe-3 me-3 mb-0">Projects Completed</h5>
            <h2 class="text-primary fw-bold mb-0" data-toggle="counter-up">
              > 40
            </h2>
          </div>
          <p class="mb-0">
            Developed an different platform as a full-stack developer using
            HTML, CSS, and Tailwind CSS for the frontend, Vue.js and JavaScript
            for interactive features, and Node.js, laravel with Express.js for
            the backend. Managed MySQL for efficient data storage and retrieval,
            integrated Git for version control, ensuring a successful and
            user-friendly online marketplace.
          </p>
        </div>
      </div>
    </div>
  </div>
  <!-- About End -->
  <!-- Expertise Start -->
  <div class="container-xxl py-6 pb-5" id="skill">
    <div class="container">
      <div class="row g-5">
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
          <h1 class="display-5 mb-5">Skills & Experience</h1>
          <p class="mb-4">
            "I possess expertise in web development with skills in HTML, CSS,
            JavaScript, React, and Vue.js for frontend, alongside Node.js, PHP,
            Laravel and MySQL for backend. Experienced in Git version control
            and adept at project management using Agile methodologies."
          </p>
          <h3 class="mb-4">My Skills</h3>
          <div class="row align-items-center">
            <div class="col-md-6">
              <div class="skill mb-4">
                <div class="d-flex justify-content-between">
                  <h6 class="font-weight-bold">HTML</h6>
                  <h6 class="font-weight-bold">95%</h6>
                </div>
                <div class="progress">
                  <div
                    class="progress-bar bg-primary"
                    role="progressbar"
                    aria-valuenow="95"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill mb-4">
                <div class="d-flex justify-content-between">
                  <h6 class="font-weight-bold">CSS</h6>
                  <h6 class="font-weight-bold">85%</h6>
                </div>
                <div class="progress">
                  <div
                    class="progress-bar bg-warning"
                    role="progressbar"
                    aria-valuenow="85"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill mb-4">
                <div class="d-flex justify-content-between">
                  <h6 class="font-weight-bold">PHP</h6>
                  <h6 class="font-weight-bold">90%</h6>
                </div>
                <div class="progress">
                  <div
                    class="progress-bar bg-danger"
                    role="progressbar"
                    aria-valuenow="90"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="skill mb-4">
                <div class="d-flex justify-content-between">
                  <h6 class="font-weight-bold">Javascript</h6>
                  <h6 class="font-weight-bold">90%</h6>
                </div>
                <div class="progress">
                  <div
                    class="progress-bar bg-danger"
                    role="progressbar"
                    aria-valuenow="90"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill mb-4">
                <div class="d-flex justify-content-between">
                  <h6 class="font-weight-bold">Vue JS</h6>
                  <h6 class="font-weight-bold">95%</h6>
                </div>
                <div class="progress">
                  <div
                    class="progress-bar bg-dark"
                    role="progressbar"
                    aria-valuenow="95"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill mb-4">
                <div class="d-flex justify-content-between">
                  <h6 class="font-weight-bold">Laravel</h6>
                  <h6 class="font-weight-bold">95%</h6>
                </div>
                <div class="progress">
                  <div
                    class="progress-bar bg-info"
                    role="progressbar"
                    aria-valuenow="85"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.5s">
          <ul class="nav nav-pills rounded border border-2 border-primary mb-5">
            <li class="nav-item w-50">
              <button
                class="nav-link w-100 py-3 fs-5 active"
                data-bs-toggle="pill"
                href="#tab-1"
              >
                Experience
              </button>
            </li>
            <li class="nav-item w-50">
              <button
                class="nav-link w-100 py-3 fs-5"
                data-bs-toggle="pill"
                href="#tab-2"
              >
                Education
              </button>
            </li>
          </ul>
          <div class="tab-content">
            <div id="tab-1" class="tab-pane fade show p-0 active">
              <div class="row gy-5 gx-4">
                <div class="col-sm-6">
                  <h5>Software Engeneer</h5>
                  <hr class="text-primary my-2" />
                  <p class="text-primary mb-1">2023 - Present</p>
                  <h6 class="mb-0">Fashionox Inc</h6>
                </div>
                <div class="col-sm-6">
                  <h5>Software Engeneer</h5>
                  <hr class="text-primary my-2" />
                  <p class="text-primary mb-1">2023 - 2023</p>
                  <h6 class="mb-0">Msg Trade</h6>
                </div>
                <div class="col-sm-6">
                  <h5>Full Stack Developer</h5>
                  <hr class="text-primary my-2" />
                  <p class="text-primary mb-1">2021 - 2023</p>
                  <h6 class="mb-0">Kudibooks HQ</h6>
                </div>
                <div class="col-sm-6">
                  <h5>Software Developer</h5>
                  <hr class="text-primary my-2" />
                  <p class="text-primary mb-1">2019 - 2020</p>
                  <h6 class="mb-0">Mvend Ltd</h6>
                </div>
              </div>
            </div>
            <div id="tab-2" class="tab-pane fade show p-0">
              <div class="row gy-5 gx-4">
                <div class="col-sm-6">
                  <h5>Software Engeneering</h5>
                  <hr class="text-primary my-2" />
                  <p class="text-primary mb-1">2016 - 2019</p>
                  <h6 class="mb-0">Unilak</h6>
                </div>
                <div class="col-sm-6">
                  <h5>Mathematics, Computer & Economics</h5>
                  <hr class="text-primary my-2" />
                  <p class="text-primary mb-1">2013 - 2015</p>
                  <h6 class="mb-0">Gisenyi Adventist Secondary School</h6>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Expertise End -->
  <!-- Service Start -->
  <div class="container-fluid bg-light my-5 py-6" id="service">
    <div class="container">
      <div class="row g-5 mb-5 wow fadeInUp" data-wow-delay="0.1s">
        <div class="col-lg-6">
          <h1 class="display-5 mb-0">My Services</h1>
        </div>
        <div class="col-lg-6 text-lg-end">
          <a class="btn btn-primary py-3 px-5" href="">Hire Me</a>
        </div>
      </div>
      <div class="row g-4">
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
          <div
            class="service-item d-flex flex-column flex-sm-row bg-white rounded h-100 p-4 p-lg-5"
          >
            <div class="bg-icon flex-shrink-0 mb-3">
              <i class="fa fa-crop-alt fa-2x text-dark"></i>
            </div>
            <div class="ms-sm-4">
              <h4 class="mb-3">Creative Design</h4>
              <h6 class="mb-3">
                Start from <span class="text-primary">$199</span>
              </h6>
              <span>
                "As a dedicated creative designer, I personally handle every
                aspect of the design process. From conceptualization to
                execution, I bring your brand's essence to life through my
                artistic vision. With a keen eye for detail and a passion for
                creativity, I work closely with you to deliver tailored designs
                across various platforms. My goal is to ensure your brand stands
                out, leaving a memorable impact in the digital realm.."</span
              >
            </div>
          </div>
        </div>
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.3s">
          <div
            class="service-item d-flex flex-column flex-sm-row bg-white rounded h-100 p-4 p-lg-5"
          >
            <div class="bg-icon flex-shrink-0 mb-3">
              <i class="fa fa-code-branch fa-2x text-dark"></i>
            </div>
            <div class="ms-sm-4">
              <h4 class="mb-3">Graphic Design</h4>
              <h6 class="mb-3">
                Start from <span class="text-primary">$199</span>
              </h6>
              <span
                >We specialize in creating impactful graphic designs that
                effectively communicate your brand's story. From logos to
                multimedia designs, our creative approach ensures visually
                compelling elements tailored to your brand identity, enhancing
                your overall brand presence..</span
              >
            </div>
          </div>
        </div>
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.1s">
          <div
            class="service-item d-flex flex-column flex-sm-row bg-white rounded h-100 p-4 p-lg-5"
          >
            <div class="bg-icon flex-shrink-0 mb-3">
              <i class="fa fa-code fa-2x text-dark"></i>
            </div>
            <div class="ms-sm-4">
              <h4 class="mb-3">Web Development</h4>
              <h6 class="mb-3">
                Start from <span class="text-primary">$199</span>
              </h6>
              <span
                >I provide personalized web development services, creating
                seamless and user-centric websites. With expertise in HTML, CSS,
                JavaScript, and modern frameworks, I craft visually appealing
                and responsive designs that enhance online presence and engage
                audiences effectively..</span
              >
            </div>
          </div>
        </div>
        <div class="col-lg-6 wow fadeInUp" data-wow-delay="0.3s">
          <div
            class="service-item d-flex flex-column flex-sm-row bg-white rounded h-100 p-4 p-lg-5"
          >
            <div class="bg-icon flex-shrink-0 mb-3">
              <i class="fa fa-laptop-code fa-2x text-dark"></i>
            </div>
            <div class="ms-sm-4">
              <h4 class="mb-3">UI/UX Design</h4>
              <h6 class="mb-3">
                Start from <span class="text-primary">$199</span>
              </h6>
              <span
                >We specialize in creating intuitive and visually appealing
                UI/UX designs that prioritize user satisfaction. Our designs
                focus on seamless interactions, understanding user behaviors,
                and aligning with brand vision to enhance engagement and
                usability.</span
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Service End -->
  <!-- Projects Start -->
  <div class="container-xxl py-6 pt-5" id="project">
    <div class="container">
      <div
        class="row g-5 mb-5 align-items-center wow fadeInUp"
        data-wow-delay="0.1s"
      >
        <div class="col-lg-6">
          <h1 class="display-5 mb-0"> Main Projects Worked On It</h1>
        </div>
        <!-- <div class="col-lg-6 text-lg-end">
          <ul class="list-inline mx-n3 mb-0" id="portfolio-flters">
            <li class="mx-3 active" data-filter="*">All Projects</li>
            <li class="mx-3" data-filter=".first">UI/UX Design</li>
            <li class="mx-3" data-filter=".second">Graphic Design</li>
          </ul>
        </div> -->
      </div>
      <div
        class="row g-4 portfolio-container wow fadeInUp"
        data-wow-delay="0.1s"
      >
        <div class="col-lg-4 col-md-6 portfolio-item first">
          <div class="portfolio-img rounded overflow-hidden">
            <img class="img-fluid" src="img/logo-white.svg" alt="" />
            <div class="portfolio-btn">
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="img/logo-white.svg"
                data-lightbox="portfolio"
                ><i class="fa fa-eye"></i
              ></a>
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="https://family-group-ikimina.pages.dev/"
                ><i class="fa fa-link"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 portfolio-item second">
          <div class="portfolio-img rounded overflow-hidden">
            <img class="img-fluid" src="img/fashionox.jpeg" alt="" />
            <div class="portfolio-btn">
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="img/fashionox.jpeg"
                data-lightbox="portfolio"
                ><i class="fa fa-eye"></i
              ></a>
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="https://fashionox.art/"
                ><i class="fa fa-link"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 portfolio-item first">
          <div class="portfolio-img rounded overflow-hidden">
            <img class="img-fluid" src="img/kudibooks.png" alt="" />
            <div class="portfolio-btn">
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="img/kudibooks.png"
                data-lightbox="portfolio"
                ><i class="fa fa-eye"></i
              ></a>
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="https://kudibooks.com/"
                ><i class="fa fa-link"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 portfolio-item second">
          <div class="portfolio-img rounded overflow-hidden">
            <img class="img-fluid" src="img/gwiza.jpeg" alt="" />
            <div class="portfolio-btn">
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="img/gwiza.jpeg"
                data-lightbox="portfolio"
                ><i class="fa fa-eye"></i
              ></a>
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href=""
                ><i class="fa fa-link"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 portfolio-item first">
          <div class="portfolio-img rounded overflow-hidden">
            <img class="img-fluid" src="img/beone organization logo.jpeg" alt="" />
            <div class="portfolio-btn">
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="img/beone organization logo.jpeg"
                data-lightbox="portfolio"
                ><i class="fa fa-eye"></i
              ></a>
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href=""
                ><i class="fa fa-link"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 portfolio-item second">
          <div class="portfolio-img rounded overflow-hidden">
            <img class="img-fluid" src="img/pacific-painter-training-center-high-resolution-logo.png" alt="" />
            <div class="portfolio-btn">
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href="img/pacific-painter-training-center-high-resolution-logo.png"
                data-lightbox="portfolio"
                ><i class="fa fa-eye"></i
              ></a>
              <a
                class="btn btn-lg-square btn-outline-secondary border-2 mx-1"
                href=""
                ><i class="fa fa-link"></i
              ></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Projects End -->
  <!-- Contact Start -->
  <div class="container-xxl pb-5" id="contact">
    <div class="container py-5">
      <div class="row g-5 mb-5 wow fadeInUp" data-wow-delay="0.1s">
        <div class="col-lg-6">
          <h1 class="display-5 mb-0">Let's Work Together</h1>
        </div>
        <div class="col-lg-6 text-lg-end">
          <a class="btn btn-primary py-3 px-5" href="">Say Hello</a>
        </div>
      </div>
      <div class="row g-5">
        <div class="col-lg-5 col-md-6 wow fadeInUp" data-wow-delay="0.1s">
          <p class="mb-2">My office:</p>
          <h3 class="fw-bold">kk 505 st kicukiro, Kigali, RWANDA</h3>
          <hr class="w-100" />
          <p class="mb-2">Call me:</p>
          <h3 class="fw-bold">+250789 326 245</h3>
          <hr class="w-100" />
          <p class="mb-2">Mail me:</p>
          <h3 class="fw-bold">ganzatambaheritier24@gmail.com</h3>
          <hr class="w-100" />
          <p class="mb-2">Follow me:</p>
          <div class="d-flex pt-2">
            <a class="btn btn-square btn-primary me-2" href=""
              ><i class="fab fa-twitter"></i
            ></a>
            <a class="btn btn-square btn-primary me-2" href=""
              ><i class="fab fa-facebook-f"></i
            ></a>
            <a class="btn btn-square btn-primary me-2" href=""
              ><i class="fab fa-youtube"></i
            ></a>
            <a class="btn btn-square btn-primary me-2" href=""
              ><i class="fab fa-linkedin-in"></i
            ></a>
          </div>
        </div>
        <div class="col-lg-7 col-md-6 wow fadeInUp" data-wow-delay="0.5s">
          <p class="mb-4">
            The contact form is currently inactive.
          </p>
          <form>
            <div class="row g-3">
              <div class="col-md-6">
                <div class="form-floating">
                  <input
                    type="text"
                    class="form-control"
                    id="name"
                    placeholder="Your Name"
                  />
                  <label for="name">Your Name</label>
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-floating">
                  <input
                    type="email"
                    class="form-control"
                    id="email"
                    placeholder="Your Email"
                  />
                  <label for="email">Your Email</label>
                </div>
              </div>
              <div class="col-12">
                <div class="form-floating">
                  <input
                    type="text"
                    class="form-control"
                    id="subject"
                    placeholder="Subject"
                  />
                  <label for="subject">Subject</label>
                </div>
              </div>
              <div class="col-12">
                <div class="form-floating">
                  <textarea
                    class="form-control"
                    placeholder="Leave a message here"
                    id="message"
                    style="height: 100px"
                  ></textarea>
                  <label for="message">Message</label>
                </div>
              </div>
              <div class="col-12">
                <button class="btn btn-primary py-3 px-5" type="submit">
                  Send Message
                </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
  <!-- Contact End -->
  <!-- Map Start -->
  <div class="container-xxl pt-5 px-0 wow fadeInUp" data-wow-delay="0.1s">
    <div class="container-xxl pt-5 px-0">
      <div class="bg-dark">
        <iframe
          src="https://www.google.com/maps/place/ICT+Innovation+Center/@-1.9769362,30.1027503,17z/data=!3m1!4b1!4m6!3m5!1s0x19dca7e706ef65af:0x7d9cd4ddcbefe8bc!8m2!3d-1.9769416!4d30.1053252!16s%2Fg%2F11j4dktw2f?hl=en&entry=ttu"
          frameborder="0"
          style="width: 100%; height: 450px; border: 0"
          allowfullscreen=""
          aria-hidden="false"
          tabindex="0"
        ></iframe>
      </div>
    </div>
  </div>
  <!-- Map End -->
  <!-- Copyright Start -->
  <div class="container-fluid bg-dark text-white py-4">
    <div class="container">
      <div class="row">
        <div class="col-md-6 text-center text-md-start mb-3 mb-md-0">
          &copy;
          <a class="border-bottom text-secondary" href="#">portfolio Ganza</a>,
          All Right Reserved.
        </div>
        <div class="col-md-6 text-center text-md-end">
          <!--/*** This template is free as long as you keep the footer author’s credit link/attribution link/backlink. If you'd like to use the template without the footer author’s credit link/attribution link/backlink, you can purchase the Credit Removal License from "https://htmlcodex.com/credit-removal". Thank you for your support. ***/-->
          <!-- Designed By <a class="border-bottom text-secondary" href="https://htmlcodex.com">HTML Codex</a> -->
        </div>
      </div>
    </div>
  </div>
  <a href="#" class="btn btn-lg btn-primary btn-lg-square back-to-top"
    ><i class="bi bi-arrow-up"></i
  ></a>
</template>

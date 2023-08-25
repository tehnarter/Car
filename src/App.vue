<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="wrapper">
    <Header />
    <main>
      <section class="who">
        <div class="who__container">
          <div class="who__inner">
            <div class="who__sub-title">Who we are</div>
            <h2 class="who__title">
              Nemo enim ipsam voluptatem quia voluptas in proident
            </h2>
            <div class="who__text">
              Ut enim ad minima veniam, quis nostrum exercitationem ullam
              corporis suscipit laboriosam, nisi ut aliquid ex ea commodi
              consequatur. Quis autem vel eum iure reprehenderit qui in ea
              voluptate velit esse quam nihil molestiae consequatur, vel illum
              qui dolorem eum fugiat quo voluptas nulla pariatur.
            </div>
            <div class="who__img">
              <img src="./assets/img/main/sec__who/car.jpg" alt="" />
            </div>
          </div>
        </div>
      </section>
      <section class="our">
        <div class="our__container">
          <div class="our__sub-title">OUR PROMISE TO YOU</div>
          <h2 class="our__title">Sed perspiciatis omnis iste natus</h2>
          <div class="our__row">
            <article class="card-our our__card">
              <div class="card-our__icon">
                <img
                  src="./assets/img/main/sec__our/car_quality_service_24x.png"
                  alt=""
                />
              </div>
              <div class="card-our__body">
                <div class="card-our__title">Quality service. Everytime.</div>

                <div class="card-our__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
            <article class="card-our our__card">
              <div class="card-our__icon">
                <img
                  src="./assets/img/main/sec__our/car_certified_pros_24x.png"
                  alt=""
                />
              </div>
              <div class="card-our__body">
                <div class="card-our__title">Services by certified pros</div>

                <div class="card-our__text">
                  Dolorem ipsum quia dolor sit amet, consectetur, adipisci
                  velit, sed quia non numquam eius modi tempora incidunt.
                </div>
              </div>
            </article>
            <article class="card-our our__card">
              <div class="card-our__icon">
                <img src="./assets/img/main/sec__our/car_team_24x.png" alt="" />
              </div>
              <div class="card-our__body">
                <div class="card-our__title">Real people. Honest work.</div>

                <div class="card-our__text">
                  Quis autem vel eum iure reprehenderit qui in ea voluptate
                  velit esse quam nihil molestiae consequatur illum.
                </div>
              </div>
            </article>
          </div>
        </div>
      </section>
      <section class="play">
        <div class="play__text">
          Nemo enim ipsam voluptatem quia voluptas in proident
        </div>
        <a href="#" class="play__button">
          <img src="./assets/img/main/sec__play/play.png" alt="" />
        </a>
      </section>
      <section class="servises">
        <div class="servises__container">
          <div class="servises__sub-title">Our Services</div>
          <h2 class="servises__title">Sed perspiciatis omnis iste natus</h2>
          <div class="servises__row">
            <article class="card-serv servises__card">
              <div class="card-serv__card">
                <div class="card-serv__icon">
                  <img
                    src="./assets/img/main/sec__serv/car_bay_24x.svg"
                    alt=""
                  />
                </div>
                <div class="card-serv__title">Multi Point Inspections</div>
                <div class="card-serv__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
            <article class="card-serv servises__card">
              <div class="card-serv__card">
                <div class="card-serv__icon">
                  <img
                    src="./assets/img/main/sec__serv/car_engine_24x.svg"
                    alt=""
                  />
                </div>
                <div class="card-serv__title">Auto Repair</div>
                <div class="card-serv__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
            <article class="card-serv servises__card">
              <div class="card-serv__card">
                <div class="card-serv__icon">
                  <img
                    src="./assets/img/main/sec__serv/car_breaks_24x.svg"
                    alt=""
                  />
                </div>
                <div class="card-serv__title">Auto Maintenance</div>
                <div class="card-serv__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
            <article class="card-serv servises__card">
              <div class="card-serv__card">
                <div class="card-serv__icon">
                  <img
                    src="./assets/img/main/sec__serv/car_tires_24x.svg"
                    alt=""
                  />
                </div>
                <div class="card-serv__title">Tires</div>
                <div class="card-serv__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
            <article class="card-serv servises__card">
              <div class="card-serv__card">
                <div class="card-serv__icon">
                  <img
                    src="./assets/img/main/sec__serv/car_engine_check_24x.svg"
                    alt=""
                  />
                </div>
                <div class="card-serv__title">Service Warranty</div>
                <div class="card-serv__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
            <article class="card-serv servises__card">
              <div class="card-serv__card">
                <div class="card-serv__icon">
                  <img
                    src="./assets/img/main/sec__serv/car_bay_24x.svg"
                    alt=""
                  />
                </div>
                <div class="card-serv__title">Shop Online</div>
                <div class="card-serv__text">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium corrupti quos dolores et quas.
                </div>
              </div>
            </article>
          </div>
          <div class="servises__button button-red">Shop Online</div>
        </div>
      </section>
      <section class="form">
        <div class="form__container">
          <div class="form__row">
            <form class="form__card card-form">
              <h3 class="card-form__title">Make an appointment</h3>
              <div class="card-form__row">
                <input class="card-form__name" type="text" placeholder="Name" />
                <input
                  class="card-form__email"
                  type="email"
                  placeholder="Email"
                />
                <input
                  class="card-form__number"
                  type="tel"
                  placeholder="Phone Number"
                />
                <input
                  class="card-form__servisc"
                  type="text"
                  placeholder="Select Service"
                />
              </div>
              <textarea
                class="card-form__text"
                placeholder="Tell us about the car needing service(s)"
                name="text"
                id=""
                cols="30"
                rows="10"
              ></textarea>
              <button type="submit" class="card-form__button button-red">
                Make an Appointment
              </button>
            </form>
            <div class="form__text">
              <div class="form__sub-title">
                Maxime placeat facere possimus omnis
              </div>
              <div class="form__subject">17k</div>
              <div class="form__content">customers served (and counting)</div>
            </div>
          </div>
        </div>
      </section>
      <section class="gallery">
        <div class="gallery__container">
          <div class="gallery__inner">
            <div class="gallery__subtitle">GALLERY & LIVE STREAMS</div>
            <div class="gallery__title">Check out our hard workers</div>
            <div class="gallery__lists">
              <ul class="gallery__row">
                <li class="gallery__list">Gallery</li>
                <li class="gallery__list">Live stream: Bay 1</li>
                <li class="gallery__list">Live stream: Bay 2</li>
                <li class="gallery__list">Live stream: Bay 3</li>
              </ul>
            </div>
            <div class="gallery__img">
              <img src="./assets/img/main/sec__gallery/gallery.jpg" alt="" />
            </div>
          </div>
        </div>
      </section>
      <section class="cust">
        <div class="cust__container">
          <div class="cust__row">
            <article class="cust__card card-cust">
              <div class="card-cust__subtitle">Our CUSTOMERS</div>
              <h3 class="card-cust__title">
                Illum qui dolorem eum quo voluptas ut distinctio
              </h3>
            </article>
            <article class="cust__card card-cust">
              <div class="card-cust__inner">
                <div class="card-cust__text">
                  “Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore ex magna
                  aliqua. Ut enim illum ad minim veniam, quis ea exercitation
                  ullamco cillum ut enim dolore.”
                </div>
                <div class="card-cust__work">
                  <div class="card-cust__img">
                    <img src="./assets/img/main/sec__cust/man.jpg" alt="" />
                  </div>
                  <div class="card-cust__name">Cullen Bohannon</div>
                </div>
              </div>
            </article>
            <article class="cust__card card-cust">
              <div class="card-cust__inner">
                <div class="card-cust__text">
                  “Sed ut perspiciatis unde omnis iste natus error sit
                  voluptatem accusantium doloremque laudantium, totam rem
                  aperiam, eaque ipsa quae ab illo inventore veritatis et quasi
                  ipsam voluptatem aspernatur.”
                </div>
                <div class="card-cust__work">
                  <div class="card-cust__img">
                    <img src="./assets/img/main/sec__cust/women.jpg" alt="" />
                  </div>
                  <div class="card-cust__name">Jennifer Thomas</div>
                </div>
              </div>
            </article>
          </div>
        </div>
      </section>
      <section class="impact">
        <div class="impact__container">
          <div class="impact__first-row row-first">
            <div class="row-first__content">
              <div class="row-first__subtitle">OUR IMPACT</div>
              <div class="row-first__title">
                Nemo enim ipsam voluptatem quia voluptas
              </div>
            </div>
            <div class="row-first__img">
              <img src="./assets/img/main/sec__impact/car.jpg" alt="" />
            </div>
          </div>
          <div class="impact__row">
            <div class="impact__inner">
              <div class="impact__icons">
                <img
                  src="./assets/img/main/sec__impact/car_oil-24x.svg"
                  alt=""
                />
              </div>
              <div class="impact__content">
                <div class="impact__title">16k+</div>
                <div class="impact__text">Oil changes</div>
              </div>
            </div>
            <div class="impact__inner">
              <div class="impact__icons">
                <img
                  src="./assets/img/main/sec__impact/car_transmission_24x.svg"
                  alt=""
                />
              </div>
              <div class="impact__content">
                <div class="impact__title">13k+</div>
                <div class="impact__text">Transmission repairs</div>
              </div>
            </div>
            <div class="impact__inner">
              <div class="impact__icons">
                <img src="./assets/img/main/sec__impact/FlatTyre.svg" alt="" />
              </div>
              <div class="impact__content">
                <div class="impact__title">15k+</div>
                <div class="impact__text">Alignments made</div>
              </div>
            </div>
            <div class="impact__inner">
              <div class="impact__icons">
                <img
                  src="./assets/img/main/sec__impact/car_transmission_24x.svg"
                  alt=""
                />
              </div>
              <div class="impact__content">
                <div class="impact__title">11,500+</div>
                <div class="impact__text">Engines repaired</div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="contact">
        <div class="contact__container">
          <div class="contact__block-row">
            <h2 class="contact__title">
              Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
            <div class="contact__button button-red">Make an Appointment</div>
          </div>
          <div class="contact__footer-row list-contact">
            <div class="list-contact__block">
              <a class="list-contact__logo" href="#"
                ><img src="./assets/img/main/sec__contact/Vector.svg" alt="" />
              </a>
              <div class="list-contact__text">
                This is a blurb about the company sed do eiusmod tempor
                incididunt ut labore et dolore ex magna aliqua.
              </div>
              <div class="list-contact__icons">
                <a class="list-contact__facebook" href=""
                  ><img
                    src="./assets/img/main/sec__contact/facebook.svg"
                    alt=""
                /></a>
                <a class="list-contact__twit" href=""
                  ><img src="./assets/img/main/sec__contact/twitter.svg" alt=""
                /></a>
                <a class="list-contact__inst" href=""
                  ><img
                    src="./assets/img/main/sec__contact/instagram.svg"
                    alt=""
                /></a>
                <a class="list-contact__youtube" href=""
                  ><img src="./assets/img/main/sec__contact/youtube.svg" alt=""
                /></a>
              </div>
            </div>
            <div class="list-contact__block list-contact_two">
              <div class="list-contact__explore">EXPLORE LINKS</div>
              <div class="list-contact__colum">
                <ul class="list-contact__ul">
                  <li>About</li>
                  <li>Services</li>
                  <li>Specials</li>
                  <li>Estimates</li>
                </ul>
                <ul class="list-contact__ul">
                  <li>Reviews</li>
                  <li>Shop</li>
                  <li>Careers</li>
                  <li>FAQs</li>
                </ul>
              </div>
            </div>
            <!-- <div class="list-contact">
                <ul class="list-contact__shops"></ul>
              </div> -->
            <div class="list-contact__block">
              <ul class="list-contact__head-contact">
                <li class="list-contact__contact">CONTACT</li>
                <li class="list-contact__adress">
                  321 Pikes Place Parkway <br />
                  Seattle, WA 54321
                </li>
                <li class="list-contact__tel">(555) 765-4321</li>
                <li class="list-contact__mail">Info@company.com</li>
                <li class="list-contact__clock">
                  Mon - Sat: 7:000 am - 6:00 pm
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>
    </main>
    <Footer />
  </div>
</template>
<style scoped></style>

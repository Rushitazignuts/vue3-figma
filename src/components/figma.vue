<template>
  <div>
    <div class="header-back-img d-flex flex-column justify-space-between">
      <div>
        <div class="header-logo d-flex justify-space-around align-center pt-15">
          <div>
            <VImg
              width="60"
              :aspect-ratio="1"
              src="../../public/images/Logo.png"
            ></VImg>
          </div>
          <div class="d-flex align-center justify-center h-100">
            <VIcon icon="mdi-magnify" color="white" class="mr-4"></VIcon>
            <VBtn rounded="pill" class="px-7 menu-btn"> Menu </VBtn>
          </div>
        </div>
        <div class="trip-content">
          <h1 class="trip-title text-center">Night Trips</h1>
          <p class="trip-para1 text-center mt-2">
            WE GOT TRIPS FOR THE TRIPPSTER IN YOU
          </p>
          <p class="text-center text-white mt-10 trip-para2">
            Neque, eros commodo, nascetur ullamcorper vitae. Tincidunt ut
            venenatis, volutpat lorem ut faucibus mauris, quisque. Integer
            gravida sed quis congue. Vel risus, arcu a viverra leo id pulvinar
            ultricies. Enim in in in pulvinar nulla sollicitudin. Ullamcorper.
          </p>
        </div>
      </div>
      <div class="trip-plan">
        <div class="trip-icon">
          <div>
            <p class="text-white trip-scroll">SCROLL</p>
            <VImg
              width="60"
              :aspect-ratio="1"
              src="../../public/images/Rectangle 15.png"
              class="mt-8"
            ></VImg>
          </div>
          <div>
            <VIcon icon="mdi-twitter" color="white"></VIcon><br />
            <VIcon icon="mdi-instagram" color="white" class="my-3"></VIcon
            ><br />
            <VIcon icon="mdi-facebook" color="white"></VIcon>
          </div>
        </div>
      </div>
    </div>

    <div class="pick-trip">
      
      <div class="trip-box">
        <div class="d-flex justify-center align-center text-white">
          <p class="pick-title">Pick your trip</p>
          <VIcon icon="mdi-close" color="white" class="mx-5"></VIcon>
          <p>
            Our team put together some trips to you to discover,<br />
            feel free to discover each of them.
          </p>
        </div>
<div>
        <div class="trip-navigation">
          <div class="chill-title">Chill Adventure</div>
          <div>Spooky Times</div>
          <div>Desert Madness</div>
          <div>Out in the wild</div>
        </div>
        <div class="ms-10">
        <VImg
            width="1200"
            height="2"
            :aspect-ratio="1"
            src="../../public/images/Menu line.png"
            class="mt-8"
          ><div class="active-menu"></div></VImg>
        </div>
      </div>
        <div class="d-flex justify-space-evenly">
          <div class="trip-img">
            <div>
              <VImg
                width="486"
                :aspect-ratio="1"
                src="../../public/images/image.png"
              ></VImg>
            </div>
            <div class="trip-img-position">
              <VImg
                width="182"
                height="13"
                :aspect-ratio="1"
                src="../../public/images/Gimmick line.png"
                class="trip-img1"
              ></VImg>
              <div>01.</div>
              <h3>
                GRAND DUNES<br />
                LANDSCAPE
              </h3>
            </div>
            <div class="trip-img3">
              <VImg
                width="130"
                height="65"
                :aspect-ratio="1"
                src="../../public/images/Slider controller.png"
              ></VImg>
            </div>
          </div>
          <div class="d-flex flex-column justify-space-evenly">
            <h1 class="text-white">Chill Adventure</h1>
            <p class="text-white adventure-para">
              Ornare vivamus molestie pellentesque nunc. Sed sapien erat
              ultrices curabitur. Erat id fringilla arcu condimentum fames.<br /><br />
              Aliquet dictum aliquet faucibus cursus turpis. Suspendisse cum
              rutrum sit ut sociis. Pellentesque neque orci adipiscing pharetra
              lacus, dignissim pharetra ipsum blandit. Feugiat quis quam
              consectetur lectus id quis tortor vel, mattis.
            </p>
            <VBtn rounded="pill" class="px-7 offer-btn">
              SEE OUR LATEST OFFER
            </VBtn>
            <div class="text-end share-img">
              <div class="text-white">SHARE IT :</div>
              <div class="mt-3">
                <VIcon icon="mdi-twitter" color="white"></VIcon>
                <VIcon icon="mdi-instagram" color="white" class="mx-3"></VIcon>

                <VIcon icon="mdi-facebook" color="white"></VIcon>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="about-us mt-15">
        <div class="about-height">
          <div class="d-flex justify-space-evenly">
            <div class="text-white about-content">
              <h1>About us</h1>
              <p>
                We’re a team of four passioned people.<br /><br />
                We’re ready to take the world by storm and let you find new
                travel opportunities.<br /><br />
                Our everyday task is to make sure that you satisfied with the
                services and products that we provide.<br /><br />
                With 💖 from Amsterdam, Netherlands.
              </p>
              <VBtn
                rounded="pill"
                class="px-7 mt-7 offer-btn"
              >
                READ MORE ABOUT US
              </VBtn>
            </div>
            <div class="dot-img">
              <div class="d-flex">
                <div class="about-img1">
                  <VImg
                    width="395"
                    height="395"
                    :aspect-ratio="1"
                    src="../../public/images/img1.png"
                    class="mt-8"
                  ></VImg>
                  <div class="ceo-btn">
                    <p class="text-center text-black py-6">
                      MARTIN JACK,<span class="text-info"> CEO</span>
                    </p>
                  </div>
                </div>
                <div>
                  <VImg
                    width="395"
                    height="395"
                    :aspect-ratio="1"
                    src="../../public/images/img2.png"
                    class="mt-8"
                  ></VImg>
                </div>
              </div>
              <div class="d-flex">
                <div>
                  <VImg
                    width="395"
                    height="395"
                    :aspect-ratio="1"
                    src="../../public/images/img3.png"
                    class="mt-8"
                  ></VImg>
                </div>
                <div>
                  <VImg
                    width="395"
                    height="395"
                    :aspect-ratio="1"
                    src="../../public/images/img4.png"
                    class="mt-8"
                  ></VImg>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="d-flex justify-center">
          <div class="people-thought">
            <div class="text-center text-white mt-15">
              <h1 class="people-heading">People’s thoughts</h1>
              <p class="mt-3">SEE WHAT ARE OTHERS SAYING</p>
            </div>

            <div>
              <PeopleCard />
            </div>

            <div class="text-white text-center mt-15">
              <h1 class="heading">See you soon!</h1>
              <p class="paragraph">
                We hope to meet each other<br />
                very soon.
              </p>
            </div>

            <div class="mt-15 d-flex">
              <VImg
                width="2"
                height="80"
                :aspect-ratio="1"
                src="../../public/images/Rectangle 15.png"
              ></VImg>
            </div>

            <div class="d-flex justify-space-evenly text-white mt-15 footer">
              <ul>
                <p>ABOUT</p>
                <VImg
                  width="56"
                  height="8"
                  :aspect-ratio="1"
                  src="../../public/images/Divider.png"
                ></VImg>
                <li>our mission</li>
                <li>terms</li>
                <li>copywright</li>
              </ul>

              <ul>
                <p>FAQ</p>
                <VImg
                  width="56"
                  height="8"
                  :aspect-ratio="1"
                  src="../../public/images/Divider.png"
                ></VImg>
                <li>Rules</li>
                <li>Tickets</li>
                <li>Editions</li>
                <li>Contribute</li>
              </ul>

              <ul>
                <p>EVENTS</p>
                <VImg
                  width="56"
                  height="8"
                  :aspect-ratio="1"
                  src="../../public/images/Divider.png"
                ></VImg>
                <li>Star Gazing</li>
                <li>Desert Mania</li>
                <li>Dunes Madness</li>
                <li>Spooky Land</li>
              </ul>

              <ul>
                <p>CONTACT US</p>
                <VImg
                  width="56"
                  height="8"
                  :aspect-ratio="1"
                  src="../../public/images/Divider.png"
                ></VImg>
                <li>hello@example.com</li>
                <li>(405) 555-0128</li>
                <li>(252) 555-0126</li>
              </ul>
              <div>
                <p>FOLLOW US</p>
                <VImg
                  width="56"
                  height="8"
                  :aspect-ratio="1"
                  src="../../public/images/Divider.png"
                  class="mb-3"
                ></VImg>
                <VIcon icon="mdi-twitter" color="white"></VIcon>
                <VIcon icon="mdi-instagram" color="white" class="mx-3"></VIcon>
                <VIcon icon="mdi-facebook" color="white"></VIcon>
              </div>
            </div>

            <div class="mt-10 d-flex flex-column align-center">
              <div class="text-white">
                <p>Copyright © Night Trips 2019. All rights reserved.</p>
              </div>

              <div>
                <VImg
                  width="60"
                  :aspect-ratio="1"
                  src="../../public/images/Logo.png"
                ></VImg>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import PeopleCard from "../components/PeopleCard.vue";
</script>

<style scoped>
</style>
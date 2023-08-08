<template>
  <section class="hero">
    <div class="position-relative">
      <img src="/assets/images/hero-bg.png" style="width: 100%;" />
      <div>
        <div class="position-absolute text-center text-white w-100 header-text">
          <div class="container-lg">
            <div class="row justify-content-between align-items-center w-100">
              <div class="col-4 text-start">
                <div
                  class="font-weight-700 font-size-xl-40 font-size-lg-36 font-size-md-30 font-size-sm-20 font-size-10"
                >
                  Welcome
                </div>
              </div>
              <div class="col-8 text-end">
                <div
                  class="font-size-xl-21 font-size-lg-18 font-size-md-16 font-size-sm-10 font-size-6 font-weight-400"
                >
                  We <span class="font-weight-700">Focus</span> to help local
                  businesses <br />
                  that specify the products on raw materials local comodities
                  <br />
                  and ingredient platforms to empower <br />
                  and expand sales through domestic and global markets
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="product">
    <div class="image-hero position-relative">
      <img src="/assets/images/product-bg.png" style="width: 100%;" />
      <div class="container">
        <div
          class="position-absolute text-center text-white"
          style="top: 50%; left: 15%; transform: translate(-50%, -50%);"
        >
          <div
            class="py-md-4 px-md-5 px-sm-4 py-sm-3 px-3 py-2"
            style="
              filter: drop-shadow(4px 4px 4px rgba(0, 0, 0, 0.25));
              border: 3px solid white;
            "
          >
            <div
              class="font-size-xl-40 font-size-lg-36 font-size-md-20 font-size-10 font-weight-700 text-center text-p-orange-12"
            >
              New <br />
              Product
            </div>
          </div>
        </div>
        <div
          class="position-absolute"
          style="top: 50%; left: 67%; transform: translate(-50%, -50%);"
        >
          <div class="d-flex justify-content-between list-product">
            <div class="product-item">
              <div class="position-relative product-item-image">
                <div class="bg-p-white">
                    <img src="/assets/images/cengkeh-gapokan.png" />
                </div>
                <div
                  class="img-product-overlay d-flex align-items-center pe-md-4 ps-md-2 pe-1"
                >
                  <p
                    class="text-p-white font-weight-600 text-center font-size-lg-12 font-size-md-10 font-size-4"
                  >
                    Fuli Kelurahan Bunga Harapan Luwu Timur
                  </p>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="position-relative product-item-image">
                <div class="bg-p-white">
                    <img src="/assets/images/full-lpig.png" />
                </div>
                <div
                  class="img-product-overlay d-flex align-items-center pe-md-4 ps-md-2 pe-1"
                >
                  <p
                    class="text-p-white font-weight-600 text-center font-size-lg-12 font-size-md-10 font-size-4"
                  >
                    Fuli Kelurahan Bunga Harapan Luwu Timur
                  </p>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="position-relative product-item-image">
                <div class="bg-p-white">
                    <img src="/assets/images/pala-abcd.png" />
                </div>
                <div
                  class="img-product-overlay d-flex align-items-center pe-md-4 ps-md-2 pe-1"
                >
                  <p
                    class="text-p-white font-weight-600 text-center font-size-lg-12 font-size-md-10 font-size-4"
                  >
                    Fuli Kelurahan Bunga Harapan Luwu Timur
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section>
    <div class="">
      <swiper :navigation="true" :modules="modules" class="mySwiper">
        <swiper-slide>
          <img src="/assets/images/slider-home-01.png" class="w-100" />
        </swiper-slide>
        <swiper-slide>
          <img src="/assets/images/slider-home-02.png" class="w-100" />
        </swiper-slide>
        <swiper-slide>
          <img src="/assets/images/slider-home-3.png" class="w-100" />
        </swiper-slide>
      </swiper>
    </div>
  </section>
  <section class="container mt-5">
    <div
      class="font-size-28 font-weight-600 text-p-green-20 text-center"
      style="text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);"
    >
      Category Product
    </div>
    <div class="row align-items-start py-5 g-5">
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div style="min-width: 220px;">
          <div class="">
            <img
              src="/assets/images/spices.png"
              class="w-100 object-fit-cover"
              style="height: 220px; min-width: 290px;"
            />
          </div>
          <div class="bg-p-green-20 py-3 px-4 text-center">
            <div class="font-weight-700 text-p-white font-size-18">
              Spices
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div style="min-width: 220px;">
          <div class="">
            <img
              src="/assets/images/fishery.png"
              class="w-100 object-fit-cover"
              style="height: 220px; min-width: 290px;"
            />
          </div>
          <div class="bg-p-green-20 py-3 px-4 text-center">
            <div class="font-weight-700 text-p-white font-size-18">
              Fish Meal
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div style="min-width: 220px;">
          <div class="">
            <img
              src="/assets/images/palm_oil.png"
              class="w-100 object-fit-cover"
              style="height: 220px; min-width: 290px;"
            />
          </div>
          <div class="bg-p-green-20 py-3 px-4 text-center">
            <div class="font-weight-700 text-p-white font-size-18">
              Palm Oil
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div style="min-width: 220px;">
          <div class="">
            <img
              src="/assets/images/chinese-med.png"
              class="w-100 object-fit-cover"
              style="height: 220px; min-width: 290px;"
            />
          </div>
          <div class="bg-p-green-20 py-3 px-4 text-center">
            <div class="font-weight-700 text-p-white font-size-18">
              Chinese Med
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Navigation } from "swiper/modules";
import "swiper/css";
import "swiper/css/navigation";

export default {
  name: "Home",
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Navigation],
    };
  },
};
</script>
<style>
.swiper-button-next:after,
.swiper-button-prev:after {
  color: white;
}
</style>

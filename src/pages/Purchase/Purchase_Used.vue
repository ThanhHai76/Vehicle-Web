<template>
  <div>
    <!------ Purchase new section Start ------>
    <div class="impl_purchase_wrapper impl_old_purchase_wrapper">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 col-md-6">
            <div class="impl_sorting_text custom_select">
              <span class="impl_show"> Showing 9 of 68 Results</span>
            </div>
          </div>
          <div class="col-lg-6 col-md-6">
            <div class="impl_category_type">
              <a href="javascript:void(0)" @click="$emit('typeTab', 'NEW')" class="impl_btn">
                New car
              </a>
              <a href="javascript:void(0)" @click="$emit('typeTab', 'USED')" class="impl_btn impl_used_car active">
                Used car
              </a>
            </div>
          </div>
          <div class="col-lg-12 col-md-12">
            <div class="impl_purchase_inner">
              <div class="row">
                <div class="col-lg-3 col-md-4">
                  <div class="impl_sidebar">
                    <div class="impl_product_search widget woocommerce">
                      <div class="impl_footer_subs">
                        <input
                          type="text"
                          class="form-control"
                          placeholder="Search..."
                        />
                        <button class="foo_subs_btn">
                          <i class="fa fa-search" aria-hidden="true"></i>
                        </button>
                      </div>
                    </div>
                    <!--Brands-->
                    <div class="impl_product_brand widget woocommerce">
                      <h2 class="widget-title">brands</h2>
                      <ul>
                        <li>
                          <label class="brnds_check_label">
                            Paradox
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Voyage
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Passion
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Curiosity
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Ivory
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Dawn
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Temper
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Thunder
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Blade
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Origin
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Titan
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Dominion
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Ferocity
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Tempest
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Flow
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Prime
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Grit
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Nimbus
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Essence
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            Aura
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                      </ul>
                    </div>
                    <!--Colors-->
                    <div class="impl_product_color widget woocommerce">
                      <h2 class="widget-title">color</h2>
                      <ul>
                        <li>
                          <label class="brnds_check_label">
                            black
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            blue
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            white
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            yellow
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            red
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            grey
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            brown
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                        <li>
                          <label class="brnds_check_label">
                            orange
                            <input type="checkbox" name="check" />
                            <span class="label-text"></span>
                          </label>
                        </li>
                      </ul>
                    </div>
                    <!--Price Range-->
                    <div class="impl_product_price widget woocommerce">
                      <h2 class="widget-title">price range</h2>
                      <div class="price_range">
                        <!-- <input
                          type="text"
                          id="range_24"
                          name="ionRangeSlider"
                          value=""
                        /> -->
                         <b-form-input id="range-1" v-model="minPrice" type="range" min="1000" max="2000"></b-form-input>
                         <div class="mt-2">Min: {{ minPrice }}</div>
                         <b-form-input id="range-1" v-model="maxPrice" type="range" min="1000" max="2000"></b-form-input>
                         <div class="mt-2">Max: {{ maxPrice }}</div>
                      </div>
                    </div>
                    <!--Car Type-->
                    <div class="impl_product_type widget woocommerce">
                      <h2 class="widget-title">car type</h2>
                      <ul>
                        <li><a href="#">Hatchback</a></li>
                        <li><a href="#">Sedan</a></li>
                        <li><a href="#">MPV</a></li>
                        <li><a href="#">SUV</a></li>
                        <li><a href="#">Couple</a></li>
                        <li><a href="#">Convertible</a></li>
                      </ul>
                    </div>
                  </div>
                </div>
                <div class="col-lg-9 col-md-8">
                  <div class="row">
                    <div class="col-lg-4 col-md-6" v-for="item in dataVehicleList" :key="item.id">
                      <div class="impl_fea_car_box">
                        <div class="impl_fea_car_img" @click="$router.push(`/detail?id=${item.id}`)">
                          <img
                            :src="item.avatar"
                            alt=""
                            class="img-fluid impl_frst_car_img"
                            width="370"
                            height="320"
                          />
                          <img
                            :src="item.subAvatar"
                            alt=""
                            class="img-fluid impl_hover_car_img"
                          />
                          <span class="impl_img_tag" title="compare"
                            ><a href="javascript:void(0)" @click="$router.push(`/detail?id=${item.id}`)"
                              ><i
                                class="fa fa-exchange"
                                aria-hidden="true"
                              ></i></a
                          ></span>
                        </div>
                        <div class="impl_fea_car_data">
                          <h2>
                            <a href="javascript:void(0)" @click="$router.push(`/detail?id=${item.id}`)">
                              {{ item.titleSell }}
                            </a>
                          </h2>
                          <ul>
                            <!-- <li>
                              <span class="impl_fea_title">model</span>
                              <span class="impl_fea_name">Aurora 811</span>
                            </li> -->
                            <li>
                              <span class="impl_fea_title">Nơi bán</span>
                              <span class="impl_fea_name">{{ item.nameCity }}</span>
                            </li>
                            <li>
                              <span class="impl_fea_title">Tình trạng</span>
                              <span class="impl_fea_name">{{ item.statusVehicle }}</span>
                            </li>
                            <li>
                              <span class="impl_fea_title">Năm SX</span>
                              <span class="impl_fea_name">{{ item.manufactureYear }}</span>
                            </li>
                            <li>
                              <span class="impl_fea_title">Số dặm</span>
                              <span class="impl_fea_name">{{ item.odometer | transformNumber }}</span>
                            </li>
                          </ul>
                          <div class="impl_fea_btn">
                            <button class="impl_btn" @click="$router.push(`/detail?id=${item.id}`)">
                              <span class="impl_doller">{{ item.price | formatPriceToText }} </span
                              ><span class="impl_bnw">Mua ngay</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>

                    <!--pagination start-->
                    <div class="col-lg-12 col-md-12">
                      <div class="impl_pagination_wrapper">
                        <nav aria-label="Page navigation example">
                          <ul class="pagination">
                            <li class="page-item">
                              <a class="page-link" href="#"
                                ><i
                                  class="fa fa-angle-left"
                                  aria-hidden="true"
                                ></i
                              ></a>
                            </li>
                            <li class="page-item">
                              <a class="page-link active" href="#">1</a>
                            </li>
                            <li class="page-item">
                              <a class="page-link" href="#">2</a>
                            </li>
                            <li class="page-item">
                              <a class="page-link" href="#">3</a>
                            </li>
                            <li class="page-item">
                              <a class="page-link" href="#"
                                ><i
                                  class="fa fa-angle-right"
                                  aria-hidden="true"
                                ></i
                              ></a>
                            </li>
                          </ul>
                        </nav>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['dataVehicleList'],
  mounted () {

  },
  filters: {
    transformNumber (data) {
      return data ? data.toString().replace(/(\d)(?=(\d{3})+(?!\d))/g, '$1.') : ''
    }
  },
  data () {
    return {
      minPrice: null,
      maxPrice: null
    }
  }
}
</script>

<style scoped>
.impl_fea_car_data ul li span.impl_fea_title {
  width: 50%;
}
.impl_fea_car_img:hover {
  cursor: pointer;
}
</style>

<template>
  <q-page class="q-pa-sm">
    <section style="min-height: 70vh;">
      <q-card class="bg-transparent no-shadow text-center text-white" style="margin-top: 10%">
        <q-card-section>
          <span class="text-body1">Hi, my name is</span>
          <div class="text-h2 q-ma-md text-weight-bolder text-color1">
            Pratik Patel
          </div>
          <div class="text-h2 text-weight-bolder text-color2">
            I build things for the web
          </div>
          <div class="text-subtitle1 text-white q-ma-md">
            I'm a software engineer based in Pune specializing in building websites, applications, and everything in
            between.
          </div>
        </q-card-section>
      </q-card>
    </section>
    <section style="min-height: 30vh;">
      <div ref="about">
        <q-card class="bg-transparent no-shadow row q-col-gutter-sm q-pa-lg  justify-center  text-white">
          <q-card-section class="col-lg-12 col-sm-12 col-md-12 col-xs-12 ">
            <span class="text-h5 text-color2 text-weight-bolder q-ml-xl">01. About Me </span>
            <div class="line"></div>
          </q-card-section>
          <div class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <q-card-section>
              <div class="q-pt-lg text-subtitle1 text-color2 text-justify">
                My name is Pratik Patel (also known as @pratik227). <br/><br/>

                I noticed myself pulling into programming since 2013,
                and then determined myself to become a skilled and knowledgeable programmer.

                <br/><br/>
                I started my career by working with HTML5, CSS3, AngularJS, Vue.js, Elasticsearch, and Python and
                eventually
                introduced myself with
                Quasar-Framework. After getting hands-on experience on Quasar-Framework for 6 years, I got heavily
                involved
                in creating plugins for Quasar Framework such as QHierarchy, Qgrid Quasar App Extension.
              </div>
            </q-card-section>
          </div>
          <div class="col-lg-4 col-sm-12 col-md-4 col-xs-12">
            <q-card-section>
              <!--            <q-img class="q-mt-md"-->
              <!--                   :src="require('src/statics/profile2.jpg')"-->
              <!--                   style="width: 100%;"-->
              <!--                   native-context-menu-->
              <!--            >-->
              <!--              <template v-slot:loading>-->
              <!--                <q-spinner-gears color="white"/>-->
              <!--              </template>-->
              <!--            </q-img>-->

              <q-img class=""
                     :src="require('src/statics/IMG_4832.jpg')"
                     :style="$q.screen.lt.lg?{'width': '100%'}:{'width': '100%'}"/>
            </q-card-section>
          </div>
        </q-card>
      </div>
      <div ref="projects">
        <q-card class="bg-transparent no-shadow row q-col-gutter-lg q-pa-lg justify-center  text-white">
          <q-card-section class="col-lg-12 col-sm-12 col-md-12 col-xs-12 ">
            <span class="text-h5 text-color2 text-weight-bolder q-ml-xl">02. Some Things I've Built </span>
            <div class="line"></div>
          </q-card-section>


          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/quasar_prime.png')"
                     style="width: 100%;"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12  col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar Admin Premium Template
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Quasar Prime
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Quasar Prime Template – Empowering Developers with an Exceptional Vue.js Admin Dashboard

                  Unlock the full potential of your development projects with the Quasar Prime Template – a Vue.js Admin
                  Dashboard that sets the standard for developer-friendly interfaces. Meticulously crafted to adhere to
                  the highest industry standards, this template combines speed, usability, and scalability, providing an
                  unparalleled foundation for creating dynamic and customizable admin dashboards.


                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/Quasar-Admin-Templates/quasar_prime_admin_template"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://quasar-prime-admin-template.netlify.app/analytics"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>

          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Quasar Minimalist Design
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  Quasar Minimalist Design is a premium admin template that offers a range of features and
                  functionalities.
                  To gain access to the code, you'll need to sponsor me for $49 per month (one-time payment).
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-left text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://quasar-minimalist-design.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/QMD.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/Vue-json-excel.png')"
                     style="width: 100%;"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12  col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                NPM Package
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Vue Json Excel
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  JSON to Excel for VUE 3.
                  Download your JSON data as an Excel file directly from the browser.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227/vue3-json-excel"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://vue-json-excel.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>

          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Quasar Admin Premium
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  Looking for beautiful premium Quasar admin template for Vue 3? Please drop me an <a class="text-white"
                                                                                                      href="mailto:pratikpatelpp802@gmail.com">email</a>.
                  Buy only at $69!
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-left text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://quasar-admin-premium.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/Quasar_Admin_Premium.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/Quasar_Admin.png')"
                     style="width: 100%;"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12  col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Quasar Admin Template
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Free Quasar Admin Template based on Vue.js and used Quasar Framework.This template also includes a
                  variety of features that are required for admin template needs. Now Supports Vue2/Vue3.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227/quasar-admin"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://next-quasar-admin.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>

          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Quasar QGrid
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  QGrid is a Quasar App Extension. It allows you to filter data for each column, Drag and Drop Rows and
                  also allows you to filter data using header filters. Now Supports Vue2/Vue3.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-left text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227/quasar-qgrid"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://next-quasar-qgrid.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/QGridNew.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/quasar_echart.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Quasar Echarts
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Demo Project using Quasar and ECharts.It includes multiple charts like Scatter Plot, Bar char, Pie
                  Chart, Guage Chart etc.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227/quasar-echarts"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://quasar-echarts-v5.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Quasar QHierarchy
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  QHierarchy is a Quasar App Extension. It allows you to display data in hierarchy structure on your
                  page. Now Supports Vue2/Vue3.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-left text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227/quasar-qhierarchy"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://next-quasar-qhierarchy.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/QHierarchy.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/qdraggable-tree.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Quasar QDraggableTree
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Contributed to QDraggableTree for Vue js 3 Support. QDraggableTree is a component that displays
                  hierarchical data with drag and drop ability.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://next-quasar-draggable-tree.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Quasar Gaming
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  This Template comes with all the necessary pages for a successful gaming website, like Team, Pricing
                  Plan, Games, Posts so on.

                  So this template is surely going to boost to your business.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-left text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227/quasar-gaming"
                       target="_blank" padding="sm" outline>
                </q-btn>
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://quasar-gaming.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/gaming.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>

          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/skarv-technologies.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar/Vuejs Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Skarv Technologies
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Skarv Technologies develops control and data analysis software, sensor-platforms, and underwater
                  cameras for a wide range of marine applications.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <!--                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"-->
                <!--                       href="https://skarv-technologies.web.app"-->
                <!--                       target="_blank" padding="sm" outline>-->
                <!--                </q-btn>-->
              </div>
            </div>
          </q-card-section>


          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar/Vuejs Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Skarv Technologies
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  Skarv Technologies develops control and data analysis software, sensor-platforms, and underwater
                  cameras for a wide range of marine applications.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-left text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                <!--                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"-->
                <!--                       href="https://map.skarvtech.com"-->
                <!--                       target="_blank" padding="sm" outline>-->
                <!--                </q-btn>-->
              </div>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/map-skarvtech.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>

          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/Kameleon-maling.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar/Vuejs Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Kameleon Maling
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Kameleon Maling specializes in innovative solutions for the world of painting and coatings. We are
                  dedicated to developing cutting-edge paint formulations, application technologies, and surface
                  treatments that transform industries and exceed customer expectations. With a commitment to quality,
                  sustainability, and creative problem-solving, Kameleon Maling is your partner for a colorful future.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <!--                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"-->
                <!--                       href="https://skarv-technologies.web.app"-->
                <!--                       target="_blank" padding="sm" outline>-->
                <!--                </q-btn>-->
              </div>
            </div>
          </q-card-section>

          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-left text-color1">
                Quasar/Vuejs/Python Flask Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-left text-color1">
                Reblue SustainSwift
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style2'">
                <q-card-section>
                  ReBlue Sustainability Integration Solutions is a project dedicated to empowering enterprises to
                  seamlessly integrate sustainability into their core business strategies. The project aims to provide
                  tools and technology solutions that make sustainability efforts both effortless and profitable.
                  Through continuous research and design thinking, we identify and address emerging sustainability
                  challenges, offering innovative solutions that drive growth. We also build an ecosystem of
                  partnerships to deliver comprehensive and optimized sustainability transformations.
                </q-card-section>
              </q-card>

            </div>
          </q-card-section>
          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/reblue.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>



          <q-card-section class="col-lg-7 col-sm-12 col-md-7 col-xs-12">
            <!--          <span class="text-h5 text-color2 text-weight-bolder">01. Some Things I've Built </span>-->
            <div class="q-pt-lg  text-text-subtitle1 text-color2">
              <q-img class="q-mt-md "
                     :src="require('src/statics/Dashboard_Training.png')"
                     style="width: 100%"
                     native-context-menu
              >
                <template v-slot:loading>
                  <q-spinner-gears color="white"/>
                </template>
              </q-img>
            </div>
          </q-card-section>
          <q-card-section class="col-lg-4 col-sm-12 q-mt-lg col-md-4 col-xs-12">
            <div class="q-pt-lg float-right">
              <div class="text-subtitle2 q-ma-sm text-right text-color1">
                Quasar/Vuejs Project
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                Personal Training Program Dashboard
              </div>

              <q-card
                :class="!$q.platform.is.desktop?'card-color2 text-justify':'card-color2 text-justify q-my-xl img-style1'">
                <q-card-section>
                  Personal Training Program Dashboard is a project dedicated to empowering enterprises to seamlessly
                  integrate sustainability into their core business strategies. The project aims to provide tools and
                  technology solutions that make sustainability efforts both effortless and profitable.
                </q-card-section>
              </q-card>

              <div class="text-subtitle1 q-ma-sm text-right text-color1">
                Quasar Vuejs Github
              </div>
              <div class="text-h6 q-ma-sm text-weight-bolder text-right text-color1">
                <q-btn icon="fas fa-external-link-alt" class="q-ml-sm" size="sm" type="a"
                       href="https://66b36d84abac60dbc1d1d2bf--remarkable-youtiao-2e0c87.netlify.app/"
                       target="_blank" padding="sm" outline>
                </q-btn>
              </div>
            </div>
          </q-card-section>

        </q-card>
      </div>
      <div ref="sponsors">
        <q-card class="bg-transparent no-shadow row q-col-gutter-lg q-pa-lg justify-center  text-white">
          <q-card-section class="text-center col-12">
            <span class="text-h5 text-color2 text-weight-bolder">03. Sponsors </span>
            <div class="text-h6 q-ma-md text-weight-bolder text-color1">
              Sponsor me on GitHub Sponsors
              <q-btn icon="fas fa-heart" flat type="a" href="https://github.com/sponsors/pratik227" target="_blank">

              </q-btn>
            </div>
            <div class="text-h2 q-ma-md text-weight-bolder text-color1">
              Sponsors
            </div>
          </q-card-section>
          <q-card-section class="col-12 text-center">
            <img src='https://raw.githubusercontent.com/pratik227/static/main/sponsors.svg'/>
          </q-card-section>
        </q-card>
      </div>

      <div ref="contact">
        <q-card class="bg-transparent no-shadow row q-col-gutter-lg q-pa-lg justify-center  text-white">
          <q-card-section class="text-center">
            <span class="text-h5 text-color2 text-weight-bolder">04. What's Next? </span>
            <div class="text-h2 q-ma-md text-weight-bolder text-color1">
              Get In Touch
            </div>
            <div style="width: 430px" class="text-color2">
              Although I'm not currently looking for any new opportunities, my inbox is always open. Whether you have a
              question or just want to say hi, I'll try my best to get back to you!
            </div>

            <q-btn label="Say Hello" class="q-mt-xl text-capitalize" padding="sm" outline>
              <q-popup-proxy class="q-pa-none" transition-show="flip-up" transition-hide="flip-down" :offset="[10, 10]">
                <q-banner class="card-color2 text-white">
                  <template v-slot:avatar>
                    <q-icon name="mail"/>
                  </template>
                  Mail Address - pratikpatelpp802@gmail.com
                  <br/>
                  Discord - Pratik Patel#9040
                </q-banner>
              </q-popup-proxy>
            </q-btn>
          </q-card-section>
        </q-card>
      </div>
      <q-card class="bg-transparent no-shadow text-white">
        <q-card-section class="text-center">
          <q-btn icon="fab fa-github" size="sm" type="a" href="https://github.com/pratik227"
                 target="_blank" padding="sm" flat>
          </q-btn>
          <q-btn icon="fab fa-codepen" size="sm" type="a" href="https://codepen.io/Pratik__007"
                 target="_blank" padding="sm" flat>
          </q-btn>
          <q-btn icon="fab fa-twitter" size="sm" type="a" href="https://twitter.com/pratikPatel_227"
                 target="_blank" padding="sm" flat></q-btn>
          <q-btn icon="fab fa-medium" size="sm" type="a" href="https://medium.com/@pratikpatel_60309"
                 target="_blank" padding="sm" flat>
          </q-btn>
        </q-card-section>
      </q-card>
    </section>
    <q-page-scroller position="bottom-right" :scroll-offset="150" :offset="[18, 18]">
      <q-btn
        fab size="sm"
        icon="keyboard_arrow_up"
        :class="{ 'text-black bg-transparent': $q.dark.isActive, 'text-white card-color2': !$q.dark.isActive }"
      >
      </q-btn>
    </q-page-scroller>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  methods: {
    go(ref) {
      this.$refs[ref].scrollIntoView({
        behavior: 'smooth',
        block: 'start',
        inline: 'start'
      })
    },
    openurl(url) {
      window.open(url)
    }
  },
  mounted() {
    this.$root.$on('goAbout', this.go.bind(this, 'about'));
    this.$root.$on('goProjects', this.go.bind(this, 'projects'));
    this.$root.$on('goContact', this.go.bind(this, 'contact'));
    this.$root.$on('goSponsors', this.go.bind(this, 'sponsors'))
  }
}
</script>
<style>
.line {
  width: 303px;
  height: 0;
  border: 1px solid #8892b0;
  margin: 3px;
  display: inline-block;
}
</style>

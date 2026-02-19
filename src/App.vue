<template>
  <v-app>
    <!----NAVIGATION BAR---->
    <v-app-bar elevation="0" app>
      <div class="custom-container d-flex align-center h-100">
        <v-app-bar-title class="text-deep-purple-accent-4">Isabella Barbosa</v-app-bar-title>
        <v-list class="d-none d-md-flex bg-transparent">
          <v-list-item class="mx-1" title="Home" href="#home" rounded="xl"></v-list-item>
          <v-list-item class="mx-1" title="About" href="#about" rounded="xl"></v-list-item>
          <v-list-item class="mx-1" title="Projects" href="#projects" rounded="xl"></v-list-item>
          <v-list-item class="mx-1" title="Skills" href="#skills" rounded="xl"></v-list-item>
          <v-list-item class="mx-1" title="Contact" href="#contact" rounded="xl"></v-list-item>
        </v-list>
      </div>
    </v-app-bar>

    <v-main>
      <!----INITIAL SECTION---->
      <div id="home" class="home-section text-center">
        <p class="mb-4 mt-3 mx-auto text-3xl home-title">
          Hi, I'm <span style="color: var(--deep-purple-accent-4)">Isabella</span>
        </p>

        <p
          class="mb-6 mx-auto text-2xl font-weight-medium"
          style="color: var(--blue-grey-darken-1); max-width: 750px"
        >
          Full Stack Developer & Data-Driven Problem Solver
        </p>

        <p
          class="mx-auto text-xl mb-10"
          style="color: var(--blue-grey-lighten-1); max-width: 700px; line-height: 1.6"
        >
          Building intelligent systems with clean architecture and purposeful design
        </p>

        <div class="text-center">
          <v-btn
            href="https://github.com/IsaBarb0sa"
            target="_blank"
            class="btn-shadow"
            size="large"
            icon
          >
            <v-icon color="var(--deep-purple-accent-4)">mdi-github</v-icon>
          </v-btn>

          <v-btn
            href="https://www.linkedin.com/in/isabella-barbosa-9140ba303/"
            target="_blank"
            class="ml-4 btn-shadow"
            size="large"
            icon
          >
            <v-icon color="var(--deep-purple-accent-4)">mdi-linkedin</v-icon>
          </v-btn>

          <v-btn
            href="https://www.instagram.com/isaa_barb0sa"
            target="_blank"
            class="ml-4 btn-shadow"
            size="large"
            icon
          >
            <v-icon color="var(--deep-purple-accent-4)">mdi-instagram</v-icon>
          </v-btn>
        </div>

        <div class="mt-16 text-center">
          <v-btn
            size="x-large"
            icon="mdi-chevron-down"
            color="var(--deep-purple-accent-4)"
            class="scroll-indicator"
            variant="text"
            href="#about"
          ></v-btn>
        </div>
      </div>

      <!----ABOUT ME SECTION---->
      <div id="about" class="text-center section">
        <h1 class="mb-6 font-weight-bold text-h3">About Me</h1>

        <p class="text-body-1 mx-auto" style="max-width: 800px">
          I'm a Computer Science student and Database Analyst with experience in web development,
          data systems, and software architecture.
        </p>
        <p style="max-width: 800px" class="mx-auto mt-4 text-body-1">
          When I'm not coding, I’m exploring new technologies, refining my SQL and backend skills,
          and designing structured systems to solve real-world problems.
        </p>

        <div class="py-16 text-center">
          <v-container>
            <v-row class="mt-4">
              <v-col cols="12" md="4">
                <v-card class="h-100 card project-card">
                  <div class="text-center mt-4 mb-2">
                    <v-avatar color="var(--indigo-lighten-5)" size="80"
                      ><v-icon color="var(--deep-purple-accent-4)" size="40">
                        mdi-unfold-more-vertical
                      </v-icon>
                    </v-avatar>
                  </div>
                  <v-card-title class="font-weight-bold">Clean Code</v-card-title>
                  <v-card-text class="text-body-1 text-grey-darken-1"
                    >Designing structured, maintainable, and scalable systems
                  </v-card-text>
                </v-card>
              </v-col>

              <v-col cols="12" md="4">
                <v-card class="h-100 card project-card">
                  <div class="text-center mt-4 mb-2">
                    <v-avatar color="var(--indigo-lighten-5)" size="80">
                      <v-icon color="var(--deep-purple-accent-4)" size="40"> mdi-laptop </v-icon>
                    </v-avatar>
                  </div>
                  <v-card-title class="font-weight-bold">Full Stack Development</v-card-title>
                  <v-card-text class="text-body-1 text-grey-darken-1"
                    >Building responsive interfaces and robust back-end logic</v-card-text
                  >
                </v-card>
              </v-col>

              <v-col cols="12" md="4">
                <v-card class="h-100 card project-card">
                  <div class="text-center mt-4 mb-2">
                    <v-avatar color="var(--indigo-lighten-5)" size="80">
                      <v-icon color="var(--deep-purple-accent-4)" size="40">
                        mdi-lightning-bolt-outline
                      </v-icon></v-avatar
                    >
                  </div>
                  <v-card-title class="font-weight-bold">Data & Performance</v-card-title>
                  <v-card-text class="text-body-1 text-grey-darken-1"
                    >Creating optimized queries and efficient data-driven applications</v-card-text
                  >
                </v-card>
              </v-col>
            </v-row>
          </v-container>
        </div>
      </div>

      <!----FEATURED PROJECTS SECTION---->
      <div id="projects" class="section-grey">
        <h1 class="text-center mb-6 font-weight-bold text-h3">Featured Projects</h1>

        <v-container>
          <v-row>
            <v-col cols="12" md="6">
              <v-card class="h-100 card">
                <v-card-title class="text-h5 font-weight-bold mt-2">Social Music</v-card-title>
                <v-card-text class="text-body-1 mt-2">
                  Web system developed as a core project for the Web Technology course. It features
                  a social network platform specifically designed for music reviews and ratings.
                </v-card-text>
                <div class="px-4 mb-4">
                  <span class="span">Vue.js</span>
                  <span class="span">PHP</span>
                  <span class="span">MySQL</span>
                </div>
                <v-divider></v-divider>
                <v-card-actions class="px-4 mb-4">
                  <v-btn
                    href="https://socialmusic.vercel.app/"
                    target="_blank"
                    prepend-icon="mdi-open-in-new"
                    color="var(--deep-purple-accent-4)"
                    >Live Demo</v-btn
                  >
                  <v-btn
                    href="https://github.com/brenocoelhos/Backend-SocialMusic"
                    target="_blank"
                    variant="plain"
                    prepend-icon="mdi-github"
                    >Code</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-col>

            <v-col cols="12" md="6">
              <v-card class="h-100 card">
                <v-card-title class="text-h5 font-weight-bold mt-2">
                  User Registration
                </v-card-title>
                <v-card-text class="text-body-1 mt-2">
                  User registration system featuring real-time form validation and Income Tax (IR)
                  calculation. Developed for educational purposes, focusing on implementing complex
                  validation logic using JavaScript, HTML, and CSS.
                </v-card-text>
                <div class="px-4 mb-4">
                  <span class="span">HTML</span>
                  <span class="span">CSS</span>
                  <span class="span">JavaScript</span>
                </div>
                <v-divider></v-divider>
                <v-card-actions class="px-4 mb-4">
                  <v-btn
                    href="https://github.com/IsaBarb0sa/Cadastro_Usuario"
                    target="_blank"
                    variant="plain"
                    prepend-icon="mdi-github"
                    >Code</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-col>
          </v-row>

          <v-row class="mt-8">
            <v-col cols="12" md="6">
              <v-card class="h-100 card">
                <v-card-title class="text-h5 font-weight-bold mt-2">
                  Market Basket Analysis
                </v-card-title>
                <v-card-text class="text-body-1 mt-2">
                  Market basket analysis using the Apriori algorithm to identify association rules
                  between supermarket products.
                </v-card-text>
                <div class="px-4 mb-4">
                  <span class="span">Python</span>
                  <span class="span">Jupyter Notebook</span>
                  <span class="span">Apriori Algorithm</span>
                  <span class="span">Pandas</span>
                </div>
                <v-divider></v-divider>
                <v-card-actions class="px-4 mb-4">
                  <v-btn
                    href="https://github.com/IsaBarb0sa/market-basket-analysis"
                    target="_blank"
                    variant="plain"
                    prepend-icon="mdi-github"
                    >Code</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-col>

            <!----I WILL LEAVE READY FOR FUTURE PROJECTS
            <v-col cols="12" md="6">
              <v-card class="h-100 card px-4">
                <v-card-title class="text-h5 font-weight-bold mt-2">

                </v-card-title>
                <v-card-text class="text-body-1 mt-2">

                </v-card-text>
                <div class="px-4 mb-4">
                  <span class="span"> </span>
                  <span class="span"> </span>
                  <span class="span"> </span>
                  <span class="span"> </span>
                </div>
                <v-divider></v-divider>
                <v-card-actions class="px-4 mb-4">
                  <v-btn
                    href=""
                    target="_blank"
                    prepend-icon=""
                    color="var(--deep-purple-accent-4)"
                    >Live Demo</v-btn
                  >
                  <v-btn
                    href=""
                    target="_blank"
                    variant="plain"
                    prepend-icon=""
                    >Code</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-col>
            ---->
          </v-row>
        </v-container>
      </div>

      <!----SKILLS & TECHNOLOGIES SECTION---->
      <div id="skills" class="section">
        <h1 class="text-center mb-6 font-weight-bold text-h3">Skills & Technologies</h1>

        <v-container>
          <v-row class="mt-8">
            <v-col cols="12" md="4">
              <v-card
                class="card"
                style="border-top: 5px solid var(--deep-purple-accent-4) !important"
              >
                <v-card-title class="text-center text-h5 font-weight-bold mb-4"
                  >Frontend</v-card-title
                >
                <div class="d-flex flex-wrap justify-center gap-2 pa-4">
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >HTML</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >CSS</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >JavaScript</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >Vue.js</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >Vuetify</v-chip
                  >
                </div>
              </v-card>
            </v-col>

            <v-col cols="12" md="4">
              <v-card
                class="card"
                style="border-top: 5px solid var(--blue-grey-darken-1) !important"
              >
                <v-card-title class="text-center text-h5 font-weight-bold mb-4"
                  >Backend</v-card-title
                >
                <div class="d-flex flex-wrap justify-center gap-2 pa-4">
                  <v-chip class="ma-1" color="var(--blue-grey-darken-1)" variant="outlined"
                    >PHP</v-chip
                  >
                  <v-chip class="ma-1" color="var(--blue-grey-darken-1)" variant="outlined"
                    >Java</v-chip
                  >
                  <v-chip class="ma-1" color="var(--blue-grey-darken-1)" variant="outlined"
                    >C</v-chip
                  >
                  <v-chip class="ma-1" color="var(--blue-grey-darken-1)" variant="outlined"
                    >Python</v-chip
                  >
                  <v-chip class="ma-1" color="var(--blue-grey-darken-1)" variant="outlined"
                    >SQLServer</v-chip
                  >
                </div>
              </v-card>
            </v-col>

            <v-col cols="12" md="4">
              <v-card
                class="card"
                style="border-top: 5px solid var(--deep-purple-accent-4) !important"
              >
                <v-card-title class="text-center text-h5 font-weight-bold mb-4"
                  >Tools & Others</v-card-title
                >
                <div class="d-flex flex-wrap justify-center gap-2 pa-4">
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >Figma</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >Totvs/RM</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >Data Analysis</v-chip
                  >
                  <v-chip class="ma-1" color="var(--deep-purple-accent-4)" variant="outlined"
                    >English</v-chip
                  >
                </div>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </div>

      <!----CONTACT SECTION---->
      <div id="contact" class="section-grey">
        <h1 class="text-center mb-6 font-weight-bold text-h3">Get In Touch</h1>

        <v-container>
          <v-row class="mt-8 align-center">
            <v-col cols="12" md="5">
              <p class="text-h5 mb-6 font-weight-regular">
                I'm always open to discussing new projects, creative ideas, or opportunities to be
                part of your vision.
              </p>

              <div class="d-flex align-center mb-4">
                <v-avatar class="elevation-2 mr-4" size="50">
                  <v-icon color="var(--deep-purple-accent-4)">mdi-email-outline</v-icon>
                </v-avatar>
                <span class="text-body-1 font-weight-medium">isabellabarbosa393@gmail.com</span>
              </div>

              <div class="d-flex align-center mb-4">
                <v-avatar class="elevation-2 mr-4" size="50">
                  <v-icon color="var(--deep-purple-accent-4)">mdi-phone-outline</v-icon>
                </v-avatar>
                <span class="text-body-1 font-weight-medium">55+ (32)99967-3903</span>
              </div>

              <div class="d-flex align-center mb-4">
                <v-avatar class="elevation-2 mr-4" size="50">
                  <v-icon color="var(--deep-purple-accent-4)">mdi-map-marker-outline</v-icon>
                </v-avatar>
                <span class="text-body-1 font-weight-medium">Barbacena, MG</span>
              </div>
            </v-col>

            <v-col cols="12" md="6" offset-md="1">
              <v-card class="pa-8 card">
                <v-form ref="contactForm" @submit.prevent="sendEmail">
                  <v-text-field
                    label="Name"
                    v-model="form.name"
                    rounded="lg"
                    color="var(--deep-purple-accent-4)"
                    variant="outlined"
                    :rules="nameRules"
                    required
                  >
                  </v-text-field>

                  <v-text-field
                    label="E-mail"
                    v-model="form.email"
                    rounded="lg"
                    color="var(--deep-purple-accent-4)"
                    variant="outlined"
                    :rules="emailRules"
                    required
                  >
                  </v-text-field>

                  <v-textarea
                    label="Message"
                    v-model="form.message"
                    rounded="lg"
                    color="var(--deep-purple-accent-4)"
                    variant="outlined"
                    :rules="messageRules"
                    required
                  >
                  </v-textarea>

                  <v-btn
                    type="submit"
                    block
                    color="var(--deep-purple-accent-4)"
                    variant="outlined"
                    :loading="loading"
                    text="Send Message"
                  ></v-btn>
                </v-form>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </div>

      <v-footer class="text-center d-flex flex-column py-10" color="grey-lighten-4">
        <div class="mb-4">
          <v-btn
            href="https://github.com/IsaBarb0sa"
            target="_blank"
            icon
            variant="text"
            color="deep-purple-accent-4"
            class="mx-2"
          >
            <v-icon size="28">mdi-github</v-icon>
          </v-btn>

          <v-btn
            href="https://www.linkedin.com/in/isabella-barbosa-9140ba303/"
            target="_blank"
            icon
            variant="text"
            color="deep-purple-accent-4"
            class="mx-2"
          >
            <v-icon size="28">mdi-linkedin</v-icon>
          </v-btn>

          <v-btn
            href="https://www.instagram.com/isaa_barb0sa"
            target="_blank"
            icon
            variant="text"
            color="deep-purple-accent-4"
            class="mx-2"
          >
            <v-icon size="28">mdi-instagram</v-icon>
          </v-btn>
        </div>

        <div class="mb-6">
          <v-btn href="#home" variant="text" class="mx-1 text-capitalize" rounded="xl">Home</v-btn>
          <v-btn href="#about" variant="text" class="mx-1 text-capitalize" rounded="xl"
            >About</v-btn
          >
          <v-btn href="#projects" variant="text" class="mx-1 text-capitalize" rounded="xl"
            >Projects</v-btn
          >
          <v-btn href="#skills" variant="text" class="mx-1 text-capitalize" rounded="xl"
            >Skills</v-btn
          >
          <v-btn href="#contact" variant="text" class="mx-1 text-capitalize" rounded="xl"
            >Contact</v-btn
          >
        </div>

        <div class="text-caption text-medium-emphasis">
          &copy; {{ new Date().getFullYear() }} <strong>Isabella Barbosa</strong>. All rights
          reserved.
        </div>
      </v-footer>

      <!----SNACKBAR FOR FEEDBACK ON SUBMISSION---->
      <v-snackbar
        v-model="snackbar.show"
        :color="snackbar.color"
        :timeout="4000"
        location="top right"
      >
        <div class="text-center">{{ snackbar.text }}</div>
      </v-snackbar>
    </v-main>
  </v-app>
</template>

<script setup>
// Necessary imports
import { ref, reactive } from 'vue'
import emailjs from '@emailjs/browser'

// Loading state for the submit button
const loading = ref(false)

// Reference for the contact form
const contactForm = ref(null)

// State for the feedback snackbar
const snackbar = reactive({
  show: false,
  text: '',
  color: 'success',
})

// Contact form data
const form = reactive({
  name: '',
  email: '',
  message: '',
})

// Validation rules
const nameRules = [
  (v) => !!v || 'Required',
  (v) => (v && v.length >= 3) || 'Name must be at least 3 characters',
]

const emailRules = [(v) => !!v || 'Required', (v) => /.+@.+\..+/.test(v) || 'Invalid e-mail']

const messageRules = [
  (v) => !!v || 'Required',
  (v) => (v && v.length >= 10) || 'Message must be at least 10 characters',
]

// Function to send the email using EmailJS
const sendEmail = async () => {
  const { valid } = await contactForm.value.validate()
  if (!valid) {
    return
  }

  loading.value = true

  // EmailJS credentials
  const serviceID = import.meta.env.VITE_EMAILJS_SERVICE_ID
  const templateID = import.meta.env.VITE_EMAILJS_TEMPLATE_ID
  const publicKey = import.meta.env.VITE_EMAILJS_PUBLIC_KEY

  // Template parameters
  const templateParams = {
    name: form.name,
    email: form.email,
    message: form.message,
  }

  // Send e-mail
  emailjs
    .send(serviceID, templateID, templateParams, publicKey)
    .then(() => {
      snackbar.text = 'Message sent successfully!'
      snackbar.color = 'success'
      snackbar.show = true
      // Clear the form after sending
      form.name = ''
      form.email = ''
      form.message = ''
      // Reset form validation
      contactForm.value.resetValidation()
    })
    .catch((error) => {
      console.error('Failed to send:', error)
      snackbar.text = 'Something went wrong. Please try again.'
      snackbar.color = 'error'
      snackbar.show = true
    })
    .finally(() => {
      loading.value = false
    })
}
</script>

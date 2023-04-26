<template>
  <section id="portfolio" class="bg-light py-5">
    <div class="container">
      <h2 class="text-center">Portfolio</h2>
      <p class="text-center">Check out my latest projects</p>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="/image/GitHub-Logo.png" alt="Project 1" class="card-img-top" />
            <div class="card-body">
              <h5 class="card-title">Bots Creations - Freya IA</h5>
              <p class="card-text">
                A Personal Project for Disabled Individuals: Aims to Assist Them in Utilizing Technology through
                Speech-to-Text and Text-to-Speech Functionality, as well as ChatGpt4 Integration, Web Scraping, and Custom
                Commands.
              </p>
              <p>
                <a href="">For more details on our Freya IA, click here</a>
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="/image/Landings.png" alt="Project 2" class="card-img-top" />
            <div class="card-body">
              <h5 class="card-title">Landings Creation</h5>
              <p class="card-text">
                Landings and app for edugami
              </p>
              <p>
                <a target="blank" href="https://www.edugami.pro">Take a look</a>
              </p>
              <small class="card-text">
                For confidentiality reasons, I cannot give you full access to the project.
              </small>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="/image/Dashboard.png" alt="Project 3" class="card-img-top" />
            <div class="card-body">
              <h5 class="card-title">Metric Dashboard Project</h5>
              <p class="card-text">
                This is an SPA project dedicated to obtaining metrics about all the products being sold and their containers. The technologies used include Vue, Vuetify, and ApexChart.
              </p>
              <small class="card-text">
                For confidentiality reasons, I cannot give you full access to the project.
              </small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts" setup>

//Fetch new proyects from backend

// --->




interface Project {
  _id: string;
  name: string;
  link: string;
  image: string;
}


//Pending backend portfolio - this will be building with nestjs and graphql

const proyects: Project[] = [
  {
    name: '1',
    _id: '2',
    link: '3',
    image: '4'
  }

]


</script>
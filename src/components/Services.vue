<template>
  <!-- Services section -->
  <section id="services" class="section" style="margin-top: 50px;">
    <h2>Services Offered</h2>
    <div class="container">
      <!-- Services section -->
      <div class="services-container">
        <!-- Individual services -->
        <div class="service">
          <img src="@/assets/img/Services/service1.jpg" alt="Service 1" />
          <h3>Preventive Care</h3>
            <p>
              We believe that prevention is better than cure. Our preventive care services include vaccinations, wellness exams, parasite prevention, and tailored health plans for your pet's unique needs.
            </p>
        </div>
        <div class="service">
          <img src="@/assets/img/Services/service2.jpg" alt="Service 2" />
          <h3>Diagnostics</h3>
            <p>
              Our advanced diagnostic tools and technology allow us to detect and treat a wide range of illnesses and conditions early, ensuring the best possible outcome for your pet.
            </p>
        </div>
        <div class="service">
          <img src="@/assets/img/Services/service3.jpg" alt="Service 3" />
          <h3>Surgery</h3>
            <p>
              Our skilled veterinarians are experienced in performing a variety of surgical procedures, from routine spays and neuters to more complex soft tissue and orthopedic surgeries.
            </p>
        </div>
        <div class="service">
          <img src="@/assets/img/Services/service4.jpg" alt="Service 4" />
          <h3>Dental Care</h3>
            <p>
              Good oral health is crucial for your pet's overall well-being. Our comprehensive dental care services include dental cleanings, extractions, and preventive measures to keep your pet's mouth healthy and pain-free.
            </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ServicesSection',
};
</script>

<style scoped>
.section {
  text-align: center;
  padding: 50px 0;
}

.services-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.service {
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 5px;
  background-color: #f8f8f8;
  overflow: hidden;
}

.service img {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 5px;
  margin-bottom: 1rem;
}

.service h3 {
  margin-bottom: 10px;
}

@media (max-width: 768px) {
  .services-container {
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  }
}
</style>

<template>
  <div class="main">
    <HeaderComponent />
    <main>
      <HeroComponent />

      <FeatureSection />

      <section class="cta section">
        <div class="container">
          <div class="cta-inner section-inner">
            <h3 class="section-title mt-0">Still not convinced on buying?</h3>
            <div class="cta-cta">
              <a class="button button-primary button-wide-mobile" href="#"
                >Get in touch</a
              >
            </div>
          </div>
        </div>
      </section>
    </main>

    <FooterComponent />
  </div>
</template>

<script setup>
try {
  const {
    data: [landingData],
  } = await $fetch("http://localhost:1337/api/landing-pages?populate=*");

  useHead({
    title: landingData.title,
  });
} catch (error) {
  console.log(error);
}
</script>

<style scoped>
.cta {
  text-align: center;
}
.cta .section-inner {
  padding: 48px 16px;
}
.cta .section-title {
  margin-bottom: 40px;
}
.cta-inner {
  position: relative;
  background: #15181d;
  overflow: hidden;
}
.cta-inner::before {
  content: "";
  position: absolute;
  right: 98px;
  top: -117px;
  width: 160px;
  height: 187px;
  background-image: url("../images/cta-illustration.svg");
  background-repeat: no-repeat;
}
.cta-inner > * {
  position: relative;
}
@media (min-width: 641px) {
  .cta {
    text-align: left;
  }
  .cta .section-inner {
    padding: 64px 32px;
  }
  .cta .section-title {
    margin-bottom: 0;
    padding-right: 24px;
  }
  .cta-inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
}
</style>

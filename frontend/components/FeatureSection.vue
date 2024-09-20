<template>
  <section class="features section">
    <div class="container">
      <div class="features-inner section-inner has-bottom-divider">
        <div class="features-wrap">
          <div class="feature text-center is-revealing">
            <div class="feature-inner">
              <div class="feature-icon">
                <img
                  src="@/assets/images/feature-icon-01.svg"
                  alt="Feature 01"
                />
              </div>
              <h4 class="feature-title mt-24">Be Productive</h4>
              <p class="text-sm mb-0">
                Fermentum posuere urna nec tincidunt praesent semper feugiat
                nibh. A arcu cursus vitae congue mauris. Nam at lectus urna duis
                convallis. Mauris rhoncus aenean vel elit scelerisque mauris.
              </p>
            </div>
          </div>
          <div class="feature text-center is-revealing">
            <div class="feature-inner">
              <div class="feature-icon">
                <img
                  src="@/assets/images/feature-icon-02.svg"
                  alt="Feature 02"
                />
              </div>
              <h4 class="feature-title mt-24">Be Productive</h4>
              <p class="text-sm mb-0">
                Fermentum posuere urna nec tincidunt praesent semper feugiat
                nibh. A arcu cursus vitae congue mauris. Nam at lectus urna duis
                convallis. Mauris rhoncus aenean vel elit scelerisque mauris.
              </p>
            </div>
          </div>
          <div class="feature text-center is-revealing">
            <div class="feature-inner">
              <div class="feature-icon">
                <img
                  src="@/assets/images/feature-icon-03.svg"
                  alt="Feature 03"
                />
              </div>
              <h4 class="feature-title mt-24">Be Productive</h4>
              <p class="text-sm mb-0">
                Fermentum posuere urna nec tincidunt praesent semper feugiat
                nibh. A arcu cursus vitae congue mauris. Nam at lectus urna duis
                convallis. Mauris rhoncus aenean vel elit scelerisque mauris.
              </p>
            </div>
          </div>
          <div class="feature text-center is-revealing">
            <div class="feature-inner">
              <div class="feature-icon">
                <img
                  src="@/assets/images/feature-icon-04.svg"
                  alt="Feature 04"
                />
              </div>
              <h4 class="feature-title mt-24">Be Productive</h4>
              <p class="text-sm mb-0">
                Fermentum posuere urna nec tincidunt praesent semper feugiat
                nibh. A arcu cursus vitae congue mauris. Nam at lectus urna duis
                convallis. Mauris rhoncus aenean vel elit scelerisque mauris.
              </p>
            </div>
          </div>
          <div class="feature text-center is-revealing">
            <div class="feature-inner">
              <div class="feature-icon">
                <img
                  src="@/assets/images/feature-icon-05.svg"
                  alt="Feature 05"
                />
              </div>
              <h4 class="feature-title mt-24">Be Productive</h4>
              <p class="text-sm mb-0">
                Fermentum posuere urna nec tincidunt praesent semper feugiat
                nibh. A arcu cursus vitae congue mauris. Nam at lectus urna duis
                convallis. Mauris rhoncus aenean vel elit scelerisque mauris.
              </p>
            </div>
          </div>
          <div class="feature text-center is-revealing">
            <div class="feature-inner">
              <div class="feature-icon">
                <img
                  src="@/assets/images/feature-icon-06.svg"
                  alt="Feature 06"
                />
              </div>
              <h4 class="feature-title mt-24">Be Productive</h4>
              <p class="text-sm mb-0">
                Fermentum posuere urna nec tincidunt praesent semper feugiat
                nibh. A arcu cursus vitae congue mauris. Nam at lectus urna duis
                convallis. Mauris rhoncus aenean vel elit scelerisque mauris.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.features-wrap {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  margin-right: -32px;
  margin-left: -32px;
}
.features-wrap:first-of-type {
  margin-top: -16px;
}
.features-wrap:last-of-type {
  margin-bottom: -16px;
}
.feature {
  padding: 16px 32px;
  width: 380px;
  max-width: 380px;
  flex-grow: 1;
}
.feature-inner {
  height: 100%;
}
.feature-icon {
  display: flex;
  justify-content: center;
}
@media (min-width: 641px) {
  .features-wrap:first-of-type {
    margin-top: -24px;
  }
  .features-wrap:last-of-type {
    margin-bottom: -24px;
  }
  .feature {
    padding: 32px 32px;
  }
}
</style>

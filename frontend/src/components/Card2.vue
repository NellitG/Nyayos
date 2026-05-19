<template>
  <div
    class="min-h-screen bg-gradient-to-br from-gray-50 via-white to-gray-100 py-16 mt-16"
  >
    <!-- Decorative Background Elements -->
    <div class="absolute inset-0 overflow-hidden pointer-events-none">
      <div
        class="absolute -top-40 -right-40 w-80 h-80 bg-yellow-200 rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob"
      ></div>
      <div
        class="absolute -bottom-40 -left-40 w-80 h-80 bg-blue-200 rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob animation-delay-2000"
      ></div>
    </div>

    <div class="relative max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Hero Section with Logo and Tagline -->
      <div class="text-center mb-16">
        <div class="inline-block animate-fade-in-up">
          <div class="flex justify-center mb-6">
            <div class="relative">
              <div
                class="absolute inset-0 bg-yellow-400 rounded-full blur-2xl opacity-30 animate-pulse"
              ></div>
              <img
                src="https://pikaso.cdnpk.net/private/production/4344532521/render.jpg?token=exp=1779408000~hmac=b31a8b17d71377f22b0c9423bedaeb2d70933b239aed2bc42b33dc37894d6eb3&preview=true"
                alt="Nyayo Foundation Logo"
                class="w-40 h-40 md:w-48 md:h-48 object-cover rounded-full shadow-2xl border-4 border-white relative z-10"
              />
            </div>
          </div>
          <h1
            class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 mb-4 font-finger-paint"
          >
            Nyayo's <span class="text-yellow-500">Foundation</span>
          </h1>
          <p class="text-xl md:text-2xl text-gray-600 max-w-3xl mx-auto">
            Where Disability Meets Capability
          </p>
        </div>
      </div>

      <!-- Main Content Grid -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-start">
        <!-- Left Column: Stats & Impact -->
        <div class="space-y-8 animate-fade-in-up animation-delay-300">
          <div
            class="bg-white rounded-2xl shadow-xl p-8 border-l-8 border-yellow-500 hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1"
          >
            <div class="flex items-center justify-between mb-4">
              <div class="text-4xl font-bold text-yellow-500">2024</div>
              <div
                class="w-12 h-12 bg-yellow-100 rounded-full flex items-center justify-center"
              >
                <svg
                  class="w-6 h-6 text-yellow-600"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                  ></path>
                </svg>
              </div>
            </div>
            <h3 class="text-xl font-semibold text-gray-800 mb-2">
              Established
            </h3>
            <p class="text-gray-600">
              Founded in Nairobi, Kenya, with a mission to transform digital
              education access
            </p>
          </div>

          <div
            class="bg-gradient-to-br from-yellow-50 to-blue-50 rounded-2xl shadow-xl p-8 hover:shadow-2xl transition-all duration-300"
          >
            <div class="flex items-center gap-3 mb-4">
              <div
                class="w-10 h-10 bg-yellow-500 rounded-lg flex items-center justify-center"
              >
                <svg
                  class="w-5 h-5 text-white"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M13 10V3L4 14h7v7l9-11h-7z"
                  ></path>
                </svg>
              </div>
              <h3 class="text-xl font-semibold text-gray-800">Our Impact</h3>
            </div>
            <p class="text-gray-700 leading-relaxed">
              Creating lasting change by ensuring no child is left behind,
              providing resources and opportunities for academic and life
              success.
            </p>
          </div>

          <div
            class="bg-white rounded-2xl shadow-xl p-8 border-t-4 border-blue-500"
          >
            <div class="flex items-center gap-3 mb-4">
              <div
                class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center"
              >
                <svg
                  class="w-6 h-6 text-blue-600"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"
                  ></path>
                </svg>
              </div>
              <h3 class="text-xl font-semibold text-gray-800">
                Our Commitment
              </h3>
            </div>
            <p class="text-gray-700 leading-relaxed">
              Fostering a culture of continuous learning, personal growth, and
              empowerment for differently-abled children.
            </p>
          </div>
        </div>

        <!-- Right Column: Mission Text -->
        <div class="space-y-6 animate-fade-in-up animation-delay-600">
          <div
            class="bg-white rounded-2xl shadow-xl p-8 hover:shadow-2xl transition-shadow duration-300"
          >
            <div class="flex items-center gap-3 mb-6">
              <div class="w-1 h-12 bg-yellow-500 rounded-full"></div>
              <h2 class="text-2xl font-bold text-gray-800">Our Story</h2>
            </div>
            <div class="space-y-4 text-gray-700 leading-relaxed">
              <p
                class="first-letter:text-4xl first-letter:font-bold first-letter:text-yellow-500 first-letter:mr-2"
              >
                Nyayo's Foundation, established in 2024 in Nairobi, Kenya, is
                dedicated to transforming the lives of differently-abled
                children by providing them with access to digital education.
              </p>

              <div
                class="bg-gray-50 p-6 rounded-xl border-l-4 border-yellow-500 my-6"
              >
                <p class="text-gray-800 font-medium italic">
                  "In Africa, disability often translates to invisibility in the
                  classroom. At Nyayo's Foundation, we believe that a lack of a
                  system that suits special learners does not mean those
                  learners are incapable. We are building the bridge between
                  exclusion and academic integrity through technology."
                </p>
              </div>

              <p>
                Recognizing the educational barriers faced by children with
                disabilities in underserved communities, our foundation strives
                to bridge the gap by offering inclusive and accessible learning
                opportunities.
              </p>

              <p>
                We are committed to empowering these children with the tools,
                resources, and support they need to thrive in a digital world,
                ensuring that every child has the chance to succeed, regardless
                of their abilities.
              </p>

              <p>
                At the heart of our mission is the belief that education is a
                fundamental right for all. Through our technology-driven
                initiatives, we aim to create an inclusive educational
                environment where children with disabilities can reach their
                full potential.
              </p>

              <div
                class="bg-gradient-to-r from-yellow-500 to-blue-600 text-white p-6 rounded-xl mt-6"
              >
                <p class="font-semibold text-lg mb-2">Our Promise</p>
                <p class="leading-relaxed">
                  Nyayo's Foundation is driven by a passion to make a meaningful
                  difference in these children's lives, fostering a culture of
                  continuous learning, personal growth, and empowerment. We are
                  committed to creating lasting change by ensuring that no child
                  is left behind, providing them with the resources and
                  opportunities to succeed both academically and in life.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Call to Action Section -->
      <div class="mt-16 text-center animate-fade-in-up animation-delay-900">
        <div
          class="bg-gradient-to-r from-yellow-500 to-blue-600 rounded-2xl shadow-xl p-10 text-white"
        >
          <h3 class="text-2xl md:text-3xl font-bold mb-4">
            Join Us in Making a Difference
          </h3>
          <p class="text-lg mb-6 opacity-95">
            Together, we can build a more inclusive future for every child.
          </p>
          <router-link to="/Donations">
            <button
              class="bg-white text-blue-600 px-8 py-3 rounded-full font-semibold hover:shadow-lg transform hover:-translate-y-1 transition-all duration-300"
            >
              Donate
            </button>
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NyayoFoundation",
};
</script>

<style scoped>
@keyframes blob {
  0% {
    transform: translate(0px, 0px) scale(1);
  }
  33% {
    transform: translate(30px, -50px) scale(1.1);
  }
  66% {
    transform: translate(-20px, 20px) scale(0.9);
  }
  100% {
    transform: translate(0px, 0px) scale(1);
  }
}

.animate-blob {
  animation: blob 7s infinite;
}

.font-finger-paint {
  font-family: 'Finger Paint', cursive;
}

.animation-delay-2000 {
  animation-delay: 2s;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in-up {
  animation: fadeInUp 0.6s ease-out forwards;
  opacity: 0;
}

.animation-delay-300 {
  animation-delay: 0.3s;
}

.animation-delay-600 {
  animation-delay: 0.6s;
}

.animation-delay-900 {
  animation-delay: 0.9s;
}
</style>

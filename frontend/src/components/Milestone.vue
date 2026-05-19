<template>
  <section class="relative py-24 lg:py-12 mt-20 overflow-hidden">
    <div class="relative z-10 px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <!-- Hero Section -->
      <div class="max-w-4xl mx-auto text-center mb-20 lg:mb-32">
        <div class="relative inline-block mb-6">
          <div
            class="absolute inset-0 bg-gradient-to-r from-yellow-500 to-orange-500 blur-xl opacity-70 animate-pulse-glow"
          ></div>
        </div>

        <h1
          class="text-5xl sm:text-6xl lg:text-5xl xl:text-5xl font-bold mb-6 bg-yellow-400 bg-clip-text text-transparent animate-gradient-x"
          style="font-family: 'Finger Paint', cursive;"
        >
          A New Journey
          <br />
          <span class="text-gray-950 font-semibold">Begins</span>
        </h1>

        <div class="relative flex justify-center mb-8">
          <div
            class="w-24 h-1 bg-gradient-to-r from-yellow-500 to-orange-500 rounded-full"
          ></div>
          <div
            class="absolute w-12 h-1 bg-yellow-400 rounded-full animate-pulse-glow"
          ></div>
        </div>

        <p
          class="text-xl lg:text-2xl text-gray-900 leading-relaxed max-w-3xl mx-auto"
          style="font-family: 'Finger Paint', cursive;"
        >
          Guided by a vision to shape a brighter future for children, we are on
          a steadfast journey to create meaningful, lasting change across
          Africa.
        </p>
      </div>

      <!-- Premium Timeline Grid -->
      <div class="relative">
        <!-- Connecting Line -->
        <div
          class="absolute left-1/2 transform -translate-x-1/2 w-0.5 h-full bg-yellow-500 lg:block"
        ></div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12">
          <!-- Steps -->
          <div
            class="relative animate-float-up"
            v-for="(step, index) in steps"
            :key="index"
            :class="{ 'lg:translate-y-12': index % 2 === 1 }"
          >
            <!-- Card Glow Effect (Always visible) -->
            <div
              class="absolute inset-0 bg-yellow-500/20 rounded-2xl blur-xl"
            ></div>

            <div
              class="relative bg-white/5 backdrop-blur-xl border border-white/10 rounded-2xl p-8"
            >
              <!-- Number Badge -->
              <div class="absolute -top-4 -left-4">
                <div
                  class="w-12 h-12 bg-yellow-500 rounded-xl flex items-center justify-center shadow-2xl"
                >
                  <span class="text-2xl font-bold text-white">{{
                    step.number
                  }}</span>
                </div>
              </div>

              <!-- Icon -->
              <div class="mb-6 text-5xl">
                {{ step.icon }}
              </div>

              <h3
                class="text-2xl font-bold text-gray-950 mb-4"
                style="font-family: 'Finger Paint', cursive;"
              >
                {{ step.title }}
              </h3>

              <p class="text-gray-950 leading-relaxed">
                {{ step.description }}
              </p>

              <!-- Decorative Line (Always full width) -->
              <div
                class="mt-6 w-full h-0.5 bg-gradient-to-r from-yellow-500 to-transparent"
              ></div>
            </div>
          </div>
        </div>
      </div>

      <!-- Button -->
      <div class="flex justify-center mt-10">
        <a
          href="https://drive.google.com/file/d/1t8v48ofPTpmARzIA3fJpu9BBOyWxRYdK/view?usp=sharing"
          target="_blank"
          rel="noopener noreferrer"
          class="inline-flex items-center gap-2 px-10 py-4 rounded-full font-bold text-white text-lg bg-blue-950 hover:bg-yellow-500 transition-all duration-300"
        >
          <span>Partner with us</span>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "JourneySection",
  data() {
    return {
      steps: [
        {
          number: "01",
          icon: "🤝",
          title: "Strategic Partnerships",
          description:
            "Forging powerful collaborations with global organizations, governments, and communities to amplify our mission and create sustainable change for differently-abled children.",
        },
        {
          number: "02",
          icon: "🌍",
          title: "Pan-African Expansion",
          description:
            "Expanding our transformative impact across Kenya and 10+ African countries by 2030, fostering inclusivity and empowering communities on a continental scale.",
        },
        {
          number: "03",
          icon: "🏆",
          title: "Global Leadership",
          description:
            "Becoming a world-class advocate for differently-abled children through centers of excellence, policy shaping, and groundbreaking innovation in inclusive education.",
        },
        {
          number: "04",
          icon: "🛠️",
          title: "Adaptive Technology",
          description:
            "Deploying cutting-edge assistive digital devices and AI-powered software tailored to specific learning needs and cognitive abilities.",
        },
        {
          number: "05",
          icon: "👩‍🏫",
          title: "Empowered Educators",
          description:
            "Training 1,000+ teachers in inclusive digital pedagogy, ensuring sustainable skills transfer and lasting community impact.",
        },
        {
          number: "06",
          icon: "📚",
          title: "Personalized Learning",
          description:
            "Developing individualized education plans for 10,000+ special needs students, unlocking their full potential and transforming futures.",
        },
      ],
    };
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Finger+Paint&display=swap");

/* Animations */
@keyframes orb-1 {
  0%,
  100% {
    transform: translate(0, 0) scale(1);
    opacity: 0.3;
  }
  50% {
    transform: translate(100px, 50px) scale(1.2);
    opacity: 0.5;
  }
}

@keyframes orb-2 {
  0%,
  100% {
    transform: translate(0, 0) scale(1);
    opacity: 0.3;
  }
  50% {
    transform: translate(-100px, -50px) scale(1.3);
    opacity: 0.5;
  }
}

@keyframes orb-3 {
  0%,
  100% {
    transform: translate(-50%, -50%) scale(1);
    opacity: 0.2;
  }
  50% {
    transform: translate(-50%, -50%) scale(1.1);
    opacity: 0.3;
  }
}

@keyframes gradient-x {
  0%,
  100% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
}

@keyframes pulse-glow {
  0%,
  100% {
    opacity: 0.7;
    transform: scale(1);
  }
  50% {
    opacity: 1;
    transform: scale(1.1);
  }
}

@keyframes float-up {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes float {
  0%,
  100% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-20px);
  }
}

@keyframes bounce {
  0%,
  100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
}

/* Animation Classes */
.animate-orb-1 {
  animation: orb-1 15s ease-in-out infinite;
}
.animate-orb-2 {
  animation: orb-2 18s ease-in-out infinite;
}
.animate-orb-3 {
  animation: orb-3 20s ease-in-out infinite;
}
.animate-gradient-x {
  background-size: 200% 200%;
  animation: gradient-x 3s ease infinite;
}
.animate-pulse-glow {
  animation: pulse-glow 2s ease-in-out infinite;
}
.animate-float-up {
  animation: float-up 0.8s ease-out forwards;
  opacity: 0;
  animation-fill-mode: forwards;
}
.animate-float {
  animation: float 6s ease-in-out infinite;
}
.animate-bounce {
  animation: bounce 2s ease-in-out infinite;
}

/* Stagger animation delays */
.animate-float-up:nth-child(1) {
  animation-delay: 0.1s;
}
.animate-float-up:nth-child(2) {
  animation-delay: 0.2s;
}
.animate-float-up:nth-child(3) {
  animation-delay: 0.3s;
}
.animate-float-up:nth-child(4) {
  animation-delay: 0.4s;
}
.animate-float-up:nth-child(5) {
  animation-delay: 0.5s;
}
.animate-float-up:nth-child(6) {
  animation-delay: 0.6s;
}

.animation-delay-2000 {
  animation-delay: 2s;
}

/* Custom Scrollbar */
::-webkit-scrollbar {
  width: 10px;
}

::-webkit-scrollbar-track {
  background: #1e1b4b;
}

::-webkit-scrollbar-thumb {
  background: linear-gradient(135deg, #f59e0b, #ea580c);
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: linear-gradient(135deg, #fbbf24, #f97316);
}

/* Glassmorphism Enhancement */
.backdrop-blur-xl {
  backdrop-filter: blur(24px);
}

/* Responsive Design */
@media (max-width: 1024px) {
  .lg\:translate-y-12 {
    transform: translateY(0);
  }
}
</style>

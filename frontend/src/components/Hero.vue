<template>
  <div class="bg-gray-50 py-4 mt-24 overflow-hidden">
    <div class="container mx-auto px-6">
      <!-- Existing Hero Section -->
      <div class="flex flex-col md:flex-row items-center">
        <!-- Left Images with staggered animations -->
        <div class="flex flex-col space-y-4 md:w-1/4">
          <div class="animate__animated animate__fadeInLeft animate__delay-1s">
            <img
              src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504818/smile_gfi32v.avif"
              alt="Nature Image 1"
              class="rounded-lg shadow-md hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="animate__animated animate__fadeInLeft animate__delay-2s">
            <img
              src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504820/water_tnsmov.avif"
              alt="Nature Image 2"
              class="rounded-lg shadow-md hover:scale-105 transition-transform duration-300"
            />
          </div>
        </div>

        <!-- Hero Content with animations -->
        <div class="text-center md:text-left md:w-1/2 md:px-8">
          <div class="animate__animated animate__fadeInUp">
            <h1
              class="text-6xl text-center font-bold text-yellow-500 hover:scale-105 transition-transform duration-300"
              style="font-family: 'Finger Paint', cursive;"
            >
              Nyayo's<br /><span class="text-blue-900 font-semibold"
                >Foundation</span
              >
            </h1>
          </div>

          <div class="animate__animated animate__zoomIn animate__delay-1s">
            <h1
              class="text-4xl mt-2 text-center text-white bg-gradient-to-r from-blue-500 to-yellow-500 p-4 rounded-lg shadow-lg hover:shadow-xl transition-all duration-300"
              style="font-family: 'Finger Paint', cursive;"
            >
              Disability translates to invisibility
            </h1>
          </div>

          <div
            class="mt-6 flex xl:justify-center md:justify-start space-x-4 justify-center"
          >
            <router-link
              to="/aboutus"
              class="relative bg-blue-900 border border-gray-300 text-white px-6 py-2 rounded overflow-hidden group hover:shadow-lg transition-all duration-300 animate__animated animate__fadeInLeft animate__delay-2s"
            >
              <span class="relative z-10">Join us</span>
              <span
                class="absolute inset-0 bg-yellow-500 transform translate-y-full group-hover:translate-y-0 transition-transform duration-300"
              ></span>
            </router-link>

            <router-link
              to="/Donations"
              class="relative bg-blue-900 text-white px-6 py-2 rounded overflow-hidden group hover:shadow-lg transition-all duration-300 animate__animated animate__fadeInUp animate__delay-2s"
            >
              <span class="relative z-10">Donate</span>
              <span
                class="absolute inset-0 bg-yellow-500 transform translate-y-full group-hover:translate-y-0 transition-transform duration-300"
              ></span>
            </router-link>

            <a
              href="https://drive.google.com/file/d/1t8v48ofPTpmARzIA3fJpu9BBOyWxRYdK/view?usp=sharing"
              target="_blank"
              rel="noopener noreferrer"
              class="relative bg-blue-900 text-white px-6 py-2 rounded overflow-hidden group hover:shadow-lg transition-all duration-300 animate__animated animate__fadeInRight animate__delay-2s"
            >
              <span class="relative z-10">Partner with us</span>
              <span
                class="absolute inset-0 bg-yellow-500 transform translate-y-full group-hover:translate-y-0 transition-transform duration-300"
              ></span>
            </a>
          </div>
        </div>

        <!-- Right Images with staggered animations -->
        <div class="flex flex-col space-y-4 md:w-1/4 mt-4 md:mt-0">
          <div class="animate__animated animate__fadeInRight animate__delay-1s">
            <img
              src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504817/playing_vxx3s8.avif"
              alt="Nature Image 3"
              class="rounded-lg shadow-md hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="animate__animated animate__fadeInRight animate__delay-2s">
            <img
              src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504748/healthcare_enrn5m.jpg"
              alt="Nature Image 4"
              class="rounded-lg shadow-md hover:scale-105 transition-transform duration-300"
            />
          </div>
        </div>
      </div>

      <!-- NEW SECTION 1: The Crisis Statistic -->
      <div class="mt-20 animate__animated animate__fadeInUp animate__delay-3s">
        <div class="bg-blue-50 rounded-2xl p-8 shadow-lg">
          <div class="text-center mb-6">
            <span
              class="text-orange-500 font-semibold text-sm uppercase tracking-wider"
              >The Crisis</span
            >
            <h2 class="text-3xl font-bold text-gray-800 mt-2">
              Understanding the Challenge
            </h2>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
            <!-- Statistic Visual -->
            <div class="relative">
              <div class="relative w-64 h-64 mx-auto">
                <!-- Outer Circle (Total) -->
                <svg class="w-full h-full transform -rotate-90">
                  <circle
                    cx="128"
                    cy="128"
                    r="100"
                    fill="none"
                    stroke="#e5e7eb"
                    stroke-width="20"
                  />
                  <!-- 45% Out of School (Red) -->
                  <circle
                    cx="128"
                    cy="128"
                    r="100"
                    fill="none"
                    stroke="#ef4444"
                    stroke-width="20"
                    stroke-dasharray="628.32"
                    stroke-dashoffset="345.576"
                  />
                  <!-- 55% In School (Green) -->
                  <circle
                    cx="128"
                    cy="128"
                    r="100"
                    fill="none"
                    stroke="#10b981"
                    stroke-width="20"
                    stroke-dasharray="628.32"
                    stroke-dashoffset="0"
                    class="origin-center"
                    style="stroke-dashoffset: 282.744"
                  />
                </svg>
                <div
                  class="absolute inset-0 flex flex-col items-center justify-center"
                >
                  <span class="text-4xl font-bold text-red-600">45%</span>
                  <span class="text-sm text-gray-600">Out of School</span>
                </div>
              </div>
            </div>
            <!-- Statistic Text -->
            <div class="text-center md:text-left">
              <p class="text-2xl font-bold text-gray-800 mb-4">
                1 in 10 Kenyan children<br />
                <span class="text-red-600">live with a disability</span>
              </p>
              <p class="text-lg text-gray-700 leading-relaxed">
                Yet
                <span class="font-bold text-red-600"
                  >45% of them remain out of school</span
                >, denied their fundamental right to education. This crisis
                demands urgent action and innovative solutions.
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- NEW SECTION 2: The Investment (Pie Chart) -->
      <div class="mt-16 animate__animated animate__fadeInUp animate__delay-4s">
        <div
          class="bg-gradient-to-r from-blue-50 to-indigo-50 rounded-2xl p-8 shadow-lg"
        >
          <div class="text-center mb-6">
            <span
              class="text-yellow-400 font-semibold text-sm uppercase tracking-wider"
              >The Investment</span
            >
            <h2 class="text-3xl font-bold text-gray-800 mt-2">
              KES 10M Budget Breakdown
            </h2>
            <p class="text-gray-600 mt-2">How your donations create impact</p>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-center">
            <!-- Pie Chart -->
            <div class="relative w-80 h-80 mx-auto">
              <canvas id="budgetPieChart" width="320" height="320"></canvas>
            </div>

            <!-- Legend and Breakdown -->
            <div class="space-y-4">
              <div
                class="flex items-center justify-between p-3 bg-white rounded-lg shadow"
              >
                <div class="flex items-center gap-3">
                  <div
                    class="w-4 h-4 rounded-full"
                    style="background-color: #f59e0b"
                  ></div>
                  <span class="font-semibold text-gray-700"
                    >EdTech Devices & Assistive Tools</span
                  >
                </div>
                <span class="font-bold text-gray-900">35% (KES 3.5M)</span>
              </div>

              <div
                class="flex items-center justify-between p-3 bg-white rounded-lg shadow"
              >
                <div class="flex items-center gap-3">
                  <div
                    class="w-4 h-4 rounded-full"
                    style="background-color: #3b82f6"
                  ></div>
                  <span class="font-semibold text-gray-700"
                    >Teacher Training & Capacity Building</span
                  >
                </div>
                <span class="font-bold text-gray-900">25% (KES 2.5M)</span>
              </div>

              <div
                class="flex items-center justify-between p-3 bg-white rounded-lg shadow"
              >
                <div class="flex items-center gap-3">
                  <div
                    class="w-4 h-4 rounded-full"
                    style="background-color: #10b981"
                  ></div>
                  <span class="font-semibold text-gray-700"
                    >Program Operations & Monitoring</span
                  >
                </div>
                <span class="font-bold text-gray-900">20% (KES 2.0M)</span>
              </div>

              <div
                class="flex items-center justify-between p-3 bg-white rounded-lg shadow"
              >
                <div class="flex items-center gap-3">
                  <div
                    class="w-4 h-4 rounded-full"
                    style="background-color: #8b5cf6"
                  ></div>
                  <span class="font-semibold text-gray-700"
                    >Community Outreach & Awareness</span
                  >
                </div>
                <span class="font-bold text-gray-900">15% (KES 1.5M)</span>
              </div>

              <div
                class="flex items-center justify-between p-3 bg-white rounded-lg shadow"
              >
                <div class="flex items-center gap-3">
                  <div
                    class="w-4 h-4 rounded-full"
                    style="background-color: #ef4444"
                  ></div>
                  <span class="font-semibold text-gray-700"
                    >Research & Impact Assessment</span
                  >
                </div>
                <span class="font-bold text-gray-900">5% (KES 0.5M)</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- NEW SECTION 3: The Roadmap (Timeline) -->
      <div
        class="mt-16 mb-16 animate__animated animate__fadeInUp animate__delay-5s"
      >
        <div class="bg-gray-50 rounded-2xl p-8 shadow-lg">
          <div class="text-center mb-10">
            <span
              class="text-orange-500 font-semibold text-sm uppercase tracking-wider"
              >The Roadmap</span
            >
            <h2 class="text-3xl font-bold text-gray-800 mt-2">
              4-Phase Implementation Plan
            </h2>
            <p class="text-gray-600 mt-2">
              From local impact to Africa-wide transformation
            </p>
          </div>

          <div class="relative">
            <!-- Timeline Line -->
            <div
              class="absolute left-8 md:left-1/2 transform md:-translate-x-1/2 w-1 h-full bg-gradient-to-b from-yellow-500 via-orange-500 to-purple-600"
            ></div>

            <!-- Phase 1 -->
            <div class="relative flex flex-col md:flex-row gap-8 mb-12">
              <div class="md:w-1/2 md:text-right">
                <div
                  class="bg-white rounded-xl p-6 shadow-md ml-12 md:ml-0 md:mr-8"
                >
                  <div
                    class="absolute left-0 md:left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-12 h-12 bg-yellow-500 rounded-full flex items-center justify-center shadow-lg"
                  >
                    <span class="text-white font-bold">1</span>
                  </div>
                  <h3 class="text-xl font-bold text-gray-800 mb-2">
                    School Onboarding
                  </h3>
                  <p class="text-gray-600">Month 1-3</p>
                  <p class="text-gray-700 mt-2">
                    Identify and onboard 20 pilot schools, assess infrastructure
                    needs, and establish partnerships with local education
                    authorities.
                  </p>
                </div>
              </div>
              <div class="hidden md:block md:w-1/2"></div>
            </div>

            <!-- Phase 2 -->
            <div class="relative flex flex-col md:flex-row gap-8 mb-12">
              <div class="hidden md:block md:w-1/2"></div>
              <div class="md:w-1/2">
                <div class="bg-white rounded-xl p-6 shadow-md mr-12 md:ml-8">
                  <div
                    class="absolute left-0 md:left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-12 h-12 bg-orange-500 rounded-full flex items-center justify-center shadow-lg"
                  >
                    <span class="text-white font-bold">2</span>
                  </div>
                  <h3 class="text-xl font-bold text-gray-800 mb-2">
                    Device Deployment & Training
                  </h3>
                  <p class="text-gray-600">Month 4-8</p>
                  <p class="text-gray-700 mt-2">
                    Distribute assistive devices, train 50 teachers on inclusive
                    digital pedagogy, and launch personalized learning programs.
                  </p>
                </div>
              </div>
            </div>

            <!-- Phase 3 -->
            <div class="relative flex flex-col md:flex-row gap-8 mb-12">
              <div class="md:w-1/2 md:text-right">
                <div
                  class="bg-white rounded-xl p-6 shadow-md ml-12 md:ml-0 md:mr-8"
                >
                  <div
                    class="absolute left-0 md:left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-12 h-12 bg-yellow-500 rounded-full flex items-center justify-center shadow-lg"
                  >
                    <span class="text-white font-bold">3</span>
                  </div>
                  <h3 class="text-xl font-bold text-gray-800 mb-2">
                    Scale & Replication
                  </h3>
                  <p class="text-gray-600">Month 9-18</p>
                  <p class="text-gray-700 mt-2">
                    Expand to 100+ schools across Kenya, establish monitoring
                    systems, and replicate successful models in new regions.
                  </p>
                </div>
              </div>
              <div class="hidden md:block md:w-1/2"></div>
            </div>

            <!-- Phase 4 -->
            <div class="relative flex flex-col md:flex-row gap-8">
              <div class="hidden md:block md:w-1/2"></div>
              <div class="md:w-1/2">
                <div class="bg-white rounded-xl p-6 shadow-md mr-12 md:ml-8">
                  <div
                    class="absolute left-0 md:left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-12 h-12 bg-orange-500 rounded-full flex items-center justify-center shadow-lg"
                  >
                    <span class="text-white font-bold">4</span>
                  </div>
                  <h3 class="text-xl font-bold text-gray-800 mb-2">
                    Africa-Wide Expansion
                  </h3>
                  <p class="text-gray-600">Month 19-24</p>
                  <p class="text-gray-700 mt-2">
                    Launch operations in 5+ African countries, establish
                    regional centers of excellence, and influence inclusive
                    education policies continent-wide.
                  </p>
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
import Chart from "chart.js/auto";

export default {
  name: "HeroSection",
  data() {
    return {
      extraImages: [
        {
          src: "https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504817/running_yvjlyc.jpg",
          alt: "Extra Image 1",
        },
        {
          src: "https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504817/playing_vxx3s8.avif",
          alt: "Extra Image 2",
        },
        {
          src: "https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504818/smiling_dn7n3w.avif",
          alt: "Extra Image 3",
        },
      ],
    };
  },
  mounted() {
    this.addScrollAnimations();
    this.createPieChart();
  },
  methods: {
    addScrollAnimations() {
      const observerOptions = {
        threshold: 0.1,
        rootMargin: "0px 0px -50px 0px",
      };

      const observer = new IntersectionObserver((entries) => {
        entries.forEach((entry) => {
          if (entry.isIntersecting) {
            const element = entry.target;
            const animation = element.dataset.animation || "fadeInUp";
            const delay = element.dataset.delay || 0;

            element.style.animation = `${animation} 0.6s ease-out ${delay}s forwards`;
            element.style.opacity = "1";
            observer.unobserve(element);
          }
        });
      }, observerOptions);

      document.querySelectorAll(".animate-on-scroll").forEach((el) => {
        el.style.opacity = "0";
        observer.observe(el);
      });
    },
    createPieChart() {
      const ctx = document.getElementById("budgetPieChart").getContext("2d");
      new Chart(ctx, {
        type: "pie",
        data: {
          labels: [
            "EdTech Devices",
            "Teacher Training",
            "Operations",
            "Community Outreach",
            "Research",
          ],
          datasets: [
            {
              data: [35, 25, 20, 15, 5],
              backgroundColor: [
                "#f59e0b",
                "#3b82f6",
                "#10b981",
                "#8b5cf6",
                "#ef4444",
              ],
              borderWidth: 0,
            },
          ],
        },
        options: {
          responsive: true,
          maintainAspectRatio: true,
          plugins: {
            legend: {
              position: "bottom",
              labels: {
                font: {
                  size: 12,
                },
              },
            },
            tooltip: {
              callbacks: {
                label: function (context) {
                  const label = context.label || "";
                  const value = context.parsed || 0;
                  const total = 100;
                  const percentage = ((value * total) / 100).toFixed(1);
                  return `${label}: ${percentage}% (KES ${(value * 0.1).toFixed(1)}M)`;
                },
              },
            },
          },
        },
      });
    },
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Finger+Paint&display=swap");
@import url("https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css");

/* Custom animations */
@keyframes float {
  0%,
  100% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-10px);
  }
}

@keyframes pulse {
  0%,
  100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
}

@keyframes shimmer {
  0% {
    background-position: -1000px 0;
  }
  100% {
    background-position: 1000px 0;
  }
}

/* Hover effects */
.hover-lift {
  transition: all 0.3s ease;
}

.hover-lift:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

/* Button hover effects */
.router-link-active {
  position: relative;
  overflow: hidden;
}

/* Image gallery animations */
.animate-on-scroll {
  opacity: 0;
}

/* Keyframe animations */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeInLeft {
  from {
    opacity: 0;
    transform: translateX(-30px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes fadeInRight {
  from {
    opacity: 0;
    transform: translateX(30px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes zoomIn {
  from {
    opacity: 0;
    transform: scale(0.8);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

/* Apply animations to elements */
.animate__animated {
  animation-duration: 1s;
  animation-fill-mode: both;
}

.animate__delay-1s {
  animation-delay: 0.3s;
}

.animate__delay-2s {
  animation-delay: 0.6s;
}

.animate__delay-3s {
  animation-delay: 0.9s;
}

.animate__delay-4s {
  animation-delay: 1.2s;
}

.animate__delay-5s {
  animation-delay: 1.5s;
}

.animate__fadeInLeft {
  animation-name: fadeInLeft;
}

.animate__fadeInRight {
  animation-name: fadeInRight;
}

.animate__fadeInUp {
  animation-name: fadeInUp;
}

.animate__zoomIn {
  animation-name: zoomIn;
}

/* Floating animation for images */
img {
  transition: all 0.3s ease;
}

img:hover {
  transform: translateY(-5px) scale(1.02);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
}

/* Gradient text animation */
@keyframes gradientShift {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

/* Responsive animations */
@media (max-width: 768px) {
  .animate__animated {
    animation-duration: 0.5s;
  }
}
</style>

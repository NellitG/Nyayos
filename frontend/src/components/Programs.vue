<template>
  <div class="bg-gray-50 py-12 relative mr-4 overflow-hidden">
    <!-- Decorative Background Shapes with animations -->
    <div
      class="absolute top-0 left-0 w-48 h-48 bg-yellow-400 rounded-full mix-blend-multiply opacity-30 blur-3xl animate-pulse-slow"
    ></div>
    <div
      class="absolute bottom-0 right-0 w-72 h-72 bg-indigo-500 rounded-full mix-blend-multiply opacity-20 blur-3xl animate-pulse-slow animation-delay-2000"
    ></div>
    <div class="absolute top-1/2 left-1/2 w-96 h-96 bg-purple-400 rounded-full mix-blend-multiply opacity-10 blur-3xl animate-float"></div>
    
    <div class="relative z-10 container mx-auto px-6 lg:px-16 space-y-32">
      <!-- Inclusive Education -->
      <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-8 animate-on-scroll" data-animation="fadeInLeft">
        <!-- Image -->
        <div class="lg:col-span-5 relative group">
          <div
            class="absolute -top-8 -left-8 w-full h-full bg-yellow-100 rounded-lg -z-10 transform rotate-3 group-hover:rotate-6 transition-transform duration-500"
          ></div>
          <img
            src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504819/student_vjs8du.avif"
            alt="Inclusive Education"
            class="w-full rounded-lg shadow-lg object-cover transform transition-all duration-500 group-hover:scale-105 group-hover:shadow-2xl"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-black/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg"></div>
        </div>
        <!-- Text -->
        <div class="lg:col-span-7 space-y-6 text-center lg:text-left pt-12">
          <h3
            class="text-transparent text-5xl font-semibold text-gray-950 bg-clip-text bg-gradient-to-r from-blue-500 to-yellow-500 animate-gradient"
            style="font-family: 'Finger Paint', cursive"
          >
            Inclusive Education
          </h3>
          <p class="text-lg text-gray-700 leading-relaxed animate-fade-in-up">
            To ensure that every differently-abled child/individual has access
            to quality digital education, has access to the same opportunities
            as any other child/individual, despite their background differences.
            We envision a future whereby every differently-abled
            child/individual thrives emotionally, professionally and physically,
            and whereby diversity is a stepping stone to greatness rather than
            an obstacle.
            <br />
            We aim to create a learning environment that caters to their needs
            and empowers them with the skills to succeed.
          </p>
          <!-- Centered Button -->
          <div class="flex justify-center">
            <!-- Button can be added here if needed -->
          </div>
        </div>
      </div>

      <!-- Workshops & Seminars -->
      <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-8 animate-on-scroll" data-animation="fadeInRight">
        <!-- Text -->
        <div class="lg:col-span-7 space-y-6 text-center lg:text-left pt-12">
          <h3
            class="text-5xl font-semibold text-gray-950 text-transparent bg-clip-text bg-gradient-to-r from-blue-500 to-yellow-500 animate-gradient animation-delay-500"
            style="font-family: 'Finger Paint', cursive"
          >
            Workshops & Seminars
          </h3>
          <p class="text-lg text-gray-700 leading-relaxed animate-fade-in-up animation-delay-300">
            We facilitate impactful educational sessions tailored for parents,
            caregivers, and educators, highlighting the importance of disability
            rights, fostering inclusion, and championing personalized education
            for children with diverse abilities. These workshops serve as
            catalysts for change, cultivating a profound understanding within
            the community and empowering participants to advocate for a more
            inclusive and equitable society.
          </p>
          <!-- Centered Button -->
          <div class="flex justify-center">
            <router-link to="/Event">
              <button
                class="relative px-6 py-3 bg-indigo-500 text-white font-semibold rounded-md shadow-lg overflow-hidden group transition-all duration-300 hover:shadow-xl transform hover:-translate-y-1"
              >
                <span class="relative z-10">View Events</span>
                <span class="absolute inset-0 bg-indigo-600 transform translate-y-full group-hover:translate-y-0 transition-transform duration-300"></span>
              </button>
            </router-link>
          </div>
        </div>
        <!-- Image -->
        <div class="lg:col-span-5 relative group">
          <div
            class="absolute -top-8 -right-8 w-full h-full bg-indigo-100 rounded-lg -z-10 transform -rotate-3 group-hover:-rotate-6 transition-transform duration-500"
          ></div>
          <img
            src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504821/workshop_qd0eyx.jpg"
            alt="Workshops & Seminars"
            class="w-full rounded-lg shadow-lg object-cover transform transition-all duration-500 group-hover:scale-105 group-hover:shadow-2xl"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-black/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg"></div>
        </div>
      </div>

      <!-- Partnerships -->
      <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-8 animate-on-scroll" data-animation="fadeInUp">
        <!-- Image -->
        <div class="lg:col-span-5 relative group">
          <div
            class="absolute -top-8 -left-8 w-full h-full bg-purple-100 rounded-lg -z-10 transform rotate-3 group-hover:rotate-6 transition-transform duration-500"
          ></div>
          <img
            src="https://res.cloudinary.com/dqe69vaz7/image/upload/v1736504817/partnerships_aevplu.avif"
            alt="Partnerships"
            class="w-full rounded-lg shadow-lg object-cover transform transition-all duration-500 group-hover:scale-105 group-hover:shadow-2xl"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-black/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg"></div>
        </div>
        <!-- Text -->
        <div class="lg:col-span-7 space-y-6 text-center lg:text-left pt-12">
          <h3
            class="text-5xl font-semibold text-gray-950 text-transparent bg-clip-text bg-gradient-to-r from-blue-500 to-yellow-500 animate-gradient animation-delay-1000"
            style="font-family: 'Finger Paint', cursive"
          >
            Partnerships
          </h3>
          <p class="text-lg text-gray-700 leading-relaxed animate-fade-in-up animation-delay-600">
            Our collaboration goes beyond mere support—it drives systemic
            change, ensuring inclusive education is not just available but
            accessible and impactful for every child. We work alongside schools,
            healthcare providers, and community organizations to establish a
            robust network of care and opportunity. Your support as a donor
            empowers us to turn this vision into reality, breaking down barriers
            and building pathways for children with disabilities to thrive,
            excel, and realize their full potential.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProgramsSection",
  mounted() {
    this.addScrollAnimations();
  },
  methods: {
    addScrollAnimations() {
      const observerOptions = {
        threshold: 0.2,
        rootMargin: "0px 0px -100px 0px"
      };

      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            const element = entry.target;
            const animation = element.dataset.animation || 'fadeInUp';
            const delay = element.dataset.delay || 0;
            
            element.style.animation = `${animation} 0.8s ease-out ${delay}s forwards`;
            element.style.opacity = '1';
            observer.unobserve(element);
          }
        });
      }, observerOptions);

      // Observe all elements with animate-on-scroll class
      document.querySelectorAll('.animate-on-scroll').forEach(el => {
        el.style.opacity = '0';
        observer.observe(el);
      });
    }
  }
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Finger+Paint&display=swap");

/* Keyframe Animations */
@keyframes fadeInLeft {
  from {
    opacity: 0;
    transform: translateX(-50px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes fadeInRight {
  from {
    opacity: 0;
    transform: translateX(50px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(50px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes pulse {
  0%, 100% {
    opacity: 0.3;
    transform: scale(1);
  }
  50% {
    opacity: 0.5;
    transform: scale(1.05);
  }
}

@keyframes float {
  0%, 100% {
    transform: translate(-50%, -50%) translateY(0px);
  }
  50% {
    transform: translate(-50%, -50%) translateY(-20px);
  }
}

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

@keyframes shimmer {
  0% {
    background-position: -1000px 0;
  }
  100% {
    background-position: 1000px 0;
  }
}

/* Animation Classes */
.animate-pulse-slow {
  animation: pulse 4s ease-in-out infinite;
}

.animate-float {
  animation: float 6s ease-in-out infinite;
}

.animate-gradient {
  background-size: 200% auto;
  animation: gradientShift 3s ease infinite;
}

.animate-fade-in-up {
  animation: fadeInUp 0.6s ease-out forwards;
}

/* Delay Classes */
.animation-delay-2000 {
  animation-delay: 2s;
}

.animation-delay-300 {
  animation-delay: 0.3s;
}

.animation-delay-500 {
  animation-delay: 0.5s;
}

.animation-delay-600 {
  animation-delay: 0.6s;
}

.animation-delay-1000 {
  animation-delay: 1s;
}

/* Scroll Animation Base */
.animate-on-scroll {
  opacity: 0;
}

/* Hover Effects */
.group:hover .group-hover\:rotate-6 {
  --tw-rotate: 6deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.group:hover .group-hover\:-rotate-6 {
  --tw-rotate: -6deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

/* Button Hover Animation */
button {
  position: relative;
  overflow: hidden;
  transition: all 0.3s ease;
}

button:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

button:active {
  transform: translateY(0);
}

/* Image Hover Effects */
img {
  transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Responsive Animations */
@media (max-width: 768px) {
  .animate-on-scroll {
    opacity: 1;
  }
  
  .animate-pulse-slow,
  .animate-float {
    animation-duration: 3s;
  }
}

/* Loading Shimmer Effect for Images */
img {
  position: relative;
  background: linear-gradient(90deg, #f0f0f0 25%, #e0e0e0 50%, #f0f0f0 75%);
  background-size: 200% 100%;
  animation: shimmer 1.5s infinite;
}

img[data-loaded="true"] {
  animation: none;
}
</style>
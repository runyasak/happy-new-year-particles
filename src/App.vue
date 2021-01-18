<template>
  <div id="app">
    <Particles
      id="tsparticles"
      class="snow-particle"
      :options="{
        fpsLimit: 60,
          interactivity: {
          detectsOn: 'canvas',
          modes: {
            bubble: {
              distance: 400,
              duration: 2,
              opacity: 0.8,
              size: 40
            },
            push: {
              quantity: 4
            },
            repulse: {
              distance: 200,
              duration: 0.4
            }
          }
        },
        particles: {
          number: {
            value: 52,
            density: {
              enable: true,
              value_area: 789.1476416322727,
            },
          },
          color: {
            value: '#ffffff',
          },
          shape: {
            type: 'image',
            stroke: {
              width: 0,
              color: '#000000',
            },
            polygon: {
              nb_sides: 9,
            },
            image: {
              src: 'http://www.dynamicdigital.us/wp-content/uploads/2013/02/starburst_white_300_drop_2.png',
              width: 1000,
              height: 1000,
            },
          },
          opacity: {
            value: 0.5291259800856225,
            random: false,
            anim: {
              enable: false,
              speed: 1,
              opacity_min: 0.1,
              sync: false,
            },
          },
          size: {
            value: 31.565905665290902,
            random: true,
            anim: {
              enable: false,
              speed: 40,
              size_min: 0.1,
              sync: false,
            },
          },
          line_linked: {
            enable: false,
            distance: 150,
            color: '#ffffff',
            opacity: 0.4,
            width: 1,
          },
          move: {
            enable: true,
            speed: 6,
            direction: 'none',
            random: false,
            straight: false,
            out_mode: 'out',
            bounce: false,
            attract: {
              enable: false,
              rotateX: 600,
              rotateY: 1200,
            },
          },
          interactivity: {
            detect_on: 'canvas',
            modes: {
              grab: {
                distance: 400,
                line_linked: {
                  opacity: 1,
                },
              },
              bubble: {
                distance: 400,
                size: 40,
                duration: 2,
                opacity: 8,
                speed: 3,
              },
              repulse: {
                distance: 200,
                duration: 0.4,
              },
              push: {
                particles_nb: 4,
              },
              remove: {
                particles_nb: 2,
              },
            },
          },
        },
        detectRetina: true
      }"
    ></Particles>
  </div>
</template>

<style scoped>
.snow-particle {
  height: 100vh;
  background: linear-gradient(150deg, rgba(20,30,48,0.9962359943977591) 0%, rgba(28,131,224,1) 100%);
}
</style>

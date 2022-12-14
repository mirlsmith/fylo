<template>
  <section class="home-container">
    <div class="top-section flex column">
      <div class="files-img">
        <img src="../assets/imgs/illustration-intro.png" alt="">
      </div>
      <h1>All your files in one secure location, accessible anywhere.</h1>
      <p>
        Fylo stores all your most important files in one secure location. Access
        them wherever you need, share and collaborate with friends family, and
        co-workers.
      </p>
      <button>Get Started</button>
    </div>
    <div class="services-section">
      <div class="service-info">
        <div class="image">
          <img src="../assets/imgs/icon-access-anywhere.svg" alt="" />
        </div>
        <div class="title">
          <p>Access your files, anywhere</p>
        </div>
        <div class="txt">
          <p>
            The ability to use a smartphone, tablet, or computer to access your
            account means your files follow you everywhere.
          </p>
        </div>
      </div>
      <div class="service-info">
        <div class="image">
          <img src="../assets/imgs/icon-security.svg" alt="" />
        </div>
        <div class="title">
          <p>Security you can trust</p>
        </div>
        <div class="txt">
          <p>
            2-factor authentication and user-controlled encryption are just a
            couple of the security features we allow to help secure your files.
          </p>
        </div>
      </div>
      <div class="service-info">
        <div class="image">
          <img src="../assets/imgs/icon-collaboration.svg" alt="" />
        </div>
        <div class="title">
          <p>Real-time collaboration</p>
        </div>
        <div class="txt">
          <p>
            Securely share files and folders with friends, family and colleagues
            for live collaboration. No email attachments required.
          </p>
        </div>
      </div>
      <div class="service-info">
        <div class="image">
          <img src="../assets/imgs/icon-any-file.svg" alt="" />
        </div>
        <div class="title">
          <p>Store any type of file</p>
        </div>
        <div class="txt">
          <p>
            Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import customButton from '../components/custom-button.vue'
import serviceInfo from '../components/service-info.vue'
export default {
  name: 'home',
  components: {
    customButton,
    serviceInfo,
  },
}
</script>

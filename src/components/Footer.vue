<template>
  <footer>
    <div class="bevel"></div>
    <div class="footer__background">
      <div class="container">
        <div class="upper">
          <router-link to="/" class="logo">
            <span class="icon-logo32 px32"> </span>
            <h3 class="logo-heading">NativeSoft</h3>
          </router-link>
          <div class="about">
            <router-link to="/integrators" class="btn text-base font-regular btnc3"
              >Интеграторы</router-link
            >
            <router-link to="/contact" class="btn text-base font-regular btnc3"
              >Компаниям</router-link
            >
          </div>
        </div>

        <div class="under">
          <p class="company__text">
            © 2022 NativeSoft. Все права на материалы, представленные на нашем
            сайте, принадлежат их законным владельцам и <wbr />
            предназначены только для ознакомления.
          </p>
          <ul class="contacts__list">
            <li class="contacts__item">
              <span class="icon-social-telegram px24 btnc3"> </span>
            </li>
            <li class="contacts__item">
              <a title="Discord" target="_blank" class="footer_disco_link" href="https://discord.gg/it-spec"><span class="icon-social-discord px24 btnc3"></span></a>
            </li>
            <li class="contacts__item">
              <a title="VK" target="_blank" class="footer_vk_link" href="https://vk.com/rusoftmain"><span class="icon-social-vk px24 btnc3"></span></a>
            </li>
            <li class="contacts__item">
              <span class="icon-social-youtube px24 btnc3"></span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup></script>

<style lang="scss" scoped></style>

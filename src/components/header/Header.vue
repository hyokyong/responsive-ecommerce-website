<template>
<!--  <header>-->
<!--    <nav class="nav bg-grid">-->
<!--      <div>-->
<!--        <a href="#" class="nav__logo">SARA</a>-->
<!--      </div>-->
<!--      <div class="nav__menu" id="nav-menu" :class="{'show' : isShowMobileMenu}">-->
<!--        <ul class="nav__list">-->
<!--          <li class="nav__item"><a href="#home" class="nav__link" @click="onShowMenu">Home</a></li>-->
<!--          <li class="nav__item"><a href="#featured" class="nav__link" @click="onShowMenu">Featured</a></li>-->
<!--          <li class="nav__item"><a href="#new" class="nav__link" @click="onShowMenu">New</a></li>-->
<!--          <li class="nav__item"><a href="#subscribed" class="nav__link" @click="onShowMenu">Subscribed</a></li>-->
<!--        </ul>-->
<!--      </div>-->
<!--      <div>-->
<!--        <i class='bx bx-cart nav__cart' />-->
<!--        <i class='bx bx-menu nav__toggle' id="nav-toggle" @click="onShowMenu"/>-->
<!--      </div>-->
<!--    </nav>-->
<!--  </header>-->
  <header>
    <nav class="container bg-grid">
          <div class="nav-logo">
            <a href="#" class="logo-img">SARA</a>
          </div>
          <div class="nav-menu" :class="{'show' : isShowMobileMenu }">
            <ul class="nav-menu-list">
              <li class="nav-menu-item">
                <a href="#" class="nav-menu-link" @click="onShowMenu">menu1</a>
              </li>
              <li class="nav-menu-item">
                <a href="#" class="nav-menu-link" @click="onShowMenu">menu2</a>
              </li>
              <li class="nav-menu-item">
                <a href="#" class="nav-menu-link" @click="onShowMenu">menu3</a>
              </li>
              <li class="nav-menu-item">
                <a href="#" class="nav-menu-link" @click="onShowMenu">menu4</a>
              </li>
              <li class="nav-menu-item">
                <a href="#" class="nav-menu-link" @click="onShowMenu">menu5</a>
              </li>
            </ul>
          </div>
          <div>
            <i class='bx bx-cart' />
            <i class='bx bx-menu' @click="onShowMenu"/>
          </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: [],
  data () {
    return {
      isShowMobileMenu: false
    }
  },
  computed: {},
  created () {},
  mounted () {},
  watch: {},
  methods: {
    onShowMenu () {
      this.isShowMobileMenu = !this.isShowMobileMenu;
    }
  },
  components: {}
}
</script>

<style scoped lang="scss">
  @import "Header";
</style>

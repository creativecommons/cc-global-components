<template>
    <header class="vocab header">
        <nav class="navbar is-default is-active">
            <div class="navbar-brand">
                
            </div>
            <div class="navbar-menu is-active">
                <div class="navbar-start">
                    <!-- Locale options 
                    <div class="locale">
                        <div class="select">
                            <select>
                                <option disabled="">Select</option>
                                <option selected="">English</option>
                                <option>le Français</option>
                                <option>日本語</option>
                                <option>Русский</option>
                                <option>Español</option>
                            </select>
                        </div>
                        <span class="icon caret-down is-small is-right">
                            <svg viewBox="0 0 30 30" xmlns="http://www.w3.org/2000/svg"><path d="M7.45896 11.25H22.5351c1.043 0 1.5645 1.2598.8262 1.998l-7.5352 7.5411c-.457.457-1.2011.457-1.6582 0L6.63279 13.248c-.73828-.7382-.2168-1.998.82617-1.998z" fill="currentColor"></path></svg>
                        </span>
                    </div>-->
                    <!-- Donate button -->
                    <a class="button donate" href="https://creativecommons.org/donate?c_src=website&amp;c_src2=NavBar">
                        <i class="icon heart"></i>
                        Donate
                    </a>
                </div>
            </div>
        </nav>
        <nav class="navbar" :aria-label="ariaPrimaryLabel">
             <div class="navbar-brand">
                <a class="main-logo" href="https://creativecommons.org" target="_blank">
                  <div class="">
                    <svg xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet" viewBox="0 0 304 73">
                      <use href="#logomark">
                        <g id="logomark" fill="currentColor">
                          <path d="M200.315 0V6.491H191.877V0H200.315ZM191.876 38.512V9.736H200.314V38.512H191.876ZM183.668 10.277H188.699H188.7V15.47H183.669V29.586C183.669 31.858 184.804 32.453 186.32 32.453C187.239 32.453 188.428 32.345 188.862 32.291V38.944C187.78 39.053 185.292 39.269 183.453 39.269C176.258 39.269 175.23 34.78 175.23 30.615V15.469H171.12V10.277H175.23V1.94699H183.668V10.277ZM81.354 8.979C86.817 8.979 91.523 10.981 94.282 16.011L87.79 19.419C86.276 16.173 83.679 15.47 82.381 15.47C77.567 15.47 75.836 19.202 75.836 24.124C75.836 29.047 77.891 32.779 82.381 32.779C84.977 32.779 87.032 31.806 88.385 28.56L94.443 31.643C91.847 36.241 87.141 39.27 81.624 39.27C73.024 39.27 67.074 33.806 67.074 24.124C67.074 14.604 73.403 8.979 81.354 8.979ZM81.354 42.084C86.817 42.084 91.523 44.086 94.282 49.116L87.79 52.525C86.276 49.279 83.679 48.576 82.381 48.576C77.567 48.576 75.836 52.308 75.836 57.231C75.836 62.153 77.891 65.885 82.381 65.885C84.977 65.885 87.032 64.911 88.385 61.665L94.443 64.748C91.847 69.346 87.141 72.375 81.624 72.375C73.024 72.375 67.074 66.912 67.074 57.23C67.074 47.709 73.403 42.084 81.354 42.084ZM109.746 42.084C100.767 42.084 94.439 47.547 94.439 57.23C94.439 66.912 100.767 72.375 109.746 72.375C118.725 72.375 125.054 66.912 125.054 57.23C125.054 47.548 118.725 42.084 109.746 42.084ZM109.746 48.575C114.56 48.575 116.616 52.307 116.616 56.905C116.616 62.152 114.56 65.884 109.746 65.884C104.932 65.884 102.877 62.152 102.877 57.23C102.877 52.308 104.932 48.575 109.746 48.575ZM126.783 71.617H135.221V53.714C135.221 51.118 136.303 48.9 139.71 48.9C142.956 48.9 143.821 50.793 143.821 53.606V71.618H152.259V53.93C152.259 51.009 153.719 48.9 156.532 48.9C159.723 48.9 160.859 50.739 160.859 54.796V71.617H169.297V49.657C169.297 43.058 163.239 42.084 160.426 42.084C157.072 42.084 153.935 43.112 151.177 45.924C149.283 43.382 146.85 42.084 143.55 42.084C140.954 42.084 137.384 42.841 135.22 45.384V42.842H126.782V71.617H126.783ZM180.435 71.617H171.997H171.996V42.842H180.434V45.384C182.598 42.841 186.168 42.084 188.764 42.084C192.064 42.084 194.498 43.382 196.391 45.924C199.15 43.112 202.286 42.084 205.64 42.084C208.452 42.084 214.511 43.058 214.511 49.657V71.617H206.073V54.796C206.073 50.739 204.936 48.9 201.745 48.9C198.933 48.9 197.473 51.009 197.473 53.93V71.618H189.035V53.606C189.035 50.793 188.17 48.9 184.924 48.9C181.517 48.9 180.435 51.118 180.435 53.714V71.617ZM216.236 57.23C216.236 47.547 222.565 42.084 231.544 42.084C240.523 42.084 246.852 47.548 246.852 57.23C246.852 66.912 240.523 72.375 231.544 72.375C222.564 72.375 216.236 66.912 216.236 57.23ZM238.413 56.905C238.413 52.307 236.357 48.575 231.544 48.575C226.73 48.575 224.674 52.308 224.674 57.23C224.674 62.152 226.73 65.884 231.544 65.884C236.357 65.884 238.413 62.152 238.413 56.905ZM257.56 71.617H249.122H249.121V42.842H257.559V45.384C259.723 42.841 263.293 42.084 265.889 42.084C272.704 42.084 274.598 46.033 274.598 50.36V71.618H266.16V53.606C266.16 50.793 265.295 48.9 262.05 48.9C258.642 48.9 257.56 51.118 257.56 53.714V71.617ZM302.774 46.25C298.879 43.654 294.499 42.085 290.063 42.085C284.22 42.085 277.892 44.898 277.892 52.146C277.892 58.2943 284.055 59.4536 288.967 60.3778C292.223 60.9902 294.93 61.4994 294.93 63.289C294.93 65.886 291.74 66.21 290.332 66.21C286.492 66.21 283.842 64.642 281.245 62.153L275.998 66.696C280.218 70.591 283.787 72.376 290.062 72.376C296.335 72.376 303.043 69.671 303.043 62.099C303.043 55.6774 296.979 54.5307 292.086 53.6055C288.778 52.9799 286.005 52.4556 286.005 50.47C286.005 49.01 287.519 48.253 289.628 48.253C292.279 48.253 295.903 49.335 297.579 51.336L302.774 46.25ZM96.34 38.512H104.778V21.852C104.778 18.661 106.779 17.795 111.81 17.2L112.729 17.092L112.675 9.62799C109.7 9.84499 106.617 10.926 104.778 12.657V9.73599H96.34V38.512ZM141.386 25.855C141.332 16.984 137.762 8.979 127.268 8.979C118.505 8.979 113.15 14.821 113.15 24.99C113.15 33.103 118.343 39.27 127.268 39.27C133.705 39.27 138.302 36.728 141.223 31.319L134.894 28.019C132.46 31.481 130.999 33.103 127.862 33.103C125.158 33.103 121.642 31.372 121.588 25.855H141.386ZM121.481 20.663C121.859 16.876 124.78 15.146 127.214 15.146C129.648 15.146 132.677 16.444 132.947 20.663H121.481ZM156.036 8.979C163.879 8.979 168.801 10.818 168.855 17.309V32.509C168.855 34.511 168.909 36.728 169.612 38.513H161.823C161.499 37.539 161.336 36.512 161.282 35.538H161.174C159.768 37.81 155.549 39.27 152.52 39.27C147.003 39.27 142.892 36.241 142.892 30.724C142.892 23.8 148.464 21.366 157.659 20.068L160.742 19.635V17.255C160.742 15.091 159.011 14.172 156.739 14.172C154.034 14.172 152.737 15.145 152.304 18.012H144.19C144.461 9.736 152.141 8.979 156.036 8.979ZM154.954 33.103C158.254 33.103 160.742 30.885 160.742 26.504V24.503L155.062 26.126C152.952 26.721 151.005 27.532 151.005 29.858C151.005 32.129 152.898 33.103 154.954 33.103ZM220.162 38.512H211.67L201.934 9.73599H210.966L215.944 30.074H216.051L221.028 9.73599H230.007L220.162 38.512ZM243.139 8.979C253.632 8.979 257.202 16.984 257.256 25.855H237.46C237.513 31.372 241.03 33.103 243.734 33.103C246.87 33.103 248.331 31.481 250.765 28.019L257.094 31.319C254.173 36.728 249.576 39.27 243.139 39.27C234.213 39.27 229.022 33.103 229.022 24.99C229.022 14.821 234.375 8.979 243.139 8.979ZM243.084 15.146C240.65 15.146 237.73 16.876 237.351 20.663H248.818C248.548 16.444 245.518 15.146 243.084 15.146ZM31.602 8.495C22.92 8.495 15.28 11.708 9.376 17.698C3.299 23.863 0 31.85 0 40.185C0 48.606 3.212 56.42 9.29 62.498C15.367 68.575 23.268 71.874 31.602 71.874C39.936 71.874 48.011 68.575 54.262 62.411C60.166 56.594 63.291 48.867 63.291 40.185C63.291 31.59 60.166 23.776 54.175 17.785C48.098 11.708 40.284 8.495 31.602 8.495ZM31.689 14.226C38.808 14.226 45.146 16.917 50.095 21.866C54.956 26.728 57.561 33.153 57.561 40.185C57.561 47.304 55.043 53.555 50.181 58.331C45.058 63.366 38.46 66.058 31.688 66.058C24.829 66.058 18.404 63.367 13.456 58.418C8.507 53.468 5.729 46.957 5.729 40.185C5.729 33.326 8.507 26.815 13.456 21.779C18.318 16.831 24.57 14.226 31.689 14.226ZM31.28 34.919C29.49 31.655 26.436 30.356 22.891 30.356C17.731 30.356 13.624 34.006 13.624 40.185C13.624 46.468 17.485 50.014 23.067 50.014C26.648 50.014 29.701 48.048 31.386 45.065L27.454 43.064C26.576 45.17 25.243 45.802 23.558 45.802C20.644 45.802 19.311 43.38 19.311 40.186C19.311 36.992 20.434 34.569 23.558 34.569C24.4 34.569 26.085 35.026 27.068 37.131L31.28 34.919ZM41.173 30.356C44.718 30.356 47.771 31.655 49.562 34.919L45.35 37.131C44.366 35.026 42.681 34.569 41.839 34.569C38.715 34.569 37.591 36.992 37.591 40.186C37.591 43.38 38.926 45.802 41.839 45.802C43.524 45.802 44.858 45.17 45.735 43.064L49.667 45.065C47.982 48.048 44.929 50.014 41.348 50.014C35.767 50.014 31.905 46.468 31.905 40.185C31.905 34.006 36.013 30.356 41.173 30.356Z"></path>
                        </g>
                      </use>
                    </svg>
                  </div>
                </a>
            </div>
            <div :class="{ ['navbar-menu']: true, ['is-active']: isBurgerMenuActive }">
                <div class="navbar-end">
                    <!-- Use this Div for dropdown menu items -->
                    <div class="navbar-item has-dropdown is-hoverable" ref="outerDiv" @mouseenter="openMenu" @mouseleave="closeMenu">
                        <button class="navbar-link is-arrowless" aria-haspopup="menu" aria-expanded="false" ref="opener" @click="toggleMenu">
                            Who we are
                            <!--  <span class="icon"><CaretDown /></span>-->
                            <i class="icon caret-down" />
                        </button>
                        <div class="navbar-dropdown">
                            <a href="#" class="navbar-item navbar-link">Item 2-1</a>
                            <a href="#" class="navbar-item navbar-link">Item 2-2</a>
                            <a href="#" class="navbar-item navbar-link">Item 2-3</a>
                            <a href="#" class="navbar-item navbar-link">Item 2-4</a>
                        </div>
                    </div>

                    <div class="navbar-item has-dropdown is-hoverable" ref="outerDiv" @mouseenter="openMenu" @mouseleave="closeMenu">
                        <button class="navbar-link is-arrowless" aria-haspopup="menu" aria-expanded="false" ref="opener" @click="toggleMenu">
                            What we do
                            <!--  <span class="icon"><CaretDown /></span>-->
                            <i class="icon caret-down" />
                        </button>
                        <div class="navbar-dropdown">
                            <a href="#" class="navbar-item navbar-link">Item 3-1</a>
                            <a href="#" class="navbar-item navbar-link">Item 3-2</a>
                        </div>
                    </div>

                    <div class="navbar-item has-dropdown is-hoverable" ref="outerDiv" @mouseenter="openMenu" @mouseleave="closeMenu">
                        <button class="navbar-link is-arrowless" aria-haspopup="menu" aria-expanded="false" ref="opener" @click="toggleMenu">
                            Licenses and tools
                            <!--  <span class="icon"><CaretDown /></span>-->
                            <i class="icon caret-down" />
                        </button>
                        <div class="navbar-dropdown">
                            <a href="#" class="navbar-item navbar-link">Item 3-1</a>
                            <a href="#" class="navbar-item navbar-link">Item 3-2</a>
                        </div>
                    </div>
                     
                    <!--Single Menu items-->
                    <a class="navbar-item navbar-link is-arrowless" tabindex="0" href="#">
                        News
                        <!--  <span class="icon"><ExternalLink /></span>-->
                        <i class="icon external-link" v-if="isExternal" />
                    </a>

                     <!--Single Menu items-->
                    <a class="navbar-item navbar-link is-arrowless" tabindex="0" href="#">
                        Support us
                        <!--  <span class="icon"><ExternalLink /></span>-->
                        <i class="icon external-link" v-if="isExternal" />
                    </a>
                </div>
            </div>
        </nav>
  </header>
</template>
<script>
    import { defineComponent } from 'vue';
    export default defineComponent({
        name: 'cc-golbal-header',
        props: {
            ariaPrimaryLabel: {
                type: String,
                default: "Main",
            },
            ariaMenuLabel: {
                type: String,
                default: "Menu",
            },
        },
        data: () => ({ isBurgerMenuActive: false }),
        methods: {
            toggleBurgerActive() {
                this.isBurgerMenuActive = !this.isBurgerMenuActive;
            },
            openMenu() {
                this.isOpen = true;
                this.$refs.opener.setAttribute("aria-expanded", "true");
            },
            closeMenu() {
                this.isOpen = false;
                this.$refs.opener.setAttribute("aria-expanded", "false");
            },
            toggleMenu() {
                this.isOpen = !this.isOpen;
                const ariaExpanded = this.$refs.opener.getAttribute("aria-expanded");
                this.$refs.opener.setAttribute("aria-expanded", `${!ariaExpanded}`);
            },
        },
    })
</script>
<style scoped>
    @import url(https://unpkg.com/@creativecommons/fonts@2020.9.3/css/fonts.css);
    @import url(https://unpkg.com/@creativecommons/vocabulary@2020.11.3/css/vocabulary.css);
    .navbar-link {
        background: transparent;
        border: none;
        font-family: "Roboto Condensed", sans-serif;
        font-size: 1.25rem;
        font-weight: bold;
        text-transform: uppercase;
        line-height: 1.5;
    }
    .navbar-item {
        cursor: pointer;
    }
    .navbar-link {
        color: #767676;
    }
</style>
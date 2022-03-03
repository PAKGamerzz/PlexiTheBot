<template>
  <div class="index-container">
    <header data-role="Header" class="index-header">
      <router-link to="/" class="index-navlink">
        <img
          alt="logo"
          src="/playground_assets/opera%20snapshot_2022-03-02_170946_www.designhill.com-1500h.png"
          loading="lazy"
          class="index-image"
        />
      </router-link>
      <div class="index-nav">
        <navigation-links1 rootClassName="rootClassName10"></navigation-links1>
      </div>
      <div class="index-btn-group">
        <button class="index-login button">Login</button>
        <button class="button">Register</button>
      </div>
      <div data-type="BurgerMenu" class="index-burger-menu">
        <svg viewBox="0 0 1024 1024" class="index-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-type="MobileMenu" class="index-mobile-menu">
        <div class="index-nav1">
          <div class="index-container1">
            <img
              alt="image"
              src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
              class="index-image01"
            />
            <div data-type="CloseMobileMenu" class="index-menu-close">
              <svg viewBox="0 0 1024 1024" class="index-icon02">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <navigation-links1 rootClassName="rootClassName11"></navigation-links1>
        </div>
        <div>
          <svg viewBox="0 0 950.8571428571428 1024" class="index-icon04">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="index-icon06">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="index-icon08">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
    <div class="index-hero">
      <span class="index-text">
        <span class="index-text01">
          Music is the universal language of mankind
        </span>
      </span>
      <h1 class="index-text02">Listen To The Music!</h1>
      <router-link to="/stream" class="index-navlink1 button">
        Listen Now!
      </router-link>
    </div>
    <div class="index-features">
      <h1 class="index-text03">Featuring...</h1>
      <div class="index-container2">
        <feature-card1 rootClassName="rootClassName4"></feature-card1>
        <div class="index-feature-card">
          <h2 class="index-text04">
            Lose Control -MEDUZA, Becky Hill, Goodboys
            <span v-html="rawfkjt"></span>
          </h2>
          <img
            alt="image"
            src="/playground_assets/meduza%2C_becky_hill_and_goodboys_-_lose_control-200h.png"
            class="index-image02"
          />
        </div>
        <div class="index-feature-card1">
          <h2 class="index-text05">Fingers Crossed - Lauren Spencer Smith</h2>
          <img
            alt="image"
            src="/playground_assets/lauren_spencer-smith_-_fingers_crossed-200h.png"
            class="index-image03"
          />
        </div>
        <div class="index-feature-card2">
          <h2 class="index-text06">
            <span>Sugarcrash! - ElyOtto</span>
            <br />
            <span></span>
          </h2>
          <img
            alt="image"
            src="/playground_assets/sugarcrash!_elyotto_song-200h.png"
            class="index-image04"
          />
        </div>
        <div class="index-feature-card3">
          <h2 class="index-text10">
            <span>Counting Stars - One Republic</span>
            <br />
            <span></span>
          </h2>
          <img
            alt="image"
            src="/playground_assets/812bztstsbl._ss500_-200h.jpg"
            class="index-image05"
          />
        </div>
        <div class="index-feature-card4">
          <h2 class="index-text14">Arcade - Duncan Laurence ft. FLETCHER</h2>
          <img
            alt="image"
            src="/playground_assets/arcade_%5Bduncan_laurence_song%5D-200h.png"
            class="index-image06"
          />
        </div>
        <div class="index-feature-card5">
          <h2 class="index-text15">
            <span>More Than You -Axwell Λ Ingrosso</span>
            <br />
            <span></span>
          </h2>
          <img
            alt="image"
            src="/playground_assets/more_than_you_know_album-200h.jpg"
            class="index-image07"
          />
        </div>
        <div class="index-feature-card6">
          <h2 class="index-text19">
            <span>No Lie - Sean Paul ft. Dua Lipa</span>
            <br />
            <span></span>
          </h2>
          <img
            alt="image"
            src="/playground_assets/sean_paul_ft_dua_lipa_-_no_lie-200h.jpg"
            class="index-image08"
          />
        </div>
      </div>
    </div>
    <div class="index-stats">
      <div class="index-stat">
        <svg viewBox="0 0 1152 1024" class="index-icon10">
          <path
            d="M768 770.612v-52.78c70.498-39.728 128-138.772 128-237.832 0-159.058 0-288-192-288s-192 128.942-192 288c0 99.060 57.502 198.104 128 237.832v52.78c-217.102 17.748-384 124.42-384 253.388h896c0-128.968-166.898-235.64-384-253.388z"
          ></path>
          <path
            d="M327.196 795.328c55.31-36.15 124.080-63.636 199.788-80.414-15.054-17.784-28.708-37.622-40.492-59.020-30.414-55.234-46.492-116.058-46.492-175.894 0-86.042 0-167.31 30.6-233.762 29.706-64.504 83.128-104.496 159.222-119.488-16.914-76.48-61.94-126.75-181.822-126.75-192 0-192 128.942-192 288 0 99.060 57.502 198.104 128 237.832v52.78c-217.102 17.748-384 124.42-384 253.388h279.006c14.518-12.91 30.596-25.172 48.19-36.672z"
          ></path>
        </svg>
        <span class="index-text23">Users</span>
        <span class="index-text24">Total Users who used Plexi.</span>
        <h1 class="index-text25">23</h1>
      </div>
      <div class="index-stat1">
        <svg viewBox="0 0 1024 1024" class="index-icon13">
          <path
            d="M598 512h234l-234-234v234zM640 214l256 256v426q0 34-26 60t-60 26h-470q-34 0-59-26t-25-60v-598q0-34 26-59t60-25h298zM682 42v86h-512v598h-84v-598q0-34 25-60t59-26h512z"
          ></path>
        </svg>
        <span class="index-text26">Commands Ran Yet!</span>
        <span class="index-text27">
          <span>Commands ran yet from the birth</span>
          <br />
          <span>of the Plexi service!</span>
        </span>
        <h1 class="index-text31"><span>325</span></h1>
      </div>
      <div class="index-stat2">
        <svg viewBox="0 0 1024 1024" class="index-icon15">
          <path
            d="M810 640v-86h-84v86h84zM810 810v-84h-84v84h84zM554 298v-84h-84v84h84zM554 470v-86h-84v86h84zM554 640v-86h-84v86h84zM554 810v-84h-84v84h84zM298 470v-86h-84v86h84zM298 640v-86h-84v86h84zM298 810v-84h-84v84h84zM640 470h256v426h-768v-598h256v-84l128-128 128 128v256z"
          ></path>
        </svg>
        <span class="index-text33">Discord Servers</span>
        <span class="index-text34">Total Joined Discord Server.</span>
        <h1 class="index-text35"><span>3</span></h1>
      </div>
    </div>
    <div class="index-banner">
      <h1 class="index-text37">About The Developer</h1>
      <span class="index-text38">
        <span>
          Hi There! Nice to meet you! I am the developer of Plexi as well as the
          designer of this website you are reading
        </span>
        <br />
        <span>
          My I real life name is Ranveer A.K.A Pak as in the gaming and coding
          community! Want to know more about me?
        </span>
      </span>
      <a
        href="https://pakrdev.netlify.app/about.html"
        target="_blank"
        rel="noreferrer noopener"
        class="index-link button"
      >
        Read more On
      </a>
    </div>
    <footer class="index-footer">
      <div class="index-container3">
        <img
          alt="logo"
          src="/playground_assets/opera%20snapshot_2022-03-02_170946_www.designhill.com-1500h.png"
          class="index-image09"
        />
        <nav class="index-nav2">
          <router-link to="/about" class="index-navlink2">About</router-link>
          <router-link to="/features" class="index-navlink3">
            Features
          </router-link>
          <router-link to="/invite-bot" class="index-navlink4">
            Invite Bot
          </router-link>
          <router-link to="/stream" class="index-navlink5">Stream</router-link>
          <router-link to="/support" class="index-navlink6">Support</router-link>
        </nav>
      </div>
      <div class="index-separator"></div>
      <div class="index-container4">
        <span class="index-text42">© 2022 Plexi Music</span>
      </div>
    </footer>
  </div>
</template>

<script>
import NavigationLinks1 from '../components/navigation-links1'
import FeatureCard1 from '../components/feature-card1'

export default {
  name: 'Home',
  components: {
    NavigationLinks1,
    FeatureCard1,
  },

  data() {
    return {
      rawfkjt: ' ',
    }
  },

  metaInfo: {
    title: 'New Project',
    meta: [
      {
        property: 'og:title',
        content: 'New Project',
      },
    ],
  },
}
</script>

<style scoped>
.index-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.index-header {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
}
.index-navlink {
  display: contents;
}
.index-image {
  width: 98px;
  height: 57px;
  text-decoration: none;
}
.index-nav {
  display: flex;
}
.index-btn-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.index-login {
  border-width: 0px;
  margin-right: var(--dl-space-space-twounits);
}
.index-burger-menu {
  display: none;
}
.index-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.index-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: absolute;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
.index-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.index-container1 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.index-image01 {
  height: 2rem;
}
.index-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.index-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.index-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.index-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.index-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.index-hero {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  min-height: 80vh;
  align-items: center;
  flex-direction: column;
  background-size: cover;
  justify-content: center;
  background-image: url("/playground_assets/3qty-1500h.gif");
}
.index-text {
  color: var(--dl-color-gray-white);
  font-size: 0.75rem;
  letter-spacing: 2px;
}
.index-text01 {
  text-transform: uppercase;
}
.index-text02 {
  color: var(--dl-color-gray-white);
  font-size: 3rem;
  max-width: 450px;
  margin-top: var(--dl-space-space-twounits);
  text-align: center;
  margin-bottom: var(--dl-space-space-twounits);
}
.index-navlink1 {
  color: var(--dl-color-gray-white);
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  text-decoration: none;
  background-color: var(--dl-color-gray-black);
}
.index-navlink1:hover {
  transform: scale(1.02);
}
.index-features {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  flex-direction: column;
}
.index-text03 {
  font-size: 3rem;
  margin-bottom: var(--dl-space-space-threeunits);
}
.index-container2 {
  flex: 0 0 auto;
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  align-items: flex-start;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}
.index-feature-card {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card:hover {
  transform: scale(1.02);
}
.index-text04 {
  margin-bottom: var(--dl-space-space-twounits);
}
.index-image02 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-feature-card1 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card1:hover {
  transform: scale(1.02);
}
.index-text05 {
  margin-bottom: var(--dl-space-space-twounits);
}
.index-image03 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-feature-card2 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card2:hover {
  transform: scale(1.02);
}
.index-text06 {
  margin-bottom: var(--dl-space-space-twounits);
}
.index-image04 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-feature-card3 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card3:hover {
  transform: scale(1.02);
}
.index-text10 {
  margin-bottom: var(--dl-space-space-twounits);
}
.index-image05 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-feature-card4 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card4:hover {
  transform: scale(1.02);
}
.index-text14 {
  margin-bottom: var(--dl-space-space-twounits);
}
.index-image06 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-feature-card5 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card5:hover {
  transform: scale(1.02);
}
.index-text15 {
  margin-bottom: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-halfunit);
}
.index-image07 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-feature-card6 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.index-feature-card6:hover {
  transform: scale(1.02);
}
.index-text19 {
  margin-bottom: var(--dl-space-space-twounits);
}
.index-image08 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}
.index-stats {
  width: 100%;
  height: 303px;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  justify-content: center;
}
.index-stat {
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-items: center;
  flex-direction: column;
}
.index-icon10 {
  fill: var(--dl-color-gray-700);
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
}
.index-text23 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.index-text24 {
  color: var(--dl-color-gray-700);
  font-size: 0.75rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.index-text25 {
  font-size: 3rem;
  margin-top: var(--dl-space-space-halfunit);
  font-weight: 300;
}
.index-stat1 {
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-items: center;
  flex-direction: column;
}
.index-icon13 {
  fill: var(--dl-color-gray-700);
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
}
.index-text26 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.index-text27 {
  color: var(--dl-color-gray-700);
  font-size: 0.75rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.index-text31 {
  font-size: 3rem;
  margin-top: var(--dl-space-space-halfunit);
  font-weight: 300;
}
.index-stat2 {
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-items: center;
  flex-direction: column;
}
.index-icon15 {
  fill: var(--dl-color-gray-700);
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
}
.index-text33 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.index-text34 {
  color: var(--dl-color-gray-700);
  font-size: 0.75rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.index-text35 {
  font-size: 3rem;
  margin-top: var(--dl-space-space-halfunit);
  font-weight: 300;
}
.index-banner {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  align-items: center;
  flex-direction: column;
  background-size: cover;
  justify-content: space-between;
  background-image: url("/playground_assets/3wmy-1500w.gif");
}
.index-text37 {
  font-size: 3rem;
  text-align: center;
}
.index-text38 {
  color: var(--dl-color-gray-black);
  background-color: var(--dl-color-gray-white);
}
.index-link {
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  text-decoration: none;
  background-color: var(--dl-color-gray-white);
}
.index-link:hover {
  transform: scale(1.02);
}
.index-footer {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  border-color: #2f2f2f;
  border-width: 6px;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
  background-color: var(--dl-color-gray-white);
}
.index-container3 {
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.index-image09 {
  height: 2rem;
  margin-bottom: var(--dl-space-space-twounits);
}
.index-nav2 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.index-navlink2 {
  margin-left: 0px;
  text-decoration: none;
}
.index-navlink3 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.index-navlink4 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.index-navlink5 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.index-navlink6 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.index-separator {
  flex: 0 0 auto;
  width: 100%;
  height: 0px;
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  margin-left: 0px;
  border-color: var(--dl-color-gray-900);
  border-style: solid;
  border-width: 1px;
  margin-right: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.index-container4 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
@media(max-width: 991px) {
  .index-text03 {
    align-self: center;
  }
  .index-container2 {
    grid-template-columns: 1fr 1fr;
  }
}
@media(max-width: 767px) {
  .index-header {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .index-nav {
    display: none;
  }
  .index-btn-group {
    display: none;
  }
  .index-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .index-hero {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .index-features {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .index-stats {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .index-stat {
    padding: var(--dl-space-space-unit);
  }
  .index-text23 {
    text-align: center;
  }
  .index-stat1 {
    padding: var(--dl-space-space-unit);
  }
  .index-text26 {
    text-align: center;
  }
  .index-stat2 {
    padding: var(--dl-space-space-unit);
  }
  .index-text33 {
    text-align: center;
  }
  .index-banner {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .index-footer {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .index-image09 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .index-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .index-container4 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .index-text42 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .index-header {
    padding: var(--dl-space-space-unit);
  }
  .index-mobile-menu {
    padding: 16px;
  }
  .index-hero {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .index-features {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .index-container2 {
    grid-gap: var(--dl-space-space-halfunit);
  }
  .index-stats {
    align-items: center;
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .index-banner {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .index-footer {
    padding: var(--dl-space-space-unit);
  }
  .index-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .index-container4 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .index-text42 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>

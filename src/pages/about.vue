<template>
  <div class="about-container">
    <header data-role="Header" class="about-header">
      <router-link to="/" class="about-navlink">
        <img
          alt="logo"
          src="/playground_assets/opera%20snapshot_2022-03-02_170946_www.designhill.com-1500h.png"
          loading="lazy"
          class="about-image"
        />
      </router-link>
      <div class="about-nav">
        <navigation-links1 rootClassName="rootClassName12"></navigation-links1>
      </div>
      <div class="about-btn-group">
        <button class="about-login button">Login</button>
        <button class="button">Register</button>
      </div>
      <div data-type="BurgerMenu" class="about-burger-menu">
        <svg viewBox="0 0 1024 1024" class="about-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-type="MobileMenu" class="about-mobile-menu">
        <div class="about-nav1">
          <div class="about-container01">
            <img
              alt="image"
              src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
              class="about-image1"
            />
            <div data-type="CloseMobileMenu" class="about-menu-close">
              <svg viewBox="0 0 1024 1024" class="about-icon02">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <navigation-links1 rootClassName="rootClassName13"></navigation-links1>
        </div>
        <div>
          <svg viewBox="0 0 950.8571428571428 1024" class="about-icon04">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="about-icon06">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="about-icon08">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
    <div class="about-hero">
      <div class="about-container02">
        <h1 class="about-text">Plexi Music!</h1>
        <span class="about-text01">
          <span>
            Plexi is a high quality music bot having it&apos;s own website for its
            users
          </span>
          <br />
          <span>for better experience!</span>
        </span>
        <div class="about-btn-group1">
          <a
            href="https://discord.com/oauth2/authorize?client_id=940982266396569610&amp;permissions=8&amp;scope=bot"
            target="_blank"
            rel="noreferrer noopener"
            class="about-link button"
          >
            Invite Bot
          </a>
          <router-link to="/support" class="about-navlink1 button">
            Command &amp; Support
          </router-link>
        </div>
      </div>
      <img
        alt="image"
        src="/playground_assets/opera%20snapshot_2022-03-02_170946_www.designhill.com-1500h.png"
        class="about-image2"
      />
    </div>
    <div class="about-steps">
      <h1 class="about-text05"><span>Discover The Process</span></h1>
      <span class="about-text07"><span></span></span>
      <div class="about-container03">
        <div class="about-step">
          <div class="about-container04">
            <div class="about-line"></div>
            <div class="about-container05">
              <svg viewBox="0 0 877.7142857142857 1024" class="about-icon10">
                <path
                  d="M731.429 914.286c0-20-16.571-36.571-36.571-36.571s-36.571 16.571-36.571 36.571 16.571 36.571 36.571 36.571 36.571-16.571 36.571-36.571zM804.571 477.714c0-64.571-26.286-108-95.429-108-10.857 0-21.714 1.143-32 2.857-13.143-24-45.714-37.143-72-37.143-13.714 0-27.429 3.429-39.429 10.286-18.286-19.429-41.143-30.286-68-30.286-18.286 0-45.143 8-58.857 20v-189.143c0-39.429-33.714-73.143-73.143-73.143-38.857 0-73.143 34.857-73.143 73.143v329.143c-36 0-73.143-54.857-146.286-54.857-54.857 0-73.143 42.857-73.143 91.429 0 16 66.286 45.143 79.429 51.429 12.571 6.857 25.143 13.714 37.143 21.143 30.286 18.857 56.571 40.571 82.857 64 41.714 36.571 93.143 77.143 93.143 137.714v18.286h365.714v-18.286c0-100 73.143-197.714 73.143-308.571zM877.714 474.857c0 64-17.714 124.571-39.429 184-12.571 34.857-33.714 91.429-33.714 127.429v164.571c0 40.571-32.571 73.143-73.143 73.143h-365.714c-40.571 0-73.143-32.571-73.143-73.143v-164.571c0-27.429-49.143-66.286-68-82.857-23.429-20.571-46.857-40-73.714-57.143-53.143-33.143-150.857-57.714-150.857-134.286 0-90.857 49.714-164.571 146.286-164.571 25.143 0 49.714 4 73.143 12.571v-213.714c0-78.857 66.857-146.286 145.714-146.286 80 0 146.857 66.286 146.857 146.286v96.571c24 1.714 46.857 9.143 68 21.143 8-1.143 16.571-1.714 24.571-1.714 36.571 0 73.143 12 101.714 34.286 108-1.143 171.429 72.571 171.429 178.286z"
                ></path>
              </svg>
            </div>
            <div class="about-line1"></div>
          </div>
          <div class="about-container06">
            <h1 class="about-text09"><span>Click the Invite Button</span></h1>
            <span class="about-text11">
              <span>Leads you to the invite page</span>
              <br />
              <span></span>
            </span>
          </div>
        </div>
        <div class="about-step1">
          <div class="about-container07">
            <div class="about-line2"></div>
            <div class="about-container08">
              <svg viewBox="0 0 1024 1024" class="about-icon12">
                <path
                  d="M170 810h684v86h-684v-86zM682 554l-170 172-170-172h128v-426h84v426h128z"
                ></path>
              </svg>
            </div>
            <div class="about-line3"></div>
          </div>
          <div class="about-container09">
            <h1 class="about-text14">Click on Invite Bot</h1>
            <span class="about-text15">
              <span>Leads you to the discord authorize D</span>
              <span>
                icord bot page , select server
                <span v-html="rawj7kd"></span>
              </span>
              <br />
              <span>(Make sure you have admin!)</span>
            </span>
          </div>
        </div>
        <div class="about-step2">
          <div class="about-container10">
            <div class="about-line4"></div>
            <div class="about-container11">
              <svg viewBox="0 0 1024 1024" class="about-icon14">
                <path
                  d="M884 300l-78 78-160-160 78-78q12-12 30-12t30 12l100 100q12 12 12 30t-12 30zM128 736l472-472 160 160-472 472h-160v-160z"
                ></path>
              </svg>
            </div>
            <div class="about-line5"></div>
          </div>
          <div class="about-container12">
            <h1 class="about-text20"><span>Create a Channel</span></h1>
            <span class="about-text22">
              <span>Create a separate channel for Plexi and type !setup</span>
              <br />
              <span></span>
            </span>
          </div>
        </div>
        <div class="about-step3">
          <div class="about-container13">
            <div class="about-line6"></div>
            <div class="about-container14">
              <svg viewBox="0 0 1024 1024" class="about-icon16">
                <path d="M384 692l452-454 60 60-512 512-238-238 58-60z"></path>
              </svg>
            </div>
            <div class="about-line7"></div>
          </div>
          <div class="about-container15">
            <h1 class="about-text25">Final Step</h1>
            <span class="about-text26">
              Join a VC and type a song&apos;s name in the channel!
            </span>
          </div>
        </div>
      </div>
      <footer class="about-footer">
        <div class="about-container16">
          <img
            alt="logo"
            src="/playground_assets/opera%20snapshot_2022-03-02_170946_www.designhill.com-1500h.png"
            class="about-image3"
          />
          <nav class="about-nav2">
            <router-link to="/about" class="about-navlink2">About</router-link>
            <router-link to="/features" class="about-navlink3">
              Features
            </router-link>
            <router-link to="/invite-bot" class="about-navlink4">
              Invite Bot
            </router-link>
            <router-link to="/stream" class="about-navlink5">Stream</router-link>
            <router-link to="/support" class="about-navlink6">
              Support
            </router-link>
          </nav>
        </div>
        <div class="about-separator"></div>
        <div class="about-container17">
          <span class="about-text27">© 2022 Plexi Music</span>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import NavigationLinks1 from '../components/navigation-links1'

export default {
  name: 'About',
  components: {
    NavigationLinks1,
  },

  data() {
    return {
      rawj7kd: ' ',
    }
  },

  metaInfo: {
    title: 'About - New Project',
    meta: [
      {
        property: 'og:title',
        content: 'About - New Project',
      },
    ],
  },
}
</script>

<style scoped>
.about-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.about-header {
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
.about-navlink {
  display: contents;
}
.about-image {
  width: 98px;
  height: 57px;
  text-decoration: none;
}
.about-nav {
  display: flex;
}
.about-btn-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.about-login {
  border-width: 0px;
  margin-right: var(--dl-space-space-twounits);
}
.about-burger-menu {
  display: none;
}
.about-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.about-mobile-menu {
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
.about-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.about-container01 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.about-image1 {
  height: 2rem;
}
.about-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.about-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.about-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.about-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.about-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.about-hero {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  min-height: 80vh;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.about-container02 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.about-text {
  font-size: 3rem;
  max-width: 450px;
}
.about-text01 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.about-btn-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.about-link {
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.about-link:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-gray-black);
}
.about-navlink1 {
  transition: 0.3s;
  margin-left: var(--dl-space-space-unit);
  padding-top: var(--dl-space-space-unit);
  border-color: transparent;
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.about-navlink1:hover {
  border-color: var(--dl-color-gray-black);
}
.about-image2 {
  width: 400px;
  object-fit: cover;
}
.about-steps {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
}
.about-text05 {
  color: var(--dl-color-gray-black);
  font-size: 3rem;
}
.about-text07 {
  color: var(--dl-color-gray-700);
  font-size: 1.15rem;
  max-width: 600px;
  margin-top: var(--dl-space-space-unit);
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.about-container03 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.about-step {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.about-container04 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: 2px;
  padding-right: 2px;
  flex-direction: row;
  justify-content: center;
}
.about-line {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: transparent;
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container05 {
  flex: 0 0 auto;
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  display: flex;
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: row;
  justify-content: center;
  background-color: #f5f5f5ff;
}
.about-icon10 {
  width: 24px;
  height: 24px;
}
.about-line1 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-gray-900);
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container06 {
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.about-text09 {
  font-size: 1.5rem;
  text-align: center;
  font-weight: 500;
  margin-bottom: var(--dl-space-space-unit);
}
.about-text11 {
  color: var(--dl-color-gray-500);
  font-size: 0.75rem;
  text-align: center;
}
.about-step1 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.about-container07 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: 2px;
  padding-right: 2px;
  flex-direction: row;
  justify-content: center;
}
.about-line2 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-gray-900);
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container08 {
  flex: 0 0 auto;
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  display: flex;
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: row;
  justify-content: center;
  background-color: #f5f5f5ff;
}
.about-icon12 {
  width: 24px;
  height: 24px;
}
.about-line3 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-gray-900);
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container09 {
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.about-text14 {
  font-size: 1.5rem;
  text-align: center;
  font-weight: 500;
  margin-bottom: var(--dl-space-space-unit);
}
.about-text15 {
  color: var(--dl-color-gray-500);
  font-size: 0.75rem;
  text-align: center;
}
.about-step2 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.about-container10 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: 2px;
  padding-right: 2px;
  flex-direction: row;
  justify-content: center;
}
.about-line4 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-gray-900);
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container11 {
  flex: 0 0 auto;
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  display: flex;
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: row;
  justify-content: center;
  background-color: #f5f5f5ff;
}
.about-icon14 {
  width: 24px;
  height: 24px;
}
.about-line5 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-gray-900);
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container12 {
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.about-text20 {
  font-size: 1.5rem;
  text-align: center;
  font-weight: 500;
  margin-bottom: var(--dl-space-space-unit);
}
.about-text22 {
  color: var(--dl-color-gray-500);
  font-size: 0.75rem;
  text-align: center;
}
.about-step3 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.about-container13 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: 2px;
  padding-right: 2px;
  flex-direction: row;
  justify-content: center;
}
.about-line6 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-gray-900);
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container14 {
  flex: 0 0 auto;
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  display: flex;
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: row;
  justify-content: center;
  background-color: #f5f5f5ff;
}
.about-icon16 {
  width: 24px;
  height: 24px;
}
.about-line7 {
  flex: 1;
  height: 0px;
  display: flex;
  align-items: flex-start;
  border-color: transparent;
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
  border-left-width: 0px;
  border-right-width: 0px;
  border-bottom-width: 0px;
}
.about-container15 {
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.about-text25 {
  font-size: 1.5rem;
  text-align: center;
  font-weight: 500;
  margin-bottom: var(--dl-space-space-unit);
}
.about-text26 {
  color: var(--dl-color-gray-500);
  font-size: 0.75rem;
  text-align: center;
}
.about-footer {
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
.about-container16 {
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.about-image3 {
  height: 2rem;
  margin-bottom: var(--dl-space-space-twounits);
}
.about-nav2 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.about-navlink2 {
  margin-left: 0px;
  text-decoration: none;
}
.about-navlink3 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.about-navlink4 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.about-navlink5 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.about-navlink6 {
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
}
.about-separator {
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
.about-container17 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
@media(max-width: 991px) {
  .about-hero {
    flex-direction: column;
  }
  .about-container02 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .about-text {
    text-align: center;
  }
  .about-text01 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .about-text05 {
    text-align: center;
  }
  .about-text07 {
    text-align: center;
  }
}
@media(max-width: 767px) {
  .about-header {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .about-nav {
    display: none;
  }
  .about-btn-group {
    display: none;
  }
  .about-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .about-hero {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .about-text01 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .about-image2 {
    width: 80%;
  }
  .about-steps {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .about-container03 {
    align-items: flex-start;
    padding-left: var(--dl-space-space-fiveunits);
    flex-direction: column;
  }
  .about-step {
    width: 100%;
    height: auto;
    flex-direction: row;
    justify-content: center;
  }
  .about-container04 {
    width: var(--dl-size-size-small);
    height: auto;
    align-self: stretch;
    padding-top: 0px;
    padding-left: 0px;
    padding-right: 0px;
    flex-direction: column;
    padding-bottom: 2px;
    justify-content: space-between;
  }
  .about-line1 {
    border-color: var(--dl-color-gray-900);
    border-style: dashed;
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-container06 {
    width: 100%;
    align-items: flex-start;
    padding-top: var(--dl-space-space-twounits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-twounits);
    justify-content: space-between;
  }
  .about-text09 {
    margin-top: var(--dl-space-space-twounits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .about-text11 {
    text-align: left;
  }
  .about-step1 {
    width: 100%;
    height: auto;
    flex-direction: row;
    justify-content: center;
  }
  .about-container07 {
    width: var(--dl-size-size-small);
    height: auto;
    align-self: stretch;
    padding-top: 0px;
    padding-left: 0px;
    padding-right: 0px;
    flex-direction: column;
    padding-bottom: 2px;
    justify-content: space-between;
  }
  .about-line2 {
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-line3 {
    border-color: var(--dl-color-gray-900);
    border-style: dashed;
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-container09 {
    width: 100%;
    align-items: flex-start;
    padding-top: var(--dl-space-space-twounits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-twounits);
    justify-content: space-between;
  }
  .about-text14 {
    margin-top: var(--dl-space-space-twounits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .about-text15 {
    text-align: left;
  }
  .about-step2 {
    width: 100%;
    height: auto;
    flex-direction: row;
    justify-content: center;
  }
  .about-container10 {
    width: var(--dl-size-size-small);
    height: auto;
    align-self: stretch;
    padding-top: 0px;
    padding-left: 0px;
    padding-right: 0px;
    flex-direction: column;
    padding-bottom: 2px;
    justify-content: space-between;
  }
  .about-line4 {
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-line5 {
    border-color: var(--dl-color-gray-900);
    border-style: dashed;
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-container12 {
    width: 100%;
    align-items: flex-start;
    padding-top: var(--dl-space-space-twounits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-twounits);
    justify-content: space-between;
  }
  .about-text20 {
    margin-top: var(--dl-space-space-twounits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .about-text22 {
    text-align: left;
  }
  .about-step3 {
    width: 100%;
    height: auto;
    flex-direction: row;
    justify-content: center;
  }
  .about-container13 {
    width: var(--dl-size-size-small);
    height: auto;
    align-self: stretch;
    padding-top: 0px;
    padding-left: 0px;
    padding-right: 0px;
    flex-direction: column;
    padding-bottom: 2px;
    justify-content: space-between;
  }
  .about-line6 {
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-line7 {
    border-color: transparent;
    border-style: dashed;
    border-top-width: 0px;
    border-left-width: 2px;
  }
  .about-container15 {
    width: 100%;
    align-items: flex-start;
    padding-top: var(--dl-space-space-twounits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-twounits);
    justify-content: space-between;
  }
  .about-text25 {
    margin-top: var(--dl-space-space-twounits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .about-text26 {
    text-align: left;
  }
  .about-footer {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .about-image3 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .about-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .about-container17 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .about-text27 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .about-header {
    padding: var(--dl-space-space-unit);
  }
  .about-mobile-menu {
    padding: 16px;
  }
  .about-hero {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .about-container02 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .about-btn-group1 {
    flex-direction: column;
  }
  .about-navlink1 {
    margin-top: var(--dl-space-space-unit);
    margin-left: 0px;
  }
  .about-steps {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .about-container03 {
    padding-left: 0px;
  }
  .about-container06 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: 0px;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .about-text09 {
    margin-left: 0px;
    margin-right: var(--dl-space-space-twounits);
  }
  .about-container09 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: 0px;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .about-text14 {
    margin-left: 0px;
    margin-right: var(--dl-space-space-twounits);
  }
  .about-container12 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: 0px;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .about-text20 {
    margin-left: 0px;
    margin-right: var(--dl-space-space-twounits);
  }
  .about-container15 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: 0px;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .about-text25 {
    margin-left: 0px;
    margin-right: var(--dl-space-space-twounits);
  }
  .about-footer {
    padding: var(--dl-space-space-unit);
  }
  .about-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .about-container17 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .about-text27 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>

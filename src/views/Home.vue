<template>
  <div class="page-wrapper" :class="{'theme-light' : isLightTheme}">
    <section class="header-section">
      <div class="header-content">
        <h1>Social Media Dashboard</h1>
        <p>Total Followers: 23,004</p>
      </div>

      <div class="theme-toggle-wrapper">
        <p>Dark Mode</p>

        <div class="toggler" @click="changeTheme" :class="{'is-active' : isLightTheme}">
          <span class="toggler-circle"></span>
        </div>
      </div>
    </section>

    <section class="main-social-wrapper">
      <div class="social-big-card facebook-card">
        <div class="social-account">
          <img src="@/assets/img/icon-facebook.svg" alt="Facebook" />
          <p>@Hartes_Desfel</p>
        </div>

        <div class="social-numbers">
          <p class="social-followers">1987</p>
          <p class="follower-text">Followers</p>
        </div>

        <div class="social-stats">
          <img src="@/assets/img/icon-up.svg" alt="Up" />
          <p>12 Today</p>
        </div>
      </div>

      <div class="social-big-card twitter-card">
        <div class="social-account">
          <img src="@/assets/img/icon-twitter.svg" alt="Twitter" />
          <p>@Hartes_Desfel</p>
        </div>

        <div class="social-numbers">
          <p class="social-followers">1044</p>
          <p class="follower-text">Followers</p>
        </div>

        <div class="social-stats">
          <img src="@/assets/img/icon-up.svg" alt="Up" />
          <p>99 Today</p>
        </div>
      </div>

      <div class="social-big-card insta-card">
        <div class="social-account">
          <img src="@/assets/img/icon-instagram.svg" alt="Instagram" />
          <p>@Hartes_Desfel</p>
        </div>

        <div class="social-numbers">
          <p class="social-followers">11k</p>
          <p class="follower-text">Followers</p>
        </div>

        <div class="social-stats">
          <img src="@/assets/img/icon-up.svg" alt="Up" />
          <p>1099 Today</p>
        </div>
      </div>

      <div class="social-big-card youtube-card">
        <div class="social-account">
          <img src="@/assets/img/icon-youtube.svg" alt="Youtube" />
          <p>Hartes_Desfel</p>
        </div>

        <div class="social-numbers">
          <p class="social-followers">8239</p>
          <p class="follower-text">Followers</p>
        </div>

        <div class="social-stats">
          <img src="@/assets/img/icon-down.svg" alt="Up" />
          <p class="down-stats">144 Today</p>
        </div>
      </div>
    </section>

    <section class="sub-social-wrapper">
      <h2>Overview - Today</h2>

      <section class="sub-social-cards">
        <div class="sub-social-card">
          <div class="top-row">
            <p>Page Views</p>
            <img src="@/assets/img/icon-facebook.svg" alt="Facebook" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">87</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-up.svg" alt="Up" />
              <p class="stats-number">3%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Likes</p>
            <img src="@/assets/img/icon-facebook.svg" alt="Facebook" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">52</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-down.svg" alt="Down" />
              <p class="stats-number down-stats">2%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Likes</p>
            <img src="@/assets/img/icon-instagram.svg" alt="Instagram" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">5462</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-up.svg" alt="Up" />
              <p class="stats-number">2257%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Profile Views</p>
            <img src="@/assets/img/icon-instagram.svg" alt="Instagram" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">52k</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-up.svg" alt="Up" />
              <p class="stats-number">1375%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Retweets</p>
            <img src="@/assets/img/icon-twitter.svg" alt="Twitter" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">117</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-up.svg" alt="Up" />
              <p class="stats-number">303%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Likes</p>
            <img src="@/assets/img/icon-twitter.svg" alt="Twitter" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">507</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-up.svg" alt="Up" />
              <p class="stats-number">553%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Likes</p>
            <img src="@/assets/img/icon-youtube.svg" alt="Youtube" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">107</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-down.svg" alt="Down" />
              <p class="stats-number down-stats">19%</p>
            </div>
          </div>
        </div>

        <div class="sub-social-card">
          <div class="top-row">
            <p>Total Views</p>
            <img src="@/assets/img/icon-youtube.svg" alt="Youtube" />
          </div>
          <div class="bottom-row">
            <p class="follows-number">1407</p>

            <div class="stats-wrapper">
              <img src="@/assets/img/icon-down.svg" alt="Down" />
              <p class="stats-number down-stats">12%</p>
            </div>
          </div>
        </div>
      </section>
    </section>
  </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
  data() {
    return {
      isLightTheme: false
    }
  },
  head() {
    return {
      title: {
        inner: 'Home'
      },
      meta: [
        {
          name: 'description',
          content: `${this.appTitle} home page`,
          id: 'desc'
        }
      ]
    }
  },
  methods: {
    changeTheme(e) {
      e.preventDefault()
      this.isLightTheme = !this.isLightTheme;
    }
  },
  computed: mapState('app', ['appTitle'])
}
</script>

<style lang="scss" scoped>
@import '@/theme/variables.scss';
@import '@/theme/header.scss';
@import '@/theme/main-social.scss';
@import '@/theme/sub-social.scss';

.page-wrapper {
  position: relative;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  height: 100%;
  background: var(--bgColor);
  padding: 36px 10%;

  @media (max-width: 768px) {
    padding: 36px 24px;
  }

  &:after {
    content: '';
    width: 100%;
    height: 244px;
    position: absolute;
    top: 0;
    left: 0;
    background: var(--topBgColor);
    border-radius: 0 0 20px 20px;
    z-index: 1;
  }
}
</style>

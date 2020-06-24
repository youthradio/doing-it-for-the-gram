<template>
  <div class="vh-100-ns flex flex-column bg-dark-gray white assistant relative">
    <MenuHeader
      class="z-10"
      :menu-fixed="true"
    />
    <!-- Slider main container -->
    <div
      ref="container"
      class="swiper-container h-100 w-100 bg-dark-gray"
    >
      <!-- Additional required wrapper -->
      <div class="swiper-wrapper">
        <!-- Slides -->
        <swiper-slide>
          <div class="flex items-center h-100 w-100 bg-dark-gray white cover" style="background:url(featurex1125.jpg) no-repeat center;">
            <article class="measure ml6-ns ph3">
              <h1 class="day-sans f1-ns f2 lh-title">
                DOING IT FOR THE ‘GRAM
              </h1>
              <h3 class="roboto-mono fw3 f3-ns f4 lh-title">
                Five Social Media Moves That Helped Or Hurt #BlackLivesMatter
              </h3>
              <h4 class="assistant normal">
                By Zoe Harwood
              </h4>
              <h4 class="assistant normal">
                06.23.20
              </h4>
            </article>
          </div>
        </swiper-slide>
        <swiper-slide>
          <article class="measure lh-copy ph3">
            <p>
              We use platforms like Instagram, Twitter and TikTok to share trivial details of our day-to-day lives and  exchange serious information, resources and calls-to-action about important things going on across the world — from COVID-19 to Black Lives Matter.
            </p>
            <p>
              But whenever hashtags start to trend, things also get complicated. How have efforts like #blackouttuesday impacted the movement for Black lives, in productive or harmful ways? To answer that question, we’re taking a look at five moments produced by social media that shine a light on the best and worst of these platforms as solidarity tools.
            </p>
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="flex flex-column flex-row-ns w-100 justify-center items-center ph3">
            <main class="flex-grow-0">
              <h3 class="roboto-mono fw6 f3-ns f4 lh-title">
                BLACKOUT TUESDAY
              </h3>
              <div class="measure-narrow-ns measure lh-copy">
                <p>
                  Blackout Tuesday, initially dubbed <a target="_blank" class="link green dim underline" href="https://www.theshowmustbepaused.com/about">#TheShowMustBePaused by Jamila Thomas and Brianna Agyemang</a>, was a way to memorialize the deaths of George Floyd and Breonna Taylor. The idea, which <a target="_blank" class="link green dim underline" href="https://www.nytimes.com/2020/06/02/arts/music/what-blackout-tuesday.html">originated in the music industry</a>, soon caught on, and people across social media started posting black squares as a sign of solidarity.
                </p>
                <p>
                  The only problem? Because people were adding #blacklivesmatter to those posts, social media algorithms boosted images of black squares instead of important information related to Black Lives Matter organizing.
                </p>
              </div>
            </main>
            <div class="pl3-ns">
              <object
                class="disable-mouse db dn-ns"
                data="images/blackouttuesday_SVG-mobile.svg"
                type="image/svg+xml"
                alt="Screenshot of Instagram feed shows results of #blacklivesmatter with the following annotations: Black squares flooded Instagram on June 2nd / Vital information on protests got lost on users' feed and searches / Quote by Victoria Balla: People are just posting because it's a trend. They know that if they didn't people would call them out for being a racist or for not supporting the movement. So, a lot of it is not genuine."
              >
                <img src="yourfallback.jpg">
              </object>
              <object
                class="disable-mouse dn db-ns mw-500"
                data="images/blackouttuesday_SVG-desktop.svg"
                type="image/svg+xml"
                alt="Black squares flooded Instagram on June 2nd / Vital information on protests got lost on users' feed and searches / Quotation by Victoria Balla: People are just posting because it's a trend. They know that if they didn't people would call them out for being a racist or for not supporting the movement. So, a lot of it is not genuine."
              >
                <img src="yourfallback.jpg">
              </object>
            </div>
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="flex flex-column flex-row-ns w-100 justify-center items-center ph3">
            <main class="flex-grow-0">
              <h3 class="roboto-mono fw6 f3-ns f4 lh-title">
                WHITEOUT WEDNESDAY
              </h3>
              <div class="measure-narrow-ns measure lh-copy">
                <p>
                  In response to Blackout Tuesday, white supremacists decided to create their own event and hashtag, #whiteoutwednesday, to advance their racist agenda. However, <a target="_blank" class="link green dim underline" href="https://yr.media/arts-culture/k-pop-fans-get-creative-to-thwart-online-trolls/">K-pop fans</a> caught on and decided to flood the hashtag with videos of their favorite stars. Soon, K-pop videos were all you could see when you searched #whiteoutwednesday or #whitelivesmatter.
                </p>
                <p>
                  This isn’t the first time K-pop fans have done this kind of thing. When the Dallas Police department tried using a video app to identify protesters, K-pop fans <a target="_blank" class="link green dim underline" href="https://www.theverge.com/2020/6/1/21277423/k-pop-dallas-pd-iwatch-app-flood-review-bomb-surveillance-protests-george-floyd">flooded the app</a> with videos of their top stars and crashed the app. More recently, K-pop stans, along with TikTok users, have taken some credit for <a target="_blank" class="link green dim underline" href="https://www.nytimes.com/2020/06/21/style/tiktok-trump-rally-tulsa.html">Trump’s underwhelming Tulsa rally on June 20th</a> — reporting that they registered thousands of tickets and then didn’t show up, creating a prime photo op: rows of empty seats.
                </p>
              </div>
            </main>
            <div class="pl3-ns">
              <object
                class="disable-mouse db dn-ns"
                data="images/whiteoutwednesday_SVG-mobile.svg"
                type="image/svg+xml"
                alt="Screenshot of Instagram feed shows K-pop content on #whiteoutwednesday with the following annotations: As of June 9th, Instagram counts 92,000+ posts under #whiteoutwednesday / K-pop content was also flooding related hastags like #whitelivesmatter, #copslivesmatter, #bluelivesmatter, and #trump2020 / Quote by Ariel Tang: I think all sides of the Internet coming together to try and contribute in some way is kind of crazy. It shows solidarity which I think is really cool."
              >
                <img src="yourfallback.jpg">
              </object>
              <object
                class="disable-mouse dn db-ns mw-500"
                data="images/whiteoutwednesday_SVG-desktop.svg"
                type="image/svg+xml"
                alt="Screenshot of Instagram feed shows K-pop content on #whiteoutwednesday with the following annotations: As of June 9th, Instagram counts 92,000+ posts under #whiteoutwednesday / K-pop content was also flooding related hastags like #whitelivesmatter, #copslivesmatter, #bluelivesmatter, and #trump2020 / Quote by Ariel Tang: I think all sides of the Internet coming together to try and contribute in some way is kind of crazy. It shows solidarity which I think is really cool."
              >
                <img src="yourfallback.jpg">
              </object>
            </div>
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="flex flex-column flex-row-ns w-100 justify-center items-center ph3">
            <main class="flex-grow-0">
              <h3 class="roboto-mono fw6 f3-ns f4 lh-title">
                SHADOW BAN CONTROVERSY
              </h3>
              <div class="measure-narrow-ns measure lh-copy">
                <p>
                  TikTok has been accused of preventing people from seeing posts with the hashtags #blacklivesmatter and #GeorgeFloyd.
                </p>
                <p>
                  Users <a target="_blank" class="link green dim underline" href="https://www.reuters.com/article/uk-factcheck-tiktok/fact-check-the-blacklivesmatter-hashtag-is-not-banned-on-tiktok-idUSKBN2360OT">reported</a> that when they searched for the terms “blacklivesmatter” and “GeorgeFloyd,” there were 0 views. TikTok claimed that, rather than a deliberate attempt at blocking the hashtags, the problem was a glitch that also affected terms like #cat and #hello. Still, many users speculate that TikTok purposefully censored the phrases. Glitch or not, the issue has been resolved and when you search for those same terms on TikTok now, you should get a full view count.
                </p>
              </div>
            </main>
            <div class="pl3-ns">
              <object
                class="disable-mouse db dn-ns"
                data="images/shadowbans_SVG-mobile.svg"
                type="image/svg+xml"
                alt="Screenshot of TikTok search with the following annotations: Both #blacklivesmatter and #GeorgeFloyd appears to have zero views in the days following national outrage of George Floyd’s killing / Users tried modifying hashtags in an attempt to get their content viewed by others"
              >
                <img src="yourfallback.jpg">
              </object>
              <object
                class="disable-mouse dn db-ns mw-500"
                data="images/shadowbans_SVG-desktop.svg"
                type="image/svg+xml"
                alt="Screenshot of TikTok search with the following annotations: Both #blacklivesmatter and #GeorgeFloyd appears to have zero views in the days following national outrage of George Floyd’s killing / Users tried modifying hashtags in an attempt to get their content viewed by others"
              >
                <img src="yourfallback.jpg">
              </object>
            </div>
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="flex flex-column flex-row-ns w-100 justify-center items-center ph3">
            <main class="flex-grow-0">
              <h3 class="roboto-mono fw6 f3-ns f4 lh-title">
                FAKE ACTIVISM
              </h3>
              <div class="measure-narrow-ns measure lh-copy">
                <p>
                  While a lot of people have been doing real work to bring about change, some have been using theatrics to get more likes. One example includes a <a target="_blank" class="link green dim underline" href="https://nypost.com/2020/06/02/woman-goes-viral-for-pretending-to-board-up-store-from-looters/">
                    woman</a> who stopped a worker from boarding up stores in Santa Monica to borrow their drill for a photo op. She then walked back into her Mercedes-Benz and drove away.
                </p>
                <p>
                  <a target="_blank" class="link green dim underline" href="https://twitter.com/ewufortheloss/status/1267539200846389249">People soon caught on to what she was doing and called her out.</a>
                </p>
              </div>
            </main>
            <div class="pl3-ns">
              <object
                class="disable-mouse db dn-ns"
                data="images/tiktok-convos_SVG-desktop-mobile.svg"
                type="image/svg+xml"
                alt="Screenshot of Twitter video by user ewufortheloss depicting a woman stopping a worker from boarding up store windows in Santa Monica, California to pose for a photo with the following annotations: Pointing at how the she is holding the drill at a tilted angle: You really don’t want want to be holding the drill like that though… / Pointing at the shoes she is wearing: Would anyone really be wearing sandals like this while working with power tools?! / Pointing at worker who was stopped: Essential worker appears to also be posing, presumably to make her photo look more real / Sarcastically adding: #4daclout, #BLM, #communityservice"
              >
                <img src="yourfallback.jpg">
              </object>
              <object
                class="disable-mouse dn db-ns mw-500"
                data="images/fakeactivism_SVG-desktop.svg"
                type="image/svg+xml"
                alt="Screenshot of Twitter video by user ewufortheloss depicting a woman stopping a worker from boarding up store windows in Santa Monica, California to pose for a photo with the following annotations: Pointing at how the she is holding the drill at a tilted angle: You really don’t want want to be holding the drill like that though… / Pointing at the shoes she is wearing: Would anyone really be wearing sandals like this while working with power tools?! / Pointing at worker who was stopped: Essential worker appears to also be posing, presumably to make her photo look more real / Sarcastically adding: #4daclout, #BLM, #communityservice"
              >
                <img src="yourfallback.jpg">
              </object>
            </div>
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="flex flex-column flex-row-ns w-100 justify-center items-center ph3">
            <main class="flex-grow-0">
              <h3 class="roboto-mono fw6 f3-ns f4 lh-title">
                TALKING TIKTOK
              </h3>
              <div class="measure-narrow-ns measure lh-copy">
                <p>
                  In attempts at solidarity, some non-Black teenagers are recording tough conversations (and their reactions) with their parents about the death of George Floyd and the importance of Black Lives Matter, and then posting them on TikTok. One of the most viral of these was posted by <a target="_blank" class="dib link green dim underline" href="https://www.insider.com/tiktok-george-floyd-black-lives-matter-teens-parents-racist-views-2020-6">Izabella</a>, a 15-year-old girl in Louisiana, upset by her family’s response. While she wasn’t able to have the talk she wanted, she found support from others online.
                </p>
                <p>
                  If you see yourself as an ally to Black communities and you’re considering posting about a conversation where you’ve called out your parents, keep an eye out for the tendency to make this moment all about yourself and try not to get caught up in wanting tons of "credit" for the necessary work you’re doing.
                </p>
              </div>
            </main>
            <div class="pl3-ns">
              <object
                class="disable-mouse db dn-ns"
                data="images/tiktok-convos_SVG-mobile.svg"
                type="image/svg+xml"
                alt="Screenshot of viral TikTok video from user Izabella Miletello depicting her distraught and crying face with the following annotations: Teens are expressing distress and anger after tough convos with their parents about race / Quote by Ariel Tang: It’s hard talking to family members about it because they just try to not get involved in politics. Because, you know, it’s the culture of assimilation. So, it’s been difficult, but I’m still working at it."
              >
                <img src="yourfallback.jpg">
              </object>
              <object
                class="disable-mouse dn db-ns mw-500"
                data="images/tiktok-convos_SVG-desktop.svg"
                type="image/svg+xml"
                alt="Screenshot of viral TikTok video from user Izabella Miletello depicting her distraught and crying face with the following annotations: Teens are expressing distress and anger after tough convos with their parents about race / Quote by Ariel Tang: It’s hard talking to family members about it because they just try to not get involved in politics. Because, you know, it’s the culture of assimilation. So, it’s been difficult, but I’m still working at it."
              >
                <img src="yourfallback.jpg">
              </object>
            </div>
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="measure lh-copy ph3">
            <p>
              In the days of perpetual quarantine when we can’t connect as easily off-line, social media is more important than ever. But if we’re going to depend this heavily on these platforms, we have to use them to impact real change. We can’t just post black squares on Instagram and say we’re done, nor can we pick up a drill just to make it look like we’re doing something. We actually have to do it.
            </p>
          </article>
        </swiper-slide>

        <swiper-slide>
          <article class="measure lh-copy ph3">
            <p>So what are some things you can do? </p>
            <ol class="list ph0">
              <li class="pv3 bb bt b--white-20">
                Got some spare change? Donate to an organization fighting for racial justice. Money is power, and every little bit helps.
              </li>
              <li class="pv3 bb bt b--white-20">
                Protest. Get your mask, make some signs, and get out of the house! Make your voice heard. Unable to make it out to protests? Call your elected officials and let them know you stand with the Black Lives Matter movement.
              </li>
              <li>Stay informed. Knowledge is also power, and you can take this opportunity to learn more. Read a book or watch a documentary on the systemic racism of our country. Understand just what we’re facing and what we need to do to fix the problem.</li>
              <li class="pv3 bb bt b--white-20">
                Need to get some things off your chest? Talk openly to others about the Black Lives Matter movement and police brutality — whether it’s someone who agrees with you or someone who might not. If you're lucky, you might even change someone’s mind!
              </li>
              <li class="pv3 bb bt b--white-20">
                Keep those Instagram posts and TikToks going — and don’t just post one thing to show your friends you’re not racist. Post on the subject over and over and over again, and pay attention to responses so you keep learning.
              </li>
            </ol>
            <p>
              Social media can — and has — sparked real-world change, but that change doesn't happen on its own. So keep fighting!
            </p>

            <ShareContainer />
          </article>
        </swiper-slide>
        <swiper-slide>
          <article class="ph3">
            <h3 class="roboto-mono fw6 f3-ns f4 lh-title">
              CREDITS
            </h3>
            <dl class="f6 lh-title mv2">
              <dt class="dib b green">
                Writer
              </dt>
              <dd class="dib ml0">
                Zoe Harwood
              </dd>
            </dl>
            <dl class="f6 lh-title mv2">
              <dt class="dib b green">
                Editors
              </dt>
              <dd class="dib ml0">
                Marjerrie Masicat, Lissa Soep
              </dd>
            </dl>
            <dl class="f6 lh-title mv2">
              <dt class="dib b green">
                Producers
              </dt>
              <dd class="dib ml0">
                Victoria Balla, Zoe Harwood, Dante Ruberto, Ariel Tang, Nimah Gobir, Devin Glover
              </dd>
            </dl>
            <dl class="f6 lh-title mv2">
              <dt class="dib b green">
                Designer
              </dt>
              <dd class="dib ml0">
                Marjerrie Masicat
              </dd>
            </dl>
            <dl class="f6 lh-title mv2">
              <dt class="dib b green">
                Developer
              </dt>
              <dd class="dib ml0">
                Radamés Ajna
              </dd>
            </dl>
          </article>
        </swiper-slide>
      </div>
      <!-- If we need pagination -->
      <div
        ref="pagination"
        class="swiper-pagination"
      />

      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev" />
      <div class="swiper-button-next" />

      <!-- If we need scrollbar -->
      <div class="swiper-scrollbar" />
    </div>
  </div>
</template>

<script>

import Swiper from 'swiper'
import CommonUtils from '../mixins/CommonUtils'
import MenuHeader from '~/components/Header/MenuHeader'
import ShareContainer from '~/components/Custom/ShareContainer'
import SwiperSlide from '~/components/Custom/SwiperSlide'

export default {
  components: {
    MenuHeader,
    ShareContainer,
    SwiperSlide
  },
  mixins: [
    CommonUtils
  ],
  asyncData (ctx) {
    return {
    }
  },
  data () {
    return {
      swiper: null
    }
  },
  computed: {},
  watch: {

  },
  mounted () {
    // initialize swiper when document ready
    if (window.innerWidth > 900) {
      this.swiper = new Swiper(this.$refs.container, {
        loop: false,
        keyboard: {
          enabled: true,
          onlyInViewport: false
        },
        mousewheel: {
          eventsTarget: document.body,
          sensitivity: 1,
          releaseOnEdges: true
        },
        direction: 'vertical',

        pagination: {
          el: this.$refs.pagination,
          clickable: true,
          renderBullet (index, className) {
            return `<span class="${className}"></span>`
          }
        }
        // navigation: {
        //   nextEl: '.swiper-button-next',
        //   prevEl: '.swiper-button-prev'
        // }
      })
    }
  },
  methods: {

  }
}
</script>

<style lang="scss">
@import "~@/assets/css/styles";
@media screen and (min-width: 50em) {
  @import "~@/node_modules/swiper/swiper";
  .swiper-pagination {
    position: absolute;
    display: flex;
    flex-direction: column;
    z-index: 1;
    bottom: 0;
    right: 0;
    padding: 0.5rem;
  }
  .swiper-pagination-bullet {
    background-color: rgba(white, 0.2);
    height: 10px;
    width: 10px;
    border-radius: 99999px;
    display: inline-block;
    margin: 0.1rem;
    cursor: pointer;
  }

  .swiper-pagination-bullet-active {
    background-color: rgba(white, 0.9);
  }
}
.disable-mouse {
  pointer-events: none;
}
</style>

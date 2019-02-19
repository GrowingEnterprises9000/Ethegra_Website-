<template>
  <div class="wrapper">
    <parallax class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">
    			<div class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100">
    				<h1 class="title">Revolutionary Technologies for to Revolutionize communities</h1>
              <h4>We are building the Technologies that will transform our communities and help us create the path to self-determfininiation. Our goal is to make our communities healthier and create a better living standard</h4>
              <br>

    			</div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
              <h2 class="title text-center">What we do</h2>
              <h5 class="description">We work with mission driven organizations and community members to target problems that affect people the most deeply and have an affect on daily life. We then take those problems and boil them down into parts that have a solution. Once we are sure our solution works we then work with organizations to install these solutions and affect change. The result is that our community becomes a little better and a little healthier.</h5>
            </div>
          </div>
          <div class="features text-center">
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <div class="icon icon-info">
                    <md-icon>chat</md-icon>
                  </div>
                  <h4 class="info-title">Submit problem</h4>
                  <p>We work in food acess, infrasturture and transportation as well as public health</p>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                  <div class="info">
                    <div class="icon icon-success">
                      <md-icon>verified_user</md-icon>
                    </div>
                    <h4 class="info-title">Something Happens</h4>
                    <p>Divide details about your product or agency work into parts. Write a few lines about each one. A paragraph describing a feature will be enough.</p>
                  </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                  <div class="info">
                    <div class="icon icon-danger">
                      <md-icon>fingerprint</md-icon>
                    </div>
                    <h4 class="info-title">Put something</h4>
                    <p>Divide details about your product or agency work into parts. Write a few lines about each one. A paragraph describing a feature will be enough.</p>
                  </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section text-center">
        <div class="container">
          <h2 class="title">This is perfect for you if</h2>
          <div class="team">
              <div class="md-layout">
                  <div class="md-layout-item md-medium-size-33 md-small-size-100">
                    <div class="team-player">
                      <md-card class="md-card-plain">
                        <div class="md-layout-item md-size-50 mx-auto">
                          <img :src="teamImg1" alt="Thumbnail Image" class="img-raised rounded-circle img-fluid">
                        </div>
                        <h4 class="card-title">Gigi Hadid
                          <br>
                          <small class="card-description text-muted">Model</small>
                        </h4>

                        <md-card-content>
                          <p class="card-description">You can write here details about one of your team members. You can give more details about what they do. Feel free to add some <a href="#">links</a> for people to be able to follow them outside the site.</p>
                        </md-card-content>

                        <md-card-actions class="text-center">
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-twitter"></i>
                          </md-button>
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-instagram"></i>
                          </md-button>
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-facebook-square"></i>
                          </md-button>
                        </md-card-actions>
                      </md-card>
                    </div>
                  </div>
                  <div class="md-layout-item md-medium-size-33 md-small-size-100">
                    <div class="team-player">
                      <md-card class="md-card-plain">
                        <div class="md-layout-item md-size-50 mx-auto">
                          <img :src="teamImg2" alt="Thumbnail Image" class="img-raised rounded-circle img-fluid">
                        </div>
                        <h4 class="card-title">Carla Hortensia
                          <br>
                          <small class="card-description text-muted">Designer</small>
                        </h4>

                        <md-card-content>
                          <p class="card-description">You can write here details about one of your team members. You can give more details about what they do. Feel free to add some <a href="#">links</a> for people to be able to follow them outside the site.</p>
                        </md-card-content>

                        <md-card-actions class="text-center">
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-twitter"></i>
                          </md-button>
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-linkedin"></i>
                          </md-button>
                        </md-card-actions>
                      </md-card>
                    </div>
                  </div>
                  <div class="md-layout-item md-medium-size-33 md-small-size-100">
                    <div class="team-player">
                      <md-card class="md-card-plain">
                        <div class="md-layout-item md-size-50 mx-auto">
                          <img :src="teamImg3" alt="Thumbnail Image" class="img-raised rounded-circle img-fluid">
                        </div>
                        <h4 class="card-title">Kendall Jenner
                          <br>
                          <small class="card-description text-muted">Model</small>
                        </h4>

                        <md-card-content>
                          <p class="card-description">You can write here details about one of your team members. You can give more details about what they do. Feel free to add some <a href="#">links</a> for people to be able to follow them outside the site.</p>
                        </md-card-content>

                        <md-card-actions class="text-center">
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-twitter"></i>
                          </md-button>
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-instagram"></i>
                          </md-button>
                          <md-button href="javascript:void(0)" class="md-just-icon md-simple">
                            <i class="fab fa-facebook-square"></i>
                          </md-button>
                        </md-card-actions>
                      </md-card>
                    </div>
                  </div>
              </div>
          </div>
        </div>
      </div>
      <div class="section section-contacts">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto">
              <h2 class="text-center title">Work with us</h2>
              <h4 class="text-center description">Divide details about your product or agency work into parts. Write a few lines about each one and contact us about any further collaboration. We will responde get back to you in a couple of hours.</h4>
              <form class="contact-form">
                  <div class="md-layout">
                      <div class="md-layout-item md-size-50">
                        <md-field>
                          <label>Your Name</label>
                          <md-input v-model="name" type="text"></md-input>
                        </md-field>
                      </div>
                      <div class="md-layout-item md-size-50">
                        <md-field>
                          <label>Your Email</label>
                          <md-input v-model="email" type="email"></md-input>
                        </md-field>
                      </div>
                  </div>
                  <md-field maxlength="5">
                    <label>Your Message</label>
                    <md-textarea v-model="message"></md-textarea>
                  </md-field>
                  <div class="md-layout">
                    <div class="md-layout-item md-size-33 mx-auto text-center">
                      <md-button class="md-success">Send Message</md-button>
                    </div>
                  </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  bodyClass: "landing-page",
  props: {
    header: {
      type: String,
      default: require("@/assets/img/bg7.jpg")
    },
    teamImg1: {
      type: String,
      default: require("@/assets/img/leaf1.png")
    },
    teamImg2: {
      type: String,
      default: require("@/assets/img/leaf2.png")
    },
    teamImg3: {
      type: String,
      default: require("@/assets/img/leaf3.png")
    }
  },
  data() {
    return {
      name: null,
      email: null,
      message: null
    };
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    }
  }
};
</script>

<style lang="scss" scoped>
.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}
</style>

<template>
  <section class="main-content">
    <div class="container">
      <div class="row">

        <div class="col-md-12">
          <center>
            <iframe title="Feedback Form" class="freshwidget-embedded-form" id="freshwidget-embedded-form"
                    src="https://ytimocin.freshdesk.com/widgets/feedback_widget/new?&widgetType=embedded&screenshot=No"
                    scrolling="no" height="500px" width="100%" frameborder="0">
            </iframe>
          </center>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
import { mapState } from 'vuex'

export default {
    name: 'EULA',
    computed: {
        ...mapState({
            user: state => state.user.user
        })
    },
    mounted () {

    }
}
</script>

<style lang="scss" scoped>
</style>

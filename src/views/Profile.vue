<template>
  <div class="profile">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-6">
                <div class="media text-left">
                    <img src="../assets/foto.jpg" class="user-pic mr-3">
                    <div class="media-body">
                        <h5 class="mt-0">{{ firstName }} {{ lastName }}</h5>
                        <p>Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'Profile',
  data: function() {
    return {
      firstName: 'Fardhi',
      lastName: 'Fathonah'
    }
  },
  components: {

  }
}
</script>

<style scoped>
.user-pic {
    height: 80px;
    width: 80px;
    border-radius: 200%;
}
</style>
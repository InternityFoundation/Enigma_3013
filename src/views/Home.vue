<template>
  <div class="home">
    <div class="container-fluid">
    <div class="row">
    <div class="col-md-4">
      
    </div>
      <div class="col-md-8">
        <img src="https://image.freepik.com/free-vector/business-leader-consulting-hr-expert_1262-21207.jpg" alt="">
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
      <Services/>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
      <Team/>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
      <Footer/>
      </div>
    </div>
    </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Footer from "@/components/common/footer";
import Team from "@/components/team";
import Services from "@/components/services";

export default {
  name: 'Home',
  components: {
    Footer,
    Services,
    Team
  }
}

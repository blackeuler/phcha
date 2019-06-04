<template>
    <div>
        <b-container fluid class="m-0 p-0">
            <b-form-row no-gutters class="d-flex m-0 p-0">
                <b-col sm="3"  >
                    <b-img  class="" fluid   src="../assets/phcha_logo-1.png" alt="logo"/>
                </b-col>
                <b-col sm="9"  class="">
                    <b-img  class=""  fluid center src="../assets/phcha_header.jpg" alt="header"/>
                </b-col>
            </b-form-row>
            <b-form-row>
                <b-col>
                    <b-img fluid-grow v-bind:src="img" v-bind:alt="img"/>
                </b-col>
            </b-form-row>
        </b-container>
       
        <div class="d-flex  ">
            
        </div>
    <div>
        <b-navbar style=" background-color:rgb(42, 63, 170);"  type="dark"  class="text-white" toggleable="lg"  >
            <b-navbar-toggle target="nav-collapse2"></b-navbar-toggle>
            <b-collapse id="nav-collapse2" is-nav>
                <b-navbar-nav>
                     <b-nav-item-dropdown text="Who We Are" >
                        <b-dropdown-item to="mission">Mission Statement</b-dropdown-item>
                        <b-dropdown-item to="staff">Staff</b-dropdown-item>
                        <b-dropdown-item to="board">Board Members</b-dropdown-item>
                        <b-dropdown-item to="partners">Partners</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item-dropdown text="Programs" >
                        <b-dropdown-item to="afya">Afya Center at Park Heights</b-dropdown-item>
                        <b-dropdown-item to="staff">Movies with a Message</b-dropdown-item>
                        <b-dropdown-item to="board">Project YES!</b-dropdown-item>
                        <b-dropdown-item to="partners">Let's Get Covered</b-dropdown-item>
                        <b-dropdown-item to="partners">Code B</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item-dropdown text="Urban Oasis" >
                        <b-dropdown-item to="garden">Afya Community Teaching Garden</b-dropdown-item>
                        <b-dropdown-item to="staff">Park Heights Community Farmers Market</b-dropdown-item>
                        <b-dropdown-item to="board">Growing Food Together CSA</b-dropdown-item>
                        <b-dropdown-item to="partners">Healthy Harvest</b-dropdown-item>
                        <b-dropdown-item to="partners">Brassica Fest!</b-dropdown-item>
                    </b-nav-item-dropdown>
                   <b-nav-item-dropdown text="Get Involved" >
                        <b-dropdown-item to="garden">Donate</b-dropdown-item>
                        <b-dropdown-item to="staff">Volunteer</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item to="Contact">Contact</b-nav-item>
                    
                </b-navbar-nav>
                <b-navbar-nav class="ml-auto">
                    <b-nav-item to="Subscribe">Subscribe to Our Mailing List
                        <i class="far fa-envelope"></i>
                    </b-nav-item>
                    <b-nav-item to="FB">
                        <i class="fab fa-facebook-f"></i>
                    </b-nav-item>
                    <b-nav-item to="Twitter">
                        <i class="fab fa-twitter"></i>
                    </b-nav-item>
                    <b-nav-item to="IG">
                        <i class="fab fa-instagram"></i>
                    </b-nav-item>
                </b-navbar-nav>
                
            </b-collapse>
                    
    
        </b-navbar>
    </div>

    </div>
    
   
</template>

<script>
export default {
    props:["img"]
}
</script>

<style scoped>
 .navI{
     color: white;
     background-color: rgb(42, 63, 170);
 }
</style>

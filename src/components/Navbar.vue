<template>
    <b-navbar type="dark" variant="dark" fixed="top"  ml-auto>

        <b-navbar-nav>
            <b-navbar-brand href="#">
                <b-img :src="require('C:\\Users\\kaouk\\WebstormProjects\\frontendbtw\\src\\assets\\bigtimewatchesresized.jpg')" fluid alt="Responsive Image"></b-img>
            </b-navbar-brand>

            <b-nav-item href="#"><router-link to="/" >Home</router-link></b-nav-item>
            <b-nav-item href="#"><router-link to="/about">About</router-link></b-nav-item>
            <b-nav-item ><router-link to="/">Brands</router-link></b-nav-item>
            <!-- Navbar dropdowns -->


            <b-nav-item-dropdown >
                <b-dropdown-item href="#">Rolex</b-dropdown-item>
                <b-dropdown-item href="#">Audemars Piguet</b-dropdown-item>
            </b-nav-item-dropdown>

        </b-navbar-nav>

    </b-navbar>
</template>
<script>
    export default {
        name: "Navbar"
    }
</script>

<style scoped>
h1 {
    font-size: small;
    text-align: center;
}
a {
    color: #7b8282;

}

nav  {
    background-color: black!important;
}
    body {
        background-color: black;
    }


    a:hover {
        color: #988057;
        text-decoration: none;
    }



</style>
<template>
    <div>
        <HeaderThree />
        <!-- <PageHeader /> -->
        <PageTitle pageTitle="Login" />
        <Login />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import Login from "~/components/Page/Login";
import Footer from "~/components/Home/Footer";
import HeaderThree from "~/components/HomeThree/HeaderThree.vue";
export default {
    components: {
    Login,
    Footer,
    PageTitle,
    PageHeader,
    HeaderThree
},
    head() {
        return {
            title: "Systemz Matrix | Login",
        };
    },
};
</script>

<style scoped>
</style>

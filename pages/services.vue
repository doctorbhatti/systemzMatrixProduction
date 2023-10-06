<template>
    <div>
        <HeaderThree />
        <!-- <PageHeader /> -->
        <PageTitle pageTitle="Services" />
        <Services />
        <Tab />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import Services from "~/components/Page/Services";
import Tab from "~/components/Home/Tab";
import Footer from "~/components/Home/Footer";
import HeaderThree from "~/components/HomeThree/HeaderThree.vue";
export default {
    name: "services",
    components: {
    Footer,
    Tab,
    Services,
    PageTitle,
    PageHeader,
    HeaderThree
},
    head() {
        return {
            title: "Systemz Matrix | Service",
        };
    },
};
</script>

<style scoped>
</style>

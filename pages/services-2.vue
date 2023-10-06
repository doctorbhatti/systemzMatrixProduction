<template>
    <div>
        <HeaderThree />
        <!-- <PageHeader /> -->
        <PageTitle pageTitle="Services" />
        <Services />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import Services from "~/components/Page/Services";
import Footer from "~/components/Home/Footer";
import HeaderThree from "~/components/HomeThree/HeaderThree.vue";
export default {
    name: "services-2",
    components: {
    Footer,
    Services,
    PageTitle,
    PageHeader,
    HeaderThree
},
    head() {
        return {
            title: "Systemz Matrix | Service - 2",
        };
    },
};
</script>

<style scoped>
</style>

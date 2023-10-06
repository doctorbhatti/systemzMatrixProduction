<template>
    <div>
        <HeaderThree />
        <!-- <PageHeader /> -->
        <PageTitle pageTitle="Blog Details" />
        <BlogDetails />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import BlogDetails from "~/components/Page/BlogDetails";
import Footer from "~/components/Home/Footer";
import HeaderThree from "~/components/HomeThree/HeaderThree.vue";

export default {
    name: "blog-details",
    components: {
    Footer,
    BlogDetails,
    PageTitle,
    PageHeader,
    HeaderThree
},
    head() {
        return {
            title: "Systemz Matrix | Blog Details",
        };
    },
};
</script>

<style scoped>
</style>

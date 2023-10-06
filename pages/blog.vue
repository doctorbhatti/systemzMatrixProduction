<template>
    <div>
        <HeaderThree />
        <!-- <PageHeader /> -->
        <PageTitle pageTitle="Blog Grid" />
        <BlogGrid />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import BlogGrid from "~/components/Page/BlogGrid";
import Footer from "~/components/Home/Footer";
import HeaderThree from "~/components/HomeThree/HeaderThree.vue";
export default {
    name: "blog",
    components: {
    Footer,
    BlogGrid,
    PageTitle,
    PageHeader,
    HeaderThree
},
    head() {
        return {
            title: "Systemz Matrix | Blog Grid",
        };
    },
};
</script>

<style scoped>
</style>

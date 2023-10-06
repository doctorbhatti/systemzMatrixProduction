<template>
    <div>
        <HeaderThree />
        <!-- <PageHeader /> -->
        <PageTitle pageTitle="Blog Sidebar" pageName="Blog List" />
        <BlogSidebar />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import BlogSidebar from "~/components/Page/BlogSidebar";
import Footer from "~/components/Home/Footer";
import HeaderThree from "~/components/HomeThree/HeaderThree.vue";
export default {
    name: "blog-sidebar",
    components: {
    Footer,
    BlogSidebar,
    PageTitle,
    PageHeader,
    HeaderThree
},
    head() {
        return {
            title: "Systemz Matrix | Blog Sidebar",
        };
    },
};
</script>

<style scoped>
</style>

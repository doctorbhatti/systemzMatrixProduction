<template>
    <div>
        <PageHeader />
        <PageTitle pageTitle="FAQ" />
        <Faq />
        <Footer />
    </div>
</template>

<script>
import PageHeader from "~/components/Page/PageHeader";
import PageTitle from "~/components/Page/PageTitle";
import Faq from "~/components/Page/Faq";
import Footer from "~/components/Home/Footer";
export default {
    name: "faq",
    components: {
        Footer,
        Faq,
        PageTitle,
        PageHeader,
    },
    head() {
        return {
            title: "Systemz Matrix | FAQ",
        };
    },
};
</script>

<style scoped>
</style>

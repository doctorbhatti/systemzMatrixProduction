<template>
    <div>
        <HeaderThree />
        <SliderThree />
        <About />
        <Service />
        <!-- Hiding Other Contents
        <Counter />
        <Team />
        <Tab />
        -->
        <DigitalService />
        <!--Hiding blog
        <Blog />
        -->
        <Footer />
    </div>
</template>

<script>
import SliderThree from "~/components/HomeThree/SliderThree";
import HeaderThree from "~/components/HomeThree/HeaderThree";
import Service from "~/components/Home/Service";
import About from "~/components/Home/About";
import Counter from "~/components/Home/Counter";
import Team from "~/components/Home/Team";
import Tab from "~/components/Home/Tab";
import DigitalService from "~/components/HomeThree/DigitalService";
import Blog from "~/components/Home/Blog";
import Footer from "~/components/Home/Footer";
export default {
    name: "index",
    components: {
        Footer,
        Blog,
        DigitalService,
        Tab,
        Team,
        Counter,
        About,
        Service,
        HeaderThree,
        SliderThree,
    },
    head() {
        return {
            title: "Systemz Matrix",
        };
    },
};
</script>

<style scoped>
</style>

<template>
  <MainLayout>
    <header class="mv-header mv-header-bg px-3 px-sm-4">
      <h1 class="fw-bold text-primary">Multividas Blog</h1>
      <h4 class="fw-bold text-muted my-2">
        Official Multividas Blog - Your go-to source for insights and
        information about Multividas
      </h4>
    </header>
    <main class="container main-container px-4 py-2 my-4 py-md-5 my-md-2">
      <article class="card mb-4">
        <header class="card-header">
          <h2 class="fw-bold text-primary">About Multividas</h2>
        </header>
        <section class="card-body">
          <p>
            Our mission is to build the app of everything, creating a diverse
            and inclusive world for everyone to share short and long blog posts.
          </p>
          <a
            href="/posts/about-multividas"
            class="g-link fw-bold text-primary"
          >
            <span class="me-2">Read more</span>
            <RightSvg :x="16"></RightSvg>
          </a>
        </section>
      </article>
      <article class="card mb-4">
        <header class="card-header">
          <h2 class="fw-bold text-primary">What is Multividas?</h2>
        </header>
        <section class="card-body">
          <p>
            Multividas.com is a social media and blogging platform where you can share short texts and posts, leaving comments and having discussions on threads.
          </p>
          <a
            href="/posts/what-is-multividas"
            class="g-link fw-bold text-primary"
          >
            <span class="me-2">Read more</span>
            <RightSvg :x="16"></RightSvg>
          </a>
        </section>
      </article>
    </main>
  </MainLayout>
</template>

<script>
import RightSvg from "~/svgs/RightSvg.vue";

export default {
  metaInfo: {
    title: "Multividas Blog",
  },
  components: {
    RightSvg,
  },
};
</script>

<style>
.g-link:hover {
  text-decoration: underline !important;
}
</style>

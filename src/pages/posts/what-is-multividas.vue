<template>
  <MainLayout>
    <main class="container px-3 py-4">
      <ForwardTag path="/" text="Back to the blog"></ForwardTag>
      <article class="my-3">
        <section class="text-right">
          <p class="text-muted text-sm">Dec 3, 2023</p>
          <h1 class="fw-bold text-primary mb-3">What is Multividas ?</h1>
        </section>
        <section>
          <div class="my-4">
            <g-image
              src="~/assets/png/cover-multividas-blogging-platform-multividas-social-media-blog-multividas-posts-threads-multividas-comments-discussions-multividas-short-texts-multividas-social-blogging.png"
              alt="multividas blog, multividas social media, multividas microblogging, multividas posts, multividas threads, multividas short texts, multividas comments, multividas discussions, multividas blogging platform, multividas blog community, multividas blog space, multividas social networking, multividas text sharing, multividas social blogging, multividas blog posts, multividas social threads, multividas blog comments, multividas blog conversations, multividas social interactions, multividas micro-content platform, multividas social engagement, multividas blog sharing, multividas blogging community, multividas social platform, multividas online community, multividas digital conversations, multividas social discussions, multividas post sharing, multividas text community, multividas microblog community, multividas social conversations, multividas blog interactions, multividas text interactions, multividas social sharing, multividas blog engagement, multividas social posts, multividas blog space, multividas text community, multividas microblog engagement, multividas social network, multividas blog connections, multividas post community, multividas text platform, multividas blog platform, multividas social media space, multividas blog hub, multividas social hub, multividas post hub, multividas blog sphere, multividas social sphere, multividas text sphere, multividas blog world, multividas social world, multividas post world, multividas blog realm, multividas social realm, multividas post realm, multividas blog kingdom, multividas social kingdom, multividas post kingdom, multividas blog domain, multividas social domain, multividas post domain, multividas blog galaxy, multividas social galaxy, multividas post galaxy, multividas blog universe, multividas social universe, multividas post universe, multividas blog environment, multividas social environment, multividas post environment, multividas blog atmosphere, multividas social atmosphere, multividas post atmosphere, multividas blog ecosystem, multividas social ecosystem, multividas post ecosystem, multividas blog landscape, multividas social landscape, multividas post landscape, multividas blog terrain, multividas social terrain, multividas post terrain, multividas blog habitat, multividas social habitat, multividas post habitat, multividas blog domain, multividas social domain, multividas post domain, multividas blog niche, multividas social niche, multividas post niche, multividas blog corner, multividas social corner, multividas post corner, multividas blog spot, multividas social spot, multividas post spot, multividas blog junction, multividas memes, multividas meme sharing, multividas funny posts, multividas meme community, multividas humor blog, multividas memes and jokes, multividas meme hub, multividas meme world, multividas meme sharing platform, multividas social memes, multividas blog memes, multividas post memes, multividas meme interactions."
              class="post-thumbnail image-fluid w-100"
            />
            <p class="text-center text-muted text-sm my-2">
              What is Multividas ?
            </p>
          </div>
          <div class="my-3">
            <section>
              <p class="lh-lg mb-2">
                Multividas is a social media blogging platform that allows users
                to post short texts known as <code class="fw-bold text-primary">"Threads"</code>. These threads are
                limited to 250 characters, promoting concise and to-the-point
                communication. Multividas was created in 2023 by Soulaimane
                Yahya.
              </p>
              <p class="lh-lg mb-2">Key features of Multividas include:</p>
              <ul class="key-features">
                <li class="mb-2">
                  <b><i>Threads:</i></b> The core element of Multividas, threads
                  are short posts that can include text, images, videos, links,
                  and hashtags. Users can share their thoughts, opinions, news,
                  or other content in these posts.
                </li>
                <li class="mb-2">
                  <b><i>Rehtreads:</i></b> Users can share threads from others with their own followers by rethreading. This helps in amplifying content and making it more visible to a broader audience.
                </li>
                <li class="mb-2">
                  <b><i>Likes:</i></b> Users can express their appreciation for a thread by clicking the "Like" button. The number of likes a thread receives can indicate its popularity.
                </li>
                <li class="mb-2">
                  <b><i>Hashtags:</i></b> Users often include hashtags (#) in
                  their threads to categorize and make them discoverable by a
                  wider audience interested in a specific topic.
                </li>
              </ul>
              <p class="lh-lg mb-2">
                Multividas is widely used for various purposes, including
                sharing posts, participating in discussions, using hashtags, promoting businesses, and connecting with people
                globally. Its real-time nature and brevity make it a dynamic
                platform for information dissemination and social interaction.
              </p>
              <p class="lg-lg mb-2">
                Multividas is a <b>'microblogging'</b> system that allows you to send and receive short posts called "threads".
              </p>
              <p class="lh-lg mb-2">
                Stay tuned ⌛ :
                <a
                  href="https://multividas.com"
                  target="_blank"
                  class="fw-bold text-decoration-underline"
                  >https://multividas.com</a
                >
              </p>
            </section>
          </div>
        </section>
      </article>
    </main>
  </MainLayout>
</template>

<script>
import ForwardTag from "~/layouts/ForwardTag.vue";

export default {
  metaInfo: {
    title: "What is Multividas",
  },
  components: {
    ForwardTag,
  },
};
</script>

<style>
ul.key-features {
  list-style-type: decimal;
  padding-left: 10px !important;
  margin: 25px !important;
}
</style>

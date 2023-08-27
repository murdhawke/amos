<template>
  <Layout>
    <div class="not-found">
    <h1>404 - Page Not Found</h1>
    <p>Oops! The page you're looking for doesn't exist.</p>
  </div>

  </Layout>
</template>

<style>
.not-found {
  text-align: center;
  padding: 100px;
  background: linear-gradient(to bottom right, #ff8a00, #e52e71); /* Adjust gradient colors */
  color: white; /* Text color */
}
</style>

<script>
export default {
  metaInfo: {
    title: 'Page Not Found'
  }
}
</script>


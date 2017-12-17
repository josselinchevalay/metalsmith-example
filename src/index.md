---
layout: layout.html
---

<h2>My Articles</h2>

<a href="/posts/first-post/">First post</a>

<a href="/posts/second-post/">Second post</a>

<a href="/posts/third-post/">Third post</a>

<a href="/posts/fourth-post/">Fourth post</a>

<script src="https://unpkg.com/ipfs/dist/index.js"></script>

<script>
const node = new Ipfs()

node.on('ready', () => {
  // Your node is now ready to use \o/

  // stopping a node
  node.stop(() => {
    // node is now 'offline'
  })
})
</script>

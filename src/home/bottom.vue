<template>
  <div>
    <div class="footer-container">
      <div class="footer">
        <p>RSS | 源码地址</p>
        <p>CNode 社区为国内最专业的 Node.js 开源技术社区，致力于 Node.js 的技术研究。</p>
        <p>服务器赞助商为 ucloud ，存储赞助商为 七牛云存储 ，由 alinode 提供应用性能服务。</p>
        <p>新手搭建 Node.js 服务器，推荐使用无需备案的 DigitalOcean(https://www.digitalocean.com/)</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'bottom'
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer-container{
  position: relative;
  background:white;
}
.footer{
  width: 90%;
  padding: .5rem 0;
  margin: 0 auto;
}
</style>

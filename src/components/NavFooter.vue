<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="/imgs/logo-footer.png" alt />
      <p>lingjoy商城</p>
      <div class="footer-link">
        <a href="https://github.com/lingjoy602/MIMAL" target="_blank">lingjoy</a>
        <span>|</span>
        <a href="https://github.com/lingjoy602/MIMAL" target="_blank">lingjoy</a>
        <span>|</span>
        <a href="https://github.com/lingjoy602/MIMAL" target="_blank">lingjoy</a>
        <span>|</span>
        <a href="https://github.com/lingjoy602/MIMAL" target="_blank">lingjoy</a>
        <span>|</span>
        <a href="https://github.com/lingjoy602/MIMAL" target="_blank">lingjoy</a>
      </div>
      <div class="copyright">
        copyright ©2020
        <span class="domain">
          <a
            href="https://github.com/lingjoy602/MIMAL"
            target="_blank"
          >https://github.com/lingjoy602/MIMAL</a>
        </span>All Rights Reserved.
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "nav-footer"
};
</script>
<style lang="scss" scoped>
.footer {
  height: 234px;
  border-top: 4px solid #ff6600;
  background-color: #333333;
  color: #999999;
  font-size: 16px;
  text-align: center;
  .footer-logo {
    margin: 46px 0 31px 0;
    img {
      width: 53px;
      height: 36px;
      margin-bottom: 13px;
    }
  }
  .footer-link {
    a {
      display: inline-block;
      color: #999999;
    }
    a:hover {
      color: #ff6600;
    }
    span {
      margin: 0 10px;
    }
    margin-bottom: 13px;
  }
  .copyright {
    .domain {
      a {
        color: #ff6600;
      }
    }
  }
}
</style>
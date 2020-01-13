<!-- main: #4169e1, base: #0045ff, accent: #ffba00 -->
<template>
<div class="container-fluid">
  <div class="row">
    <nav class="col-sm-3 sidebar">
      <div class="sidebar-sticky">
        <div>
          icon
        </div>
        <ul class="nav flex-column">
          <li class="nav-item">
            <a href="/">home</a>
          </li>
          <li class="nav-item">
            <a href="/profile">profile</a>
          </li>
          <li class="nav-item">
            <a href="/activity">activity</a>
          </li>
          <li class="nav-item">
            <a href="http://sinner-shiki.hatenablog.com/" target="_blank">blog</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="col-sm-9 main">
      <nuxt />
    </div>
  </div>
</div>
</template>

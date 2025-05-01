<template>
    <nav class="navbar">
      <!-- 这里可以添加导航栏的具体内容，例如菜单、搜索框等 -->
      <ul>
        <li><a href="#">首页</a></li>
        <li><a href="#">地图</a></li>
        <li><a href="#">图表</a></li>
      </ul>
    </nav>
  </template>
  
  <style scoped>
  .navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5); /* 半透明背景 */
    z-index: 1000;
    color: white;
  }
  
  .navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
  }
  
  .navbar li {
    margin: 0 10px;
  }
  
  .navbar a {
    color: white;
    text-decoration: none;
  }
  </style>
<script setup>
import './style/normalize.css';
import './style/reset.css';
import './style/app.css';
// import Vue from 'vue';

// const app = new Vue({
//   // el: '#app',
//   data: {
//     aa: '11',
//   },

//   methods: {},
// });
// app.$mount('#app');
</script>

<template>
  <div id="app">
    <div class="title-container container">
      <div class="title">中国设计智造协同创新国际学术研讨会</div>
      <div class="date">日期：12.02-12.04</div>
      <div class="location">地点：绍兴国际会展中心</div>
    </div>
    <div class="card-container container">
      <div class="sub-title">请选择要参加的活动</div>

      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <div class="card active">
        <p>中国设计智造协同创新国际学术研讨会</p>
        <p>主论坛</p>
        <p>09:00-12:00 主论坛：设计智造·协同创新（上）</p>
        <p>14:00-17:00 主论坛：设计智造·协同创新（下）</p>
        <p>
          <span>12月3日</span><span>余量:10/20</span>
          <span>已选<img src="ok.svg" /></span>
        </p>
      </div>
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <div class="card active">
        <p>中国设计智造协同创新国际学术研讨会</p>
        <p>平行分论坛</p>
        <p>09:00-12:00 学术研讨会-平行分论坛</p>
        <p></p>
        <p>
          <span>12月4日</span>
          <span>余量:10/20</span>
          <span>已选<img src="ok.svg" /></span>
        </p>
      </div>
    </div>

    <!-- 此处需要vue if -->
    <!-- 此处需要vue if -->
    <!-- 此处需要vue if -->
    <!-- 此处需要vue if -->
    <!-- 此处需要vue if -->
    <!-- 此处需要vue if -->
    <div class="sub-card-container container">
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <!-- 此处修改active class就行 -->
      <div class="sub-item active">
        <p>行分论坛一：国际设计政策研究</p>
        <p>
          <span>平3号馆3楼新闻发布厅</span><span>10/50</span>
          <span><img src="ok.svg" /></span>
        </p>
      </div>
      <div class="sub-item">
        <p>平行分论坛二：创新设计管理研究</p>
        <p>
          <span>3号馆2楼宴会厅C201A</span><span>10/50</span> <span><img src="ok.svg" /></span>
        </p>
      </div>
      <div class="sub-item">
        <p>平行分论坛三：文化创新与数化感知</p>
        <p>
          <span>3号馆2楼宴会C2016</span><span>10/50</span> <span><img src="ok.svg" /></span>
        </p>
      </div>
      <div class="sub-item">
        <p>平行分论坛四：智能制造与创新设计</p>
        <p>
          <span>3号馆1楼多功能101A</span><span>10/50</span> <span><img src="ok.svg" /></span>
        </p>
      </div>
      <div class="sub-item">
        <p>平行分论坛五：网络社会与服务系统</p>
        <p>
          <span>3号馆1楼多功能101B</span><span>10/50</span> <span><img src="ok.svg" /></span>
        </p>
      </div>
    </div>
    <div class="info-container container">
      <div class="sub-title">个人信息</div>
      <div class="form">
        <div class="form-info">
          <p>姓名</p>
          <p>年龄</p>
          <p>职业</p>
          <p>单位</p>
          <p>邮箱</p>
          <p>联系电话</p>
        </div>
        <div class="form-input" aria-placeholder="">
          <input type="text" placeholder="请输入姓名" />
          <input type="text" placeholder="请输入年龄" />
          <input type="text" placeholder="请输入职业" />
          <input type="text" placeholder="请输入单位" />
          <input type="text" placeholder="请输入邮箱" />
          <input type="text" placeholder="请输入联系电话" />
        </div>
      </div>
    </div>
    <div class="btn-submit container">
      <div>完成</div>
    </div>
  </div>
</template>

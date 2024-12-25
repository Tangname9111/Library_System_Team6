<template>
  <div class="dashboard-container">
    <!-- 欢迎信息区块 -->
    <div class="block">
      <div class="welcome-message">
        <b>欢迎使用图书管理系统</b>
        <p>team6</p>
      </div>
    </div>

    <!-- 个人数据板块 -->
    <div class="personal-data">
      <div class="data-card blue">我的图书<br>0本</div>
      <div class="data-card green">我的借阅<br>0本</div>
      <div class="data-card yellow">我的邮箱<br>0封</div>
    </div>

    <!-- 信息区块 -->
    <div class="block">
      <div class="school-info">
        <h3>公告</h3>
        <ul>
          <li>新版图书管理系统上线 <span>2024-12-25</span></li>
          <!-- 添加更多信息项 -->
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'id',
      'name',
      'roles'
    ])
  }
}
</script>

<style scoped>
.dashboard-container {
  padding: 20px;
}

.block {
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 5px;
  margin-bottom: 20px;
}

.welcome-message {
  text-align: center;
  color: #409eff;
  font-family: 'Arial', sans-serif;
}

.welcome-message b {
  font-size: 48px;
  font-weight: bold;
}

.personal-data {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.data-card {
  padding: 20px;
  border-radius: 5px;
  text-align: center;
  flex: 1;
  margin: 0 10px;
  color: #fff;
}

.data-card.blue {
  background-color: #409eff;
}

.data-card.green {
  background-color: #67c23a;
}

.data-card.yellow {
  background-color: #e6a23c;
}

.data-card.red {
  background-color: #f56c6c;
}

.school-info {
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
}

.school-info h3 {
  margin-bottom: 10px;
}

.school-info ul {
  list-style: none;
  padding: 0;
}

.school-info li {
  display: flex;
  justify-content: space-between;
  margin-bottom: 5px;
}
</style>

<template>
  <div class="page-navbar">
    <!-- navbar -->
    <mt-navbar class="page-part" v-model="selected">
      <mt-tab-item id="1">可使用(0)</mt-tab-item>
      <mt-tab-item id="2">已使用(0)</mt-tab-item>
      <mt-tab-item id="3">已过期(0)</mt-tab-item>
    </mt-navbar> 
	<!-- tabcontainer -->
    <mt-tab-container v-model="selected">
      <mt-tab-container-item id="1">
		<div class="default">
					<img :src="defaultImg"/>
					<p>您的订单空空如也~</p>
				</div>
      </mt-tab-container-item>
      <mt-tab-container-item id="2">
        <div class="default">
					<img :src="defaultImg"/>
					<p>您的订单空空如也~</p>
				</div>
      </mt-tab-container-item>
      <mt-tab-container-item id="3">
        <div class="default">
					<img :src="defaultImg"/>
					<p>您的订单空空如也~</p>
				</div>
      </mt-tab-container-item>
    </mt-tab-container>
  </div>
</template>
 
<script>
export default { 
  data() {
    return {
      selected: '1',
			defaultImg:require('../../assets/img/coupon.png')
    };
  }
};
</script>
<style scoped>
.page-navbar {
	width:100%;
	height:100%;
	background-color: #dfe4e8;
}
.page-navbar .mint-tab-item-label {
	font-size: 1rem;
}

.page-navbar .default {
	text-align: center;
	margin-top: 12rem;
}
.page-navbar .default p{
	font-size: 1.5rem;
    color: #7993ad;
    margin-top: 2rem;
}
</style>

<template>
	<div id="app">
		<router-view></router-view>
		<PersonalIndex></PersonalIndex>
		<!--<like></like>-->
		<!--<orderDetails></orderDetails>-->
		<!--<myOrder></myOrder>-->
		<!--<setting></setting>-->
		
		<!--<myAddress></myAddress>-->
		<!--<addSite></addSite>-->
		<!--<myLogin></myLogin>-->
		<!--<modifyPass></modifyPass>-->
		<!--<myRegister></myRegister>-->
	</div>
</template>

<script>
	import PersonalIndex from './components/personal/index';
	
//	import like from './components/personal/like';
//	import orderDetails from './components/personal/orderDetails';
//	import myOrder from './components/personal/myOrder';
//	import setting from './components/personal/setting';
	
//	import myAddress from './components/personal/myAddress';
//	import addSite from './components/personal/addSite';
//	import myLogin from './components/personal/myLogin';
//	import modifyPass from './components/personal/modifyPass';
//	import myRegister from './components/personal/myRegister';
	
	export default {
		name: 'app',
		components: {
			PersonalIndex,
//			like,
//			orderDetails,
//			myOrder,
//			setting,
			
//      		myAddress,
//			addSite,
//			myLogin,
//			modifyPass,
//			myRegister
		}
	}
</script>

<style>
	@import '/static/css/common.css';
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		height: 100%;
	}
</style>
<script>
	export default {
		onLaunch: function() {
			this.$store.commit('initUser')
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>
<style>
	/*每个页面公共css */
	@import './common/uni.css';
	@import './common/common.css';
	@import './common/iconfont.css';
	
	::-webkit-scrollbar{
		display:none;
		width: 0 !important;
		height: 0 !important;
		-webkit-appearance: none;
		background: transparent;
	}
</style>

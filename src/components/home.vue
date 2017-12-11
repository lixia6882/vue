<template>
	<div id="home">
		<img src="../assets/logo_red.png" class="log_red">
		<div class="phone">
			<img src="../assets/username.png">
			<input type="number" placeholder="请输入手机号码">
		</div>
		<div class="phone phone2">
			<img src="../assets/pwd.png">
			<input type="password" placeholder="请输入登录密码">
		</div>
		<div class="get_paw">
			<p>忘记密码</p>
		</div>
		<button class="login">登录</button>
		<button class="register">注册</button>
 	</div>
</template>
<style type="text/css">
	#home{
		width: 100%;
		height: 100%;
		background: url("../assets/merchant-_background.jpg") no-repeat;
		position: relative;
		background-size: contain;
	}
	.log_red{
		width: 90px;
		height: 90px;
		margin-top: 90px;
		margin-bottom: 45px;
	}
	.phone{
		width: 74%;
		height: 30px;
		display: -webkit-flex;
		margin:0 auto;
	}
	.phone img{
		width: 28px;
		height: 28px;
	}
	.phone input{
		border:none;
		border-bottom: 2px solid #f58aa1;
		font-size: 16px;
		background:transparent;
		outline: none;
		margin-left: 10px;
		-webkit-flex:1;
		padding-left: 5px;
	}
	.phone2{
		margin-top: 19px;
	}
	.get_paw{
		width: 74%;
		height: 40px;
		margin: 0 auto;
		color: #e98d99;
		font-size: 12px;

	}
	.get_paw p{
		float: right;
		background: url("../assets/23.png") no-repeat 0px center;
		background-size: 15px 15px;
		padding-left: 20px;
		line-height: 40px;
	}
	.login{
		width: 74%;
		height: 35px;
		background: #f23861;
		color: #fff;
		border-radius: 20px;
		outline: none;
		border: 0;
		background-color:none;
		margin:0 auto;
		margin-bottom: 13px;
		border: 1px solid #e94d6f;
	}
	.register{
		width: 74%;
		height: 35px;
		background: transparent;
		color: #f23861;
		border-radius: 20px;
		outline: none;
		margin:0 auto;
		margin-bottom: 13px;
		border: 1px solid #e94d6f;
	}
</style>
<script type="text/javascript">
	
</script>
 <template>
  <div class="xm-top-sub">
      <div class="xm-top-sub-son"> 
		<div class="sub-1">
			<ul class="channels">
				<li class="channel">
                   <a href="http://www.mi.com/compare/" target="_blank">
  					<i class="fa fa-mobile fa-fw sub-icon"></i>
                     <p class="channel-txt">  选购手机  </p>
                   </a>
				</li>
				<div class="line-vertical"> </div>
				<li class="channel">
                  <a href="http://qiye.mi.com/" target="_blank">
  					<i class="fa fa-gift fa-fw sub-icon"></i>
                     <p class="channel-txt"> 企业团购 </p>
                  </a>
				</li>
				<div class="line-vertical"> </div>
				<li class="channel">
                    <a href="http://item.mi.com/re" target="_blank">
  					<i class="fa fa-refresh fa-fw sub-icon"></i>
                    <p class="channel-txt">  官翻产品  </p>
                    </a>
				</li>
				<div class="line-horizontal"> </div>
				<div class="line-horizontal"> </div>
				<div class="line-horizontal"> </div>
				<li class="channel">
                  <a href="http://huanxin.mi.com/product/list" target="_blank">
  					<i class="fa fa-credit-card fa-fw sub-icon"></i>
                    <p class="channel-txt">小米移动</p>
                  </a>
				</li>
				<div class="line-vertical"> </div>
				<li class="channel">
                  <a href="http://huanxin.mi.com/product/list" target="_blank">
  					<i class="fa fa-recycle fa-fw sub-icon"></i>
  					<p class="channel-txt">  以旧换新 </p>
                  </a>
				</li>
				<div class="line-vertical"> </div>
				<li class="channel">
                   <a href="http://recharge.10046.mi.com/" target="_blank">
  					 <i class="fa fa-credit-card-alt fa-fw sub-icon"></i>
                     <p class="channel-txt"> 话费充值 </p>
                   </a>
				</li>
			</ul>
		</div>
		<ul class="subs">
			<li>
				<a href="http://hd.mi.com/y/08191p/index.html" class="sub-item sub-2" target="_blank">
					<img src="http://i3.mifile.cn/a4/1327d707-4f67-4c36-8ae5-3d7704c989eb" alt="" />
				</a>
			</li>
			<li>
				<a href="http://item.mi.com/buyphone/redmipro/" class="sub-item sub-3" target="_blank">
					<img src="http://i3.mifile.cn/a4/c202123c-4197-4666-9793-2f1e156ab23a" alt="" />
				</a>
			</li>
			<li>
				<a href="http://item.mi.com/static/buymipad" class="sub-item sub-4" target="_blank">
					<img src="http://i3.mifile.cn/a4/216f7f38-66ee-4c1b-8409-8d77cb64d386" alt="" />
				</a>
			</li>
		</ul>
		</div>
	</div>
</template>


<script>
import ss from "../assets/style/font-awesome-4.7.0/css/font-awesome.min.css"
export default {
	data () {
		return {
		}
	},
	methods: {
		evtSubEnter (selector) {
		}
	}
}
</script>

<style scope>
.xm-top-sub {
	position: relative;
	width: 100%;
	height: 170px;
	 
}
.xm-top-sub-son {
	position: relative;
    width: 90%;
    height: auto;
    margin: 14px auto 26px;
	 
	 
}
.sub-1 {
	float: left;
	width: 20%;
    height: 170px;
	background: #5f5750;
}
.channels {
	display: flex;
	flex-flow: row wrap;
	justify-content: flex-start;
	align-items: flex-start;
	list-style: none;
	margin: 0;
	padding: 3px;
}
.channel {
    width: 30%;
    height: 82px;
    cursor: pointer;
    margin-left: 6px;
}
.channel:hover .channel-txt {
	color: #fff;
}
.channel:hover	.sub-icon {
	 color: #fff;
}
		
.channel-txt {
	display: block;
    margin: 0;
	width: 75px;
	font-size: 12px;
	text-align: center;
	text-decoration: none;
	color: rgba(255,255,255,0.7);
		}
	 
	.sub-icon {
	width: 75px;
	height: 24px;
	margin-top: 18px;
	margin-bottom: 5px;
	font-size: 20px;
	color: rgba(255,255,255,0.7);
	}
 

.subs {
	display: flex;
	flex-flow: row nowrap;
	justify-content: flex-start;
	margin: 0;
	padding: 0;
	list-style: none;
}
.subs li {
    width: 31%;
    height: 170px;
    margin-left: 26px;
}
	.sub-item {
	display: block;
	transition: all 0.3s;
}
.sub-item:hover {
	 box-shadow: 0 5px 30px #ccc;
		}
 .subs  img {
	display: block;
	width: 100%;
	height: 170px;
		}
 

. {
	width: 1px;
	height: 60px;
	margin-top: 10px;
	background: rgba(255,255,255,0.1);
}

.line-horizontal {
    width: 24%;
    height: 1px;
    margin: 0 11px;
    background: rgba(255,255,255,0.1);
}
.line-vertical{
    width: 1px;
    height: 60px;
    margin-top: 10px;
    background: hsla(0,0%,100%,.1);
}

.fa-mobile-phone:before, .fa-mobile:before {
    content: "\F10B";
}
.fa-gift:before {
    content: "\F06B";
}
 


</style>

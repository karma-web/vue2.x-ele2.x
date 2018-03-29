<template>
    <div class="index">
      <header class="index-header">
        <div class="nav-wrapper">
          <div class="nav-logo" @click="_home">慧智</div>
          <div class="nav-menus">
            <div class="nav-item">
              <input @click="miaodian('shouye')" ref="shouye" id="shouye" checked type="radio" name="nav">
              <label for="shouye">首页</label>
            </div>
            <div class="nav-item">
              <input @click="miaodian('doc')" id="doccenter" type="radio" name="nav">
              <label for="doccenter">文档中心</label>
            </div>
            <div class="nav-item">
              <input @click="miaodian('aboutus')" id="aboutus" type="radio" name="nav">
              <label for="aboutus">关于我们</label>
            </div>
          </div>
          <div class="nav-login">
            <el-button @click="_login">登录</el-button>
            <el-button @click="_register">注册</el-button>
          </div>
        </div>
      </header>
      <div ref="shouye_miaoshu" class="first-page">
	      <div class="jianjie">
	        <h2>产品概述</h2>
	        <p>
	          慧新鲜在线商业管理软件，面向各类专营专卖行业的在线管理软件。慧新鲜POS，让企业以极低的成本[零安装，零启用，零维护]，迅速实现信息化；让员工随时随地，只要电脑有网络，打开浏览器就可以操作！慧新鲜在线商业管理软件是科脉面向各类专营专卖行业推出应用于互联网平台，基于云服务模式、B/S架构的在线管理软件。让员工随时随地，只要电脑有网络，打开浏览器就可以操作！</p>
	      </div>
	  </div>
      <article ref="cmdb_wenan" class="project-detail">
        <div class="detail-content">
          <div class="project-title tc">慧新鲜</div>
          <div class="project-des tc">零售连锁企业运营管理软件慧新鲜是一款集批次成本、配送复核、自助收银、供应链、加盟管理等于一身的零售管理软件。</div>
          <div class="project-block">
            <div class="project-item">
              <div class="item-icon tc"><span class="fa fa-asl-interpreting"></span></div>
              <div class="item-leftcontent">
                <div class="item-title">易用性</div>
                <div class="item-des">简单易用，便于管理深度集成数据处理服务</div>
              </div>
            </div>
            <div class="project-item">
              <div class="item-icon tc"><span class="fa fa-cubes"></span></div>
              <div class="item-leftcontent">
                <div class="item-title">强安全</div>
                <div class="item-des">多层次安全防护支持跨区域复制、异地容灾机制</div>
              </div>
            </div>
          </div>
          <div class="project-block">
            <div class="project-item">
              <div class="item-icon tc"><span class="fa fa-life-saver"></span></div>
              <div class="item-leftcontent">
                <div class="item-title">低成本</div>
                <div class="item-des">总体TCO更低生命周期管理成本进一步降低</div>
              </div>
            </div>
            <div class="project-item">
              <div class="item-icon tc"><span class="fa fa-gears"></span></div>
              <div class="item-leftcontent">
                <div class="item-title">高可靠</div>
                <div class="item-des">冗余备份服务设计可用性不低于99.99%</div>
              </div>
            </div>
          </div>
        </div>
      </article>
      <article ref="aboutus_miaoshu" class="about-us">
        <div class="aboutus-content">
          <h2>关于我们</h2>
          <p>吉林省慧智科技有限公司成立于2016年，是一家具有多年行业资深精英联合创办的科技型企业。以"互联网+餐饮"为切入点，专注于将互联网应用与传统餐饮行业信息化建设进行应用整合，应用新的理念、技术和服务，助力餐饮业信息化建设跨入新舌尖时代。为企业提供包括轻量级020、ERP以及云计算系统在内的一整套云平台解决方案，助力传统行业拥抱"互联网+"。慧智科技研发团队拥有十多年的管理系统的开发和服务经验。经过不断努力，紧抓时代脉搏，从最初的管理软件开发公司发展成为全国领先的基于移动互联与云计算技术的整体信息化解决方案提供商和服务商，2015年"点食云平台"正式上线，即将全国推广。

		  慧智科技科技以"成就客户，诚信为本，承担责任，团队合作，变革创新！"时刻鞭策前行，在各环节上打造核心竞争能力，为利益相关者创造最大化价值，并以此回报全体客户、股东和员工。通过日益完善的产业和研发链条，慧智科技科技为餐饮娱乐经营者量身开发的"点食云平台"管理系统，功能涵盖了餐饮企业从顾客自主点餐、智慧后厨、老板小秘书、成本分析和收银结算，以及供应链管理的方方面面。这些产品与服务均具有完全自主知识产权，同时铸就了慧智科技科技的高效率、高品质、高技术含量的良好口碑。

		  慧智科技人深知在信息化大潮侵袭下唯有创新才是一切动力的源泉，开放将是我们推行的原则，为更多的餐饮企业提供更便捷的解决方案和高性价比的营运工具。"君子择时而动，顺势而为"，借互联网信息化之东风，慧智科技科技愿与所有志同道合的友人一起扬帆起航。</p>
        </div>
      </article>
      <footer>
        <div class="version-heart">
          <div class="about-us-links">
            <div class="us-links">
              <div class="aboutus-yjfk">
                <div>联系我们</div>
                <div>加入我们</div>
              </div>
            </div>
            <div class="name-tel">
              <div class="name">吉林省慧智科技有限公司</div>
              <div class="tel">TEL:010-56918888</div>
            </div>
          </div>
          <div class="beian">All Rights Reserved 京ICP备16888888号</div>
        </div>
      </footer>
    </div>
</template>
<script>
    export default {
        data() {
            return {}
        },
        computed: {},
        methods: {
          _home(){
            this.$refs.shouye.checked = true;
            this.$router.replace('/index');
            this.$refs['shouye_miaoshu'].scrollIntoView();
          },
          _login(){
            this.$router.push({path: 'dashboard'})
          },
          _register(){
            // this.$router.push({path: 'register'})
          },
          miaodian(key){
            if(key === 'shouye'){
              this.$refs['shouye_miaoshu'].scrollIntoView();
            }else if(key === 'doc'){
              this.$refs['cmdb_wenan'].scrollIntoView();
            }else if(key === 'aboutus'){
              this.$refs['aboutus_miaoshu'].scrollIntoView();
            }
          }
        },
        components: {}
    }
</script>

<style lang="less">
  @import '~assets/styles/variable.less';
</style>

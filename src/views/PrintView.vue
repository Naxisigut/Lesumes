<template>
  <div class="max-w-[900px] mx-auto p-5 font-sans text-gray-800 bg-white shadow-md">
    <!-- 头部信息 -->
    <header class="flex gap-8 pb-5 border-b border-gray-200">
      <div class="w-[100px] h-[100px] overflow-hidden rounded-lg ">
        <!-- 使用assets里的avatar.jpg作为头像 -->
        <img src="@/assets/avatar.png" alt="头像" class="w-full h-full object-cover bg-[#ffdfc6] scale-125" />
      </div>
      <div class="flex-1">
        <h1 class="text-3xl font-bold mb-2.5">李程程</h1>
        <div class="flex flex-wrap">
          <div class="mr-4 mb-2 flex items-center text-sm"><span class="mr-1.5 not-italic">👤</span> 男 | 1995.07.15 | 30岁 | 本科</div>
          <div class="mr-4 mb-2 flex items-center text-sm"><span class="mr-1.5 not-italic">📱</span> 13136355078</div>
          <div class="mr-4 mb-2 flex items-center text-sm"><span class="mr-1.5 not-italic">✉️</span> jojo@hotmail.com</div>
        </div>
        <div class="flex flex-wrap">
          <div class="mr-4 mb-2 flex items-center text-sm"><span class="mr-1.5 not-italic">💼</span> 5年前端工作经验</div>
          <div class="mr-4 mb-2 flex items-center text-sm"><span class="mr-1.5 not-italic">🎯</span> 求职意向：前端开发工程师</div>
          <div class="mr-4 mb-2 flex items-center text-sm"><span class="mr-1.5 not-italic">💰</span> 期望薪资：面议</div>
        </div>
      </div>
    </header>

    <!-- 工作经历 -->
    <section class="mt-4 flex gap-8">
      <h2 class="text-xl font-bold w-[100px]">工作经历</h2>
      <div class="flex-1">
        <div class="flex justify-between mb-4">
          <div class="flex items-center font-bold gap-5">
            <div class="text-base">杭州优工品科技有限公司</div>
            <div class="text-sm">前端开发工程师</div>
          </div>
          <div class="text-sm text-gray-600">2023.02-2025.03</div>
        </div>
        <div class="flex justify-between mb-4">
          <div class="flex items-center font-bold gap-5">
            <div class="text-base">宁波酷旺智能科技有限公司</div>
            <div class="text-sm">前端开发工程师</div>
          </div>
          <div class="text-sm text-gray-600">2020.05-2022.12</div>
        </div>
        <div class="flex justify-between mb-4">
          <div class="flex items-center font-bold gap-5">
            <div class="text-base">宁波爱博特集团有限公司</div>
            <div class="text-sm">硬件工程师助理</div>
          </div>
          <div class="text-sm text-gray-600">2018.03-2020.04</div>
        </div>
      </div>
    </section>

    <!-- 专业技能 -->
    <section class="mt-3 flex gap-8">
      <h2 class="text-xl font-bold w-[100px]">专业技能</h2>
      <div class="flex-1">
        <ul class="list-disc pl-5">
          <li class="mb-2 leading-normal"><span class="font-bold">基础：</span>熟练掌握JS/TS，ES6+，HTML5，CSS3，HTTP及相关基本技能</li>
          <li class="mb-2 leading-normal"><span class="font-bold">平台：</span>Web、Node(了解)、微信小程序、Uniapp</li>
          <li class="mb-2 leading-normal"><span class="font-bold">框架：</span>Vue2、Vue3、React(了解)、Wxt</li>
          <li class="mb-2 leading-normal"><span class="font-bold">UI：</span>熟练使用Element-ui、Vant，掌握TailwindCSS，UnoCSS等css框架</li>
          <li class="mb-2 leading-normal"><span class="font-bold">工具：</span>熟练使用Scss、Git、Vitest等</li>
          <li class="mb-2 leading-normal"><span class="font-bold">其它：</span>熟悉常用的业务相关各类第三方库，如Leaflet、Konvajs等，了解部分后端知识如Mysql，英语六级</li>
          <li class="mb-2 leading-normal"><span class="font-bold">经验：</span>能够封装常用组件，由接入微信支付、移动端权限、阿里云OSS、微信公众号发布等经验</li>
        </ul>
      </div>
    </section>

    <!-- 项目经历 -->
    <section class="mt-3 flex gap-8">
      <h2 class="text-xl font-bold w-[100px]">项目经历</h2>
      <div class="flex-1">
        <div class="mb-4">
          <h3 class="text-lg font-bold mb-2.5">工云链紧固件ERP系统</h3>
          <div class="pl-4">
            <p class="my-1.5 leading-normal"><span class="font-bold">1.项目描述：</span></p>
            <p class="my-1.5 leading-normal pl-4">
              本系统是高度针对紧固件行业的综合性的企业管理系统，主要包括线上商城、ERP系统和生产管理系统。客户群体主要为全国各地紧固件行业的中小型企业。
            </p>
            <p class="my-1.5 leading-normal"><span class="font-bold">2.项目技术栈：</span></p>
            <p class="my-1.5 leading-normal pl-4">后端使用C#进行开发，前端采用微前端架构，页面使用Vue2全家桶+ElementUI完成</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">3.项目职责：</span></p>
            <p class="my-1.5 leading-normal pl-4">
              本项目属于公司的核心项目，已有大量前后端不分离的C#旧代码。本人参与销售、采购、仓库、生产、财务、物流、系统设置等多个功能模块的讨论和开发，迁移、重构了大量旧代码，在此过程中共同攻克了一系列的技术难题，解决了大量Bug，优化了用户体验，提升了系统稳定性。编写了一些新业务需要用到的工具，提升项目代码的复用程度，减少后期的开发和维护成本。
            </p>
            <p class="my-1.5 leading-normal"><span class="font-bold">4.项目链接：</span>https://www.51serp.com/hqadmin/#/home</p>
          </div>
        </div>

        <div class="mb-4">
          <h3 class="text-lg font-bold mb-2.5">工云链APP</h3>
          <div class="pl-4">
            <p class="my-1.5 leading-normal"><span class="font-bold">1.项目描述：</span></p>
            <p class="my-1.5 leading-normal pl-4">该项目为上述ERP项目为一线员工准备的配套APP，方便一线员工录入生产数据、扫描商品标签、生成业务单据，以推进企业生产流程的数字化，提高生产效率。</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">2.项目技术栈：</span></p>
            <p class="my-1.5 leading-normal pl-4">基于UniApp进行开发，使用Vue2+Vuex，编译了App和H5两个平台。</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">3.项目职责：</span></p>
            <p class="my-1.5 leading-normal pl-4">该项目主要包括生产、仓库、拣货、员工业绩等功能模块，本人参与了生产和拣货模块的开发，如创建工单、领料、报工、检验、入库、出库、拣货、装车等业务流程。在此过程中封装了部分公共功能，如适用于双端的扫码组件和适用于PDA的扫码组件；解决了如录入数据不准等影响业务流程的bug，保证业务的正常进行。</p>
          </div>
        </div>

        <div class="mb-4">
          <h3 class="text-lg font-bold mb-2.5">钱塘文旅手绘地图项目</h3>
          <div class="pl-4">
            <p class="my-1.5 leading-normal"><span class="font-bold">1.项目描述：</span></p>
            <p class="my-1.5 leading-normal pl-4">该项目为杭州文旅局推出的手绘地图项目，旨在为游客在移动端提供一个更加直观、便捷的旅游指南，功能包括景点分类、景点介绍、景点搜索、导航等。</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">2.项目技术栈：</span></p>
            <p class="my-1.5 leading-normal pl-4">Vue3+Vite+TailwindCSS+Leaflet+jWeixinSDK</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">3.项目职责：</span></p>
            <p class="my-1.5 leading-normal pl-4">该项目前端部分由本人独立开发，参与了技术选型、需求分析、UI的简单设计等，主要完成了地图绘制、点位绘制、地图交互、点位搜索、点位导航等一系列功能。过程中解决了一些技术难题如地图数据量过大造成操作卡顿、加载缓慢等。本人也负责了在公众号上的发布工作。</p>
          </div>
        </div>

        <div>
          <h3 class="text-lg font-bold mb-2.5">杭州基础创新iems能源管理和计量计费系统</h3>
          <div class="pl-4">
            <p class="my-1.5 leading-normal"><span class="font-bold">1.项目描述：</span></p>
            <p class="my-1.5 leading-normal pl-4">该项目为公司核心项目，搭配公司主营的水电表一同出售给客户，为其旗下的智能水电表提供定制化的能源管理和计量计费平台。</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">2.项目技术栈：</span></p>
            <p class="my-1.5 leading-normal pl-4">Vue2全家桶+ElementUI+Echarts</p>
            <p class="my-1.5 leading-normal"><span class="font-bold">3.项目职责：</span></p>
            <p class="my-1.5 leading-normal pl-4">参与项目的重大迭代，根据新型智能水电表的计费方式更新计费方案。根据UI撰写样式，处理各种bug。除了常规的增删查改，完成了事件报警、设备状态监控、数据可视化等新功能。</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">

</script>

<style>
@media print {
  body {
    margin: 0;
    padding: 0;
  }
  
  .shadow-md {
    box-shadow: none !important;
  }
}
</style>
<template>
  <div>
    <div class="hearer-box">
      <search />
    </div>

    <ul class="item-box">
      <li>
        <div class="item-img">
          <img src alt />
        </div>
        <div class="item-tet"></div>
      </li>
    </ul>
  </div>
</template>

<script>
import search from "@/components/search.vue";
export default {
  // 组件参数 接收来自父组件的数据
  props: [],
  // 局部注册的组件
  components: { search },
  // 组件状态值
  data() {
    return {};
  },
  // 侦听器
  watch: {},
  // 组件实例创建完成，属性已绑定，但DOM还未生成，$ el属性还不存在
  created() {},
  //  el 被新创建的 vm.$ el 替换，并挂载到实例上去之后调用该钩子。
  //  如果 root 实例挂载了一个文档内元素，当 mounted 被调用时 vm.$ el 也在文档内。
  mounted() {},
  // 组件方法
  methods: {},
  // 计算属性
  computed: {}
};
</script>

<style lang="scss" scoped>
.hearer-box {
  width: 100%;
  height: 1.2rem;
  background: #fff;
}
.item-box {
  width: 100%;
  height: 2.1rem;
}
li {
  width: 100%;
  height: 2.1rem;
  display: flex;
  padding: 0px 0.3rem;
  box-sizing: border-box;
}
.item-img {
  width: 2.7rem;
  height: 2.1rem;
  background: pink;
}
.item-tet {
  width: 4.6rem;
  height: 2.1rem;
  background: green;
}
</style>
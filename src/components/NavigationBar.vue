<template lang="pug">
  v-navigation-drawer
    h1 John Doe
    v-divider
    v-list
      v-list-item(v-for="item in menuItens")
        v-list-item-content
          a(:href="item.link") {{item.title}}
</template>

<script>
export default {
  data: function () {
    return {
      menuItens: [
        {
          title: "Dashboard",
          icon: "",
          link: "/",
        },
        {
          title: "Messages",
          icon: "",
          link: "/",
        },
        {
          title: "My tasks",
          icon: "",
          link: "/",
        },
      ],
    };
  },
};
</script>

<style lang="less"></style>

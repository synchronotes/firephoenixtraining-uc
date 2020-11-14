<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>FIRE PHOENIX TRAINING - Săn học bổng ĐH FPT</p>
    <h3>Mọi thông tin chi tiết xin liên hệ:</h3>

    <ul>
      👉 Facebook:
      <a
        href="https://www.facebook.com/fire.phoenix.training/"
        target="https://www.facebook.com/fire.phoenix.training/"
        rel="noopener"
        >https://www.facebook.com/fire.phoenix.training</a
      >
    </ul>
    <ul>
      ✔️ Group:
      <a
        href="https://www.facebook.com/groups/luyenthifpt2020/"
        target="_blank"
        rel="noopener"
        >https://www.facebook.com/groups/luyenthifpt2020/</a
      >
    </ul>
    <ul>
      📞 Contact:
    </ul>
    <ul>
      070 445 1334 (Mr. Vy)
    </ul>
    <ul>
      091 596 1857 (Ms. Ha)
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

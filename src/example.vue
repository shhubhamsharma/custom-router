<template>
    <ul>
        <li @click="naigateTo('https://router.vuejs.org/guide/#html')"> Router</li>
        <li @click="naigateTo('https://jsfiddle.net/posva/wtpuevc6/')">JSFiddle</li>
        </li>
    </ul>
</template>

<script>
export default {
  name:'custom-router',
  methods:{
      naigateTo(url){
          window.location=url;
      }
  }
}
</script>

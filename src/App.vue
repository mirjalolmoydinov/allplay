<template>
  <div>
    <channel-list></channel-list>
    <channel-list></channel-list>
<h2>hellol</h2>
    <channel-card :channel="{name : 'My channel'}"></channel-card>
  </div>
</template>

<script>
import ChannelList from "@/components/ChannelList.vue"
export default {
  components : {
    ChannelList,
  }
}
</script>

<style>

</style>
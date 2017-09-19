<template>
<mu-appbar>
    
    <mu-text-field icon="search" class="appbar-search-field" hintText="搜索所有联想产品" fullWidth />
    <mu-icon-button icon="android" slot="left"/>
</mu-appbar>
</template>

<script>

    export default {
        name:'search'
    }
</script>

<style lang="less">
.appbar-search-field{
  color: #FFF;
  margin-bottom: 0;
  &.focus-state {
    color: #FFF;
  }
  .mu-text-field-hint {
    color: fade(#FFF, 54%);
  }
  .mu-text-field-input {
    color: #FFF;
  }
  .mu-text-field-focus-line {
    background-color: #FFF;
  }
}

</style>
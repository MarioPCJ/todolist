
<template>
  <div id="app">
 <router-view/>

  <b-input-group class="mb-2">
    <b-input-group-prepend is-text>
      <b-form-checkbox class="mr-n2">
        <span class="sr-only">Checkbox for following text input</span>
      </b-form-checkbox>
    </b-input-group-prepend>
    <b-form-input aria-label="Text input with checkbox"></b-form-input>
  </b-input-group>

  </div>
</template>
<style>
.mb-2{
  position: absolute;
margin-top: -60px;
z-index:9999;
}

</style>

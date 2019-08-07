<template>
  <div class = "temperature">
    :min = "min"
    :max = "max"
    :style = "{background: color}"
    :value = "value"
    @input = "handleInput"
    type = "range"

    <div class = "labels">
      <div>{{ min }}</div>
        <div>temperature: {{ value }}F</div>
      <div>{{ max }}</div> 
    </div>

    <div class = "evaluation">
      {{ evaluation }}
    </div>

  </div>
</template>


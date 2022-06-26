<template>
    <form>
      <div class="helps">
        <slot name="helps"></slot>
      </div>
       <div class="fields">
        <slot name="fields"></slot>
       </div>
        <div class="buttons">
          <slot name="buttons"></slot>
        </div>
    </form>
    <slot></slot>
</template>
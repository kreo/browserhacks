<style lang="scss">
    @import '../index';

    div {
        font-family: 'Open Sans', sans-serif;
        font-size: 20px;
        line-height: 32px;
    }

    .edge { @include edge { color: green } }
    .firefox { @include firefox { color: green } }
    .ie-10-up { @include ie-10-up { color: green } }
    .ie-11 { @include ie-11 { color: green } }
    .webkit { @include webkit { color: green } }
</style>

<template>
    <div>
        <div class="edge">Edge</div>
        <div class="firefox">Firefox</div>
        <div class="ie-10-up">IE 10+</div>
        <div class="ie-11">IE 11</div>
        <div class="webkit">Webkit</div>
    </div>
</template>

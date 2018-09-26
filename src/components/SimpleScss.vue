<template>
  <nav>
    <ul class="navigation">
      <li><a href="#">About us</a></li>
      <li><a href="#">Pricing</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
    <div class="buttons">
      <a href="#" class="btn-main">Sign up</a>
      <a href="#" class="btn-hot">Get a quote</a>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss">
$color-primary: #f9ed69; //yellow
$color-secondary: #f08a5d; //orange
$color-terriary: #b83b5e; //pink
$color-text-dark: #333;
$color-text-light: #eee;

$width-button: 150px;

@mixin clearfix {
  &::after {
    content: '';
    clear: both;
    display: table;
  }
}

@mixin style-link-text($color) {
  text-decoration: none;
  text-transform: uppercase;
  color: $color;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

@function divide($a, $b) {
  @return $a / $b;
}

nav {
  margin: divide(90, 3) * 1px; //30px
  background-color: $color-primary;

  @include clearfix;
}

.navigation {
  list-style: none;
  float: left;

  li {
    display: inline-block;
    margin-left: 30px;

    &:first-child {
      margin-left: 0;
    }

    a:link {
      @include style-link-text($color-text-dark);
    }
  }
}

.buttons {
  float: right;
}

%btn-placeholder {
  @include style-link-text($color-text-light);
  padding: 10px;
  display: inline-block;
  text-align: center;
  border-radius: 100px;
  width: $width-button;
}

// @mixin btn-placeholder {
//   @include style-link-text($color-text-light);
//   padding: 10px;
//   display: inline-block;
//   text-align: center;
//   border-radius: 100px;
//   width: $width-button;
// }

.btn-main {
  @extend %btn-placeholder;
  // @include btn-placeholder;
  &:link {
    background-color: $color-secondary;
  }

  &:hover {
    background-color: darken($color-secondary, 15%);
  }
}

.btn-hot {
  @extend %btn-placeholder;
  // @include btn-placeholder;
  &:link {
    background-color: $color-terriary;
  }

  &:hover {
    background-color: lighten($color-terriary, 10%);
  }
}
</style>

# Vue Files Dropper
Simple input for drop files on vue

### [Live Demo](https://d-shorkin.github.io/vue-files-dropper/)

## Install
### npm
```
npm install vue-files-dropper --save
```

```ecmascript 6
import "vue-files-dropper";
import "vue-files-dropper/dist/vue-files-dropper.css";
```

## Usage
Use it with `v-model` :
```vue
<vue-files-dropper v-model="file">Drop yor file</vue-files-dropper>
```

You can use `multiple` property:
```vue
<vue-files-dropper v-model="files" multiple>Drop yor files</vue-files-dropper>
```

## Customize

You can add class and customize input.
```vue
<vue-files-dropper v-model="file" class="aqua">Drop yor file</vue-files-dropper>
```

```scss
.aqua{
    background: aqua;
    border-color: darken(aqua, 5);
    min-height: 10em;
    transition: 1s;

    &:not(.disabled){
      &:hover, &.hover{
        background: chocolate !important;
        color: white;
        border-color: darken(chocolate, 5);
      }
    }
  }
```

#### Contributors

- [Vlad Nerbeer](https://github.com/Nerbeer)
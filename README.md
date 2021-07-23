# VUE JS  

директивы 

v-claok  для скрытия не отпрендеринного обьекта, требует написания в css ``` [v-cloak] { display: hiden} ``` <br>
v-text  для передачи текста в тег, пример  ```<h1 v-text="text"></h1>  => HELLO WORLD```   <br>
v-html для передачи куска разметки  html   ```<h1 v-html="embolden(fullName)"></h1>   =>  <strong>Jan Kowalski</strong>``` <br>
v-once  еденичный рендеринг <br>
v-bind  =>  ``` <a v-bind:href="url">{{ url }} </a>  or  <a :href="url">{{ url }} </a> ``` <br> 
v-on:? or @click => evelListener  ``` <button class="..." v-on:click="naFunction">click me </button>``` <br> 
``` <button class="btn btn-primary" v-on:click="increment" :disabled="counter >= 10">click me </button>``` <br> 

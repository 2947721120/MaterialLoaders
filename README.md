![Image](/art/poster-github.png)

[![GitHub stars](https://img.shields.io/github/stars/smartagent47/MaterialLoaders.svg)](https://github.com/smartagent47/MaterialLoaders/stargazers) [![GitHub forks](https://img.shields.io/github/forks/smartagent47/MaterialLoaders.svg)](https://github.com/smartagent47/MaterialLoaders/network) [![GitHub issues](https://img.shields.io/github/issues/smartagent47/MaterialLoaders.svg)](https://github.com/smartagent47/MaterialLoaders/issues) [![GitHub license](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/smartagent47/MaterialLoaders/master/LICENSE)

# Material Loaders

Material Loaders is a small library which contains loaders and spinners which act as small elements of a professional website 
having a fill of material colors. 


### How to implement a loader ?

I have found a great resource. Go <a href="https://www.w3schools.com/howto/howto_css_loader.asp">here.</a> Follow the instructions over there


### 用法 

* 包括该 **MLoaders.css** 或缩小版本 `<head>` 标签.

```html
  <head> 
    <link rel="stylesheet" href="Mloaders.min.css">
  </head>
  ```
  
* 其次，包括主类'mloader'和来自下面提到的类中的任何一个类 :- 
  
  
##### 弹性 
 ```html
   <div class="mloader bouncy bouncy-balls">
     <span></span>
     <span></span>
     <span></span>
   </div>
  ```
##### 圈
  ```html
  <div class="mloader circle c-red-500"></div>
  ```
  * 圆的类是 :- 
    `c-red-500`
    `c-pink-500`
    `c-purple-500`
    `c-deep-purple-500`
    `c-indigo-500`
    `c-blue-500`
    `c-light-blue-500`
    `c-cyan-500`
    `c-teal-500`
    `c-green-500`
    `c-light-green-500`
    `c-lime-500`
    `c-yellow-500`
    `c-amber-500`
    `c-orange-500`
    `c-deep-orange-500`
    `c-brown-500`
    `c-blue-grey-500`
    `c-black-500`
    
    
##### 五颜六色的正方形
  ```html
  <div class="mloader s-colorful"></div>
  ```
    
##### 旋转圈
  ```html
  <div class="mloader spin-circle">
    <span></span>
    <span></span>
  </div>
  ```
##### 环
  ```html
  <div class="mloader ring r-red-500"></div>
  ```
  
  * Classes of circle are :- 
    `r-red-500`
    `r-pink-500`
    `r-purple-500`
    `r-deep-purple-500`
    `r-indigo-500`
    `r-blue-500`
    `r-light-blue-500`
    `r-cyan-500`
    `r-teal-500`
    `r-green-500`
    `r-light-green-500`
    `r-lime-500`
    `r-yellow-500`
    `r-amber-500`
    `r-orange-500`
    `r-deep-orange-500`
    `r-brown-500`
    `r-blue-grey-500`
    `r-black-500`
    
    
##### Square
  ```html
  <div class="mloader square s-red-500">
    <div class="square-inside"></div>
  </div>
  ```
  
  * Classes of circle are :- 
    `s-red-500`
    `s-pink-500`
    `s-purple-500`
    `s-deep-purple-500`
    `s-indigo-500`
    `s-blue-500`
    `s-light-blue-500`
    `s-cyan-500`
    `s-teal-500`
    `s-green-500`
    `s-light-green-500`
    `s-lime-500`
    `s-yellow-500`
    `s-amber-500`
    `s-orange-500`
    `s-deep-orange-500`
    `s-brown-500`
    `s-blue-grey-500`
    `s-black-500`
    
    
##### 定时器
  ```html
  <div class="mloader timer"></div>
  ```
##### 虚线圆
```html
  <div class="mloader circle-dot"></div>
  ```
##### 环演化
```html
  <div class="mloader e-ring"></div>
  ```

##### 棍子
```html
  <div class="sticks"></div>
  ```
  
##### 填充圆
```html
  <div class="mloader fill-circle">
     <span></span>
  </div>
  ```
  
##### Flip-board
```html
  <div class="mloader flip-board">
  </div>
  ```
  
##### 谷歌加载
```html
  <div class="mloader google">
    <div></div>
    <div></div>
    <div></div>
    <div></div>
  </div>
  ```
##### 双圈
```html
  <div class="mloader double-circle"></div>
```

##### Bar
```html
  <div class="bar"></div>
```

##### Spin Wheel
```html
  <div class="four-color"></div>
```

##### Lines 
```html
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
  <div class="line"></div>
 ```

##### Flying Dots
```html
  <div class="flying-dots">
       <span></span>
       <span></span>
       <span></span>
  </div>
 ```
 
##### Oscillation
```html
  <div class="oscillate"></div>
```

##### 移动正方形
```html
  <div class="moving-square"></div>
```

### :bulb: Tip

建议用另一个div包装加载器或旋转器div，以便可以水平和垂直地居中包装器div. 

  
 * Lastly, enjoy the loaders and spinners. As a token of appreciation, a **star** to this repository will help me to bring you more libraries in near future.


 ### License
 
    Copyright 2017 Idrees Dargahwala

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

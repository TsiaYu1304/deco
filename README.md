# decollte


### function slideIndicatorCarousel (可自動 / 滑動 / 手動 輪播)
* `x-data="slideIndicatorCarousel"` 
* 自動播放 `x-data="slideIndicatorCarousel(true)"` 就帶 true (預設不自動撥放)
* 搭配 daisyUI
* 輪播的div  class="carousel" x-ref="carousel"
* 輪播的每個項目 class="carousel-item"
* 下面有點點的 每個點點 @click="goTo('第幾個item')"
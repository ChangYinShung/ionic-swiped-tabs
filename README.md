ionic-swiped-tabs
=====================

> fork from [newsof1111/ionic_swiped-tabs-v1.1](https://github.com/ChangYinShung/ionic-swiped-tabs).

#Table of contents
- [Installation](#installation)
- [Usage](#Usage)

# Installation

1. Import the `ionic-swiped-tabs` javascript and css file into your HTML file:

  ```html
  <script src="/src/js/slidingTabsDirective.js"></script>
  <link href="/src/css/slidingTab.css" rel="stylesheet">
  ```
  

# Usage
1.Setting `Css`
  ```css
          .slider-slide-tab span:last-child {
            border-radius: 10px;
            background: #ef473a;
            padding: 3px 8px;
            color: white;
            position: relative;
            bottom: 8px;
            left: 5px;
            font-weight: bold;
            box-shadow: 0 0 1px #333;
        }
          .scrollmenu.scroll-view.scroll-x {
            overflow-x: hidden; 
        }
  ```
2.See Full Detail `www/templates/tab-charts.html` 
  ```html
	 <ion-slide-box slide-tabs-scrollable="true"  show-pager="false" ion-slide-tabs>
                <ion-slide ion-slide-tab-label="{{Height}}"><div ng-include src="'templates/chats.html'" style="height: {{Height}}px;"></div></ion-slide>
                <ion-slide ion-slide-tab-label="another tab"><div ui-view="e"  class="col col-dynamic-40" dynamic-md-layout></div></ion-slide>
                <ion-slide ion-slide-tab-label="tab3"><h1>Tab 3</h1><button ng-click="nextSlide()" >Next slide!</button></ion-slide>
                <ion-slide ion-slide-tab-label="another tab again"><h1>Tab 4</h1><button ng-click="nextSlide()">Next slide!</button></ion-slide>
                <ion-slide ion-slide-tab-label="a very large tab"><h1>Tab 5</h1><button ng-click="nextSlide()">Next slide!</button></ion-slide>
                <ion-slide ion-slide-tab-label="tab6"><h1>Tab 6</h1><button ng-click="nextSlide()">Next slide!</button></ion-slide>
            </ion-slide-box>
  ```





(c) Author: newsof1111  | https://github.com/newsof1111/ionic_swiped-tabs-v1.1

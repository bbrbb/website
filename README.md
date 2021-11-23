# CHANEL Website
Establishment of a responsive shopping mall website using Bootstrap.    
Bootstrapを用いた反応型ウェブサイトを構築。     
![preview1](https://user-images.githubusercontent.com/87357349/142412421-a22fa89a-54fb-4f39-a69f-40f0f7591de1.jpg)
* DEMO : https://new-chanel.boribori3.repl.co
## Development goal.
1. Use of various components and classes of Bootstrap and understanding of Bootstrap Grid.       
  Bootstrapの様々なコンポーネントとクラス使用、およびBootstrap Gridを理解する。    
2. Building a responsive web page using Media query.    
    メディアクォーリーを利用した反応型ウェブページを構築
## Technology of use 使用技術
* HTML
* CSS
* Bootstrap
* Media Query
## Advanced Feature
* Footer development using Media query    
* Media queryを利用したFooter開発   
(Web version)    
![그리드](https://user-images.githubusercontent.com/87357349/142878827-f84e29cf-8d23-495a-81d2-0e5ee490db16.JPG)    
(Mobile version)   
![그리드 2](https://user-images.githubusercontent.com/87357349/142878850-85f0b57b-9b6d-43b0-a279-335123ffec11.JPG)    

```
@media screen and (max-width: 48rem) {
  .one-box {
    font-size: 10px;
    display: flex;
  }
  .two-box {
    display: flex;
    font-size: 12px;
  }
}

```


   
* Building a responsive layout using bootstrap Grid.       
 Bootstrap Gridを用いた反応型レイアウトの構築    
(Web version)    
![웹버전](https://user-images.githubusercontent.com/87357349/142879505-c073b10b-cac3-47bd-82c0-78d06de14601.JPG)
(Mobile version)    
![모바일](https://user-images.githubusercontent.com/87357349/142879530-184df82b-cd31-4b7c-ad42-db4397113305.JPG)

```
<div class="container card-box mt-5 mb-5">
    <div class="row">

      <div class="col-md-4 col-sm-12">
        <div class="card"  >
        <img src="https://www.chanel.com/i18n/en_CA/slides/1600_j12.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-text text-center">J12 LIMITED EDITIONS</p>
        </div>
        </div>
      </div>


      <div class="col-md-4 col-sm-12">
        <div class="card"  >
        <img src="https://www.chanel.com/i18n/en_CA/slides/1600_n5_holiday.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-text text-center">Ask for the moon*
            N°5 LIMITED EDITIONS</p>
        </div>
        </div>
      </div>

      <div class="col-md-4 col-sm-12">
      <div class="card">
        <img src="https://www.chanel.com/i18n/en_CA/slides/1600_holiday_mu.jpg"  class="card-img-top " alt="...">
        <div class="card-body">
          <p class="card-text text-center">THE INTERSTELLAR MAKEUP LOOK</p>
        </div>
        </div>
      </div>
     </div>
  </div>
  ```
 * Use classes provided by Bootstrap to eliminate unnecessary duplication of CSS code.     
  Bootstrapで提供するクラスを使用してCSSコードの不必要な重複をなくす。
 
 

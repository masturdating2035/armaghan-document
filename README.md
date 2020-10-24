## Packages :package:
`axios`,
`fontawesome`,
`formik`,
`history`,
`jalali-moment`,
`logrocket`,
`react`,
`react-dom`,
`react-countdown`,
`react-fade-in`,
`react-image-appear`,
`react-loading-skeleton`,
`react-modern-calendar-datepicker`,
`redux`,
`react-redux`,
`redux-thunk`,
`react-redux-loading-bar`,
`react-redux-toastr`,
`react-router-dom`,
`react-scripts`,
`react-select`,
`styled-components`,
`swiper`,
`video.js`,
`videojs-contrib-hls`, 
`videojs-contrib-quality-levels`,
`videojs-hls-quality-selector`,
`videojs-landscape-fullscreen`,
`videojs-seek-buttons`,
`videojs-titleoverlay`,
`videojs-vtt-thumbnails` 


## Routes :door:
* this route forward user to __Home__ component                         => `<Route path='/' exact component={Home}/>`
* this route forward user to __Vod__ component                          => `<Route path='/vod' exact component={Vod}/>`
* this route forward user to __SingleVod__ component                    => `<Route path='/vod/:id' component={SingleVod}/>`
* this route forward user to __Pardis__ component                       => `<Route path='/pardis' component={Pardis}/>`
* this route forward user to __Learning__ component                     => `<Route path='/learning' component={Learning}/>`
* this route forward user to __Kids__ component                         => `<Route path='/children' component={Kids}/>`
* this route forward user to __PaymentReceipt__ component               => `<Route path='/invoice/:id' exact component={PaymentReceipt}/>`
* this route forward user to __Live__ component                         => `<Route path='/live' component={Live}/>`
* this route forward user to __Search__ component                       => `<Route path='/search' component={Search}/>`
* this route forward user to __Series__ component                       => `<Route path='/series' exact component={Series}/>`
* this route forward user to __SingleSerial__ component                 => `<Route path='/series/:id' component={SingleSerial}/>`
* this route forward user to __Genres__ component                       => `<Route path='/genres' exact component={Genres}/>`
* this route forward user to __SingleGenre__ component                  => `<Route path='/genres/:name' component={SingleGenre}/>`
* this route forward user to __Cast__ component                         => `<Route path='/cast/:id' component={Cast}/>`
* this route forward user to __Sport__ component                        => `<Route path='/sport' component={Sport}/>`
* this route forward user to __TermsAndConditions__ component           => `<Route path='/terms-and-conditions' component={TermsAndConditions}/>`
* this route forward user to __SingleCategory__ component               => `<Route path='/category/:type/:id/:name' component={SingleCategory}/>`
* if user enter the wrong url so user forward to __NotFound__ component => `<Route path='*' component={NotFound}/>`


## Private Routes :door::key:



















#### if action call an api start with *get*,              example : `getHomeSlider`
#### if action set data to store start with *set*,        example : `setHomeSlider`
#### if action clear store start with *clear*,            example : `clearHomeSlider`
#### if action set loading , start with *is_x_loading*,   example : `isHomeSliderLoading`

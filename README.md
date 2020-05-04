# Uber
Uber
*
  font-family: 'Roboto', sans-serif

header
  position: relative
  height: 50px

nav
  height: 50px
  background-color: #212121
  position: fixed
  width: 100%
  z-index: 2

.menu
  display: flex
  justify-content: space-between
  padding: 13px 70px
  margin: 0
  list-style-type: none

  .menu_link
    color: #ffffff
    font-size: 15px
    font-weight: 300

  .menu_item
    border-right: 2px dotted black
    padding-right: 28px

.subheader
  margin-top: 50px
  position: absolute
  width: 100%
  height: 84px
  background-color: rgba(0, 0, 0, 0.6)

  .subheader_logo
    display: block
    max-width: 100%
    margin-top: 16px

  .subheader_official
    margin-top: 6px
    opacity: 0.5
    color: #ffffff
    font-size: 13px
    font-weight: 400

  .subheader_call
    margin-top: 19px
    text-align: right
    margin-top: 23px
    color: #ffffff
    font-size: 12px
    font-weight: 300

  .subheader_phone
    display: block
    margin-top: 8px
    color: #ffffff
    font-size: 22px
    font-weight: 400
    text-transform: uppercase
    text-align: right
    line-height: 12px

  .subheader_btn
    margin-top: 19px
    width: 172px
    height: 46px
    box-shadow: inset 0 -3px 0 rgba(0, 0, 0, 0.12)
    border: none
    border-radius: 4px
    background-image: linear-gradient(to top, #1eacc7 0%, #4ce2ff 100%)
    text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.21)
    color: #ffffff
    font-size: 14px
    font-weight: 400
    text-transform: uppercase

.promo
  min-height: 800px
  background: url('../img/bg_1car.jpg') center (center / cover) no-repeat
  padding: 150px 0 135px 0

  .promo_header
    color: #ffffff
    font-weight: 700
    text-transform: uppercase
    font-size: 60px
    line-height: 60px
    margin: 0
    text-align: center

  .promo_subheader
    color: #ffffff
    font-weight: 700
    text-transform: uppercase
    font-size: 36px
    line-height: 36px
    margin: 0
    margin-top: 22px
    text-align: center

  .promo_descr
    color: #ffffff
    font-size: 18px
    font-weight: 400
    line-height: 24px
    text-align: center
    margin-top: 23px

  .promo_btn
    display: block
    margin: 118px auto 0 auto
    width: 259px
    height: 63px
    box-shadow: inset 0 -4px 0 rgba(0, 0, 0, 0.12)
    border: none
    border-radius: 4px
    background-image: linear-gradient(to top, #1eacc7 0%, #4ce2ff 100%)
    color: #ffffff
    font-size: 18px
    font-weight: 400
    line-height: 68px
    text-transform: uppercase

.reasons
  padding: 71px

.logo
  position: relative
  margin: 0 auto
  height: 24px
  width: 112px
  padding: 5px 12px
  background-color: #000000
  color: #ffffff
  font-size: 11px
  font-weight: 300
  text-transform: uppercase
  text-align: center
  &_white 
    background-color: #fff
    color: #000
  
  
  

.title
  position: relative
  margin-bottom: 0
  margin-top: 38px
  color: #222222
  font-size: 38px
  font-weight: 700
  line-height: 48px
  text-transform: uppercase
  text-align: center
  &_white 
    color: #fff

.subtitle
  position: relative
  margin-top: 19px
  color: #222222
  font-size: 17px
  font-weight: 400
  text-align: center
  &_white 
    color: #fff
  

.reasons .reasons_block
  display: flex
  justify-content: center
  align-items: center
  margin-top: 40px

  .reasons_round
    display: flex
    justify-content: center
    align-items: center
    margin-right: 25px
    width: 113px
    height: 113px
    background-color: #1eacc7
    border-radius: 100%

  .reasons_descr
    width: 341px

    .reasons_subtitle
      line-height: 21px
      color: #1eacc7
      font-size: 17px
      font-weight: 400

    .reasons_text
      font-size: 15px
      font-weight: 300
      line-height: 21px

.mobile
  min-height: 864px
  padding: 48px 0 79px 0
  background: url('../img/bg_2.png') center (center / cover) no-repeat
  .row
    margin-top: 32px
  &_item
    position: relative
    width: 320px
    height: 280px
    margin: 0 auto
    margin-bottom: 19px
    padding-top: 92px
    &_1
      background: url('../icons/bf_1.jpg') center (center / cover) no-repeat
    &_2
      background: url('../icons/bf_2.jpg') center (center / cover) no-repeat
    &_3
      background: url('../icons/bf_3.jpg') center (center / cover) no-repeat
    &_4
      background: url('../icons/bf_4.jpg') center (center / cover) no-repeat
    &_5
      background: url('../icons/bf_5.jpg') center (center / cover) no-repeat
    &_6
      background: url('../icons/bf_6.jpg') center (center / cover) no-repeat
    &_subtitle
      color: #ffffff
      font-size: 24px
      font-weight: 400
      line-height: 31px
      text-transform: uppercase
      text-align: center
    &_plus
      display: flex 
      justify-content: center
      align-items: center
      position: absolute 
      bottom: 35px
      left: 50%
      transform: translateX(-50%)
      width: 26px
      height: 26px
      background-color: #000000
      margin: 0 auto
      border-radius: 100%
      cursor: pointer
      
.choice
  position: relative
  min-height: 895px
  padding: 57px 0 138px 0
  background: url('../img/bg_2.png') center (center / cover) no-repeat
  &_img
    position: relative
    display: block
    margin: 56px auto 0 auto
    z-index: 2
  &_descr
    text-align: center
    color: #222222
    font-size: 17px
    font-weight: 300
    line-height: 24px
  

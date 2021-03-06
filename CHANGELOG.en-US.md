---
order: 2
title: Change Log
timeline: true
toc: false
---

`antd-mobile` strictly follows [Semantic Versioning 2.0.0](http://semver.org/).

#### Release Schedule

- Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
- Monthly release: minor version at the end of every month for new features.
- Major version release is not included in this schedule for breadking change and new features.

---
### 2.3.3

`2020-05-19`

- **Bug Fix**
  - ð `InputItem` revert event to click from touchend, which changed by 2.3.2 [#3613](https://github.com/ant-design/ant-design-mobile/pull/3613)

### 2.3.2

`2020-05-13`

- **Enhancement**
  - ð `Switch` change style [#3606](https://github.com/ant-design/ant-design-mobile/pull/3606)

### 2.3.0

`2019-08-15`

- **Feature**
  - ð `Toast` add two method `Toast.config` ã`Toast.hide` [#3304](https://github.com/ant-design/ant-design-mobile/pull/3304)
  - ð `Input-Item`   add new `disabledKeys` prop for `type='money'`  [#3330](https://github.com/ant-design/ant-design-mobile/pull/3330)
- **Enhancement**
  - ð `notice-bar`  fix `typescript` error.
- **Bug Fix**
  - ð`DatePicker` fix infinite loop when select some date.[#125](https://github.com/react-component/m-picker/pull/125) ã[#191](
https://github.com/react-component/m-date-picker/pull/191)
  - ð`ImagePicker` fix preview picture not show when the url contains space. [#3311](https://github.com/ant-design/ant-design-mobile/pull/3311)
  - ðfix component demo not render in iOS 9. [#3292](https://github.com/ant-design/ant-design-mobile/pull/3292)
  -  ð`Modal.prompt` fix prompt can not be focus in Wechat [#3346](https://github.com/ant-design/ant-design-mobile/pull/3346)
  - `Tabs` support  `null` for tabs's children [#3270](https://github.com/ant-design/ant-design-mobile/pull/3270)

### 2.2.14

`2019-06-13`

- **Feature**

  - ð `InputItem` Add `autoAdjustHeight` config [#3246](https://github.com/ant-design/ant-design-mobile/pull/3246)

- **Enhancement**

  - ð `Tab` Update `initalPage` to `initialPage` [#3235](https://github.com/ant-design/ant-design-mobile/pull/3235)
  - ð `ListView` Update `dataSource` link [#3253](https://github.com/ant-design/ant-design-mobile/pull/3253)

- **Bug Fix**

  - ð `Calendar` Fixed element with flexbox can't scroll on Chrome [#3152](https://github.com/ant-design/ant-design-mobile/pull/3252)
  - ð `Picker` Fixed trigger `onPickerChange` problem [#3174](https://github.com/ant-design/ant-design-mobile/issues/3174)
  - ð `InputItem` add try catch to getSelection [#3237](https://github.com/ant-design/ant-design-mobile/pull/3237)
  - ð `Modal` Fixed show problem of using svg with Modal on iOS9 [#3229](https://github.com/ant-design/ant-design-mobile/pull/3229)


### 2.2.12

`2019-04-28`

- **Feature**

  - ð `ImagePicker` Add `disableDelete` config [#3185](https://github.com/ant-design/ant-design-mobile/pull/3185)

- **Enhancement**

  - ð Update modularized Doc [#3132](https://github.com/ant-design/ant-design-mobile/pull/3132)
  - ð§ `deploy` Add CNAME [#3172](https://github.com/ant-design/ant-design-mobile/pull/3172)
  - ð `InputItem` Optimize cursor position [#3189](https://github.com/ant-design/ant-design-mobile/pull/3189)
  - ð `@types/react` `@types/react-dom` Update [#3186](https://github.com/ant-design/ant-design-mobile/pull/3186)
  - ð `React import` Optimize [#3179](https://github.com/ant-design/ant-design-mobile/pull/3179)
  - ð `TypeScript` Update [#3181](https://github.com/ant-design/ant-design-mobile/pull/3181)
  - ð Add IPhoneX `safe-area` support [#3180](https://github.com/ant-design/ant-design-mobile/pull/3180)

- **Bug Fix**

  - ð `Typo` Fixed `datePicker` and `site` error [#3152](https://github.com/ant-design/ant-design-mobile/pull/3252) [#3187](https://github.com/ant-design/ant-design-mobile/pull/3187)
  - ð `Modal` Add `onPresss` parameter declaration [#3136](https://github.com/ant-design/ant-design-mobile/pull/3136)
  - ð `gitter` Fixed link error in Doc [US](https://github.com/ant-design/ant-design-mobile/commit/b32b3e3ef382d8496e67e1ce1928b22d3b301dfb) [CN](https://github.com/ant-design/ant-design-mobile/commit/6f0a04536e8d028e2111697820e8700142156f40)
  - ð `Tabs` Fixed `height` style error [#3188](https://github.com/ant-design/ant-design-mobile/pull/3188)
  - ð `List` Fixed `typescript` declaration error [#3183](https://github.com/ant-design/ant-design-mobile/pull/3183)

---

### 2.2.10

`2019-03-21`

- **Feature**

  - ð `ImagePicker` support multiple images [#3115](https://github.com/ant-design/ant-design-mobile/pull/3115)
  - ð `ImagePicker` support props.capture for mobile camera [#3114](https://github.com/ant-design/ant-design-mobile/pull/3114)

- **Bug Fix**

  - ð `TabBar` Fixed error caused by empty props.children [#3113](https://github.com/ant-design/ant-design-mobile/pull/3113)
  - ð `Flex` Fixed wrong classname with css [#3106](https://github.com/ant-design/ant-design-mobile/pull/3106)
  - ð `InputItem` Fixed display after input blur by click `complete` [#3017](https://github.com/ant-design/ant-design-mobile/pull/3017)
  - ð `InputItem` Fixed `setSelection` error on some browsers [#3124](https://github.com/ant-design/ant-design-mobile/pull/3124)

### 2.2.9

---

`2019-02-19`

- **Bug Fix**

  - ð `InputItem` Fixed `state.value` is undefined [#3044](https://github.com/ant-design/ant-design-mobile/pull/3044)
  - ð `InputItem` Fixed controled onChange [#3045](https://github.com/ant-design/ant-design-mobile/pull/3045)
  - ð `Button` Fixed props.icon typing error [#3051](https://github.com/ant-design/ant-design-mobile/pull/3051)
  - ð `Drawer` Fixed style z-index error [#3052](https://github.com/ant-design/ant-design-mobile/pull/3052)
  - ð `Toast` Fixed content typing error [#3067](https://github.com/ant-design/ant-design-mobile/pull/3067)

---

### 2.2.7

`2018-12-28`

- **Bug Fix**

  - ð `InputItem` Fixed an issue where the cursor position moved to the end after the `InputItem` formatted the text [#2854](https://github.com/ant-design/ant-design-mobile/pull/2854)
  - ð `Grid` Fix activeStyle declaration type error [#2996](https://github.com/ant-design/ant-design-mobile/issues/2996)

- **Enhancement**

  - ð Update `Modal`å`InputItem` document [#3023](https://github.com/ant-design/ant-design-mobile/pull/3023) [#3014](https://github.com/ant-design/ant-design-mobile/pull/3014)
  - ð Dependency update [#3013](https://github.com/ant-design/ant-design-mobile/issues/3013) [#3004](https://github.com/ant-design/ant-design-mobile/issues/3004)

### 2.2.6

`2018-10-25`

- **Bug Fix**
  - `Carousel` add property declaration [#2848](https://github.com/ant-design/ant-design-mobile/pull/2848)
- **Enhancement**

  - ð `Switch` Update Demo [Commit](https://github.com/ant-design/ant-design-mobile/commit/3c8a5e92c43899582c335ddc2d352b1e916ea9e9)
  - ð Site update [#2894](https://github.com/ant-design/ant-design-mobile/pull/2894) , [#2903](https://github.com/ant-design/ant-design-mobile/pull/2903)

### 2.2.4

`2018-09-06`

- **Feature**

  - ð `InputItem` add `moneyKeyboardHeader` property [#2820](https://github.com/ant-design/ant-design-mobile/pull/2820)
  - ð `PickerView` accept one-dimensional array as data property [#2815](https://github.com/ant-design/ant-design-mobile/pull/2815)

- **Bug Fix**

  - ð `Popup` Popup should be compatible with bottom safe area [#2810](https://github.com/ant-design/ant-design-mobile/pull/2810)
  - ð `Button` fix button with icon and inline style [#2822](https://github.com/ant-design/ant-design-mobile/pull/2822)
  - ð `TextareaItem` fix line break cause by textareaItem word count corrupt for iOS [#2825](https://github.com/ant-design/ant-design-mobile/pull/2825)

### 2.2.3

`2018-08-09`

- **Feature**

  - ð `ImagePicker` support customized length ([#2700](https://github.com/ant-design/ant-design-mobile/pull/2700))
  - ð `Picker` support using label prop with ReactNode ([#2720](https://github.com/ant-design/ant-design-mobile/pull/2720))

- **Enhancement**

  - ð `DatePicker` Update Doc ([#2657](https://github.com/ant-design/ant-design-mobile/pull/2657))

### 2.2.2

`2018-07-12`

- **Feature**

  - ð `Tabs`: support Barrier Free Access [PR](https://github.com/react-component/m-tabs/pull/25)
  - ð `ImagePicker`: support customized length [#2619](https://github.com/ant-design/ant-design-mobile/issues/2619) [#2668](https://github.com/ant-design/ant-design-mobile/issues/2668)

- **Bug Fix**

  - ð `Picker`: fix get wrong value when `prop.value` has `undefined` [#2695](https://github.com/react-component/m-cascader/pull/18)
  - ð `Flex`: fix style when `direction=column` [#2683](https://github.com/ant-design/ant-design-mobile/pull/2711)

### 2.2.1

`2018-06-27`

- **Feature**

  - ð `TabBar` add tabBarPosition on TabBar [#2564](https://github.com/ant-design/ant-design-mobile/pull/2564)
  - ð `Menu` & `PullToRefresh` support locale [#2669](https://github.com/ant-design/ant-design-mobile/pull/2669)

- **Bug Fix**

  - ð `Picker` add translateZ on wrap and mask [#2653](https://github.com/ant-design/ant-design-mobile/pull/2653)
  - ð `Tabs` fix underline render error on some webview [#2674](https://github.com/ant-design/ant-design-mobile/pull/2674)
  - ð `PopOver` (iOS) fix event onVisibleChange not trigger when click mask [#2659](https://github.com/ant-design/ant-design-mobile/issues/2659)
  - ð `Calendar` fix error [#2655](https://github.com/ant-design/ant-design-mobile/issues/2655)

- **Enhancement**

  - ð Update Jest [#2657](https://github.com/ant-design/ant-design-mobile/pull/2657)

### 2.2.0

`2018-06-15`

Note: According to the previous [2.1.x final version plan](https://github.com/ant-design/ant-design-mobile/issues/2556), we have separated the react native components into a separate [ant-design-mobile-rn](https://github.com/ant-design/ant-design-mobile-rn) repo, and the `antd-mobile-rn` npm package has been released. If you use the react native components, modify your `package.json` file like so:

```diff
  ...
  "dependencies": {
-   "antd-mobile": "^2.1.11",
+   "antd-mobile-rn": "^2.2.0",
    "react": "16.3.1",
    ...
  },
  ...
```

Then reinstall node_modules.

- **Feature**

  - ð add `prerenderingSiblingsNumber` prop for `TabBar` ([#2607](https://github.com/ant-design/ant-design-mobile/pull/2607))
  - ð add ssr support ([#2605](https://github.com/ant-design/ant-design-mobile/issues/2605))

- **Bug Fix**

  - ð Fix `Popover` ts type ([#2571](https://github.com/ant-design/ant-design-mobile/issues/2571))

- **Enhancement**

  - ð Update `Stepper` API doc ([#2573](https://github.com/ant-design/ant-design-mobile/issues/2573))
  - Improve test

### 2.1.11

`2018-05-31`

- **Bug Fix**

  - ð Fix `InputItem`'s unknown-prop warning ([#2565](https://github.com/ant-design/ant-design-mobile/pull/2565) [#2601](https://github.com/ant-design/ant-design-mobile/issues/2601))
  - ð Fix `Steps` may have null children ([#2329](https://github.com/ant-design/ant-design-mobile/issues/2329))
  - ð RN: fix `Modal` footer button vertical alignment ([#2325](https://github.com/ant-design/ant-design-mobile/pull/2325))
  - ð RN: fix `NoticeBar` Animate ([#2267](https://github.com/ant-design/ant-design-mobile/issues/2267))
  - ð RN: fix `SearchBar` style ([#2593](https://github.com/ant-design/ant-design-mobile/issues/2593))

- **Enhancement**

  - ð RN: add a hint of `antd-mobile-rn` package ([#2556](https://github.com/ant-design/ant-design-mobile/issues/2556))
  - ð Workflow: add lock-issue script ([86fb0787e9e13754](https://github.com/ant-design/ant-design-mobile/commit/86fb0787e9e137548ef03517e1ca9fa2e061ceaa))
  - ð Demo: update `Card` `TextareaItem` `PullToRefresh` `Picker` demo

### 2.1.10

`2018-05-24`

- **Feature**

  - ð RN `InputItem` add custom `focus` prop ([#2408](https://github.com/ant-design/ant-design-mobile/pull/2408))
  - ð RN `InputItem` add clear button for android([#2358](https://github.com/ant-design/ant-design-mobile/pull/2358))

* **Bug Fix**

  - ð Fix `InputItem` error focus in aria mode([#2568](https://github.com/ant-design/ant-design-mobile/pull/2568))
  - ð Fix input embeded `Modal` can not focus ([#2177](https://github.com/ant-design/ant-design-mobile/issues/2177))
  - ð Fix RN `DatePicker` mode month([#0a701](https://github.com/ant-design/ant-design-mobile/commit/0a701dd205c636804f7e63d7b7d3a2283aad293b))
  - ð Fix RN `InputItem` error input content on the type of `phone`([#4ab82](https://github.com/ant-design/ant-design-mobile/commit/4ab82fadc55268cef8558f0423d5ba2f6e4b38d5))

- **Enhancement**

  - ð Update RN `Icon` demo
  - ð Update RN `Picker` docs, add `onVisibleChange` prop
  - ð Update RN `Range` demo
  - ð Update RN `LocaleProvider` demo

### 2.1.9

`2018-05-21`

- **Feature**

  - ð `InputItem` add custom `onVirtualKeyboardConfirm` prop, supporting confirm callback of virtual keyboard([#2551](https://github.com/ant-design/ant-design-mobile/pull/2551))
  - ð `InputItem` add custom `moneyKeyboardWrapProps` prop, by which can solve the click penetrate problem ([#2550](https://github.com/ant-design/ant-design-mobile/pull/2550))
  - ð [React Native] support focus callback for `InputItem` under React Native ([#2381](https://github.com/ant-design/ant-design-mobile/issues/2381))
  - ð support Russian language ([#2400](https://github.com/ant-design/ant-design-mobile/pull/2400))

* **Bug Fix**

  - ð Fix `TextareaItem`ã`InputItem` invalid `clear` prop([#2372](https://github.com/ant-design/ant-design-mobile/issues/2372))
  - ð Fix `SearchBar` appear error style when using with `TabBar`([#2447](https://github.com/ant-design/ant-design-mobile/issues/2447))
  - ð Fix `InputItem` can not delete the default value when defaultValue or value is number on the type of `money` ([#2493](https://github.com/ant-design/ant-design-mobile/issues/2493))
  - ð Fix `Accordion` can not read expand and folding status in Preact under talkback mode in Android ([#2491](https://github.com/ant-design/ant-design-mobile/issues/2491))
  - ð Fix `InputItem` misplaced cursor in UC Browser on the type of `bankCard`([#2441](https://github.com/ant-design/ant-design-mobile/issues/2441))
  - ð Fix `Modal` can not close ([#2486](https://github.com/ant-design/ant-design-mobile/issues/2486))
  - ð Fix `Picker`ã`SearchBar` I18n ([#2502](https://github.com/ant-design/ant-design-mobile/issues/2502))
  - ð Fix `InputItem` aria support when using virtual keyboard([#2419](https://github.com/ant-design/ant-design-mobile/issues/2419), [#2418](https://github.com/ant-design/ant-design-mobile/issues/2418))
  - ð Fix component definition ([5a2d0d](https://github.com/ant-design/ant-design-mobile/commit/5a2d0d57a796ca739cb22306d48377ea5a2c27c3))

- **Enhancement**

  - ð Update `Carousel` demo([#2434](https://github.com/ant-design/ant-design-mobile/issues/2434))
  - ð Update `Progress` api docs
  - ð Update `LocaleProvider` demo
  - ð Add `tabbar` using with `ListView` demo
  - ð change the dep of `rc-drawer` to `rmc-drawer` ([3fd1a5d](https://github.com/ant-design/ant-design-mobile/commit/3fd1a5d97273d32195da0a863ecc81b32e2b0d07)

### 2.1.8

`2018-03-19`

- **Bug Fix**

  - ð Fix `InputItem[type="money"]` onChange handler arguments change from value to event object. ([#2403](https://github.com/ant-design/ant-design-mobile/pull/2403))

### 2.1.7

`2018-03-16`

- **Bug Fix**

  - ð Fix `Grid` no border usage.
  - ð Fix `Modal.prompt` onPress return promise. ([#2243](https://github.com/ant-design/ant-design-mobile/pull/2243))
  - ð Fix `ImagePicker` throw Error when readd pic after deleteã([#2302](https://github.com/ant-design/ant-design-mobile/pull/2302))
  - ð Fix `Carousel` `autoplayInterval` usage. ([#2369](https://github.com/ant-design/ant-design-mobile/issues/2369))
  - ð Fix RN `Modal.Alert` content not align center. ([#2347](https://github.com/ant-design/ant-design-mobile/pull/2347))

- **Enhancement**

  - ð Refactor all TypeScript Interface definition. [#2323](https://github.com/ant-design/ant-design-mobile/pull/2323)ã
  - ð Add [Demo](https://github.com/ant-design/ant-design-mobile/commit/e210a6db81af48d2e0aa1881c4a192ca4a10dfb2) about custom `Tabs` page number.

### 2.1.6

`2018-02-05`

- **Bug Fix**

  - ð Fix `Modal.prompt` can not input.

### 2.1.5

`2018-01-29`

- **Feature**

  - ð `ImagePicker` support custom `accept`.([#2269](https://github.com/ant-design/ant-design-mobile/pull/2269))

- **Bug Fix**

  - ð Fix `InputItem` be cover by keyboard in ios 11. ([#2289](https://github.com/ant-design/ant-design-mobile/pull/2289))
  - ð Fix `Menu` be content be coverd by confim button.([#2273](https://github.com/ant-design/ant-design-mobile/issues/2273))
  - ð Fix `Progress` tsdã([#2292](https://github.com/ant-design/ant-design-mobile/issues/2292))
  - ð [React Native] Fix `TextareaItem` extra margin left.([#2260](https://github.com/ant-design/ant-design-mobile/pull/2260))

* **Enhancement**

  - ð Fix [Picker](https://github.com/ant-design/ant-design-mobile/issues/2291), [DatePicker, Calendar](https://github.com/ant-design/ant-design-mobile/issues/2282) doc.

### 2.1.4

`2018-01-23`

- **Bug Fix**

  - Fix: Modal defaultValue problem. ([#2221](https://github.com/ant-design/ant-design-mobile/pull/2221))
  - Fix: Modal click event not correctly. ([#1975](https://github.com/ant-design/ant-design-mobile/pull/1975))
  - Fix: TextArea styles.
  - Fix: DatePicker/Picker value cache problem.
  - Fix: InputItem error. ([#2220](https://github.com/ant-design/ant-design-mobile/pull/2220))

### 2.1.3

`2017-12-29`

Happy new year 2018 ð

- **Enhancement**

  - New website.
  - Improve InputItem doc.

- **Bug Fix**

  - Fix: Add defaultDate for DatePicker.
  - Fix: Delete redundant Modal code.

### 2.1.2

`2017-12-15`

- **Bug Fix**

  - Fix `Modal` buttons can't trigger more than once.([#1975](https://github.com/ant-design/ant-design-mobile/issues/1975))
  - Fix `Modal` `DatePicker` document issues.
  - Fix upgradeTip / site style issues.

### 2.1.1

`2017-12-06`

- **Bug Fix**

  - ð Fix `List` padding incrase in rem style page. ([#2145](https://github.com/ant-design/ant-design-mobile/pull/2145))
  - ð Fix `body.fontSize` to `@font-sizep-base` 14pxã ([8973a0f](https://github.com/ant-design/ant-design-mobile/commit/8973a0f890e776a47743188b14356bee34b68ad6))
  - ð Fix `Button` do not show until scroll in iOS 11. ([6b571bef](https://github.com/ant-design/ant-design-mobile/commit/6b571bef0d714e8fdb7c4434ee1ab280be9952fd))

### 2.1.0

`2017-12-03`

- **Feature**

  - ð `Steps` [React Native] support `horizontal`. ([#2090](https://github.com/ant-design/ant-design-mobile/pull/2090))
  - ð `ImagePicker` support `multiple`. ([#2017](https://github.com/ant-design/ant-design-mobile/issues/2017))
  - ð¸ðª `LocaleProvider` add swedish. ([#2132](https://github.com/ant-design/ant-design-mobile/pull/2132))

- **Bug Fix**

  - ð Fix `[InputItem type="money"]` cover page content. ([#1893](https://github.com/ant-design/ant-design-mobile/issues/1893))
  - ð Fix `[InputItem type="money"]` multi instance at one page. ([#2065](https://github.com/ant-design/ant-design-mobile/issues/2065))
  - ð Fix `Menu` props.data null array. ([#2079](https://github.com/ant-design/ant-design-mobile/pull/2079))
  - ð Fix `Menu` lost Button style. ([#2097](https://github.com/ant-design/ant-design-mobile/issues/2097))
  - ð Fix `InputItem`, `Drawer` tsd. ([#2100](https://github.com/ant-design/ant-design-mobile/issues/2100), [#2138](https://github.com/ant-design/ant-design-mobile/issues/2138))
  - ð Fix `Picker` cascader data not accuracy. ([59a66c](https://github.com/ant-design/ant-design-mobile/commit/59a66cfbe0daef8c9f080d0387bc880e54632fe0))
  - ð Fix `TabBar` animation. ([#2072](https://github.com/ant-design/ant-design-mobile/issues/2072))
  - ð Fix `Textarea` autoHeight not work when init. ([#2118](https://github.com/ant-design/ant-design-mobile/issues/2118))
  - ð Fix `Flex` [React Native] no need to add touch feedback when no event handler ([#2095](https://github.com/ant-design/ant-design-mobile/pull/2095))
  - ð Fix `Toast` can not hide after click. ([#2103](https://github.com/ant-design/ant-design-mobile/issues/2103))
  - ð Fix `Textarea` clear not work in controlled mode. ([#2131](https://github.com/ant-design/ant-design-mobile/issues/2131))
  - ð Fix `TabBar` sticky. ([#2136](https://github.com/ant-design/ant-design-mobile/issues/2136))

- **Theme**

  - ð Delete bulit-in `body` font-size style. ([#2106](https://github.com/ant-design/ant-design-mobile/pull/2106))
  - ð `brand-primary-tap` change to `0e80d2`ã ([#2115](https://github.com/ant-design/ant-design-mobile/pull/2115))

### 2.0.3

`2017-11-11`

- **Bug Fix**

- Fix: InputItem error with react@16 when unmountï¼([#2040](https://github.com/ant-design/ant-design-mobile/issues/2040))
- Fix: InputItem onBlur cannot be triggered when unmountï¼
- Fix: ListItem RN content centerï¼([#2052](https://github.com/ant-design/ant-design-mobile/issues/2052))
- Fix: SwipeAction may not work in iOS8; ([#2063](https://github.com/ant-design/ant-design-mobile/issues/2063))
- Fix: Stepper buttons cannot be disable if mininus value is 0ï¼([#2062](https://github.com/ant-design/ant-design-mobile/issues/2062))

- **Feature**

  - Grid RN add `itemStyle` property to customize item styleï¼([#2046](https://github.com/ant-design/ant-design-mobile/pull/2046))
  - TabBar(web) add `noRenderContent` property to support no render content;

- **Enhancement**

  - 1.x doc `open in codepen` is OK now.ï¼([#2032](https://github.com/ant-design/ant-design-mobile/issues/2032))

### 2.0.2

`2017-11-04`

- **Bug Fix**

  - Fixï¼`onTouch` event cannot be trigged when components use `List.Item` with rmc-feedbackï¼
  - Fix: Tabs invalid z-index; ([#2014](https://github.com/ant-design/ant-design-mobile/issues/2014))
  - Fix: Picker `onOk` cannot be triggerd correctly; ([#2042](https://github.com/ant-design/ant-design-mobile/issues/2042))

- **Enhancement**

  - RN stepper numberic keyboard type by defaultï¼

### 2.0.1

`2017-10-28`

- **Bug Fix**

  - Fix `Modal` button event is triggered more than once in android. ([#1975](https://github.com/ant-design/ant-design-mobile/issues/1975)).
  - Fix: `Accordion` crashed under react-native@0.49. ([#1969](https://github.com/ant-design/ant-design-mobile/pull/1969))
  - Fix: `Toast` show in componentDidMount and compatibility with react@16. ([#1980](https://github.com/ant-design/ant-design-mobile/issues/1980))
  - Fix: `Modal.alert/prompt` buttons cannot close Modal in iOS.([#1976](https://github.com/ant-design/ant-design-mobile/issues/1976))
  - Fix: `Modal` RN button promise.
  - Fix: `Picker/DatePicker`,the `okText/dismissText/extra` cannot be setï¼ ([#1984](https://github.com/ant-design/ant-design-mobile/issues/1984))
  - Fix: `Picker` RN i18nï¼([#2001](https://github.com/ant-design/ant-design-mobile/issues/2001))
  - Fix: `SearchBar` input content is covered by clear iconï¼([#2010](https://github.com/ant-design/ant-design-mobile/issues/2010))
  - Fix: `SearchBar` input cannot be focused when clicked clear iconï¼
  - Fix: `TextareaItem` autoHeight crashed under RN@49; ([#1970](https://github.com/ant-design/ant-design-mobile/issues/1970))

### 2.0.0

`2017-10-20`

- **Feature**

  - [Web] `DatePicker` Add `use12Hours`, support 12-hour am/pm format ([#1578](https://github.com/ant-design/ant-design-mobile/issues/1578))
  - [Web] `Button` Support `disabled` style for diffrent `type`.
  - [Web] `Grid` add `square` api, support both square mode and auto height mode.
  - [Web] `Grid` add `activeClassName`, `activeStyle` api, support custom touch feedback style.
  - [Web] `Modal.alert / Modal.prompt / Modal.opeartion` add optional `platform` api, support switch between android and ios design.
  - [Web] `ListView`(beta.3) add pull-up feature.
  - Add `DatePickerView` ([#1232](https://github.com/ant-design/ant-design-mobile/issues/1232))
  - Add `Calendar` ([#1610](https://github.com/ant-design/ant-design-mobile/issues/1610))
  - [Web] locale support for `Picker` `SearchBar`
  - [Web/RN] `NoticeBar` can use `action` prop to customize action text. ([#1959](https://github.com/ant-design/ant-design-mobile/issues/1959))

- **Break Change**

  - [Web] "Web page HD display" / "SVG Icon" optimization features, Changed from "built-in" to "external".
  - [Web] remove `across` mode of `Button`.
  - remove global `user-select: none`ã[#1793](https://github.com/ant-design/ant-design-mobile/issues/1793)
  - [Web/RN] all component's `ref` switch from `string` to `function` ([#1354](https://github.com/ant-design/ant-design-mobile/issues/1354))
  - [Web/RN] Rewrite `Tabs`ï¼**Redesigned all api**
  - [Web/RN] Remove `Popup`ï¼Add `popup` api for `Modal`, Modal `animationType` support web, to custom popup animation style [#1125](https://github.com/ant-design/ant-design-mobile/issues/1125)
  - [Web/RN] `InputItem` / `TextareaItem` / `SearchBar`
    - pass `style` to input(web) / TextInput(rn)
    - remove `focused` / `autoFocus` (use `focus()` instance method)
  - [Web/RN] `DatePicker` remove moment.js
    - `value` / `minDate` / `maxDate` / `format` / `onChange` change to pure`Date` Object
  - [Web/RN] `pagination` api `current` change to start with `1`.
  - [Web/RN] `Progress`
    - `wrapStyle` change to `style`, original `style` change to`barStyle`
    - `unfilled` change to `boolean` type
  - [Web/RN] remove `List` api `onLongPress`
  - [Web/RN] `Result` api `buttonClick` renamed to `onButtonClick`
  - [Web/RN] remove `Table`
  - [Web] remove `createTooltip`ï¼which can use [react-component/slider/createSliderWithTooltip](https://github.com/react-component/slider/blob/master/src/createSliderWithTooltip.jsx) replace
  - [Web] `Switch` api `style` change to applied with inner element
  - [Web] `Slider` remove default margin & padding style
  - [Web] `Carousel`'s `easing` prop type changed from string to Function
  - [Web] `Flex` remove redundancy `align` value `top / middle / bottom`
  - [Web] `ListView`(beta.3) Remove `stickyHeader` prop and [react-sticky](https://github.com/captivationsoftware/react-sticky) dependency, but you can also use react-sticky and `useBodyScroll` in listview by your self. (see demo)
    > Because this feature is not commonly used and does not contain UI, so it is not suitable for integration.
  - [Web] `RefreshControl`(beta.3) Change inner dom className
    - from `${prefixCls}-ptr` to `${prefixCls}-indicator`
    - from `${prefixCls}-ptr-icon` to `${prefixCls}-indicator-icon-wrapper`
    - from `${prefixCls}-ptr-loading` to `${prefixCls}-indicator-loading-wrapper`
  - [Web] `ListView`(beta.6) add `pullToRefresh` prop and remove `useZscroller` `scrollerOptions` `refreshControl` `pullUpEnabled` `pullUpRefreshing` `pullUpOnRefresh` `pullUpDistanceToRefresh` `pullUpRenderer` props.
  - [Web] `RefreshControl` (beta.6) has been removed, please use the new `PullToRefresh` component instead
  - [RN] `RefreshControl` (beta.6) has been removed, please use react-native RefreshControl directly
  - [RN] `ActionSheet.showShareActionSheetWithOptions` rewrite with react native `Share`
  - [RN] `Button` api `style` attribute `disabledRaw` / `disabledRawText` rename to `defaultDisabledRaw` / `defaultDisabledRawText`
  - [Web] `NavBar`(rc.1) modify the prop `iconName` to `icon`, you need to use `Icon` component or your custom icon
  - [Web] `ActionSheet`(rc.1) delete `iconName` prop, use `icon` instead
  - [RN] `ListView`(rc.3) has been removed, please use react-native ListView directly
  - [Web/RN] `ImagePicker`(rc.3) add `onFail` prop and remove `Toast.fail` infomation within component

- **Theme**

  - Delete `@fill-overlay-inverse`, `@color-shadow`, `@brand-hot`, `@font-size-display-sm`, `@font-size-display-md`, `@font-size-display-xl`, `@font-size-display-lg`,`@font-family-code`, `@font-family-base`ï¼
  - `@searchbar-font-size` rename to `@search-bar-font-size`ã

- **Enhancement**
  - no need of `webpack.resolve`
  - `rmc-picker` upgradeï¼dom structure simplify ([#1593](https://github.com/ant-design/ant-design-mobile/issues/1593)ï¼
  - remove global `user-select: none`ã[#1793](https://github.com/ant-design/ant-design-mobile/issues/1793)

## 1.7.2

`2017-12-14`

- Fix `Picker` do not compatibility with Android 4.4. ([dbe8ce](https://github.com/ant-design/ant-design-mobile/commit/dbe8ce99bf1d18e3e68a0bba4c8d6907cc3c6e0f))

## 1.7.1

`2017-10-20`

- Fix `InputItem`/`TextareaItem` clear button is not displayed. ([#1955](https://github.com/ant-design/ant-design-mobile/issues/1955))

## 1.7.0

`2017-10-13`

- **Feature**

  - `Menu` add mulit-choose feature.

- **Bug Fix**

  - Fix `Icon` spell error.
  - Fix `Popover` styles.
  - Fix `Steps` styles.

## 1.6.10/1.6.11

`2017-09-25`

- **Bug Fix**

  - Fix `InputItem` can't be focused when click clear icon.

## 1.6.9

`2017-09-25`

- **Bug Fix**

  - Fix `Modal.prompt` focus delay. ([#1857](https://github.com/ant-design/ant-design-mobile/issues/1857))
  - Fix `TextareaItem` with `autoHeight` and much texts causing page scrolling. ([#1858](https://github.com/ant-design/ant-design-mobile/issues/1858))
  - Fix `Popvoer` ts definition.

- **Improve && Enhancement**

  - Add `indicatorStyle` and `itemStyle` for `Picker/PickerView`. ([#1856](https://github.com/ant-design/ant-design-mobile/issues/1856))

## 1.6.8

`2017-09-18`

- **Bug Fix**

  - Fix `segmented-control` without active style. ([#1832](https://github.com/ant-design/ant-design-mobile/issues/1832))
  - Fix `InputItem` `TextareaItem` [onClick tsd](https://github.com/ant-design/ant-design-mobile/commit/5fd21d1539f19fe80fd415716d349d82c1a77408).
  - Fix `swipe-action` [button height overflow](https://github.com/ant-design/ant-design-mobile/commit/ab2297c64fcde0766b502b96349bc8824cbd8bff).

## 1.6.7

`2017-09-11`

- **Bug Fix**

  - Fix `Carousel` on `swipeSpeed` ts lost. ([#1824](https://github.com/ant-design/ant-design-mobile/issues/1824))
  - Fix `TabBar` crash on android when item size is one. ([#1827](https://github.com/ant-design/ant-design-mobile/issues/1827))
  - Fix RN `PickerView` vertical layout error ([#1795](https://github.com/ant-design/ant-design-mobile/issues/1795))

## 1.6.6

`2017-09-09`

- **Bug Fix**

  - Fix `Modal.operation` style of multiple options for android ([#1791](https://github.com/ant-design/ant-design-mobile/issues/1791))
  - Fix RN `Accordion` must depend on `Icon` component ([#1784](https://github.com/ant-design/ant-design-mobile/issues/1784))
  - Fix `Modal` with `href="#"` cousing react-router to jump to '/' ([#1780](https://github.com/ant-design/ant-design-mobile/issues/1780))
  - Fix RN `ActionSheet` with empty `title / message` casusing error ([#1767](https://github.com/ant-design/ant-design-mobile/issues/1767)
  - Fix RN `PickerãPickerView` vertical layout error ([#1767](https://github.com/ant-design/ant-design-mobile/issues/1767))

## 1.6.5

`2017-08-29`

- **Bug Fix**
  - Fix `SeachBar` cancel can not blur. ([#1721](https://github.com/ant-design/ant-design-mobile/issues/1721))
  - Fix `InputItem` unkown props warningã([#1754](https://github.com/ant-design/ant-design-mobile/issues/1754))
  - Fix `InputItem[type='money']` `focused` do not work when init. ([#1758](https://github.com/ant-design/ant-design-mobile/issues/1758))

## 1.6.4

`2017-08-29`

- **Bug Fix**

  - Fix `SeachBar` in specific Client when `onClear` event was triggered, the `SearchBar` can't be auto focused. ([#1721](https://github.com/ant-design/ant-design-mobile/issues/1721))
  - Fix `ListView` `scrollerOptions` undefined. ([#16](https://github.com/react-component/m-list-view/pull/16))
  - Fix `SwipeAction` [touchabled feedback conflict with swipe gesture](https://github.com/react-component/swipeout/commit/b9b373bf4d378c5c98730b5ce96953050c29dbe2)ã
  - Fix `Stepper` icon can not custom icon colorã([#1694](https://github.com/ant-design/ant-design-mobile/issues/1694))
  - Fix React Native `ImagePicker` throw error in react 16. ([#1707](https://github.com/ant-design/ant-design-mobile/issues/1707))
  - Fix `SwipeAction` z-index conflict with `InputItem`. ([#1720](https://github.com/ant-design/ant-design-mobile/issues/1720))

- **Improve && Enhancement**
  - upgrade `rmc-picker` to v4ã([#1593](https://github.com/ant-design/ant-design-mobile/issues/1593))
  - `SearchBar` [support MaxLength](https://github.com/ant-design/ant-design-mobile/commit/cb674f77d8e6495a081c06c65b71f23a04c32954)ã
  - `InputItem[type=money]` refactor to use global standalone instanceã([#1724](https://github.com/ant-design/ant-design-mobile/issues/1724))
  - `SearchBar` refactor to clear not blurã([#1731](https://github.com/ant-design/ant-design-mobile/pull/1731))
  - `Picker` support visiable in controlled modeã([900f691](https://github.com/ant-design/ant-design-mobile/commit/900f6910bdd2b42fa97bac142671bf5089abc0a3))

## 1.6.3

`2017-08-15`

- **Bug Fix**

  - Fix `TextareaItem` calculate new line charater lengthã ([#1265](https://github.com/ant-design/ant-design-mobile/issues/1265))

- **Improve && Enhancement**
  - `SwipeAction` ignore swipe vertical; ï¼Remove event binding when disabled; auto adjust swipe button widthã ([#1595](https://github.com/ant-design/ant-design-mobile/issues/1595))

## 1.6.2

`2017-08-13`

- **Improve && Enhancement**
  - `Tabs` support `data-*` attribute ([#1648](https://github.com/ant-design/ant-design-mobile/issues/1648))

## 1.6.1

`2017-08-12`

- **Bug Fix**
  - ä¿®å¤ `TextareaItem` è¾å¥è¡¨æç¬¦å·è®¡æ°ä¸æ­£ç¡®ç bug ([#1670](https://github.com/ant-design/ant-design-mobile/pull/1670))
  - ä¿®å¤ `SwipeAction` åªè®¾ç½® left æè right æ¶ï¼ç¸åä¸è¾¹è¿å¯ä»¥æ»å¨çé®é¢ï¼([#1655](https://github.com/ant-design/ant-design-mobile/issues/1655))
  - ä¿®å¤ `RN InputItem` èªå®ä¹æ ·å¼ color ä¸çæï¼è¢«å¼ºå¶è¦çï¼çé®é¢; ([#1471](https://github.com/ant-design/ant-design-mobile/issues/1471))
  - ä¿®å¤ `Toast[mask=false]` æ¶è·éé¡µé¢æ»å¨é®é¢ï¼([#1642](https://github.com/ant-design/ant-design-mobile/issues/1642))
  - ä¿®å¤ `ListView` å­å¨ body æ»å¨æ¡çæ¶åï¼æ æ³å®ç°æ»å¨å°é¡¶é¨å¨ä¸æå·æ°; ([#1588](https://github.com/ant-design/ant-design-mobile/issues/1588))
- **Improve && Enhancement**
  - ç½ç«å¯¼èªæ é«äº® ([#1534](https://github.com/ant-design/ant-design-mobile/issues/1534))

## 1.6.0

`2017-07-30`

- **Feature**

  - `Tabs` æ°å¢æ¯æ`Badge` ([#1604](https://github.com/ant-design/ant-design-mobile/pull/1604))
  - `Modal` æ¯æ placeholder ([#1603](https://github.com/ant-design/ant-design-mobile/pull/1603))

- **Bug Fix**

  - ä¿®å¤`SearchBar` `onClear`æ¶å­å¨çæ ·å¼æ¸²æé®é¢ ([#1621](https://github.com/ant-design/ant-design-mobile/pull/1621))
  - ä¿®å¤`SearchBar` æ¯æ data-\* å±æ§. ([bbb358](https://github.com/ant-design/ant-design-mobile/commit/bbb35826872841f50ae31d795f67a97fd3231ca4))

- **Improve && Enhancement**
  - ç½ç«ä¼å ([#1622](https://github.com/ant-design/ant-design-mobile/pull/1622))

## 1.5.0

`2017-07-22`

- **Feature**

  - `ListItem` æ¯æ `onLongPress`. ([#1533](https://github.com/ant-design/ant-design-mobile/pull/1533))

- **Bug Fix**

  - ä¿®å¤ `Tabs` æ»å¨æµ®å±è¦ç `Popup` èççé®é¢ã([#1512](https://github.com/ant-design/ant-design-mobile/pull/1512))
  - ä¿®å¤ `Switch` å¨ android ä¸ 0.5px å¯¼è´æ¾ç¤ºä¸æ­£å¸¸çé®é¢ã([86dabf](https://github.com/ant-design/ant-design-mobile/commit/86dabfea9841695fbca5319b422f11a0ddb17184))
  - ä¿®å¤ React Native `Modal.prompt` é®çé®æ¡çé®é¢ã([#1489](https://github.com/ant-design/ant-design-mobile/issues/1489))

- **Improve && Enhancement**
  - å¢å å¯¹ `Icon` svg-sprite-loader å¯è½æªæ­£ç¡®éç½®çæ£æµå warningã([#1574](https://github.com/ant-design/ant-design-mobile/issues/1574))

## 1.4.2

`2017-07-12`

- **Bug Fix**
  - ä¿®å¤ Toast æªä»¥èªèº«ä¸­å¿ç¹çºµåå±ä¸­ã ([#1389](https://github.com/ant-design/ant-design-mobile/issues/1389))
  - ä¿®å¤ç®åæªå®ç°ç NavBarãMenuãRangeãTable å¼å¥ react-native çæ¬ç»ä»¶æ¥éçé®é¢ã([#1526](https://github.com/ant-design/ant-design-mobile/issues/1526))

* **Improve && Enhancement**
  - åçº§ Slider ä¾èµç rc-slider çæ¬ã
  - é¨åç»ä»¶ææ¡£å½éåå®åï¼å¢å é¨åç»ä»¶æµè¯ç¨ä¾ã

## 1.4.1

`2017-07-01`

- **Bug Fix**

  - ä¿®å¤ `Grid` æ ·å¼é®é¢ãï¼[635a9d3](https://github.com/ant-design/ant-design-mobile/commit/635a9d3d4b93e5a7304d5620ad6550827c303b1d) [#1455](https://github.com/ant-design/ant-design-mobile/issues/1455)ï¼
  - ä¿®å¤ create-react-app ææ¡£éè¯¯ãï¼[#1501](https://github.com/ant-design/ant-design-mobile/issues/1501)ï¼
  - ä¿®å¤ `Modal` android å¹³å°ä¸æ ·å¼éè¯¯ãï¼[#1499](https://github.com/ant-design/ant-design-mobile/issues/1499)ï¼
  - ä¿®å¤ `SearchBar` iOS é®çç±»åä¸æ¯æç´¢é®é¢ã ([#1510](https://github.com/ant-design/ant-design-mobile/issues/1510))
  - ææ¶åæ» typescript interface åæ³ï¼è§£å³ dist æä»¶éè¯¯é®é¢ã ([#1517](https://github.com/ant-design/ant-design-mobile/pull/1517))

- **Improve && Enhancement**
  - `SegmentedControl` å¼å®¹ preact ([#1374](https://github.com/ant-design/ant-design-mobile/pull/1374))
  - `ActionSheet`/`SearchBar`/`ImagePicker`/`Picker` ç»èæ ·å¼ä¼å
  - `Modal.prompt` æ©å¤§ç¹å»åºå ([#1489](https://github.com/ant-design/ant-design-mobile/issues/1489))
  - `InputItem` ç money ç±»åæ·»å  demo æ¼ç¤ºåªè½è¾å¥èªç¶æ°([#1493](https://github.com/ant-design/ant-design-mobile/pull/1493))
  - æ´æ°ä¸»è¦çä»ç»ææ¡£ ([#1503](https://github.com/ant-design/ant-design-mobile/pull/1503))
  - å»é¤ object-assign ä¾èµï¼æ¹ä¸ºä½¿ç¨ es6 å±å¼æä½ç¬¦ ([67e0ee6](https://github.com/ant-design/ant-design-mobile/commit/67e0ee6a985d1e143f3dbbf63988d01a05d67b59))
  - ç½ç«ä¿¡æ¯ç»æä¼åï¼å¹¶å¢å æ·è´ä»£ç æé® ([#1481](https://github.com/ant-design/ant-design-mobile/issues/1481))

## 1.4.0

`2017-06-24`

- **Feature**

  - `Button` æ°å¢ `activeClassName` ä»¥èªå®ä¹ç¹å»æ¶ç±»åã([3331f00](https://github.com/ant-design/ant-design-mobile/commit/3331f00b1a89d7fb76dcffa554f1cf9b165819d9))
  - `Card.Header` ç thumb æ¯æ React.Elementã([#1484](https://github.com/ant-design/ant-design-mobile/issues/1484))
  - `InputItem` æ¯æéè¿ locale æ¥èªå®ä¹åç½®ææ¡ã([#1475](https://github.com/ant-design/ant-design-mobile/issues/1475))

- **Bug Fix**
  - ä¿®å¤ ListView sticky header è¢«é®æ¡çé®é¢ã([#1456](https://github.com/ant-design/ant-design-mobile/issues/1456))
  - `InputItem` ä¿®å¤å½`type=money` èæé®çæ æ³éèçé®é¢ã([#1468](https://github.com/ant-design/ant-design-mobile/issues/1468))

* **Improve && Enhancement**
  - `InputItem` èæ¯å¾çæ¿æ¢ä¸º svgã([#1470](https://github.com/ant-design/ant-design-mobile/issues/1470))
  - `Button` é«åº¦å¢å¤§ä¸º `94px`ã
  - `ListItem` é«åº¦åå°ä¸º `88px`ã
  - `Result` é´è·ï¼å­ä½ï¼é¢è²è°æ´ã

## 1.3.1

`2017-06-19`

- **Feature**

  - `PickerView` æ¯æ`indicatorStyle`ã([3184179d2](https://github.com/ant-design/ant-design-mobile/commit/3184179d2ba4b5bccde83d8590d3e538fab0ad22))

- **Bug Fix**
  - `InputItem` ä¿®å¤å½`type=money`æ¶`disabled`å`editable`ä¸çæçé®é¢ã([#1437](https://github.com/ant-design/ant-design-mobile/issues/1437))
  - `Menu` ä¿®å¤å½æ°æ®æºäºçº§æ°æ®ä¸å¯ä¸æ¶å¯¼è´çé®é¢ã([#1427](https://github.com/ant-design/ant-design-mobile/issues/1427))
  - `Slider` [#1439](https://github.com/ant-design/ant-design-mobile/pull/1439)ï¼æ´æ° TS definition
  - `ListView` ä¿®å¤ scrollTo çé®é¢ ([97ed6795](https://github.com/ant-design/ant-design-mobile/commit/97ed67955243643fcc1de3debd0d507b87d6380b))
  - React-Native `Flex` `Flex.Item`æ¯æ`children`æ°ç»ã([#1442](https://github.com/ant-design/ant-design-mobile/pull/1442))

## 1.3.0

`2017-06-09`

- **Feature**

  - `InputItem` æ¯æèæçéé¢è¾å¥é®ç (`type="money"`)ã([#1419](https://github.com/ant-design/ant-design-mobile/pull/1419))
  - `Slider` & `Range` æ°å¢ `handleStyle`, `trackStyle`, `railStyle` ä»¥æ¯æèªå®ä¹æ ·å¼ã([a83d0fe](https://github.com/ant-design/ant-design-mobile/commit/a83d0fefffbdd05ce9f89a78508a544cd95e4fb5))
  - React-Native `Progress` æ°å¢ `wrapStyle` å·²èªå®ä¹å®¹å¨æ ·å¼ã([3ad012a](https://github.com/ant-design/ant-design-mobile/blob/3ad012ae265182cebc677efb309c92238eb8377a/components/progress/index.web.tsx))
  - React-Native `Carousel` æ°å¢ `dotStyle`, `dotActiveStyle` ä»¥èªå®ä¹æç¤ºå¨æ ·å¼ã([#1425](https://github.com/ant-design/ant-design-mobile/pull/1425))
  - React-Native `Button` æ°å¢ `delayPressin`, `delayPressout` ä»¥èªå®ä¹ç¹å»å»¶æ¶ã([b6ec8e2](https://github.com/ant-design/ant-design-mobile/commit/b6ec8e217bc3ed56702c819885948839c14bf8e3))

- **Bug Fix**
  - ä¿®å¤ React-Native `Accordion` ä¸è½è®¾ç½® styleã([#1407](https://github.com/ant-design/ant-design-mobile/issues/1407))
  - ä¿®å¤ `Popup` èªå®ä¹èå±æ ·å¼çé®é¢ã([#1420](https://github.com/ant-design/ant-design-mobile/issues/1420))
  - ä¿®å¤ `Pagination` èªå®ä¹ç¿»é¡µææ¡ä¸å¾æ æ ·å¼çé®é¢ã([#1429](https://github.com/ant-design/ant-design-mobile/issues/1429))
  - ä¿®å¤ `Modal` å¨ android ä¸å³é­ä¹åæ ·å¼åæ¢çé®é¢ã([#1433](https://github.com/ant-design/ant-design-mobile/issues/1433))

## 1.2.0

`2017-06-03`

- **Notice**

  - antd-mobile `Icon` æä¾èµçå¼æº webpack loader `svg-sprite-loader` æè¿ä» `0.3` ç´æ¥åçº§å°äº `2.0`, å¶éç½®æ¹æ¡åçäº break changeï¼ä½ç±äºæ­¤ loader ççæ¬ç±ç¨æ·ä»£ç æ§å¶ï¼èåè½è¢« antd-mobile åç¨æ·ä»£ç æå±åä¾èµï¼ antd-mobile å¢éåªè½éæ©å¨ `2.0` å¯¹å¶è¿è¡åçº§ï¼è¯·åä½ç¨æ·å¨ `antd-mobile@1.x` æé´ææ¶ä¸è¦åçº§ `svg-sprite-loader`ï¼å¨é¡¹ç®éä»ç¶ä½¿ç¨ `svg-sprite-loader@0.3.x` å³å¯ã[#1283](https://github.com/ant-design/ant-design-mobile/issues/1283)
  - æ°å¢ warningï¼æéç¨æ· antd-mobile `2.0` å°ä¼åºå¼ `Table`ã[e1009015e](https://github.com/ant-design/ant-design-mobile/commit/e1009015e0c0740045995555831d1598a99c629f)

- **Feature**

  - åºå± Touch äºä»¶åºæ´æ°ï¼ææ `onPress` å `onLongPress` æ¯æ `stopPropagation`ã[e7400b699](https://github.com/ant-design/ant-design-mobile/commit/e7400b6994d3a9127bd1bd6fa418996ad8206f96)
  - éæ `carousel`, æ°å¢ [swipeSpeed](https://github.com/react-component/nuka-carousel#modify-from-upstream-nuka-carousel204) api ä»¥èªå®ä¹æå¨éåº¦ã
  - Theme æ°å¢ `@toast-fill` ç¨äºèªå®ä¹ toast èæ¯è²ã[acaeff017171](https://github.com/ant-design/ant-design-mobile/commit/acaeff017171fd06bf8700b849a7fff917c6d260)
  - æ°å¢ä¸ crate-react-app å create-react-native-app èææ¶éåä½¿ç¨çææ¡£ã[#1362](https://github.com/ant-design/ant-design-mobile/issues/1362)

- **Bug Fix**

  - ä¿®å¤ `ListView` ä¸­éææ¨ªæ»ç»ä»¶, å¦ `SwipeAction`, `Carousel`, ä¸ä¸ä¸æ»å¨å²çªçé®é¢ã[#1254](https://github.com/ant-design/ant-design-mobile/issues/1254)
  - ä¿®å¤ `Popover` èªå®ä¹æ ·å¼çé®é¢ã[#1364](https://github.com/ant-design/ant-design-mobile/issues/1364)
  - ä¿®å¤ Theme `@radius-circle` åéä¸çæ [#1301](https://github.com/ant-design/ant-design-mobile/issues/1301)
  - ä¿®å¤ Theme æ æ³èªå®ä¹ `SearchBar` placeholder font-size [#1324](https://github.com/ant-design/ant-design-mobile/pull/1324)
  - ä¿®å¤ React-Native `picker` æ æ³èªå®ä¹å­ä½æ ·å¼ã [#1323](https://github.com/ant-design/ant-design-mobile/issues/1323)
  - ä¿®å¤ SearchBar å¨ android çç¹å»åæ æ³ focus é®é¢ã[#1342](https://github.com/ant-design/ant-design-mobile/issues/1341)
  - ä¿®å¤ React-Native `tabs` swipeable å±æ§æ æçé®é¢ã[#1346](https://github.com/ant-design/ant-design-mobile/issues/1346)
  - ä¿®å¤ `InputItem` ç­è¾å¥ç±»ç»ä»¶æå­è¢«æªæ­çé®é¢ã[#1358](https://github.com/ant-design/ant-design-mobile/issues/1358)
  - ä¿®å¤ SwipeAction ç±»ååæ ·å¼ã[e42430f9a68f2](https://github.com/ant-design/ant-design-mobile/commit/e42430f9a68f25a4b22cd2e65c05009fbb678fdd)
  - ä¿®å¤éè¯¯ç API ææ¡£ï¼ `ActivityIndicator` color API åªæ React-Native ç»ä»¶æ¯æã[#1370](https://github.com/ant-design/ant-design-mobile/issues/1370)
  - ä¿®å¤ `Tabs` å½ liner-gradient ä¸æ¯ææ¶æ¾ç¤ºä¸æ­£å¸¸çé®é¢ã[824da3466](https://github.com/ant-design/ant-design-mobile/commit/824da34667f9e974747d9f344b0bef3dc0bdae36)
  - ä¿®å¤ `Grid` å¨ isCarousel æ¨¡å¼ä¸ä¸ä¼èªå¨å¡«åç©ºç½æ ¼å­çé®é¢ã[#1398](https://github.com/ant-design/ant-design-mobile/pull/1398)
  - ä¿®å¤ `Toast` æ²¡æä»¥èªèº«ä¸­å¿ç¹åç´å±ä¸­çé®é¢ã[#1389](https://github.com/ant-design/ant-design-mobile/issues/1389)

- **Improve && Enhancement**
  - `Tabs` å¤´é¨æ»å¨æ§è½ï¼ä½éªä¼åã
  - å¢å¤§ `SearchBar` ç¹å»åºåã[#1344](https://github.com/ant-design/ant-design-mobile/pull/1344)
  - éæ `Switch`, `Modal` ä»¥æ¯ææå¡ç«¯æ¸²æ [#1307](https://github.com/ant-design/ant-design-mobile/pull/1307/)
  - ä¼å Flex, Button, List ç typescript å®ä¹ã[#1339](https://github.com/ant-design/ant-design-mobile/issues/1339)
  - `Button`, `Tag` ç±å¤è¾¹æ¡æ¹ä¸ºåè¾¹æ¡ï¼æ´ç¬¦åè®¾è®¡è§èã[4c8051032](https://github.com/ant-design/ant-design-mobile/commit/4c8051032005fe042df38d4b3bddf5f8405fb8fd)
  - æ°å¢ `pkg.module`, æå ES2015 modulesï¼æ´å¥½å°æ¯æ rollup å webpack2ã[#12](https://github.com/react-component/react-component.github.io/issues/12)
  - éæ React-Native `Toast`, `ActivityIndicator` æ ·å¼ï¼æ´æ¹å°æ¯æéè¿ Theme èªå®ä¹ã[b7094e2a2dc](https://github.com/ant-design/ant-design-mobile/commit/b7094e2a2dc0aa9433f2f2f7388a3e8313681888)
  - `Tabs` æ°å¢å¯¹ `TabPane.props.key` çæ ¡éªï¼å¿é¡»å­å¨ä¸å¯ä¸ã[#1365](https://github.com/ant-design/ant-design-mobile/issues/1365)
  - éæå¹¶ä» React-Native `InputItem` æååº `TextInput`ï¼ä¾¿äºèªå®ä¹æ ·å¼ã[#1174](https://github.com/ant-design/ant-design-mobile/issues/1174)
  - éæ `Grid`, é¿åå½æ ¼å­æ°éååï¼å¨ carousel åé carousel æ¨¡å¼åæ¢åé«åº¦ååçæåµã[63c28b31f](https://github.com/ant-design/ant-design-mobile/commit/63c28b31fba19cb7f68a36a71259a5b57ffe0bc8)
  - æ°å¢ demo å³äºå¦ä½æ©å± `InputItem` label ä¸ºå¯ç¹å»åºåã[db8582781](https://github.com/ant-design/ant-design-mobile/commit/db8582781f0aa7663fb02db315de49cf9d00822b)

## 1.1.3

`2017-05-14`

- **Bug Fix**

  - ä¿®å¤ `ListItem` unknown props warningãï¼[#1278](https://github.com/ant-design/ant-design-mobile/issues/1278)ï¼
  - ä¿®å¤ React Native `Pagination` disable æ¶ç active æ ·å¼é®é¢ãï¼[1b01652797](https://github.com/ant-design/ant-design-mobile/commit/1b01652797daebd1af0547f19b005199fa6413e5)ï¼
  - ä¿®å¤ React Native `List` renderFooter éè¯¯ãï¼[#1294](https://github.com/ant-design/ant-design-mobile/pull/1294/files)ï¼
  - ä¿®å¤ `tabs` createClass warning

- **Improve && Enhancement**
  - `Switch` æ¯æ onClick ([#1290](https://github.com/ant-design/ant-design-mobile/issues/1290))

## 1.1.2

`2017-05-07`

- **Bug Fix**

  - ä¿®å¤ åç¬ä½¿ç¨ `Stepper` ç¼ºå°ä¾èµç Icon æ ·å¼é®é¢ã([d86c3dda](https://github.com/ant-design/ant-design-mobile/commit/d86c3dda267864721273f258dad3193c69d8e838)
  - ä¿®å¤ `Modal` å³é­æé®æ¾ç¤ºä¸é½çé®é¢ã([bf64803d](https://github.com/ant-design/ant-design-mobile/commit/bf64803d01082f0dd924c41ca778dfadb177bc92))
  - ä¿®å¤ `Switch` android æ ·å¼ãï¼[56bf4a93](https://github.com/ant-design/ant-design-mobile/commit/56bf4a93f55f021206aa99551039e68c9518c85c)ï¼
  - ä¿®å¤ `Slider` active æ ·å¼ãï¼[5a012ead](https://github.com/ant-design/ant-design-mobile/commit/5a012ead269e212dda6fb751a29a1e43f28e9848)ï¼
  - ä¿®å¤ `Stepper` éä¸­æ ·å¼æªèªå¨æ¶å¤±çé®é¢ã([006a5e2](https://github.com/ant-design/ant-design-mobile/commit/006a5e2184f3402fa9351186d65f8ab24a7c4b23))
  - ä¿®å¤ RN `InputItem` èªå®ä¹å­ä½å¤§å°ãï¼[#1174](https://github.com/ant-design/ant-design-mobile/issues/1174)ï¼([@kimjuny](https://github.com/kimjuny))
  - ä¿®å¤ RN `Popup` èªå®ä¹èçèæ¯æ ·å¼ãï¼[#1234](https://github.com/ant-design/ant-design-mobile/issues/1234)ï¼
  - ä¿®å¤ RN `Modal` ç¹å»ç³»ç»è¿åæ æ³èªå¨å³é­çé®é¢ã ([#1218](https://github.com/ant-design/ant-design-mobile/issues/1218))
  - ä¿®å¤ RN `Modal.prompt`, `InputItem` æ ·å¼ã([#1199](https://github.com/ant-design/ant-design-mobile/issues/1199))
  - ä¿®å¤ Normalize.css ç¼ºå°å¯¹ body margin éç½®çé®é¢ãï¼[#1264](https://github.com/ant-design/ant-design-mobile/issues/1264)ï¼
  - ä¿®å¤ RN ææç»ä»¶ç»ä¸æ¥å `style`, `styles` åæ°çé®é¢ãï¼[#1262](https://github.com/ant-design/ant-design-mobile/pull/1262)ï¼

- **Improve && Enhancement**
  - ææç»ä»¶æ¯ææ éç¢è®¿é®ãï¼[#1179](https://github.com/ant-design/ant-design-mobile/pull/1179)ï¼
  - å¢å¤§ `SearchBar` åæ¶æé®ç¹å»åºåã([#1250](https://github.com/ant-design/ant-design-mobile/issues/1250))
  - éæ RN `Carousel` ä»¥æ¯æèªå®ä¹ Paginationãï¼[#1146](https://github.com/ant-design/ant-design-mobile/issues/1146)ï¼
  - éæ `ListItem` ä»¥æ¯ææå¡ç«¯æ¸²æãï¼[#1219](https://github.com/ant-design/ant-design-mobile/pull/1219)ï¼

## 1.1.1

`2017-04-28`

- **Feature**

  - `InputItem`æ·»å å¤èµ·èªå®ä¹æ°å­é®çç¹æ§ï¼ä»æ¯ä»å®ç­å®¢æ·ç«¯ï¼ã([#1231](https://github.com/ant-design/ant-design-mobile/pull/1231))

- **Bug Fix**

  - ä¿®å¤ `Grid`ç`renderItem`æ¹æ³ã([é¾æ¥](https://github.com/ant-design/ant-design-mobile/commit/1316154cce6324c04a2cd7f36c8d229573dcde6b))
  - ä¿®å¤`SearchBar`clear icon å¯è½ä¸åºç°çé®é¢ã([#1204](https://github.com/ant-design/ant-design-mobile/issues/1204))
  - ä¿®å¤`InputItem`ç`placeholder`å£°æï¼æ¹ä¸ºå¯éã([#1216](https://github.com/ant-design/ant-design-mobile/pull/1216))
  - ä¿®å¤`TabBar`å£°ææä»¶ï¼`TabBarItemProps`é¨åçæ°å¢`dot`ã([#1209](https://github.com/ant-design/ant-design-mobile/pull/1209))
  - ä¿®å¤ç½ç«çè¯­è¨åæ¢é»è¾ã([é¾æ¥](https://github.com/ant-design/ant-design-mobile/commit/ec839dc4fdc7bfd54a9bd389cd3699bcbf8ac1ee))
  - `RefreshControl`æ¯æ SSR æ¸²æã([#1201](https://github.com/ant-design/ant-design-mobile/pull/1201))

- **Improve && Enhancement**
  - ä¼å`Icon`ç»ä»¶åç½®ç svg æä»¶ï¼åæå°åå¤çã([#1220](https://github.com/ant-design/ant-design-mobile/pull/1220))
  - å®æ`NoticeBar`ã`Grid`ã`Radio`ç»ä»¶è±æææ¡£çç¿»è¯å·¥ä½ã([#1230](https://github.com/ant-design/ant-design-mobile/pull/1230))ã([#1228](https://github.com/ant-design/ant-design-mobile/pull/1228))ã([#1227](https://github.com/ant-design/ant-design-mobile/pull/1227))
  - `InputItem`ä¸ºæ¯ä»å®å°ç¨åºæååºåç¬çåé¨ç»ä»¶`Input`ã([#1225](https://github.com/ant-design/ant-design-mobile/pull/1225))
  - `Card`ç»ä»¶æ´åå£°ææä»¶ã([#1222](https://github.com/ant-design/ant-design-mobile/pull/1222))

## 1.1.0

`2017-04-21`

- **Bug Fix**

  - ä¿®å¤ `Steps` æº¢åºãï¼[#5623](https://github.com/ant-design/ant-design/issues/5623]))
  - æç´¢æ¡æ¯æå¨ä¸»é¢åéèªå®ä¹é«åº¦ï¼èæ¯è²ç­ãï¼[PR 1113](https://github.com/ant-design/ant-design-mobile/pull/1113)ï¼[@yezongyang](https://github.com/yezongyang)
  - ä¿®å¤ React-Native `Steps` ä¸æ¯æèªå®ä¹ Icon ([#1088](https://github.com/ant-design/ant-design-mobile/issues/1088))
  - ä¿®å¤ `Progress` ä¸æ¯æèªå®ä¹ `className`ãï¼[PR 1126](https://github.com/ant-design/ant-design-mobile/pull/1126)ï¼
  - ä¿®å¤ React-Native `InputItem` ä¸æ¯æèªå®ä¹åå®¹ã([#1113](https://github.com/ant-design/ant-design-mobile/issues/1133))
  - ä¿®å¤ `InputItem` æ°å­é®çå¨ Android çå¼å®¹é®é¢ã([1073](https://github.com/ant-design/ant-design-mobile/issues/#1073))ã
  - ä¿®å¤ `InputItem` autoFocus å¨ safari æ æ³èç¦ç bugã([PR 1134](https://github.com/ant-design/ant-design-mobile/pull/1134))
  - ä¿®å¤å°å°ºå¯¸ `Button` ç loading icon å°ºå¯¸ã([587963](https://github.com/ant-design/ant-design-mobile/commit/587936abc43015ed2fa9be1b3493b3a8c4f98334))
  - ä¿®å¤é¨å React15.5 å³äº PropType å CreateClass ç warningã([#1118](https://github.com/ant-design/ant-design-mobile/issues/1118))
  - ä¿®å¤é¨ååç½® svg èæ¯çå°ºå¯¸ã([#1140](https://github.com/ant-design/ant-design-mobile/issues/1140))

- **Improve && Enhancement**
  - éæ `Grid`, `ImagePicker`, `Modal` ä»¥æ¯ææå¡ç«¯æ¸²æã
  - `Flex`, `FlexItem` æ¯æä¼ é `data-` ç­ä»»æèªå®ä¹å±æ§ã([#1150](https://github.com/ant-design/ant-design-mobile/issues/1150))
  - `Grid` å¨ carousel æ¨¡å¼ä¸æ¯æ `Carousel` çç¸åº APIãï¼[#1164](https://github.com/ant-design/ant-design-mobile/issues/1164)ï¼

## 1.0.8

`2017-04-07`

- **Feature**

  - RN modal å¢å  Modal.prompt ï¼[#1089](https://github.com/ant-design/ant-design-mobile/pull/1089)ï¼

- **Bug Fix**

  - ä¿®å¤ InputItemãTextareaItemãSearch autofocus ç bug ï¼[#1103](https://github.com/ant-design/ant-design-mobile/pull/1103)ï¼
  - ä¿®å¤ SearchBar ç¹å» `x` åæ¶æ¶ï¼placeholder æ¾ç¤ºä¸æ­£ç¡®ç bug ï¼[#1047](https://github.com/ant-design/ant-design-mobile/pull/1047)ï¼
  - ä¿®å¤ TextareaItem è¾å¥ emoji è¡¨æï¼å­ç¬¦ç»è®¡éè¯¯é®é¢ ï¼[#1085](https://github.com/ant-design/ant-design-mobile/pull/1085)ï¼
  - ä¿®å¤ SearchBar æäº¤åä¸èªå¨éèé®ççé®é¢ï¼
  - ä¿®å¤ Tabs onTabClick æ æé®é¢ ï¼[#1099](https://github.com/ant-design/ant-design-mobile/pull/1099)ï¼
  - ä¿®å¤ RN Steps ç©ºæ ¼å¼èµ·çé®é¢ ï¼[#1008](https://github.com/ant-design/ant-design-mobile/pull/1008)ï¼

- **Improve && Enhancement**
  - æ´æ° rc-slider çæ¬ï¼å¢å  `minimumTrackStyle`ã`maximumTrackStyle`ã`handleStyle` å±æ§ï¼

## 1.0.7

`2017-03-24`

- **Feature**

  - Slider æ¯æèªå®ä¹é¢è²ãï¼[#1024](https://github.com/ant-design/ant-design-mobile/pull/1024)ï¼
  - ListItem å¨ Android ä¸ç¹å»æ°å¢æ°´æ³¢çº¹å¨æãï¼[é¾æ¥](https://github.com/ant-design/ant-design-mobile/commit/d8fd66992fdfe53745fb43d9e27bffd025b8fdb0)ï¼

- **Bug Fix**

  - DatePicker æ¥æ¶ `minuteStep`ã ([#1020](https://github.com/ant-design/ant-design-mobile/issues/1020))
  - ä¿®å¤ Stepper ç icon å¤éè¾¹æ¡é®é¢ãï¼[#1038](https://github.com/ant-design/ant-design-mobile/issues/1038)ï¼
  - ä¿®å¤ SearchBar placeholder å¨èç¦æ¶æ¾ç¤ºä¸å¨çé®é¢ãï¼[#1047](https://github.com/ant-design/ant-design-mobile/issues/1047)ï¼

- **Improve && Enhancement**
  - Modal, Switch, ListItem æ°å¢ `platform` åæ°ï¼å¯èªå®ä¹ç»ä»¶æ ·å¼æ¯å¦åºå Android/iOS å¹³å°ã([#1030](https://github.com/ant-design/ant-design-mobile/issues/1030))
  - SearchBar èªå®ä¹ä¸»é¢æ¶çå¸å±ä¼åã ([#1014](https://github.com/ant-design/ant-design-mobile/issues/1014))
  - InputItem, TextareaItem, SearchBar ç»ä»¶æ ·å¼ä¼åï¼å¢å¤§å¯ç¹å»åºåã ([#1017](https://github.com/ant-design/ant-design-mobile/issues/1017))
  - React-Native Steps æ¯æ React.Node ç±»åç `title`, `description`ã [#1008](https://github.com/ant-design/ant-design-mobile/issues/1008)
  - DatePicker ç¡®ä¿é»è®¤æ¥æå¨ `minDate`, `maxDate` èå´å ï¼[#1033](https://github.com/ant-design/ant-design-mobile/issues/1033)ï¼

## 1.0.6

`2017-03-17`

- **Feature**

  - Modal æ·»å  close apiï¼æ¹ä¾¿æå·¥éæ¯ï¼#995

- **Bug Fix**

  - ä¿®å¤ ImagePicker clear icon æè½¬é®é¢ï¼#944

- **Improve && Enhancement**
  - ä¼å Modal button é¿æçé»è®¤è¡ä¸ºï¼
  - StepperãToastãModal ä¾èµç rc-util åçº§ï¼å»é¤æ§å¶å°ä¸­ warningï¼#959
  - é¨åææ¡£ä¼åï¼#997 #993 #984 #1009ï¼é¨å demo ä¼åï¼

## 1.0.5

`2017-03-10`

- **Feature**

  - è¡¥å¨ `accordion` React-Native çæ¬ ([#931](https://github.com/ant-design/ant-design-mobile/pull/931))
  - `stepper` å¾æ æ¯æç¨æ·èªå®ä¹ ([é¾æ¥](https://github.com/ant-design/ant-design-mobile/commit/78ab295f69cd1441b600aa6c2d921c7d658096ca))
  - è¡¥å¨ React-Native `Button` ç loading æ ·å¼ ï¼[#946](https://github.com/ant-design/ant-design-mobile/issues/946)ï¼
  - React-Native `InputItem` æ¯æè¾å¥å°æ° ï¼[950](https://github.com/ant-design/ant-design-mobile/issues/950)ï¼
  - `Icon` æ¯æç´æ¥æ·»å äºä»¶ ([#955](https://github.com/ant-design/ant-design-mobile/issues/955))
  - React-Native `InputItem`, `TextItem` æ¯æèªå®ä¹ style ([#949](https://github.com/ant-design/ant-design-mobile/issues/949))

- **Bug Fix**

  - React Native `SearchBar` èªå¨æ¾ç¤ºåæ¶æé® ([#957](https://github.com/ant-design/ant-design-mobile/issues/957))
  - ä¿®å¤ `Tabs` å¨ä½çæ¬ Android æµè§å¨å¼å®¹æ§é®é¢ ([#940](https://github.com/ant-design/ant-design-mobile/issues/940))
  - React Native ä¿®å¤ `Card` extra è¦çç bug ([#969](https://github.com/ant-design/ant-design-mobile/issues/969))
  - ä¿®å¤ `ImagePicker` å¾çæè½¬æ¹åé®é¢ ([#944](https://github.com/ant-design/ant-design-mobile/issues/944))
  - ä¿®å¤ `Step` æ°´å¹³æº¢åºçé®é¢ ([#952](https://github.com/ant-design/ant-design-mobile/issues/952))

- **Improve && Enhancement**
  - æ°å¢ Web && React Native ç»ä»¶ç snapshot æµè¯ï¼è¦çç 59% ([#921](https://github.com/ant-design/ant-design-mobile/pull/921))
  - ææ¡£ç¿»è¯è¿åº¦ ([#329](https://github.com/ant-design/ant-design-mobile/issues/329))
  - [å®æ¹ Demo éå](https://github.com/ant-design/antd-mobile-samples) æ°å¢ roadhog ç¤ºä¾

## 1.0.4

`2017-03-07`

- **Bug Fix**
  - ä¿®å¤ `Button`, `ListItem` å¨ Android ä¸ç¹å»ç©¿éçé®é¢ãï¼[#937](https://github.com/ant-design/ant-design-mobile/issues/937)ï¼

## 1.0.3

`2017-03-04`

- **Bug Fix**
  - ä¿®å¤ `Tabs` å¨è®¾ç½® pageSize æåµä¸å®½åº¦è®¡ç®çé®é¢ãï¼[#935](https://github.com/ant-design/ant-design-mobile/issues/935)ï¼

## 1.0.2

`2017-03-04`

- **Feature**

  - Tabs æ°å¢ `pageSize` APIï¼æ°å¢æ¯æ swipeableTabBar æ»å¨å¤´é¨ã ï¼[#882](https://github.com/ant-design/ant-design-mobile/pull/882)ï¼
  - Modal å¢å  Modal.operation ([#925](https://github.com/ant-design/ant-design-mobile/pull/925)) æè°¢ @lixiaoyang1992
  - æ°å¢ Russian Locale ([#901](https://github.com/ant-design/ant-design-mobile/pull/901)) æè°¢ @NeonXP

- **Bug Fix**
  - Stepper `onChange` éå¤è§¦å ï¼[#891](https://github.com/ant-design/ant-design-mobile/issues/891)ï¼
  - ä¿®å¤ CheckboxItem ä¸ BrowserSync ä¸å¼å®¹çé®é¢ ([#350](https://github.com/ant-design/ant-design-mobile/issues/350))
  - ä¿®å¤ Tabs `className` æ ¡éªç bug ([#904](https://github.com/ant-design/ant-design-mobile/issues/904))
  - RN stepper `readOnly` é»è®¤æ¹ä¸º `false` ([#890](https://github.com/ant-design/ant-design-mobile/issues/890))
  - ä¿®å¤ Grid å¨è¾èæ§ Android çæ¬ä¸å®½åº¦è®¡ç®çé®é¢
  - ä¿®å¤ RN android Tabbar å ToastãPopupãActionSheet æ··åä½¿ç¨æ¶ zIndex æ··ä¹±ç bugï¼ï¼[#910](https://github.com/ant-design/ant-design-mobile/issues/910)ï¼
  - ä¿®å¤ RN Carousel android éªçãcomponentWillUnmount ä¸æ§è¡ç bugï¼([#899](https://github.com/ant-design/ant-design-mobile/issues/899),[#906](https://github.com/ant-design/ant-design-mobile/issues/906))
  - ä¿®å¤ ActionSheet(web & RN) maskClosable ä¸æ¯æ callback index çé®é¢ï¼([#908](https://github.com/ant-design/ant-design-mobile/issues/908))
  - ä¿®å¤ RN Button åè°åæ°éè¯¯ï¼restProps è¦çé®é¢;

* **Improve & Enhancement**
  - Icon å¢å  try catchï¼é¿åæ§å¶å°æ¥é ([#895](https://github.com/ant-design/ant-design-mobile/issues/895))
  - å®ç½éææ¯æå½éåï¼èªå¨æ£æµæµè§å¨è¯­è¨å¹¶æ¯æä¸­/è±æåæ¢
  - ææ¡£ç¿»è¯è¿è¡ä¸­ï¼æ¬¢è¿åä¸è´¡ç®~ ([#329](https://github.com/ant-design/ant-design-mobile/issues/329))
  - å®æ¹ demo æ´æ° [antd-mobile-samples](https://github.com/ant-design/antd-mobile-samples)

## 1.0.1

`2017-02-24`

- **Feature**

  - roadhog æ¯æéç½® svg-sprite-loader [icon ææ¡£](https://mobile.ant.design/components/icon) ([#144](https://github.com/sorrycc/roadhog/pull/144))
  - React Native å¢å  `LocalProvider` å½éåæ¹æ¡ ([#886](https://github.com/ant-design/ant-design-mobile/pull/886))
  - React Native `Button` , `Progress`, `TextareaItem` æ¯æèªå®ä¹æ ·å¼ ([#560](https://github.com/ant-design/ant-design-mobile/issues/560))
  - æä¾ 0.9.x iconfont å¾æ å¯¹åºç svg icon ([#866](https://github.com/ant-design/ant-design-mobile/issues/866))

- **Improve & Enhancement**
  - ææ demo ä»£ç è¿ç§»å° ES6 class å Pure functionï¼å»é¤ React.createClass ([#824](https://github.com/ant-design/ant-design-mobile/issues/824))
  - NavBar è¿åé´éä» margin æ¹ä¸º paddingï¼å¢å¤§ç¹å»åºå ([#844](https://github.com/ant-design/ant-design-mobile/issues/844))
  - carouse å»é¤ mixin ([#859](https://github.com/ant-design/ant-design-mobile/pull/859))
  - Tabs æ°å¢ `className` ([#861](https://github.com/ant-design/ant-design-mobile/issues/861))
  - stepper æ¹ä¸ºä½¿ç¨ svg icon, åçº§ rc-input-number
  - ä¸»é¢åéåç±»è°æ´ ([ref](https://github.com/ant-design/ant-design-mobile/commit/daea9a38133e0670926af6c0bd9233057eb9c3aa))

* **Bug Fix**
  - ä¿®å¤ List extra ä¸ºç©ºçå¤æ­é»è¾ ([#831](https://github.com/ant-design/ant-design-mobile/issues/831))
  - ä¿®å¤ Toast ä¸å±ä¸­çé®é¢ ([#827](https://github.com/ant-design/ant-design-mobile/issues/827))
  - ä¿®å¤ InputItem PC ä¸æ æ³ clear ç bug ([#832](https://github.com/ant-design/ant-design-mobile/pull/832))
  - ä¿®å¤ React-Native SearchBar onChange éå¤è§¦åç bug ([#739](https://github.com/ant-design/ant-design-mobile/issues/739))
  - ä¿®å¤ TabBar icon å±ä¸­çé®é¢ ([#836](https://github.com/ant-design/ant-design-mobile/issues/836))
  - ä¿®å¤å¸¦è·é©¬ç¯ææç Grid ç»ä»¶åå§åæ¶è·é©¬ç¯åå§å®½åº¦ä¸º 0 çé®é¢ã([ref](https://github.com/ant-design/ant-design-mobile/commit/1a897c46999e2325acd3754e52dba9144d04695e))
  - ä¿®å¤ Button warning çæ ·å¼ ([#863](https://github.com/ant-design/ant-design-mobile/issues/863))

## 1.0.0

`2017-02-17`

- **Feature**

  - Icon ä» iconfont è½¬ä¸ºä½¿ç¨ svg å¾ç [#156](https://github.com/ant-design/ant-design-mobile/issues/156)ã
  - Icon å¢å  React Native çæ¬ï¼[æ¥å¥æå](https://github.com/ant-design/ant-design-mobile/blob/master/components/icon/index.en-US.md#å¦ä½ä½¿ç¨-rn)ã
  - Button æ°å¢ `across` APIï¼æ¯æéæ æé®ã
  - Progress ç»ä»¶æ°å¢ `appearTransition` APIï¼æ¯æåå§æ¾ç¤ºçå¨ç»ææã
  - Checkbox / Radio ç»ä»¶æ¯æ children [#499](https://github.com/ant-design/ant-design-mobile/issues/499)ã
  - NoticeBar æ¯æ `marqueeProps`ã
  - Steps æ¯ææ¨ªåå¾æ ã
  - TabBar web icon å±æ§æ°å¢ `React.Node` æ¯æï¼å¯ä»¥ä½¿ç¨ Icon æè backgroundï¼ã
  - Toast æ°å¢ `duration = 0` ææï¼ä¸ä¼èªå¨æ¶å¤±ï¼ã
  - åç»ä»¶ RN çæ¬å å¥ `styles` å±æ§ï¼æ¯æå®å¨èªå®ä¹ç»ä»¶ç»èæ ·å¼ [#560](https://github.com/ant-design/ant-design-mobile/issues/560)ã
  - æ°å¢ [LocaleProvider](https://mobile.ant.design/components/locale-provider)ï¼åç½®ä¸­è±è¯­è¨åï¼é»è®¤ä¸­æ)ï¼ä¸ææç»ä»¶å¯ä»¥ç¨ `props.locale` è¦çå¨å± `LocaleProvider` éç½®ã
  - `Tabs` è¶è¿ 5 ä¸ªèªå¨åé¡µï¼æ°å¢ `hammerOptions` API å¯éç½®æå¿åé, åè [API ææ¡£](https://mobile.ant.design/components/tabs)ã
  - `TabBar` æ¯æ `dot` dot ç±»åç Badgeã
  - Modal alert å prompt ç `onPress` AI æ¯æ promise, åè [demo](https://github.com/ant-design/ant-design-mobile/blob/master/components/modal/demo/alert.md)ã
  - RN Flex æ¯ææ´å¤ `touchableWithOutFeedback` å±æ§ã

- **Break Change**

  - NoticeBar type åä¸º icon ï¼æ¯æå®å¨çèªå®ä¹åå®¹ã
  - Popover `iconName` åä¸º `icon` ï¼åå²çº¿ç css è®¾ç½®ä»åºè¾¹çº¿ä¿®æ¹ä¸ºé¡¶è¾¹çº¿ã
  - ä¿®æ¹é¨å css åéåååéå¼ãå¦ï¼zindex ç­ã
  - RN List å»é¤ last å±æ§ã
  - `DatePicker` å `Pagination` ä¸åæ¥å `okText`, `dismissText` å±æ§ï¼`DatePicker`ç`locale`å±æ§ç»æååï¼åè§ [åçº§ææ¡£](https://github.com/ant-design/ant-design-mobile/blob/master/docs/react/upgrade-notes.en-US.md#å¶ä»å¸¸ç¨ç»ä»¶æ´æ°æ³¨æäºé¡¹)ã
  - å Web ç `Slider` æåæ `Slider`, `Range`, `createTooltip`, ä½¿ç¨æ¹å¼åè§ [Slider ææ¡£](https://mobile.ant.design/components/slider), [Range ææ¡£](https://mobile.ant.design/components/range)ã
  - Toast æ´æ¹ä¸º single instanceï¼æ°æ¾ç¤ºç toast ä¼è¦çèçï¼åæ¶å¢å  mask ç¹æ§ï¼ã
  - Modal å Switch å¢å  android å¹³å°ç¬ç« UIã

- **Bug Fix**

  - åè¾å¥ç±»ç»ä»¶åæ§ä¸éåæ§ç¶æé®é¢ä¿®å¤ã
  - ä¿®å¤é¨åç»ä»¶(å¤ä¸ºä¾èµ List)çå¤ä½è¾¹çº¿ç­ç»èé®é¢ã
  - ä¿®å¤ RN `CheckBox` åæ§æ¨¡å¼ä¸ç bugã ([#784](https://github.com/ant-design/ant-design-mobile/issues/784))

- **Improve & Enhancement**
  - åç»ä»¶æ ¸å¿å®ç°ãæ ·å¼ãæ¼ç¤ºç­å¨é¢ä¼åã
  - RN Carousel æ¯ææ ¹æ®å­è§å¾é«åº¦èªéåºï¼å»é¤ heightï¼width è®¾ç½®ã
  - ç½ç«éæ°è®¾è®¡ãæ´å è½»çç®æ´ï¼ä¼åäºç½ç«èµæºå¤§å°ãå è½½éåº¦æ´å¿«ã
  - RN android tabbar æ·»å  iconStyle æ¯æã
  - Modalï¼Toastï¼ActionSheet ä» api ä¸­ æååº component å½¢å¼ã

## 0.9.15

`2017-02-15`

- ä¿®å¤å¹¶ä¼å TextareaItem, Accordion, Popover, ListView, InputItem ç­ç»ä»¶ç»èé®é¢ #724 #725 #788 #426
- ä¿®å¤ RN Grid ç onClick ç¹å»å¤±æé®é¢ #755
- Toast ç»ä»¶ä¿®æ¹æåä¾æ¨¡å¼ï¼é¿åå¤ä¸ª toast åæ¶ææ åºåºç°çé®é¢ #745
- Modal ç»ä»¶å¨ alert / prompt ç action éå¢å  Promise æ¯æ
- TabBar ç»ä»¶ Android ä»£ç æ°å¢ iconStyle å±æ§æ¯æ #776
- SwipeAction ç»ä»¶å¢å é®ç½©èæ¯æ ·å¼ï¼å¹¶ä¼å demo

## 0.9.14

`2017-01-13`

- ä¿®å¤ Carousel afterChange ä¸è§¦åé®é¢ #711
- ä¿®å¤ RadioItemãCheckboxItem ç»ä»¶ onChange äºä»¶è§¦åä¸¤æ¬¡é®é¢ #689 #721
- ä¿®å¤ç¸å³ RN ç»ä»¶ï¼ä½¿ä¹è½ä¸ææ°ç RN å¼å®¹
- ä¿®å¤åç»ä»¶ç TypeScript ç±»åå®ä¹ç¼ºå¤±æéè¯¯çé®é¢ #667
- ç» package.json æ·»å  main å­æ®µï¼å å¥éè¯¯æç¤ºï¼è§£å³å¸¸è§ä¸æä½¿ç¨é®é¢ #602
- æ´æ° rc-swipeout ä¾èµï¼æ·»å æ´å¤ç¹æ§
- ä¼å DatePicker ç»ä»¶ãå¯ä»¥èªå®ä¹å³é­æ¥æéæ©çå¼¹åºæ¡ #639
- å¯¹ TableãListViewãRadioãModalãToastãCarousel ç­ç»ä»¶æ demo åç»èä¼å(å« RN)
- rn-tabs å¢å  `barStyle` å±æ§ï¼æ´å æ¹ä¾¿éç½®æ ·å¼ #676

## 0.9.13

`2016-12-23`

- ä¿®å¤ TextareaItem è®¾ç½® autoHeight åå§é«åº¦ä¸å¯¹çé®é¢ #671
- ä¿®å¤ SreachBar placeholder ç z-index è®¾ç½®è¿é«é®é¢ #650
- ä¿®æ¹ List å·¦å³åå®¹å¹³åå æ®ç©ºé´çæ ·å¼è®¾ç½®ï¼å¸æ¾åå®¹çä¸»æ¬¡ä¹å #655
- å¨é¢æ¿æ¢ touchableFeedback ä¸º `rc-touchable`ï¼åæ¶ä¿®å¤ TS type ç¼ºå¤±é®é¢ #636 #667
- ä¿®å¤ Modal ææ¡£éè¯¯ï¼ä¼å ModalãSegmentedControlãTabBar (#646) çå®ç°åç¤ºä¾
- ä¿®å¤ ListItem æ²¡æ onClick äºä»¶æ¶ä¹ä¼è§¦åç¹å»åé¦é®é¢ #220#issuecomment-267587198
- ä¼å ListViewãInputItemãTextareaItem ç­ç»ä»¶ææ¡£

## 0.9.12

`2016-12-15`

- ä¿®å¤ SearchBarãButtonãSegmentedControl ç­ TypeScript ç±»åå¼ç¨éè¯¯çé®é¢
- ä¿®å¤ CheckboxãRadio å¨æäºè®¾å¤ä¸ç¹å» label ä¸ä¼éä¸­çå¼å®¹æ§é®é¢
- ä¿®å¤ InputItem æåä¸é¡¹å¤ä½è¾¹çº¿é®é¢ï¼éæ CarouselãMenu æ ¸å¿å®ç°
- ä¿®æ­£ NoticeBar æå­å¤§å°åéï¼ä¿®å¤ RN Radio åæ§ç¶æå®ç°éè¯¯çé®é¢
- ä¿®å¤ RefreshControl ç`distanceToRefresh`è®¾ç½®ï¼ä½¿å¶è½èªéåºä¸ååè¾¨ççå±å¹
- æ¢å¤ PickerãDatePicker ç extra è®¾ç½®å¹¶æ´æ°å¶ææ¡£ï¼å¹¶å¢å èªå®ä¹ children ç demo
- ä¿®å¤ Steps status error ç¶æå±ç¤ºé®é¢ï¼å¯¹ Popup ç¹å»é®ç½©å±çåè°å½æ°`onMaskClose`è¿è¡åè½è¡¥å
- ä¼å InputItemãTextareaItemãPickerãDatePicker ç­ç»ä»¶ demo ï¼ä¼ååç»ä»¶ææ¡£ç»è

## 0.9.11

`2016-12-03`

- ä¿®å¤ List åºé¨è¾¹çº¿éå æ¾ç¤ºé®é¢ãéæ List ç¹å»åé¦çå®ç°æ¹æ³ï¼åæ­¥ä¿®å¤ ListView.IndexedList è¾¹çº¿éå é®é¢
- ä¿®å¤ Checkbox å¾éç®­å¤´åç§»é®é¢ #581
- ä¿®å¤ Steps ç»ä»¶åé¨é»è¾ãæ¹è¿é¨åæ ·å¼è®¾ç½®
- ä¿®å¤ SearchBar å¨ç»è¡¨ç°ä¸åç¡®é®é¢
- æ¹è¿[ä¸æåä½¿ç¨ææ¡£](https://mobile.ant.design/docs/react/introduce#ä½¿ç¨)åæ³
- ä¼å PaginationãRefreshControlãRadioãDrawerãPopoverãResultãNoticeBar ç­ç»ä»¶å®ç°åç¸åº demo
- ä¿®å¤ RN InputItem Android ä¸è½è¾å¥çé®é¢ #603

## 0.9.10

`2016-11-25`

- éæ SearchBar ï¼æ¹ä¸ºæ¨¡æç placeholder å®ç°ï¼å¹¶å°å¶é»è®¤å±ä¸­å¯¹é½
- ä¿®å¤ Popup ç»ä»¶ç¹å»é®ç½©å±ä¸ä¼èªå¨å³é­ #555 #558
- æ´æ­£ RefreshControl ææ¡£ï¼ä¿®å¤é¨åç»ä»¶ demo å¨ pc å mobile ä¸å±ç¤ºä¸ä¸è´é®é¢
- ä¿®å¤ Toast å¨ Modal ä¸­ä½¿ç¨è¢«è¦çé®é¢ #547
- ä¼å ButtonãList ä»£ç ç rn å®ç°ï¼ä¿®æ­£é¨å demo ç»èé®é¢

## 0.9.9

`2016-11-18`

- æ¹è¿ Popup æ ·å¼ #525 , é»è®¤ç¦æ­¢æ popup é®ç½©å±ç onTouchStart äºä»¶ãä¼åå¨æå¨æ¶çä½éª
- ä¿®å¤ Radio å Accordion ä¸èµ·ä½¿ç¨æ ·å¼å²çªé®é¢ #542 ï¼ä¼å List.Body æ ·å¼ï¼ ImagePicker æ·»å æé®æ¯æç¹å»åé¦
- ä¿®å¤ CheckboxãRadioãTagãInputItem ç­ç»ä»¶æ ·å¼ç»èé®é¢ï¼ä¼å Flex ç»ä»¶ demo
- å¢å  React åºç¡ãç¸å³å·¥å·ãåºç¨æ¶æææ¡£æåï¼å¹¶ä¼åâå®è£&ä½¿ç¨âææ¡£ãä½¿ä¹æ´ç´§åæ¸æ°

## 0.9.7

`2016-11-11`

- ä¿®å¤ ListView éæ¼ ref è®¾ç½®é®é¢ https://github.com/ant-design/ant-design-mobile/commit/2e32956d405880f2fdca3cc88cd7c3b1b7784b7f
- è¡¥åæå é¤ ActionSheetãBadgeãListViewãPaginationãRefreshControlãSteps ä¾èµç»ä»¶çæ ·å¼
- æ´ç ts PropsType æä»¶ #495
- ä¿®å¤ Radio ç»ä»¶é»è®¤éä¸­é®é¢ï¼æ¹è¿ demo å±ç¤º
- æ¹è¿ SearchBarãImagePicker ç­ç»ä»¶ demo å±ç¤ºï¼ç»ä¸ææ¡£æ ¼å¼
- TextareaItem å¨éåæ§æ¨¡å¼ä¸æ¯æèªå¨é«åº¦åè½ #459
- ä¿®å¤ CheckboxãRadio éåæ§ç¶æå¤±æé®é¢ï¼å¹¶æ¹è¿ demo åææ¡£å±ç¤º

## 0.9.6

`2016-11-05`

- ä¿®å¤ Stepper ç»ä»¶å¼¹åºé®çåç¹å»åé¦é®é¢ https://github.com/ant-design/ant-design-mobile/commit/94f4e54ab6bb9800fc987cc57d806b5921b11c9d
- ä¿®å¤ Tabs éé¡¹å¡é«åº¦ä¸ä¸è´é®é¢ https://github.com/ant-design/ant-design-mobile/commit/f4bb4bc86e2a8400fb74a69e9f0a2359ce512b0b
- ä¿®å¤ InputItem, TextareaItem value ä¸æ¥å undefined é®é¢ https://github.com/ant-design/ant-design-mobile/commit/114fb1ed871acd94433129fda95a30649420aa2a ï¼æ¯ææ·»å ææ HTML input/textarea æ¯æçå±æ§(å¦èªå®ä¹ pattern ç­)
- ä¿®å¤ android textInput underlineColorAndroid https://github.com/ant-design/ant-design-mobile/commit/8095c924fda68f1b38acae1af09822daae95c3d2
- ä¼å Accordion, Checkbox, Popup, Badge, InputItem, TextareaItem, ListView ç­ç»ä»¶æ¼ç¤ºææ¡£åé¨åæ ¸å¿å®ç°ã
- Accordion ææ¡£å¢å éæ¼ç openAnimation API è¯´æ https://github.com/ant-design/ant-design-mobile/commit/951811484d192c2383b6f5c6815148ee1e44fab6
- ä¿®å¤ Grid rn å®ç°ä¸å®å¨é®é¢ï¼å¹¶ä¼åä»£ç  https://github.com/ant-design/ant-design-mobile/commit/839fe3518497406dc2bf9c3db82ee89d0e0e5c8f

## 0.9.5

`2016-10-28`

- ä¿®å¤é¨åç»ä»¶ç¹å»åé¦å±æ§ warning, #416
- æ´æ­£ DatePicker ç»ä»¶ API ææ¡£ï¼ä¼å Progress æ¼ç¤ºãå¢å èªå®ä¹ style æ¯æ
- ä¿®å¤ Modal.prompt ææ¶æ æ³ focus é®é¢ #415 #409
- ç§»é¤ SegmentedControl default props tintColor #432
- ä¿®å¤é¨åç»ä»¶ ts props éªè¯
- éæ NoticeBar ç»ä»¶ï¼ä½¿ click äºä»¶è½å¨æ´ä¸ªåºåè§¦åï¼é¤äºå³é­æ¨¡å¼ï¼
- å®åå¹¶ä¿®å¤ ResultãToastãrn Popup Modal ç­ç»ä»¶ demo ï¼ä¿®å¤é¨å css åé

## 0.9.4

`2016-10-21`

- Button ç»ä»¶ä¿®å¤ #396
- ä¿®å¤ rn-checkbox, rn-radio æ¯æåæ§ç»ä»¶ https://github.com/ant-design/ant-design-mobile/commit/6f47c36b8e3729674dc63eaaa39cfac05b125f3c https://github.com/ant-design/ant-design-mobile/commit/5960cd11a94570cfc0b874fa2f05ab0f2bce466a

## 0.9.3

`2016-10-17`

- é¨åç»ä»¶æ¯æ`data-api` https://github.com/ant-design/ant-design-mobile/commit/8972f980d0dddee30fd61ebaa0f75fc07a7a36b3
- ä¿®å¤ iOS ä¸ Modal éåå®¹æ»å¨æ¶å¼èµ·èéåå®¹æ»å¨é®é¢ #163 #307
- `ImagePicker`æ°å¢ä¸ä¸ªå±æ§`onAddImageClick`, `selectable`, `onImageClick`, https://github.com/ant-design/ant-design-mobile/commit/bb7e461eea71bb8ffdd2477b1b17a714beb21eb1 #252 #297 #357
- æ´æ°é¨åç»ä»¶ demo åææ¡£ç»è bug ä¿®å¤

## 0.9.2

`2016-10-10`

- Tag å¢å  closable æ¯æ #348
- package ä¸­ dist ç®å½ css æ ·å¼ä»¥ rem ä¸ºä¸»è¦åä½ï¼æ¹ä¾¿ç´æ¥å¼ç¨æ ·å¼èä¸ä¼æ¾å¤§

## 0.9.1

`2016-10-09`

- ä¿®å¤ tabbar `icon`ã`selectedIcon` ç´æ¥ require å¾çä¸æ¾ç¤ºé®é¢ #343
- ä¿®å¤`InputItem` pattern bug https://github.com/ant-design/ant-design-mobile/commit/e2b1d4336f6a19ee80667c3383c12861448937e0
- ä¿®å¤`Button` css åéæªå¼ç¨é®é¢ #339
- ä¿®å¤`Picker`æ ·å¼ https://github.com/ant-design/ant-design-mobile/commit/e7cf959fb6978b5b6fa37294007b8f214477f625 , æ°å¢`onPickerChange`api https://github.com/ant-design/ant-design-mobile/commit/69e142cddc99b0d99ae23f3435e801ddd6ab014d
- æ´æ° rn list-view demo https://github.com/ant-design/ant-design-mobile/commit/c0b4ae4797a9fac3a00c8272becc2709c2846039

## 0.9.0

`2016-09-30`

- List ç»ä»¶ API è°æ´ä¸ºä¸ ListView ä¿æä¸è´ï¼ç§»é¤ List.Bodyï¼ List.Footerï¼List.Headerï¼title å footer å±æ§åæ´ä¸º renderHeader å renderFooter æ¹æ³ [#257](https://github.com/ant-design/ant-design-mobile/issues/257)
- ä½¿ç¨ [zscroller](https://github.com/yiminghe/zscroller) éæ ListViewãæ°å¢ `renderSectionBodyWrapper` æ¥æ¯ææ¸²æèªå®ä¹çåºååè£¹ç»ä»¶ï¼æ°å¢[scrollerOptions](https://github.com/yiminghe/zscroller#options)
- ä½¿ç¨ zscroller æ¥æ¯æ RefreshControl (`useBodyScroll` and sticky å¤±æ)ï¼å·æ°åè°å½æ°ç± loadingFunction è°æ´ä¸º onRefreshï¼å¢å  refreshing è®¾ç½®æ¯å¦æ¾ç¤ºå·æ°ç¶æ [#](https://github.com/ant-design/ant-design-mobile/issues/288)ãRefreshControl åªè½å ListView ç»åä½¿ç¨ï¼ä¸è½åç¬ä½¿ç¨ã
- ä¿®å¤ Modal & SegmentedControl touch feedback ææ [#195](https://github.com/ant-design/ant-design-mobile/issues/195)
- æ´æ° Tabbarï¼æ¯æ `hidden` prop
- Steps ç»ä»¶ icon æ¯æ React.Element
- ä¿®å¤ BadgeãNavBarãActivityIndicatorãStepper ç»ä»¶çä¸äºæ ·å¼ç»èé®é¢ã
- ä¿®å¤ Carousel dots éèå¤±æçé®é¢
- ä¿®å¤ android uc modal æ ·å¼é®é¢ [#](https://github.com/ant-design/ant-design-mobile/issues/283)
- ä¿®å¤ SegmentedControl å¨æ¨¡æå¨ä¸çæ ·å¼é®é¢

## 0.8.6

`2016-09-23`

- ä¿®å¤ Carousel dot æ ·å¼é®é¢ #302
- ä¿®å¤ Tabbar æå­å±ä¸­é®é¢ #310
- ä¿®å¤ å¤ä¸ª Modal closable icon ä¸æ¾ç¤ºçé®é¢
- ä¿®å¤ NavBar è¿å Icon ä¸æ¾ç¤ºçé®é¢ï¼ #302
- ä¿®å¤ List ç®­å¤´æå å åè¡å±ç¤ºé®é¢ #273 #274
- ä¿®å¤ DatePicker demo
- æ´æ° Modalï¼API `dialog` æ¹ä¸º `transparent`
- æ°å¢ List ç»å rc-form demo
- å¢å  less æä»¶çå¥å£ï¼æ¹ä¾¿éç½®å·¥å·ç»ä¸å è½½æ ·å¼ã https://github.com/ant-design/ant-design-mobile/pull/267
- ä¼å Badge æ ·å¼
- ä¼å ActivityIndicator demo, ç½ç«ç»ä»¶åç±»ä¼å

## 0.8.5

`2016-09-14`

- ä¿®å¤ Picker å DatePicker `extra`è®¾ç½®å¨ ListItem ä¸ä¸çæé®é¢ #241
- å»é¤ Button `size=small` åªå¨ `inline` è®¾ç½®åçæçéå¶
- ä¿®å¤ Button ç»ä»¶å¨ pc çæ¬ç demo éçæä¸ææ #244
- ä¼å Picker / DatePicker ç¹å»åé¦ææ https://github.com/ant-design/ant-design-mobile/commit/adb5a45ae35e13f64d4f295dd328cf9da45aec57 #195
- å»é¤ Stepper ç»ä»¶ç input ä¸è½è¾å¥éå¶ï¼å¹¶æ´æ¹`readOnly`é»è®¤å¼ https://github.com/ant-design/ant-design-mobile/commit/8325f6444970559e465d71df625e81cbe57c0b85#commitcomment-19012543
- ä¼å Drawer / Popup ç­ç»ä»¶ demoï¼ç½ç«å±ç¤ºç»èä¼å

## 0.8.3

`2016-09-09`

- `Checkbox` ä¿®å¤åæåè®®è¿ç§åºæ¯ä¸ï¼label ä¸­æåè®®æ æ³è§¦å`onClick`ç bugã
- `SearchBar` ä¼åå¨ç»ææã
- `Carousel` ä¿®æ¹ä¸ºåºäº`nuka-carousel`ãåæ`card`æ¨¡å¼ä¸åæä¾ï¼éèªè¡å®å¶ã

ps: ç®å`listview` å `refresh-control` ä¸å¼å®¹ï¼æ­£å¨ä¿®å¤ä¸­

## 0.8.2

`2016-09-07`

- ç»`body`æ ç­¾è®¾ç½®é»è®¤èæ¯è²ï¼ä»¥åé»è®¤ç`font-size`,`html`è®¾ç½®é»è®¤ç`font-size`ã
- `Grid`å±æ§æ©å±ï¼æ¯è¡åæ°å¯éç½®ï¼æä¾`renderItem`æ¹æ³ã
- ä¿®å¤`Checkbox`ã`Radio`æ ·å¼ç»èä»¥åå¼å®¹æ§é®é¢ã
- `SearchBar`è¾å¥æ¡`Blur`ç¶ææ¶`placeholder`åºå®é å·¦å¯¹é½ã
- `Menu`é«åº¦è®¡ç® bugfixã

## 0.8.1

`2016-09-02`

- ä¿®å¤å¹¶æ´çåå¼¹åºå±ç±»ç»ä»¶ z-index é¡ºåº https://github.com/ant-design/ant-design-mobile/commit/bb875c2a924f61cc03b8d013fd1a8f5ee8e22972
- Tab å¢å ç¦æ­¢ swipeable çåè½ #209
- TabBar æ´æ¹ä¸ºå iOS åçæ¹å¼ä¸è´ï¼ä¿æ web å rn ç»ä¸ï¼å»æ swipeable
- List ç»ä»¶ list-body è¾¹æ¡æ¯æéç½® https://github.com/ant-design/ant-design-mobile/commit/76760060cb5dfa5c9474b2174ee03db3c30b5197

## 0.8.0

`2016-08-31`

> UI é£æ ¼æ´æ¢ä¸º alipay å®æ¹é£æ ¼

- **Bug Fix**

  - ä¿®å¤ `Object.assign` å¼å®¹é®é¢
  - Picker / DatePicker æ·»å  disabled æ¯æ
  - InputItem å TextareaItem API `format` æ¹ä¸º `type`ï¼ç§»é¤åæ¥ typeï¼ä¿®å¤ maxLength bug
  - ListView å¢å `useBodyScroll` API, IndexedList æ¯æåä¸¤æ­¥æ¸²æ
  - Button `ghost`ä»åæ¥çåç¬å±æ§ï¼åä¸º`type`ä¸çå±æ§å¼ï¼ä¿®å¤æ ·å¼ç»èé®é¢
  - Modal `footer` ç±»åæ´æ¹
  - Dropdown ææå `ActionSheet.showActionSheetWithCustom` ææéæå°æ°å¢ç`Popup`ç»ä»¶éï¼`ActionSheet.showActionSheetWithCustom` API ç§»é¤
  - `ActionSheet.showShareActionSheetWithOptions`æ¯æå¤è¡ï¼`options`éç½®é¡¹æ¯æäºç»´æ°ç»ï¼callback åæ°å¢å æ¾ç¤ºè¡åºå
  - `ActionSheet.showActionSheetWithOptions`/`ActionSheet.showShareActionSheetWithOptions` ç `callback`æ¯æè¿å Promise
  - ActionSheet react-native android ä¸æ°å¢`close` APIï¼æ¯æèªå®ä¹åå®¹ä¸çç¼ç¨å³é­ ActionSheet
  - Toast rn ç»ä»¶ä¿®å¤é®æ¡ NavBar é®é¢
  - ä¿®å¤ rn ç»ä»¶ç¦»çº¿å¾çæ¾ä¸å°é®é¢
  - å®æ¹ç½ç«å±ç¤ºä¼åï¼demo åç±»ä¼åï¼web demo éç¨ rem åé¡µé¢ scale ç¼©æ¾æ¹æ¡ï¼è¾¾å°é¡µé¢é«æ¸ææ

- **æ°å¢ rn ç»ä»¶**

  - Checkbox
  - Carousel
  - Radio
  - Steps
  - SearchBar
  - SegmentedControl
  - TabBar
  - Tabs

- **ç»ä»¶åæ´**

  - Timeline ç§»é¤
  - Tooltip ç§»é¤
  - Tabs æåä¸º SegmentedControlãTabBarãTabs
  - Tabs tabPosition => tabBarPosition, animation => animated

- **ç»ä»¶æ´å**
  - FloatMenu => Popover
  - Collapse => Accordion
  - PageResult => Result
  - TopNotice => NoticeBar
  - Uploader => ImagePicker

## 0.7.6

`2016-08-12`

- `Tabs` `Object.assign`ä½¿ç¨`object-assign`æ¿ä»£ã

## 0.7.5

`2016-08-11`

- `List` 1px é®é¢ä¼å,`List`çå®¹å¨è®¾å®äºåºå®é«åº¦ï¼`overflow`è®¾ç½®ä¸º`scroll`ï¼`List.Item`çè¾¹æ¡ä¼æ¶å¤±ã
- `Grid` å¤ç`Grid`ç`icon`å¾çä¸æ¯æ­£æ¹å½¢çæ¾ç¤ºé®é¢ã

## 0.7.4

`2016-08-10`

- `List.Item` è§£å³`onClick`æ¶ç»ä»¶`unmount`èåæ¶å¨æ´æ°ç»ä»¶åé¨ state å¼èµ·çæ¥éã
- `SearchBar` ä¿®å¤å¨é¨å Android æºåä¸å®½åº¦å¼å¸¸ã

## 0.7.3

`2016-08-09`

- `ListView` é sticky æ¨¡å¼åè½é®é¢ä¿®å¤ï¼å¹¶å¢å æ´å¤ demo ï¼rn demo ä¼åï¼
- `DatePicker` ä¿®æ­£å¹¶æ©å± format å½æ°åè½
- `InputNumber` `Dialog` `Menu` `ActivityIndicator` `Checkbox` ç­ç»èä¼å

## 0.7.2

`2016-08-02`

- ä¿®å¤ iconfont éå¤å¼ç¨é®é¢ï¼
- åç»ä»¶å¨ç»è®¾ç½®ç»ä¸å°`components/style/anim.less`éï¼
- ç½ç«çç§»å¨çå±ç¤ºä¼åï¼

## 0.7.1

`2016-08-01`

- `Toast`ç»ä»¶`z-index`ä¼åï¼
- çº æ­£ææ¡£ä¸­éè¯¯ç `DatePicker` value / minDate / maxDate ç±»åï¼ä¿®å¤ rn ç¹å»ä¸è½æå¼é®é¢;
- `ActionSheet` åäº«åè½ç icon æ ·å¼ä¼åï¼rn demo å±ç¤ºä¼åï¼
- å·¥å·å¢å `babel-runtime`æ¯æï¼

## 0.7.0

`2016-07-29`

- æ°å¢ `Tooltips`ã`Card`ã`Pagination`ã`Loading`ã`Table` ç»ä»¶ï¼
- `ListAction` æ´åä¸º `SwipeAction`ï¼
- `WhiteSpace` å `WingBlank` ç»ä»¶ç mode å±æ§ä¿®æ¹ä¸º size;
- `InputItem`ã`TextareaItem` çå·¦è¾¹ label å­æ°å¯ä»¥éç½®ï¼æé»è®¤å¼;
- `DatePicker` value ç±»åæ´æ¹;
- typescript æ¯æï¼
- å®æ 30+ ç»ä»¶ å¯¹åºç react native ç»ä»¶ï¼demo app beta çäºç»´ç ï¼

  ![demo app](https://zos.alipayobjects.com/rmsportal/qYVpyTZzcWMGerJ.png)

- demo app æ¯ææ«ç é¢è§ web & react native é¡¹ç®ï¼
- [å®æ¹ç½ç«](http://mobile.ant.design)ä¼åï¼

## 0.6.0

`2016-06-20`

- æ°å¢ `ListView`ã` ListAction``Grid ` `Menu`ã`Uploader`ã`RefreshControl`ç»ä»¶ï¼
- `ListPicker` / `ListDatePicker` ç»ä»¶æ´åä¸º Picker / DatePickerï¼
- å é¤ `SelectList` ç»ä»¶ï¼å¯ä½¿ç¨ `Radio` ç»ä»¶ä»£æ¿ï¼ï¼æèä½¿ç¨æ´å¼ºå¤§ç`Menu`ç»ä»¶ï¼
- æ´æ°`Flex`ï¼å¨é¨æ¯æ flex å±æ§ãï¼psï¼UC åæ ¸å¯¹ flex å¸å±æ¯æä¸å®åï¼ï¼
- æ´æ°`List.Item`ã`InputItem`ã`TextareaItem`çæ¥éæ ·å¼ï¼
- `InputItem`æ¯ææ°å­è¾å¥(`format="number"`)ï¼
- `Tabs` ç»ä»¶æ°å¢ tabbar å½¢å¼ï¼
- `TopNotice` å½ mode ä¸º `closable`æ¶, åèªå¨éæ¯;
- `Steps`ç»ä»¶æ¯æ size ä¸º`pointer`çç¹ç¶æ ·å¼;
- æä¾`List`ã`Button`ã`Flex`ã`WhiteSpace`ã`WingBlank`äºä¸ª UI ç»ä»¶ï¼

## 0.5.0

`2016-05-16`

åå¸å¨æ°çåºäº Ant Design è®¾è®¡è§èççæ¬ã

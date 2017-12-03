# 支付宝小程序 axml

为 VSCode 提供 axml 语法支持及代码片段

[![version](http://vsmarketplacebadge.apphb.com/version/coderfee.vscode-axml.svg)](http://vsmarketplacebadge.apphb.com/version/coderfee.vscode-axml.svg)
[![installs](http://vsmarketplacebadge.apphb.com/installs/coderfee.vscode-axml.svg)](http://vsmarketplacebadge.apphb.com/installs/coderfee.vscode-axml.svg)

## 安装

1. 打开编辑器，`Ctrl + Shift + X`，搜索 **antapp-axml**。
2. 点击 `install`

## 使用

键入关键词，然后回车。关键词不区分大小写

![vscode-antapp-snippets](http://oaz5uxplb.bkt.clouddn.com/vscode-axml.gif)

#### 代码示例

- swiper

  ```html
  <swiper indicator-dots="{{indicatorDots}}" autoplay="{{autoplay}}" interval="{{interval}}" duration="{{duration}}">
    <block a:for="{{imgUrls}}">
      <swiper-item>
        <image src="{{item}}" class="slide-image" />
      </swiper-item>
    </block>
  </swiper>
  ```

- actionsheet

  ```html
  <action-sheet>
    <block a:for="{{actionSheetItems}}">
      <action-sheet-item class="item" data-name="{{item}}" />{{item}}</action-sheet-item>
    </block>
  </action-sheet>
  ```

- checkgroup

  ```html
  <checkbox-group>
    <label class="" a:for="{{item}}">
      <checkbox value="item.name" />{{item.value}}
    </label>
  </checkbox-group>
  ```

-afor

  ```html
  a:for="{{item in items}}"
  ```

- button

  ```html
  <button type="" size="" loading="" plain="" bindtap=""></button>
  ```

- ······more


**Enjoy!​​**
<template>
  <div class=""
    ><h3><a name="switch" class="md-header-anchor"></a><span>Switch</span></h3
    ><figure
      ><table
        ><thead
          ><tr
            ><th><span>属性</span></th
            ><th><span>说明</span></th
            ><th><span>默认值</span></th></tr
          ></thead
        ><tbody
          ><tr
            ><td><span>checked</span></td
            ><td><span>指定当前是否选中</span></td
            ><td><span>false</span></td></tr
          ><tr
            ><td><span>size</span></td
            ><td
              ><span>开关的尺寸，可选值为</span><code>large</code><span>、</span><code>small</code
              ><span>、</span><code>default</code
              ><span>或者不写。建议开关如果使用了2个汉字的文字，使用 large。</span></td
            ><td><span>default</span></td></tr
          ><tr
            ><td><span>disabled</span></td
            ><td><span>禁用开关</span></td
            ><td><span>false</span></td></tr
          ><tr
            ><td><span>true-color</span></td
            ><td><span>自定义打开时的背景色</span></td
            ><td><span>-</span></td></tr
          ><tr
            ><td><span>false-color</span></td
            ><td><span>自定义关闭时的背景色</span></td
            ><td><span>-</span></td></tr
          ><tr
            ><td><span>loading</span></td
            ><td><span>加载中的开关</span></td
            ><td><span>false</span></td></tr
          ><tr
            ><td><span>open</span></td
            ><td><span>自定义显示打开时的内容</span></td
            ><td><span>-</span></td></tr
          ><tr
            ><td><span>close</span></td
            ><td><span>自定义显示关闭时的内容</span></td
            ><td><span>-</span></td></tr
          ></tbody
        ></table
      ></figure
    ><h3><a name="config--方法" class="md-header-anchor"></a><span>Config 方法</span></h3
    ><p
      ><span
        >配置指定的组件，并提供一些必要的响应式更新DOM内容或其他操作的
        API。（并不是每个组件都会有）</span
      ></p
    ><figure
      ><table
        ><thead
          ><tr
            ><th><span>参数</span></th
            ><th><span>说明</span></th
            ><th><span>类型</span></th></tr
          ></thead
        ><tbody
          ><tr
            ><td><span>el</span></td
            ><td><span>配置当前选定的 switch，必须是选择器名称或者元素名</span></td
            ><td><span>String</span></td></tr
          ></tbody
        ></table
      ></figure
    ><p><span>该方法返回以下值：</span></p
    ><ul
      ><li><code>checked</code></li
      ><li><code>disabled</code></li
      ><li><code>loading</code></li
      ><li><code>events(options)</code></li></ul
    ><figure
      ><table
        ><thead
          ><tr
            ><th><span>返回值</span></th
            ><th><span>说明</span></th
            ><th><span>类型</span></th
            ><th><span>默认值</span></th></tr
          ></thead
        ><tbody
          ><tr
            ><td><span>checked</span></td
            ><td><span>响应式设置或更新当前是否选中状态</span></td
            ><td><span>Boolean</span></td
            ><td><span>-</span></td></tr
          ><tr
            ><td><span>disabled</span></td
            ><td><span>响应式设置或更新禁用开关状态</span></td
            ><td><span>Boolean</span></td
            ><td><span>-</span></td></tr
          ><tr
            ><td><span>loading</span></td
            ><td><span>响应式设置或更新加载中的开关状态</span></td
            ><td><span>Boolean</span></td
            ><td><span>-</span></td></tr
          ><tr
            ><td><span>events</span></td
            ><td><span>非响应式API，添加开关事件</span></td
            ><td><span>Function</span></td
            ><td><span>-</span></td></tr
          ></tbody
        ></table
      ></figure
    ><ul
      ><li><code>events</code><span>的参数 options 为对象，具体说明如下：</span></li></ul
    ><figure
      ><table
        ><thead
          ><tr
            ><th style="text-align: left"><span>属性</span></th
            ><th style="text-align: left"><span>说明</span></th
            ><th style="text-align: left"><span>回调参数</span></th></tr
          ></thead
        ><tbody
          ><tr
            ><td style="text-align: left"><span>onChange</span></td
            ><td style="text-align: left"><span>开关变化时触发，返回当前的状态</span></td
            ><td style="text-align: left"><span>(checked: boolean) =&gt; void</span></td></tr
          ></tbody
        ></table
      ></figure
    ></div
  >
</template>
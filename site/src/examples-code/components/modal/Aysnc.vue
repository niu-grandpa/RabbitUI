<template>
  <div class="CodeMirror cm-s-inner CodeMirror-wrap CodeMirror-focused" lang="html">
    <div
      style="
        overflow: hidden;
        position: relative;
        width: 3px;
        height: 0px;
        top: 537.6px;
        left: 86.075px;
      "
    >
      <textarea
        autocorrect="off"
        autocapitalize="off"
        spellcheck="false"
        tabindex="0"
        style="
          position: absolute;
          bottom: -1em;
          padding: 0px;
          width: 1000px;
          height: 1em;
          outline: none;
        "
      ></textarea>
    </div>
    <div class="CodeMirror-scrollbar-filler" cm-not-content="true"></div>
    <div class="CodeMirror-gutter-filler" cm-not-content="true"></div>
    <div class="CodeMirror-scroll" tabindex="-1">
      <div
        class="CodeMirror-sizer"
        style="
          margin-left: 0px;
          margin-bottom: 0px;
          border-right-width: 0px;
          padding-right: 0px;
          padding-bottom: 0px;
        "
      >
        <div style="position: relative; top: 0px">
          <div class="CodeMirror-lines" role="presentation">
            <div role="presentation" style="position: relative; outline: none">
              <div class="CodeMirror-measure"><pre>x</pre></div>
              <div class="CodeMirror-measure"></div>
              <div style="position: relative; z-index: 1"></div>
              <div class="CodeMirror-code" role="presentation" style="">
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span class="cm-tag cm-bracket">&lt;</span><span class="cm-tag">button</span> <span class="cm-attribute">class</span>=<span class="cm-string">"rab-btn rab-btn-primary"</span> <span class="cm-attribute">onclick</span>=<span class="cm-string">"handleModal5()"</span><span class="cm-tag cm-bracket">&gt;</span>异步关闭<span class="cm-tag cm-bracket">&lt;/</span><span class="cm-tag">button</span><span class="cm-tag cm-bracket">&gt;</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span class="cm-tag cm-bracket">&lt;</span><span class="cm-tag">r-modal</span> <span class="cm-attribute">title</span>=<span class="cm-string">"对话框标题"</span> <span class="cm-attribute">loading</span>=<span class="cm-string">"true"</span> <span class="cm-attribute">id</span>=<span class="cm-string">"m5"</span><span class="cm-tag cm-bracket">&gt;</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp;<span class="cm-tag cm-bracket">&lt;</span><span class="cm-tag">p</span><span class="cm-tag cm-bracket">&gt;</span>点击确定后，对话框将在 2秒 后关闭。<span class="cm-tag cm-bracket">&lt;/</span><span class="cm-tag">p</span><span class="cm-tag cm-bracket">&gt;</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span class="cm-tag cm-bracket">&lt;/</span><span class="cm-tag">r-modal</span><span class="cm-tag cm-bracket">&gt;</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span class="cm-tag cm-bracket">&lt;</span><span class="cm-tag">script</span><span class="cm-tag cm-bracket">&gt;</span></span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;<span class="cm-keyword">const</span> <span class="cm-def">modal</span> <span class="cm-operator">=</span> <span class="cm-keyword">new</span> <span class="cm-variable">Rabbit</span>.<span class="cm-property">Modal</span>();</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;<span class="cm-keyword">let</span> <span class="cm-def">timer</span> <span class="cm-operator">=</span> <span class="cm-atom">null</span>;</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"><span class="cm-tab" role="presentation" cm-text="	">    </span><span class="cm-variable">handleModal5</span> <span class="cm-operator">=</span> () <span class="cm-operator">=&gt;</span> {</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp; &nbsp;<span class="cm-variable">modal</span>.<span class="cm-property">config</span>(<span class="cm-string">'#m5'</span>).<span class="cm-property">visible</span> <span class="cm-operator">=</span> <span class="cm-atom">true</span>;</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp;  };</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;<span class="cm-variable">modal</span>.<span class="cm-property">config</span>(<span class="cm-string">'#m5'</span>).<span class="cm-property">events</span>({</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp;<span class="cm-property">onOk</span>: () <span class="cm-operator">=&gt;</span> {</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<span class="cm-variable">timer</span> <span class="cm-operator">=</span> <span class="cm-variable">setTimeout</span>(() <span class="cm-operator">=&gt;</span> {</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<span class="cm-variable">modal</span>.<span class="cm-property">config</span>(<span class="cm-string">'#m5'</span>).<span class="cm-property">visible</span> <span class="cm-operator">=</span> <span class="cm-atom">false</span>;</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp; &nbsp;  }, <span class="cm-number">2000</span>);</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;  },</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp;<span class="cm-property">onCancel</span>: () <span class="cm-operator">=&gt;</span> {</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<span class="cm-variable">clearTimeout</span>(<span class="cm-variable">timer</span>);</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp; &nbsp;  }</span></pre>
                <pre
                  class="CodeMirror-line"
                  role="presentation"
                ><span role="presentation" style="padding-right: 0.1px;"> &nbsp;  });</span></pre>
                <div class="CodeMirror-activeline" style="position: relative">
                  <div
                    class="CodeMirror-activeline-background CodeMirror-linebackground"
                  ></div>
                  <div
                    class="CodeMirror-gutter-background CodeMirror-activeline-gutter"
                    style="left: 0px; width: 0px"
                  ></div>
                  <pre
                    class="CodeMirror-line"
                    role="presentation"
                  ><span role="presentation" style="padding-right: 0.1px;"><span class="cm-tag cm-bracket">&lt;/</span><span class="cm-tag">script</span><span class="cm-tag cm-bracket">&gt;</span></span></pre>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        style="
          position: absolute;
          height: 0px;
          width: 1px;
          border-bottom: 0px solid transparent;
          top: 560px;
        "
      ></div>
      <div class="CodeMirror-gutters" style="display: none; height: 560px"></div>
    </div>
  </div>
</template>
